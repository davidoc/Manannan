# Introduction

This document outlines the approach to converting the old orthography text to new orthography and standard Irish.

Parts of this task could be fully scripted. However, this has not been done for two reasons. First, it should only need to be done a once, and second, we do not want to make excessive automated calls to the [*Caighdeánaitheoir* API](https://github.com/kscanne/caighdean/blob/master/API.md).

# An Caighdeánaitheoir
Clone the [kcsanne/caighdean](https://github.com/kscanne/caighdean) repository. 

_This is a wonderful project to assist in translating between Gaelic languages and other minority languages._

This will provide the scripts we will use to call the *Caighdeánaitheoir* API to convert the old orthography texts to new orthography and standardised spelling and grammar.

The API has an individual request limit of 16k bytes, so it is necessary to break up each file into smaller files.

First, split each file into 100 line chunks:

    $ split -d -l100 manannan01.md manannan01_nua.md.
    $ ls -1 *.md.0?
    manannan01_nua.md.00
    manannan01_nua.md.01
    manannan01_nua.md.02

Next, send each file to the API using the `client.pl` script:

    perl ./client.pl ga < manannan01_nua.md.01 > manannan01_nua.md.01.pairs

This returns pairs of tokens that look like this:

    “ => “
    Bhí => Bhí
    cúis => cúis
    fé => faoi
    leith => leith
    agam => agam

Next, these can be recombined using the `detokenize.pl` script:

    perl ./detokenize.pl -t < manannan01_nua.md.01.pairs > manannan01_nua.md.01

Output looks like:
    
    “Bhí cúis faoi leith agam





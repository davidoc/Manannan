# Manannán

*[Manannán](https://www.isfdb.org/cgi-bin/pl.cgi?584553)* written in 1940 by [Máiréad Ní Ghráda](https://www.dib.ie/biography/ni-ghrada-mairead-a6187). An Irish-language young adult sci-fi space travel book. Contains one of the first uses of a [mecha](https://en.wikipedia.org/wiki/Mecha) outside of Japan and the first mention of a [gravity assist](https://en.wikipedia.org/wiki/Gravity_assist) in literature. 

The book has never been reprinted or translated. This digitisation project aims to make the book more accessible and widely read. The text used the old [Irish orthography](https://en.wikipedia.org/wiki/Irish_orthography) (dot over the letter = h after the letter, etc.).

![Manannán cover](manannan.jpg)

## Clár an Leabhair (Table of Contents)

| # | Chapter | |Pages | PDF | Text |
|---|---------|-|------|-----|------|
|   | Cover   | |      | [PNG](manannan.png) | |
| 0 | Front matter                      | | 1–8 | [PDF](caibidlí/manannan00.pdf) | [Text](caibidlí/manannan00.md) |
| 1 | Pláinéid ná Feaca Súil Duine riaṁ | _Pláinéid nach bhFaca Súil Duine riamh_ | 9–17 | [PDF](caibidlí/manannan01.pdf) | [Text](caibidlí/manannan01.md "A Planet No Human Eye Had Ever Seen Before") |
| 2 | An Raḋarc tríd an gCiandracán     | _An Radharc tríd an gCiandracán_| 18–30 | [PDF](caibidlí/manannan02.pdf) | [Text](caibidlí/manannan02.md "The View through the Telescope") | 
| 3 | An Turas go Manannán              | _An Turas go Manannán_ | 31–43 | [PDF](caibidlí/manannan03.pdf) | [Text](caibidlí/manannan03.md "The Journey to Manannán") |
| 4 | Manannán                          | _Manannán_ | 44–52 | [PDF](caibidlí/manannan04.pdf) | [Text](caibidlí/manannan04.md "Manannán") |
| 5 | Muintear Manannáin                | _Muintir Manannáin_ |53–67 | [PDF](caibidlí/manannan05.pdf) | [Text](caibidlí/manannan05.md"The People of Manannán") |
| 6 | Na ‘Cráiḋmí’                      | _Na ‘Cráidhmí’_ | 68–75 | [PDF](caibidlí/manannan06.pdf) | [Text](caibidlí/manannan06.md "The Cráidhmí") |
| 7 | An tÁrd-Ṁáiġistir                 | _An tÁrd-Mháistir_ | 76–86 | [PDF](caibidlí/manannan07.pdf) | [Text](caibidlí/manannan07.md"The High-Master") |
| 8 | An Priosún                        | _An Priosún_ | 87–97 | [PDF](caibidlí/manannan08.pdf) | [Text](caibidlí/manannan08.md "The Prison") |
| 9 | Oiḋċe sa Ċoill                    |  _Oíche sa Choill_ | 98–109 | [PDF](caibidlí/manannan09.pdf) | [Text](caibidlí/manannan09.md "The Night in the Woods") |
| 10 | An tInneall                      | _An tInneall_ | 110–123 | [PDF](caibidlí/manannan10.pdf) | [Text](caibidlí/manannan10.md "The Engine") |
| 11 | Oiḋċe ṫar Oiḋċeanta              | _Oíche thar Oícheanta_ | 124–136 | [PDF](caibidlí/manannan11.pdf) | [Text](caibidlí/manannan11.md "The Night of all Nights") |
| 12 | ‘Luġ Láṁ-ḟada’                   | _‘Lugh Lámhfhada’_ |  137–150 | [PDF](caibidlí/manannan12.pdf) | [Text](caibidlí/manannan12.md "Lugh of the Long Arm") |
| 13 | An Tróid leis na ‘Cráiḋmí’       | _An Tróid leis na ‘Cráidhmí’_ | 151–165 | [PDF](caibidlí/manannan13.pdf) | [Text](caibidlí/manannan13.md"The Fight with the Cráidhmí") |
| 14 | Díoġaltas                        | _Díoltas_ | 166–177 | [PDF](caibidlí/manannan14.pdf) | [Text](caibidlí/manannan14.md"Revenge") |
| 15 | An tÉalóḋ                        | _An tÉalú_ | 178–188 | [PDF](caibidlí/manannan15.pdf) | [Text](caibidlí/manannan15.md "The Escape") |

## How to Help

If you spot errors in the extracted text, please open an issue or submit a pull request. Corrections are especially welcome from Irish speakers.

## Contents of This Repo

1. **Manannán_pages_1-20.pdf** — PDF, pages 1–20 (full 188-page version exceeds GitHub size limit)
2. **Manannán_09-13.txt** — Extracted and corrected text, pages 9–13
3. **Manannán_13-18.txt** — Extracted and corrected text, pages 13–18


Pages 9–18 cover the start the first chapter (Pláinéid na feaca Súil Duine riamh). Page 13 appears in both files as a transition.

## Plan

We are extracting and correcting the text step by step:

1. **Pages 9–13** — Done. Hand-corrected from OCR.
2. **Pages 13–18** — Extracted
3. **Later** — Once we have further found errors in these sections we can use them to correct later pages. For example if the extract mistook ' mor ' for ' mór ' it will make the mistake again later. And we will have to easily look for and fix these errors in later chapters. Because of that fixing initial errors drastically reduces errors to find in later chapters.

## Errors

Errors are where the extract makes a spelling error. Do not worry about the page numbers and book name being present. These are easy to take out later and help keep track of where we are in the book for combining the text together later.

## Formatting

We are lightly formatting the text files in [Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github) format. 

* Keep original line breaks to make it easier to compare side by side with PDF
* Rejoin words that were hyphenated
* Leave a blank line between paragraphs
* Remove spaces between punctuation and words e.g. `“ An mar sin é ? ” arsa an garsún` becomes `“An mar sin é?” arsa an garsún`.

Mark page numbers  with a reference like this `[l.31]: #` for *leathanach 31*. This is a Markdown reference that will be hidden if the text is converted to HTML or ePUB. Leave a blank line before the page number reference. By convention, a blank line *after* the page number reference means that the following text is a new paragraph; no blank line after means that the following text runs on from the previous page. We are not currently using these references but they are useful to keep track when editing and would allow us to include print edition page numbers in output formats.




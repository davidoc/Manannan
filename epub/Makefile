old_chapters = $(wildcard ../caibidlí/old-orthography/*.md)

Manannán.epub: title.md epub.css $(old_chapters)
	pandoc -o Manannán.epub -c epub.css title.md \
	$(old_chapters)

clean:
	rm Manannán.epub

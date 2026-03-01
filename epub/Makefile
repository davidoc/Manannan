chapters = $(wildcard ../caibidlí/*.md)

Manannán.epub: title.md epub.css $(chapters)
	pandoc -o Manannán.epub -c epub.css title.md \
	$(chapters)

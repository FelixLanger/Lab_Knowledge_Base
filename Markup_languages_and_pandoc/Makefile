pdf:
	pandoc Markup_languages_and_pandoc.pdf \
	  -o Markup_languages_and_pandoc.pdf \
	  --latex-engine xelatex \
	  --toc \
	   --variable mainfont="DejaVu Sans" \
	   --variable sansfont="DejaVu Sans" \
	   Markup_languages_and_pandoc.org

html:
	pandoc -o Markup_languages_and_pandoc.html \
	  Markup_languages_and_pandoc.org

clean:
	rm *pdf *html

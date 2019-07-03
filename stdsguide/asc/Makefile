# makefile for making up the er.pdf
#
doc:
	asciidoctor-pdf -a pdf-stylesdir=resources -a pdf-style=ogc -a pdf-fontsdir=resources/fonts -r asciidoctor-bibtex er.adoc
	rm -f ../doc/pdf/er.pdf
	cp er.pdf ../doc/pdf

git:
	git commit -a

push:
	git push

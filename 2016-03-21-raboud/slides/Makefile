all: 2016-03-21-raboud-netsec-anonymity.pdf 

%.pdf: %.tex macros.tex header.tex beamercolorthemeMYplain.sty beamerinnerthemeMYplain.sty beamerouterthemeMYplain.sty beamerthemeMYplain.sty
	pdflatex -file-line-error -halt-on-error -shell-escape $<


clean:
	rm -f *.ind *.toc *.bbl *.blg *.ilg *.idx *.log *.out *.snm *.nav *.pdf *.vrb *.dvi *.aux


FILENAME:=2016-10-13-waterloo

all: $(FILENAME).pdf

clean:
	-rm $(FILENAME).pdf
	-rm $(FILENAME).toc
	-rm $(FILENAME).aux
	-rm $(FILENAME).log
	-rm $(FILENAME).nav
	-rm $(FILENAME).snm
	-rm $(FILENAME).out

2016-10-13-waterloo.pdf: clean
	pdflatex $(FILENAME).tex
	pdflatex $(FILENAME).tex

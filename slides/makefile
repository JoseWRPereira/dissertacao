show: slidesBib
		evince slides.pdf &

slidesBib: BIB slides
	pdflatex slides.tex

BIB: 	slides
	bibtex slides

slides:	slides.tex
	pdflatex slides.tex


clean:
	rm *.bbl
	rm *.blg
	rm *.aux
	rm *.log
	rm *.nav
	rm *.out
	rm *.snm
	rm *.toc
	rm *.pdf
	rm *~

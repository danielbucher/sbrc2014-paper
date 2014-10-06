all: bib tex
	pdflatex paper.tex
	evince paper.pdf &

bib: paper.bib
	pdflatex paper.tex
	bibtex paper

tex: paper.tex
	pdflatex paper.tex

clean:
	rm *.bbl *.aux *.blg *.log *.pdf

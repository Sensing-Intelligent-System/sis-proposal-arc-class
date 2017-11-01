CMD = pdflatex
DOC = arc-class-proposal
all: 
	$(CMD) $(DOC) && bibtex $(DOC) && $(CMD) $(DOC) && $(CMD) $(DOC) 

clean:
	rm *.aux *.log *.blg *.bbl *.ps *.log *.dvi

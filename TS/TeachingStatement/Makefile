EXEC = sotp
BIBLIO = references
LATEX = pdflatex
BIBTEX = bibtex

all: $(EXEC)

$(EXEC): 
	$(LATEX) $(EXEC).tex

$(BIBLIO):
	$(LATEX) $(EXEC).tex
	$(LATEX) $(EXEC).tex
	$(BIBTEX) $(EXEC).aux

clean:
	-rm -f *.aux *.dvi *.log *.pdf  *.out

distclean:
	-rm -f *.aux *.dvi *.log *.blg *.bbl *.pdf  *.out

LATEX = pdflatex
MAIN  = report

all: $(MAIN).pdf

$(MAIN).pdf: 	$(MAIN).tex  
	$(LATEX) $(MAIN).tex 
#	bibtex $(MAIN)
#	$(LATEX) $(MAIN).tex 
#	$(LATEX) $(MAIN).tex 

diff:	$(MAIN)_diff.pdf


clean:
	rm -f $(MAIN).pdf $(MAIN).out $(MAIN).bbl $(MAIN).aux

view: 
	open $(MAIN).pdf &


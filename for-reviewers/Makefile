PAPER=ae_reviewer_report

$(PAPER).pdf: $(PAPER).tex
	pdflatex $(PAPER)
	pdflatex $(PAPER)

clean:
	rm -f *.aux *.fls *.bbl *.blg *.log *.out *.fdb* *.synctex* *converted*.pdf %$(PAPER).pdf

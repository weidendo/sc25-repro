PAPER=sc25_ad_ae_template

$(PAPER).pdf: $(PAPER).tex
	pdflatex $(PAPER)
	pdflatex $(PAPER)
	pdflatex $(PAPER)

clean:
	rm -f *.aux *.fls *.bbl *.blg *.log *.out *.fdb* *.synctex* *converted*.pdf #$(PAPER).pdf

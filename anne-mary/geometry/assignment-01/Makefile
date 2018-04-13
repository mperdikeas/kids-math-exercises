DOCUMENT=assignment-01
.PHONY: all clean
all:
	pdflatex -interaction=nonstopmode $(DOCUMENT).tex
	makeglossaries $(DOCUMENT)
	pdflatex -interaction=nonstopmode $(DOCUMENT).tex
spellcheck:
	aspell -t -c $(DOCUMENT).tex
clean:
	rm -f *.pdf
	rm -f *.log
	rm -f *.lol
	rm -f *.lof
	rm -f *.toc
	rm -f *.out
	rm -f *.aux
	rm -f *.alg
	rm -f *.glg
	rm -f *.glo
	rm -f *.gls
	rm -f *.glsdefs
	rm -f *.idx
	rm -f *.ist
	rm -f *.acn
	rm -f *.acr
	rm -f *.bbl
	rm -f *.blg
	rm -f *.lot


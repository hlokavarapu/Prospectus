name = UreyReaction
all:
	pdflatex  --shell-escape $(name).tex
	biber $(name)
	pdflatex  --shell-escape $(name).tex
	rm *.out *.bbl *.bcf *.blg *.log *.aux *.nav *.run.xml *.snm *.toc
clean:
	rm *.out *.bbl *.bcf *.blg *.log *.aux *.nav *.run.xml *.snm *.toc *.pdf

name = Prospectus
all:
	pdflatex  --shell-escape $(name).tex
	pdflatex  --shell-escape $(name).tex
	bibtex $(name)
	bibtex $(name)
	pdflatex  --shell-escape $(name).tex
	pdflatex  --shell-escape $(name).tex
	bibtex $(name)
	bibtex $(name)
	pdflatex  --shell-escape $(name).tex
#	rm *.out *.bbl *.blg *.log *.aux *.spl
clean:
	rm *.out *.bbl *.blg *.log *.aux *.spl *.pdf

SRC=main
SUBS=
all: tex
tex:
	pdflatex "\input{$(SRC)}"
	bibtex "$(SRC)"
	pdflatex "\input{$(SRC)}"
	pdflatex "\input{$(SRC)}"
clean:
	rm -rf *.run.xml *.bcf *.dvi *.idx *.log *.toc *.bbl *.nav *.snm *.aux *.blg *.out *.spl *.sta *~

LAT:=pdflatex
BIB:=bibtex
GLS:=makeglossaries
FILE:=main
FILET:=$(FILE).tex

main.pdf: main.tex
	$(LAT) $(FILET)
	$(LAT) $(FILET)
	$(BIB) $(FILE)
	$(LAT) $(FILET)
	$(LAT) $(FILET)
	rm main.aux
	rm main.bbl
	rm main.blg
	rm mainNotes.bib
	rm main.out
	rm main.log

all: exam.pdf solution.pdf clean

%.pdf: %.tex ib002.cls
	texfot pdflatex $^

clean:
	rm -rf *.aux *.log *.out

pdfclean: clean
	rm -rf *.pdf

.PHONY: all clean pdfclean

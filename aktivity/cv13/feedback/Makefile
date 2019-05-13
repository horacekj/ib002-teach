# Change content of this variable to match filename
TARGET = feedback

all: a4.pdf clean

a4.pdf: $(TARGET).pdf
	pdfjam $(TARGET).pdf --nup 2x1 --landscape --outfile a4.pdf

$(TARGET).pdf: $(TARGET).tex
	texfot pdflatex $^

clean:
	rm -rf $(TARGET).aux $(TARGET).log $(TARGET).out

pdfclean: clean
	rm -rf $(TARGET).pdf a4.pdf

.PHONY: clean pdfclean

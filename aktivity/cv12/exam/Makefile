# Change content of this variable to match filename
TARGET = exam

all: $(TARGET).pdf clean

$(TARGET).pdf: $(TARGET).tex ib002-exam.cls
	pdflatex $^

clean:
	rm -rf $(TARGET).aux $(TARGET).log $(TARGET).out

pdfclean: clean
	rm -rf $(TARGET).pdf


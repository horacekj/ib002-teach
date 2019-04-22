# Change content of this variable to match filename
TARGET = logcomp

all: $(TARGET).pdf

$(TARGET).pdf: $(TARGET).tex ib002-exam.cls
	pdflatex $^

clean:
	rm -rf $(TARGET).aux $(TARGET).log $(TARGET).out

pdfclean: clean
	rm -rf $(TARGET).pdf


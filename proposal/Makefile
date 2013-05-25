document = proposal

all: q
	
q:
	pdflatex $(document).tex
	bibtex $(document)
	pdflatex $(document).tex
	pdflatex $(document).tex
	
checkspell:
	ispell -d british -p data/words.dic content/*.tex

clean:
	rm $(document).aux $(document).bbl $(document).blg $(document).log $(document).out $(document).pdf $(document).toc */*.aux

open: q
	open $(document).pdf
JobName=ACC72
TeX=pdflatex
LatexFlags= -jobname=$(JobName) --shell-escape

default:
	make build
	make build
	make clean

build:
	$(TeX) $(LatexFlags) src.tex

clean:
	rm $(JobName).log $(JobName).aux $(JobName).out
	rm -rf _minted-*

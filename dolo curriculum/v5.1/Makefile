SHELL=/bin/bash
EXP=ManuelArredondo

DEPENDENCIES=$(EXP).tex

all:
	@pdflatex $(EXP).tex
	pdflatex $(EXP).tex > .my_log

clean:
	@rm -f $(EXP).{aux,toc,log,tmp,dvi,idx,ilg,ind,bbl,blg,out,nav,snm,lof,tex.bak} .my_log


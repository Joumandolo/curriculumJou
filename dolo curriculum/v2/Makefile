SHELL=/bin/bash
EXP=ManuelArredondo

DEPENDENCIES=$(EXP).tex



all:
	        @echo "Generando pdf por primera vez..."
		        @pdflatex $(EXP).tex > .my_log || (cat .my_log && rm -rf .my_log && exit 1)
			        @echo "Generando pdf por segunda vez..."
				        @pdflatex $(EXP).tex > .my_log || (cat .my_log && rm -rf .my_log && exit 1)

clean:
	@rm -f $(EXP).{aux,toc,log,tmp,dvi,idx,ilg,ind,bbl,blg,out,nav,snm,lof} .my_log


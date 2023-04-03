all:
	latex proj3.tex
	latex proj3.tex
	dvips -t a4 proj3.dvi
	ps2pdf proj3.ps
overlay: all
	pdftk zadani/proj3.pdf multibackground proj3.pdf output overlay.pdf

archive:
	cd odevzdani && zip xvecer30.zip proj3.tex Makefile algorithm2e.sty *.eps
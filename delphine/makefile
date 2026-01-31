SRC=delphine.tex

all:
	#pdflatex ${SRC} && songidx cbtitle.sxd  && pdflatex ${SRC} && pdflatex ${SRC} 
	pdflatex ${SRC} && texlua /opt/local/share/texmf-texlive/doc/latex/songs/songidx/songidx.lua cbtitle.sxd && pdflatex ${SRC} && pdflatex ${SRC} 

clean:
	rm -f *.out *.log cbtitle.s* *.sxc *.aux


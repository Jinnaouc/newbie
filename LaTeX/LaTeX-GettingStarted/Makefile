TeXFileName = LaTeX-GettingStarted

sources = ${TeXFileName}.tex 

pdf: ${TeXFileName}.pdf

${TeXFileName}.pdf: ${sources}
	xelatex -shell-escape ${TeXFileName}.tex
	xelatex -shell-escape ${TeXFileName}.tex

clean:  
	rm -f ${TeXFileName}.aux ${TeXFileName}.log ${TeXFileName}.nav ${TeXFileName}.out ${TeXFileName}.dvi ${TeXFileName}.snm ${TeXFileName}.toc ${TeXFileName}.lof ${TeXFileName}.lot ${TeXFileName}.bbl ${TeXFileName}.blg ${TeXFileName}.vrb ${TeXFileName}.pdf

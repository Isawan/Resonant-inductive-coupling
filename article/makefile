article_tex=article.tex
article_pdf=build/article.pdf

all: $(article_pdf)

$(article_pdf): $(article_tex)
	latexmk -xelatex --outdir=build/ -use-make $(article_tex)

clean:
	latexmk -C --outdir=build/

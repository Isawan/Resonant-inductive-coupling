#cv=build/CV.pdf
#cover=build/cover.pdf
#
#
#all: $(cv) $(cover)
#
#$(cv): CV.tex
#	latexmk -pdf -outdir=build/ -use-make CV.tex;
#	mv $(cv) build/isawan_millican_cv.pdf;
#
#$(cover): cover.tex
#	latexmk -pdf -outdir=build/ -use-make cover.tex;
#	mv $(cover) build/isawan_millican_cover.pdf;
#
#clean:
#	latexmk -CA
article_tex=article.tex
article_pdf=build/article.pdf

all: $(article_pdf)

$(article_pdf): $(article_tex)
	latexmk -pdf --outdir=build/ -use-make $(article_tex)

clean:
	latexmk -C --outdir=build/

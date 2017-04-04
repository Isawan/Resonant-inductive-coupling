presentation_tex=presentation.tex
presentation_pdf=build/presentation.pdf

all: $(presentation_pdf)

$(presentation_pdf): $(presentation_tex)
	latexmk -xelatex --outdir=build/ -use-make $(presentation_tex)

clean:
	latexmk -c --outdir=build/

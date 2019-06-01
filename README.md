# LSU-ETD-Latex-Template
Latex template for formatting electronic theses and dissertations in accordance with the revised guidelines published on April 2019.

A dissertation written using this template has been approved by the editor.

Add your content to the `chapter.tex` and `references.bib` files. Changes required in the `main.tex` file are minimal.

The font used in this template us Utopia. Remove the `\usepackage{fourier}` to go back to defaults.

**Important: Dont use subsubsections.** This template doesn't handle those gracefully. I use *paragraphs* which dont look too bad.

To compile use:
```bash
pdflatex main.tex
bibtex main.aux
pdflatex main.tex
pdflatex main.tex
```

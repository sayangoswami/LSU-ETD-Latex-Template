# LSU-ETD-Latex-Template
Latex template for formatting electronic theses and dissertations in accordance with the revised guidelines published on April 2019

Add your content to the `chapter.tex` and `references.bib` files. Changes to the main.tex file is minimal.

To compile use:
```bash
pdflatex main.tex
bibtex main.aux
pdflatex main.tex
pdflatex main.tex
```

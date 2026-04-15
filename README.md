### Compile LaTeX Project Locally

```bash
latexmk -C
pdflatex Main-File.tex
bibtex Main-File
pdflatex Main-File.tex
pdflatex Main-File.tex

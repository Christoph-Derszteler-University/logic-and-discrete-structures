# Exams

The content of these exams is based on what I remembered after writing them
myself.

## Building

To build these rather simple LaTeX projects, simply choose your LaTeX ... of
your choice and build the [`main.tex`](first/src/main.tex) file.

Your command might look as follows:
```shell
pdflatex -file-line-error -interaction=nonstopmode -synctex=1 -output-format=pdf -output-directory=./out -aux-directory=./auxil main.tex
```
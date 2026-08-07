# Sundaram Singh's Resume

This repository contains the LaTeX source code for my personal resume. It is built using a clean CV template, and includes a GitHub action that automatically compiles the `*.tex` file and publishes a new PDF version when new changes are pushed to the repository.

## Compiling the CV on your local computer

To compile the CV manually, you can use the following command:
```bash
pdflatex -interaction=nonstopmode cv.tex
```

Alternatively, you can use `make`:
- Type `make` in the repository directory to produce the `cv.pdf` file.
- You can optionally type `make clean` or `make distclean` to remove intermediate compilation files.

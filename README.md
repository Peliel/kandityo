# Kandityö
Matematiikan kandityö algebrasta kesän 2026 aikana Aalto-yliopistossa.

## Usage (compile)

Build the minimal paper with pdflatex + bibtex:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

Or use `latexmk` if available:

```bash
latexmk -pdf main.tex
```

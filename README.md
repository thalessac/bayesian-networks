# bayesian-networks

## Compiling the report

Install a LaTeX distribution such as MiKTeX or TeX Live with `pdflatex` and `bibtex` available on your `PATH`. From the repository root, run:

```sh
cd report
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

The compiled PDF is generated at `report/main.pdf`.
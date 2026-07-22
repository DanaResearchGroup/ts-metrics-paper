# Cartesian similarity is a poor proxy for transition-state quality

Manuscript and figures for review.

**Authors:** Kfir Kaplan, Alon Grinberg Dana (Technion — Israel Institute of Technology)

## Contents

| Path | What |
|------|------|
| `docs/paper.pdf` | Compiled manuscript (read this) |
| `docs/paper.tex` | LaTeX source |
| `docs/refs.bib`  | Bibliography |
| `bench/plots/`   | Figures used in the paper |

## Building the PDF

```bash
cd docs
pdflatex paper.tex
bibtex   paper
pdflatex paper.tex
pdflatex paper.tex
```

This repository is scoped to the manuscript only; the datasets, cluster job
trees, and analysis code that produced the numbers live outside it.

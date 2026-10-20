---
id: Latex
aliases:
  - latex
tags:
  - Editor
  - LaTex
created: "17-10-2026 11:21"
status:
---

# Latex

LaTex is a high-quality typesetting system, it includes features designed for the production of technical and scientific documentation. Its available as a _**free software**_. It helps the author to focus more on the writing part rather than looking to the design part of the document which helps in more effective workflow on the work itself.

## LaTex Features

- Typesetting journal articles, technical reports,books and slide presentations.
- Control over large documents containing sectioning, cross-references, tables and figures.
- Typesetting of complex mathematical formulas.
- Advanced typesetting of mathematics with AMS-LaTex.
- Automatic generation of bibliographies and indexes.
- Multi-lingual typesetting.
- Inclusion of artwork, and process or spot colour.
- Using PostScript or Metafont fonts.

## Installation

In ordered to work with latex along side with neovim in fedora, we need certain packages.

- texlive --> installs the basic latex system plus recommended latex packages.
- latexmk --> automates document compilation.
- perl --> the language runtime used by LaTexmk.
- zathura --> it is optional we can use it to view the pdf created viva latex.

```zsh
sudo dnf install texlive latexmk perl zathura
```

## nvim setup for LaTex

To use LaTex along with nvim we need extra settings like nvim plugin and config relate to it.[[Nvim-latex|nvim-latex]]

LaTex is software of its own so their are certain syntax and rules within LaTex.

[[LaTex-Basics|LaTeX-Basics]]

## References

[LaTex](https://www.latex-project.org/)
[LaTex-wikibook](https://en.wikibooks.org/wiki/LaTeX)

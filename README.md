# Custom Report Template

Markdown-to-LaTeX template for easy report writing.

## Setup

1. Install `pandoc`.
2. Install LaTeX.

## Usage

    $ pandoc test.md -o test.pdf --pdf-engine=lualatex --template report-template.tex

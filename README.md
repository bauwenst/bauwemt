# bauwemt
A better LaTeX template for engineering master's theses than `kulemt`.

Also serves as a guide on how to lay out a thesis.

## Examples using bauwemt
- [My 177-page master's thesis](https://bauwenst.github.io/cdn/doc/pdf/2023/masterthesis.pdf) was typeset with `bauwemt`.
- `bauwemt` itself *is* a stripped-down thesis. Compile it to get a PDF that (1) explains how to write a thesis and (2) shows the results you can produce with `bauwemt`. If you are interested in how those results are created, `bauwemt` *is* the source code.

## Installation
If you already have LaTeX and TeXstudio installed, just **download** this repository, compile `main.tex` (with LuaLaTeX), and start working. Do **not** make a fork, unless you want your thesis source code to be publicly available.

Note: it is unlikely that you will manage to compile your thesis with Overleaf due to the limited compilation time.

## Features
Out-of-the-box support for nice-looking:
- Overall style: book margins, chapter headings, captions, hyperlink colours ...;
- List of figures, tables, and algorithms;
- Appendices;
- Bibliography (author-year citations that abbreviate to 1 author if more than 2);
- Index;
- Pseudocode;
- Syntax-highlighted code;
- Block quotes;

... and comes with a pre-determined folder structure to keep all your files organised from the start.

Contains very specific fixes for doing things like:
- Citing an author in a section title, and having it appear correctly in the page headings.
- Linking to the page of a label, rather than to the title of the section it appears in.
- Linking to a line in an algorithm.
- Continuing subequations after the next equation.
- Choosing to add terms to the index in lowercase while allowing them to be capitalised in the text.

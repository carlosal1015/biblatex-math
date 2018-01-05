BibLaTeX styles for Working Mathematicians
==========================================

What's This?
------------
This package provides a BibLaTeX (NOT BibTeX) citation styles for Mathematical articles, which looks alike [`amsrefs`](https://ctan.org/pkg/amsrefs).

It currently provides the following themes:

* `math-numeric`, which uses numbers like [1], [2], [3] ... as a reference label.
* `math-alphabetic`, which uses the part of author names such as [FMS] or [Coh].

In either case, we provide the following package options:

`sentencedtitle` (default: `true`)
:    Whether to make title alphabet sentence-style or not.
If `true`, for example, `The Proof of Riemann Hypothesis` will be rendered as "The proof of riemann hypothesis". To prevent letters to be downcased, you can use braces: `The Proof of {Riemann} Hypothesis` will result it `The proof of Riemann Hypothesis`.
You also have to embrace maths with `{}` otherwise LaTeX halts with an error.

`dashed` (default: `true`)
:    Whether to omit the same author(s) by `_____`, as in `amsrefs`.

Install
-------
Copy `./tex/latex/biblatex/{cbx,lbx,tbx}/*` to `$TEXMF` and run `mktexlsr`.

LICENSE
-------
LaTeX's.
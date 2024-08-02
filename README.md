# gmelocv, personal LaTeX CV/Résumé class

My personal approach for a LaTeX CV/Résumé class.

_Based on the AltaCV by LianTze Lim (liantze@gmail.com)_

## Requirements and Compilation Features
- pdflatex + biber + pdflatex
- gmelocv uses [`fontawesome`](http://www.ctan.org/pkg/fontawesome) and [`academicons`](http://www.ctan.org/pkg/academicons); they're included in both TeX Live 2016 and MikTeX 2.9.
- Loading `academicons` is optional: enable it by adding the `academicons` option to `\documentclass`.
- Can now be compiled with pdflatex, XeLaTeX and LuaLaTeX!
- However if you're using `academicons`, you _must_ use either XeLaTeX or LuaLaTeX. If the doc then compiles but the icons don't show up in the output PDF, try compiling with LuaLaTeX instead.

## How to run
For a simple compilation and pdf generation:
```bash
pdflatex main.tex
```
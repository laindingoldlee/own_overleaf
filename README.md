# own_overleaf

My own LaTeX editor and compiler.

- **Editor:** https://laindingoldlee.github.io/own_overleaf/ (file tree, editor, PDF preview, Compile button).
- **How it works:** the editor saves files to this repository and asks GitHub Actions to compile them. PDFs and logs are stored on the `pdf` branch.
- **Engine:** XeLaTeX if the file loads `ctex`, `xeCJK` or `fontspec`; pdfLaTeX otherwise. Asymptote diagrams run automatically.
- **Chinese:** use `\usepackage[UTF8,fontset=none]{ctex}` with `\setCJKmainfont{Noto Serif CJK TC}`, and `\usepackage[inline]{asymptote}` for Chinese inside diagrams. See `chinese-test/main.tex`.

The editor's code is `docs/index.html`. The compiler is `.github/workflows/compile.yml`.

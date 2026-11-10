# own_overleaf

My LaTeX projects. Every time a `.tex` file changes on `main`, GitHub Actions compiles it.

- **Edit:** press `.` on the repo page to open the web editor, then commit.
- **Get the PDF:** switch the branch dropdown from `main` to `pdf`. The `.log` file sits next to each PDF.
- **Engine:** XeLaTeX if the file loads `ctex`, `xeCJK` or `fontspec`; pdfLaTeX otherwise. Asymptote diagrams run automatically.

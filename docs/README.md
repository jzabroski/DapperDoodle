This is a technical analysis of features in Python's ReportLab library, that we probably want to have in our own reporting solution for .NET:

[src/reportlab/pdfgen/canvas.py](https://github.com/Distrotech/reportlab/blob/master/src/reportlab/pdfgen/canvas.py)
- a Canvas object for creating PDFs
- helpers to guess color space for gradients
  - Why not just use a color palette that works well?
    - [d3-scale-chromatic](https://github.com/d3/d3-scale-chromatic) supports Sequential, diverging and categorical color scales

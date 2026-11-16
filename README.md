# nb2pdf

Utility to convert Jupyter Notebooks to PDF for assignment submission through Turnitin.

**Use it here:** https://drjwhitty.github.io/nb2pdf/

1. In Jupyter, run every cell (Run → Run All Cells), save, and download the notebook (File → Download) as an `.ipynb` file.
2. Open the page above, drop in the `.ipynb` file and add your name and student ID.
3. Check the preview, click **Print / Save as PDF** and choose **Save as PDF**.

Everything happens in your own browser: the notebook is never uploaded anywhere. The page warns you about cells that have not been run, cells that ended in an error, and `...` gaps left from the template.

Built for Unit 4002 Engineering Mathematics (BTEC HNC), Preston College. Bundles [marked](https://github.com/markedjs/marked) (MIT) and [MathJax](https://www.mathjax.org/) (Apache 2.0).

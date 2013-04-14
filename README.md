# joycv #

This is a simple and elegant Curriculum Vitae (CV) or Resume template
for LaTeX (XeTeX, actually). This template was inspired by work from Alessandro Plasmati. You
can find the original templates in the templates dir.

I have refactored and cleaned up all the template configurations and macros into a separate style: **joycv.sty**

You can check out my own CV formatted with joycv as an example: **cv.tex**

To generate the PDF you just run:

	xelatex cv.tex

or

	pdflatex cv.tex

If you are on Mac OS X and use MacTeX Basic you will need to install the
following packages (e.g. *sudo tlmgr install PACKAGE_NAME*):

- currvita
- classicthesis
- palatino
- soul
- titlesec
- tocloft
- mathpazo
- lm
- zapfding
- enumitem


Feel free to fork and edit! I will be happy to integrate patches and improvements.

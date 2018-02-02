beamer theme for UChicago-themed presentation slides
====================================================

A custom LaTeX beamer theme is defined for University of Chicago-themed
presentation slides. The focus is simplicity;
the footer navigation symbols in standard beamer are suppressed.
The general
color theme is, not surprisingly, based on the iconic UChicago maroon.

Use
---

To use this beamer theme, simply use the beamer class as usual and
call the `UChicago` theme in the preamble of your `.tex` file:

~~~ latex
\documentclass{beamer}
\usetheme{UChicago}
~~~

The theme depends on packages `graphicx` and `textpos`.

Please be sure that `beamerthemeUChicago.sty`, `uchicago.eps`, and
`ucseal.eps`
are in the same directory as your LaTeX document.


Sample
------

For a working example, please see `sample-doc.tex` and `sample-doc.pdf`
included in this repository. Screenshots:

![slide1](slide1.png)

![slide](slide2.png)

![slide3](slide3.png)


Repository
----------

This `UChicago` LaTeX beamer theme is hosted at https://github.com/jacksonllee/uchicago-beamer


Copyright
---------

MIT License. See [LICENSE.txt](LICENSE.txt).

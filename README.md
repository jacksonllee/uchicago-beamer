LaTeX style file for UChicago-themed presentation slides
========================================================

The style file `ucslides.sty` defines a simple LaTeX template of University of
Chicago-themed presentation slides, without the beamer-specific class properties.

Use
---

To use this style file, do the following in your document's preamble:

- Define these three values: `\title`, `\author`, `\date`
- Define two new commands: `\shortauthor`, `\shorttitle`
- *After* these five things are defined, put down `\usepackage{ucslides}`.

Please be sure that both the `.sty` file and `uchicago.eps` are
in the same directory as your document.

For a working example, please consult `sample-doc.tex` and `sample-doc.pdf`
in the GitHub repository.


Copyright
---------

Copyright 2015 Jackson Lee

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

 http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.


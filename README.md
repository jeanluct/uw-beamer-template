# Madison Beamer template

A LaTeX Beamer template with a University of Wisconsin - Madison theme.

The easiest way to install this theme is to just dump the *.sty files
into the same directory as your tex source.

A minimal Beamer presentation using this template looks something like
the following:

```latex
\documentclass{beamer}

\usetheme{Madison}

\begin{document}
%% Slides
\end{document}
```

The theme currently has a few options:
  * nav          - This option includes a navigation bar in the
                   lower-right corner of each slide
  * white        - This option changes the color scheme to black-on-white
                   for projectors with poor color balance
  * nologo       - Suppress the crest in frame titles
  * compactlogo  - Compact title logo (takes less vertical space)

Options are specified as:
```latex
  \usetheme[white]{Madison}
```

Other suggested packages:
* tikz (pgf, for diagrams)
* listings (for source code listings)
* fontspec (if using xetex)

# License

# Original release

Original author: Tristan Ravitch (travitch@cs.wisc.edu)
Initial Release: June 2009
Public Domain

# This release

This release of the UW Beamer template is released under the MIT License.

Copyright 2021 Jean-Luc Thiffeault

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

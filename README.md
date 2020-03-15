# Summary

The Oscola package works (only!) with Biblatex (v3.14 or later) and
Biber (v2.14 or later). It aims to implement, almost completely, the
OSCOLA style of legal citation, according to the
[4th edition](https://www.law.ox.ac.uk/sites/files/oxlaw/oscola_4th_edn_hart_2012.pdf). For
further information about coverage see the documentation.

# Files and licence

## The package

The package consists of five principal files (`oscola.bbx`, `oscola.cbx`, and three language definition files,
`english-oscola.lbx`, `british-oscola.lbx`, and `american-oscola.lbx`). There is also a very short index
style file, `oscola.ist`. Those files are copyright (c) Paul Stanley
2012-20.

This work may be distributed and/or modified under the conditions of
the LaTeX Project Public License, either version 1.3 of this license
or (at your option) any later version.

The latest version of the license is in [available online](http://www.latex-project.org/lppl.txt)
and version 1.3 or later is part of all distributions of LaTeX version 2005/12/01 or later.

This work has the LPPL maintenance status 'maintained'. The current
maintainer of this work is Paul Stanley (pstanley@essexcourt.net).

## The documentation

The documentation consists of `oscola.tex`, `oscola.pdf` and
`oscola-examples.bib`. Those files are distributed under the Creative
Commons Attribution 3.0-Unported License (CC BY 3.0). A copy of that
license is available [online](http://creativecommons.org/licenses/by/3.0/deed.en_GB).

## Bug reports

All bug reports, questions, or suggestions should be sent to the
maintainer, whose email is pstanley@essexcourt.net.

# Installation

I find the TDS difficult. TeXlive, whose maintainers apparently don't,
currently installs as follows:

* `oscola.bbx`: in the package directory `...tex/latex/oscola`
* `oscola.cbx`: in the package directory `.../tex/latex/oscola`
* `english-oscola.lbx`: in the package directory `.../tex/latex/oscola`
* `british-oscola.lbx`: in the package directory `.../tex/latex/oscola`
* `american-oscola.lbx`: in the package directory `.../tex/latex/oscola`
* `oscola.pdf` and `oscola.tex`: with documentation under `.../doc/latex/oscola`
* `oscola.ist`: with the index style files in  `.../makeindex/oscola`

# Version history

August 2012     Version 1      Original release

May 2013        Version 1.2    Various bugfixes, and implementation
                               of citation scheme for UN documents

October 2013    Version 1.3    Corrected spacing bug

May 2014        Version 1.4    Various bugs have been fixed, an additional
                               index has been installed, and there have
                               been minor improvements to the documentation

March 2017      Version 1.5    The package has been updated to take
                               account of changes in Biblatex; various bugs
                               have been fixed; experimental support has
                               been added for the use of ECLI numbers
                               in EU cases.

March 2018      Version 1.6    The package has been updated again to take
                               account of minor changes in Biblatex; various
                               bugs have been fixed; support for \\textcite has been
                               improved.

March 2020      Version 1.7    The package has been updated to take
                               account of changes in Biblatex.

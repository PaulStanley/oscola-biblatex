SUMMARY
=======

The Oscola package works (only!) with Biblatex (v 2.0 or later) and
Biber (v 1.0 or later). It aims to implement, almost completely, the
OSCOLA style of legal citation, according to the 4th edition. For
further information about coverage see the documentation.

FILES AND LICENCE
=================

The package consists of three principal files (oscola.bbx, oscola.cbx
and english-oscola.lbx) which should be placed, documentation
(oscola-documentation.pdf), and a very short index style file
(oscola.ist). Those files are copyright (c) Paul Stanley 2012.

This work may be distributed and/or modified under the
conditions of the LaTeX Project Public License, either version 1.3
of this license or (at your option) any later version.

The latest version of the license is in
      http://www.latex-project.org/lppl.txt
and version 1.3 or later is part of all distributions of LaTeX
version 2005/12/01 or later.

This work has the LPPL maintenance status 'maintained'. The current
maintainer of this work is Paul Stanley (pstanley@essexcourt.net)

The documentation consists of oscola-documentation.pdf and
oscola-examples.bib. Those files are distributed under the Creative
Commons Attribution 3.0-Unported License (CC BY 3.0). A copy of that
license is available at
  http://creativecommons.org/licenses/by/3.0/deed.en_GB

The LaTeX source of oscola-documentation.pdf is available upon request
from the author.

All bug reports, questions, or suggestions should be sent to the
maintainer, whose email is pstanley@essexcourt.net.

INSTALLATION
============

I find the TDS difficult, but I think the correct installation (under
the local tree) is as follows:

oscola.bbx: With the bibliography style files in 
            ...tex/latex/biblatex/bbx
oscola.cbx: With the citation style files in
            .../tex/latex/biblatex/cbx
english-oscola.lbx: With the language definition files in
            .../tex/latex/biblatex/lbx
oscola-documentation.pdf: With documentation in a suitable directory 
            under .../doc/latex
oscola.ist: With the index style files in 
            .../makeindex/latex
oscola-examples.bib: With the sample bibliography files in a suitable 
            directory under .../bibtex/bib

VERSION HISTORY
===============

August 2012      Version 1	Original release

September 2012   Version 1.1	Various bugfixes and corrections to
	  	 	 	the documentation.

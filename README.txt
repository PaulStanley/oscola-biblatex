SUMMARY
=======

The Oscola package works (only!) with Biblatex (v 2.0 or later) and
Biber (v 1.0 or later). It aims to implement, almost completely, the
OSCOLA style of legal citation, according to the 4th edition. For
further information about coverage see the documentation.

FILES AND LICENCE
=================

The package consists of four principal files (oscola.bbx, oscola.cbx,
english-oscola.lbx, and british-oscola.lbx), documentation
(oscola.tex, oscola.pdf and a sample bibliography file), and a very
short index style file (oscola.ist). Those files are copyright (c)
Paul Stanley 2012-17.

This work may be distributed and/or modified under the conditions of
the LaTeX Project Public License, either version 1.3 of this license
or (at your option) any later version.

The latest version of the license is in
     http://www.latex-project.org/lppl.txt
and version 1.3 or later is part of all distributions of LaTeX
version 2005/12/01 or later.

This work has the LPPL maintenance status 'maintained'. The current
maintainer of this work is Paul Stanley (pstanley@essexcourt.com).

The documentation consists of oscola.tex, oscola.pdf and
oscola-examples.bib. Those files are distributed under the Creative
Commons Attribution 3.0-Unported License (CC BY 3.0). A copy of that
license is available at
     http://creativecommons.org/licenses/by/3.0/deed.en_GB

All bug reports, questions, or suggestions should be sent to the
maintainer, whose email is pstanley@essexcourt.com.

INSTALLATION
============

I find the TDS difficult. TeXlive, whose maintainers apparently don't,
currently installs as follows:

oscola.bbx: With the bibliography style files in 
            ...tex/latex/oscola
oscola.cbx: With the citation style files in
            .../tex/latex/oscola
english-oscola.lbx: With the language definition files in
            .../tex/latex/oscola
british-oscola.lbx: With the language definition files in
            .../tex/latex/oscola
            
oscola.pdf and oscola.tex: With documentation in a suitable directory 
            under .../doc/latex/oscola
            
oscola.ist: With the index style files in 
            .../makeindex/oscola

VERSION HISTORY
===============

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

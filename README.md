Package pgf-blur
================

The package adds blurred/faded/fuzzy shadows to PGF/TikZ pictures.
It is configured as a TikZ/PGF library module. 

Run (pdf)latex on pgf-blur.dtx to produce a TikZ library file
and the documentation.

Development
-----------

Martin Giese has stopped working on pgf-blur and pgf-blur is now
developed at https://github.com/norbusan/pgf-blur

Issues and Bugs
---------------

Please report issues to https://github.com/norbusan/pgf-blur/issues

Currently (as of TL2018) multiple drop shadows can produce problems
with xelatex (dvipdfmx) when including a pdf with drop shadows into
another pdf. A typical error is

	xdvipdfmx:fatal: Loop in object hierarchy detected. Broken PDF file?

This will be fixed in TL2019 with an update to dvipdfmx. luatex and pdftex
do not exhibit this problem.


License and Copyright
---------------------

	Copyright 2012 Martin Giese, martingi@ifi.uio.no
	Copyright 2012 Andrew Stacey
	Copyright 2018 Norbert Preining, norbert@preining.info

This file is under the LaTeX Project Public License 
See CTAN archives in directory macros/latex/base/lppl.txt.
See http://www.ctan.org/tex-archive/help/Catalogue/licenses.lppl.html
for the details of that license.


Details:

The original version was developed by Martin Giese:

	Copyright 2012 Martin Giese, martingi@ifi.uio.no

who handed over maintainership to Norbert Preining in 2018

Message-Id: <BDCE3150-A170-4AC9-B1E3-2903DA9D390F@ifi.uio.no>

	Ich finde es gut, wenn sich jemand um die Verbesserung der package kümmern möchte.
	Wenn du willst kannst du gerne die Rolle des Maintainers übernehmen.  Ich werde
	selber wahrscheinlich keine Zeit mehr haben, mich darum zu kümmern.  So lange
	die Doku einen Hinweis behält, dass die ursprüngliche Version von mir kam,
	bin ich glücklich.

Additions by Andrew Stacey are public domain, CC0, or LPPL

	Copyright 2012 Andrew Stacey

Message-ID: <cd8cae1b-c5c9-9fcc-8822-fff529375bb5@mathforge.org>

	"My additions to the pgf-blur code are hereby placed in the public domain to
	the extent governable by law.  Explicitly, they are dually placed under the
	CC0 licence and the LPPL licence."

Current maintainership, uploads, etc

	Copyright 2018 Norbert Preining, norbert@preining.info


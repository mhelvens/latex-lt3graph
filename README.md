latex-lt3graph
=============

LaTeX Package : lt3graph 0.1.1

Last Modified : 2014-04-14

Author        : Michiel Helvensteijn  (www.mhelvens.net)


Summary
-------

A graph datastructure for the LaTeX3 programming environment


Prerequisites
-------------

To use this package, you need the following packages:

*  `l3candidates`
*  `l3clist`
*  `l3msg`
*  `l3prg`
*  `l3prop`
*  `xparse`
*  `withargs`

The following package is optional, loaded only when the package
is loaded with the 'display' option, for displaying graph info
in a table:

*  `xcolor`

To generate the documentation some additional packages are needed.


Installation
-------------

`lt3graph.sty` is provided directly in the package archive. Put
it in a place where your LaTeX distribution can find it.

(`lt3graph.sty` is not generated, but manually maintained; you
 may use docstrip to remove the documentation, but you don't
 have to; it will just work the way it is)


Documentation
-------------

`lt3graph.pdf` is provided directly in the package archive. To
generate the documentation yourself, run LaTeX on lt3graph.tex.

(`lt3graph.tex` does not contain the package code itself; it inputs
 `lt3graph.sty` directly to document the implementation)


License
-------

This material is subject to the LaTeX Project Public License. See
http://www.ctan.org/tex-archive/help/Catalogue/licenses.lppl.html 
for the details of that license.

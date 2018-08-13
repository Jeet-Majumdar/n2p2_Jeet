n2p2 - The neural network potential package
===========================================

[![DOI](https://zenodo.org/badge/142296892.svg)](https://zenodo.org/badge/latestdoi/142296892)

This repository provides ready-to-use software for high-dimensional neural
network potentials in materials science.

# Documentation

## Online version
This package uses automatic documentation generation via
[doxygen](http://www.stack.nl/~dimitri/doxygen/). An online version of the
documentation which is automatically updated with the main repository can be
found [__here__](http://compphysvienna.github.io/n2p2).

## Build your own documentation
It is also possible to build your own documentation for offline reading. This
requires [doxygen](http://www.stack.nl/~dimitri/doxygen/) and
[graphviz](https://www.graphviz.org/) to be installed on your system (tested
with doxygen version 1.8.14 and graphviz version 2.36.0). If the requirements
are met change to the `src` directory and try to build the documentation:
```
cd src
make doc
```
If the build process succeeds you can browse through the documentation starting
from the main page in:
```
doc/html/index.html
```
_Note:_ If `graphviz` is not available on your system you can still build the
documentation if you set the option `HAVE_DOT` in the file `src/doc/Doxyfile` to
`NO`. However, then there will be no graphs generated by `doxygen`.

# Authors

 - Andreas Singraber (University of Vienna)

# License

This software is licensed under the [Mozilla Public License Version 2.0 (MPL 2.0)](https://www.mozilla.org/en-US/MPL/2.0/).

# Generating Closed Modular Colorings of Graphs Using SAT solver

(Accompanying materials to "The Signal Detection Problem: Closed Modular
Colorings on Grid Graphs", by Jan Hlavacek and Garry L. Johns, submitted for
publication.)

We present an algorithm for generating closed modular colorings of graphs with
no true twins, by translating the problem to a satisfiability problem and using
a satisfiability solver.  The description of the algorithm with the Python code
and number of examples of closed modular colorings of grid graphs is available
in [coloring_sat.pdf](coloring_sat.pdf).  The PythonTeX [source](coloring_sat.tex) is also provided.

## Requirements

You will need the following software to use our code to generate your own
closed modular colorings:

- A Python distribution, preferably version 3 or higher.

- The [PicoSAT](http://fmv.jku.at/picosat/) satisfiability solver.  We actually
  use the Python module [pycosat](https://github.com/ContinuumIO/pycosat), also
  available [on pypi](https://pypi.python.org/pypi/pycosat).  It can be
  installed using `pip` (or `pip3`) and is completely self contained, so you do
  not have to install PicoSAT in order to use the python module.

- We use the [graph-tool](https://graph-tool.skewed.de/) Python module for
  representing graphs.  Installation instructions are available [here](https://git.skewed.de/count0/graph-tool/wikis/installation-instructions#native-installation).  Unfortunately there currently does not seem to be a reliable way to use graph-tool on Windows.

- We provide the code and its documentation in the form of a
  [PythonTeX](https://github.com/gpoore/pythontex) document.  You may need to
  install PythonTeX in order to compile the document after making any
  modification.  You may also be able to manually extract the Python code from
  the document and run it directly.

## License

The software is released under an MIT style license. In essence, you can use and modify the
sources as you like provided that you acknowledge the origin of the software in
the source code. More details can be found in the [LICENSE](LICENSE) file that comes with
the sources.

## Availability

This material is currently available at the following locations:

- Jan Hlavacek's website: <http://www.svsu.edu/~jhlavace/close_mod_sat/README.html>
- GitHub: <https://github.com/lahvak/close_mod_sat>

## Communications

Please direct any communications about this software to Jan Hlavacek, at
`jhlavace@svsu.edu`.

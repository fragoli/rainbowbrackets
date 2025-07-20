# RainbowBrackets v. 1.2.1 \y 2025
> Part of a collection of LaTeX commands used by the institute of linguistics - Goethe University Frankfurt

Provides automatic coloring of nested parentheses using a configurable color cycle.

## Description

The primary function of this package is to replicate a common feature found in many integrated development environments (IDEs), wherein matching parentheses at the same nesting level are assigned corresponding colors. This visual aid facilitates improved readability and cognitive parsing of complex expressions.

### Dependencies

* {LaTeX2e}
* {xparse, xstring, xcolor, expl3, kvoptions}

## Authors

ex. Paul Eduard Koenig (based on work from Ryan Reich, jub0bs, and Matthew Towers)

## Version History

* 1.2.1
	* Renamed some commands to get a cohesive command style (now all start with rb).
	* Add optional package arguments to change bracket symbols.
	* Add commands to change bracket symbols.
	* Add new commands to temporarily disable coloring.
	* Add new commands to temporarily change the text mode of the brackets.
	* Add new italic environment.
* 1.1.1
    * Add new styles
    * Refactored style system.
    * Fix typos.
    * Added missing credits!
* 1.0.0
    * Initial Release

## License

This program can be redistributed and/or modified under the terms
of the LaTeX Project Public License Distributed from CTAN archives
in directory macros/latex/base/lppl.txt.

[<span style="font-size: 150%;font-weight:bold;">&#8962;</span> home](http://coasttocoastresearch.com/)

**Annotated Table of Contents**<br>
*JavaScript APG Parsing Library*

0. The GitHub & npm README page.
> [README.md](./README.html)

0. The Abstract Syntax Tree (AST) object constructor.
> [ast.js](./ast.html)<br>

0. A circular buffer object constructor. Used by [trace](./trace.html) to limit the number of trace records saved.
> [circular-buffer.js](./circular-buffer.html)<br>

0. Module to export the entire library from a single module. This is the file that loads with the statement `require("apg-lib");`
> [export.js](./export.html)<br>

0. Numerical identifiers used throughout `apg` and `apg-lib` to identify operators, states, etc.
> [identifiers.js](./identifiers.html)<br>

0. The Parser. This is the main program that traverses the parse tree of opcodes,
matching phrases from the input string as it goes.
> [parser.js](./parser.html)<br>

0. The statistics object constructor.
> [stats.js](./stats.html)<br>

0. The trace object constructor
> [trace.js](./trace.html)<br>

0. A library of utility functions and objects.
> [utilities.js](./utilities.html)<br>

0. Use apg-lib in a web page. Used to "browserify" apg-lib to apglib.js & apglib-min.js for use in a web page.
> [apglib-gen.js](./apglib-gen.html)<br>

0. The export function. Exports all of the necessary apg-lib modules upon request("apg-lib');
> [export.js](./export.html)<br>


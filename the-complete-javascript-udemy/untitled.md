# How js code works behind the Scenes

## Javascript Parsers and Engines

![](../.gitbook/assets/screen-shot-2019-06-19-at-3.52.15-pm.png)

* Our code is parsed by a parser,  which basically reads our code line by line,

  and checks if the syntax of the code that we gave it,

  is correct. So this means that the parser knows the JavaScript rules

* If the code is incorrect, parser will throws an error and stops the execution.
* If everything is correct though, then the parser produces a data structure known as the Abstract Syntax Tree, which is then translated into machine code.

## Execution contexts and the Execution Stack

All JavaScript code needs to run in an environment, and these environments are called execution contexts.


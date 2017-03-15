# optional static type notation
for a variable, the type notation comes after the variable name and is preceded by a colon, like this:
var counter : number;
this style of type notation is based on type theory and reinforce the idea of types being optional.

# any type
this is the same as declaring a variable in pure javascript

# var, let, const
var - scoped to the nearest function block
let - scoped to the nearest enclosing block
const - constant variable scoped to the nearest enclosing block

# union types
combines two or more types, separated by "|"

# type guards
statements inside an if block, if the condition is based on typeof or instanceof, will be checked against using those types, guarding against mis-using the statements.

# type aliases
use the type keyword to define an alias to a type.  avoid using this.

# ambient declaration
using declare operator to add to the scope.

typescript, by default, includes a file named lib.d.ts that provides interface declarations for built-in javascript library as well as the DOM.

declaration files use the file extension .d.ts


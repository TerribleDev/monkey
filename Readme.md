These are my source files for working on Thorsten Ball's [Writing an interpreter in go](https://interpreterbook.com/) book. The ultimate goal of this source code is to interpret, and execute code written in a language called monkey.

An example of monkey is below. Monkey is a c-like language with closures, first class functions, and variable bindings.

```monkey

let five = 5;
let ten = 10;

let add = fn(x, y) {
  x + y;
};
return add(5,5);

```
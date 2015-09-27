# math-expressions

Parse expressions like `sin^2 (x^3)` and do some basic computer
algebra with them, like symbolic differentiation and numerically
identifying equivalent expressions.

# Client-side use

There is a [demo available](https://rawgit.com/kisonecat/math-expressions/master/demo/index.html) which focuses on the equality testing.

## Installation

## Example

# Server-side use

## Installation

INSTRUCTIONS FOR npm install

## Example

```JavaScript
var Expression = require('math-expressions');

var f = Expression.fromText("sin^2 (x^3)");

console.log(f.tex());

var g = Expression.fromText("sin^2 x + cos^2 x");
var h = Expression.fromText("1");

console.log( g.equals(h) );

var g = Expression.fromText("x + x^2");
var h = Expression.fromText("x + x^3");

console.log( g.equals(h) );
```

# API

Coming soon!

# Contributing

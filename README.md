# Tom's Lisp Parser

What is it? How do you make it? How does anyone make anything ever? Maybe I'll find out.

---

## Prompt Text

Write code that takes some Lisp code and returns an abstract syntax tree. The AST should represent the structure of the code and the meaning of each token. For example, if your code is given "(first (list 1 (+ 2 3) 9))", it could return a nested array like ["first", ["list", 1, ["+", 2, 3], 9]].

During your interview, you will pair on writing an interpreter to run the AST. You can start by implementing a single built-in function (for example, +) and add more if you have time.

---

## History

Lisp or LISP is not a single programming language but more like a general definition of a language whose syntax is fully driven by parenthesizing nested or dependent operations and defining those operations with prefixed operators. What does any of that mean? From a layperson's perspective that might mean that I would express `1 + 1` like this `(+, 1, 1)` or `["+", 1, 1]` etc. And if I wanted to express something more complex like `1 + 5 * 2` I would need to manually express it as `(+, 1, (*, 5, 2))`. 

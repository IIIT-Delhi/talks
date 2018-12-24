Babel.js (& other PL projects)

Filter By Category > Programing Languages and Developement Tools
  - Projects I know about: Processing, Coala, Babel

Required:
  - JavaScript (or the PL to be analyzied)
  - Basic Compiler Concepts (~20 minutes for an intro)
      - Terms: Parser, Transforms, AST, Specification

What You Can do Afterwards:
  - not much, sadly
  - a lot if you don't care about convinience
  
## Links
  - [AST Explorer](https://astexplorer.net/) Select any language from the top menu item, default selected is JavaScript. There's another website for [Python](https://python-ast-explorer.com/)
 
The basic task I did for my gsoc proposal:

Figuring out how to convert 
```js
function hi(a, b, c, d, ...rest) {
  return rest;
}
```

to 

```js
function hi(a, b, c, d) {
  var rest = Array.prototype.slice(arguments, 4);
  return rest;
}
```

Explanation: the syntax `...rest` is also *was* new in JavaScript, what it does is if you pass 10 arguments to the function `hi`, first four get stored in `a, b, c, d`, and the other 6 get stored in an array which is set to `rest`.

`Array.prototype.slice(arguments, 4)` gives you what you're looking for - of all the arguments, it gives you an array of all but the first four.

Ideas?

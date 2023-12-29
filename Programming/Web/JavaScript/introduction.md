---
title: Introduction to JavaScript
date: Dec 29, 2023
author: Devendra Vasant Katuke
---

Earlier there was no 'Google Chrome', or other browsers, which you know today. Only 'Internet Explorer', which had nearly 95-99% market share. Of-course, 'Others' like 'Mosaic', later repackaged as 'Netscape Navigator' used to be there.

Internet Explorer only supported 'JScript' and 'VBScript'. These languages were fairly capable, but proprietory.

The story of evolution of Javascript, and it's standardization as ECMAScript can be read [here](https://en.wikipedia.org/wiki/JavaScript).

There are some transpilers(transcompilers), toolchains like babel, ESBuild, TypeScript, CoffeeScript, LiveScript etc. which make your code meet some conditions (browser compatible, minified, strict, etc.).

Most transpilers use [Abstract Syntax Tree (AST)](https://en.wikipedia.org/wiki/Abstract_syntax_tree) as intermediate format while processing source file, transforming syntax, performing optimizations.

```
Code --(parse)--> AST --(transform)--> AST --(generate)--> Code
```

There are some compilers which convert another language into Javascript. [Here](https://github.com/jashkenas/coffeescript/wiki/List-of-languages-that-compile-to-JS) is the extensive list.

So you can write browser side Javascript without knowing Javascript, but I won't recommend it.

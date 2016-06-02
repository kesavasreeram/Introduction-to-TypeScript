# Introduction-to-TypeScript
A short introduction to the world of TypeScript

## Introduction
TypeScript is a superset of JavaScript. It support strong typing of variables as opposed to JavaScript which is typeless. This makes programing in TypeScript a lot more maintainable. TypeScript also makes it easier to refactor and debug large applications written in JavaScript.

Along with the support of strong typing, TypeScript also contains ES6 features: The ability to create classes, interfaces etc. Advantages of ES6 features will be discussed later in the pages.

### Points to remember

1. TypeScript is made to use at design time
2. It renders JavaScript

## Strong typing, how does it work
Do not worry if you are unfamiliar with any typed programmed language, if you are then you should have mostly used the following style while creating a new variable:

\<variable type\> \<variable name\> = \<some valid value\>;
or 
\<variable type\> \<variable name\>;

example: **String** str; where **String** is the variable type specifying that the variable **str** is of type String.

However in case of TypeScript the declaration is a bit different, here you use

\<variable name\>: \<variable type\>

example: str: **String**; specifying that the expected type of variable **str** is String.

## Automate TypeScript builds
Inorder to automate building the TypeScript files to JavaScript files, we use Gulp. Grunt can also be used.

Gulp is a task runner for JavaScript and TypeScript. A TypeScript Gulp/Grunt task can compile the TypeScript(.ts) file to JavaScript(.js) file.
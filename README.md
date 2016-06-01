# Introduction-to-TypeScript
A short introduction to the world of typescript

## Introduction
Typescript is a superset of Javascript. It support strong typing of variables as opposed to Javascript which is typeless. This makes programing in typescript a lot more maintainable. Typescript also makes it easier to refactor and debug large applications written in Javascript.

Along with the support of strong typing, typescript also contains ES6 features: The ability to create classes, interfaces etc. Advantages of ES6 features will be discussed later in the pages.

### Points to remember

1. Typescript is made to use at design time
2. It renders Javascript

## Strong typing, how does it work
Do not worry if you are unfamiliar with any typed programmed language, if you are then you should have mostly used the following style while creating a new variable:

\<variable type\> \<variable name\> = \<some valid value\>;
or 
\<variable type\> \<variable name\>;

example: **String** str; where **String** is the variable type specifying that the variable **str** is of type String.

However in case of typescript the declaration is a bit different, here you use

\<variable name\>: \<variable type\>

example: str: **String**; specifying that the expected type of variable **str** is String.
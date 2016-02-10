# fKAT Documentation

## Coding convention

The number one rule: use common sense. Other important principles:

* give plenty of thought to naming, naming is important!
* follow widely used JS/Node coding conventions, such as:
  * http://javascript.crockford.com/code.html
  * https://github.com/felixge/node-style-guide

As a departure from most conventions, this declaration style:
```
var someVar,
    otherVar,
    yetAnotherVar;
```
... should *not* be used. It's an eyesore, and doesn't really contribute
to readability or anything. Declare `var`s separately, each on its own line:
```
var someVar;
var otherVar;
var yetAnotherVar;
``` 
Also, indentation should be 4, not 2 spaces. And because of that,
80 characters per line is awfully little - up to 120 characters per line
is perfectly fine.

## Best practices

Again, *think*. And learn as much as you can. Some sources:

* https://www.joyent.com/developers/node/design
* https://blog.risingstack.com/node-js-best-practices/
 

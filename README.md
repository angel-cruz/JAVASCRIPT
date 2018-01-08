# JAVASCRIPT
### JavaScript ES6 Notes &amp; applications

## Values & Types:

- String
- number
- boolean
- null and undefined
- object
- Symbol (new to ES6)

## typeof operator:
'''

var a;
typeof a;     // "undefined"

a = "hello world";
typeof a;     /// "String"

a = 42;
typeof a;     // "number"

a = true;
typeof a;     // "boolean"

a = null;
typeof a;     // "object"--weird, bug

a = undefined;
typeof a;     // "undefined"

'''

* typeof null is an interesting case because it errantly returns "object" when you'd expect it to return "null" *

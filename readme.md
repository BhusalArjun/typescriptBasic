transcript+transpile/compile=javascript


command prompt to install the TypeScript

npm install -g typescript
checking version=tsc --version

TypeScript is object-oriented JavaScript. TypeScript supports object-oriented programming features like classes, interfaces, etc. A class in terms of OOP is a blueprint for creating objects. A class encapsulates data for the object. Typescript gives built-in support for this concept called class. JavaScript ES5 or earlier didn’t support classes. Typescript gets this feature from ES6.

Creating classes
Use the class keyword to declare a class in TypeScript. The syntax for the same is given below −

Syntax
class class_name { 
   //class scope 
}
The class keyword is followed by the class name. The rules for identifiers must be considered while naming a class.

A class definition can include the following −

Fields − A field is any variable declared in a class. Fields represent data pertaining to objects

Constructors − Responsible for allocating memory for the objects of the class

Functions − Functions represent actions an object can take. They are also at times referred to as methods

These components put together are termed as the data members of the class.

Consider a class Person in typescript.

class Person {
}
On compiling, it will generate following JavaScript code.

Generated by typescript 1.8.10
var Person = (function () {
   function Person() {
   }
   return Person;
}());

//object
Syntax
var object_name = new class_name([ arguments ])
The new keyword is responsible for instantiation.
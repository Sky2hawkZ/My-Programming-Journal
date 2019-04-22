# Typescript Notes

When you override a function using inheritance in typescript, it doesn't automatically call the function from it's parent extender, you have to run the function with the following syntax `super.FunctionToCall()` to run the function in the parent.

The Typescript onion

Innermost Layer: ES5
Middle Layer: ES6; Class, Modules...
Outermost Layer: Typescript; ES2016, Decorators, Typing
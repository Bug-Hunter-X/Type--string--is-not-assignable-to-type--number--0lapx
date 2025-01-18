# Type 'string' is not assignable to type 'number' in TypeScript
This example demonstrates a common type error in TypeScript where you try to pass a string value to a function expecting a number. 
The `combineArrays` function is designed to work with arrays of numbers. However, `arr2` contains a string ("6"), which causes a type error. This is because TypeScript's type system enforces type safety.
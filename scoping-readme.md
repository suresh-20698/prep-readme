# Scope

### Explanation

- Scope is similar to a container where the javascript stores variables and functions
- Scope determines the visibility and lifetime of those variables and functions
- Scope helps organize and manage your code by defining where certain variables can be accessed and modified

### Types of Scopes

- Global Scope
- Function Scope
- Block Scope
- Module Scope
- Lexical Scope

## Global Scope

### Explanation

- Global variables can be declared using `var` `let` `const`
- Global scope refers to the outermost level of scope
- Variables declared in the global scope are accessible from anywhere
- Global variables persist throughout the entire lifetime of JavaScript program
- If a variable declared outside of any block or function its considered as global variable

#### Example

![decode-example-image](https://i.ibb.co/dcSggmr/Screenshot-from-2024-03-13-13-08-34.png)

## Function Scope

### Explanation

- Variables declared with `var` `let` `const` inside a function are considered local variables
- Variables declared inside a function are accessible only within that function's scope. They cannot be accessed from outside the function
- Local variables are created when the function is called and destroyed when the function exits

#### Example

![decode-example-image](https://i.ibb.co/Qb8nWJf/Screenshot-from-2024-03-13-14-13-04.png)

## Block Scope

### Explanation

- Block scope in JavaScript refers to the scope created by enclosing code within curly braces `{}`
- Variables declared using `let` and `const` within a block are scoped to that block, They are not accessible outside of that block
- Block scope is commonly used with loops and conditional statements, where the variables declared are only needed within that specific block

#### Example

![decode-example-image](https://i.ibb.co/qFCpwt1/Screenshot-from-2024-03-13-14-23-16.png)

## Module Scope

### Explanation

- Module scope in JavaScript refers to the scope created by modules, which are independent units of code 
- Each module in JavaScript has its own scope, which means that variables, functions, and other declarations within a module are not accessible outside of that module unless explicitly exported
- To make variables, functions, or objects available for use in other modules, they must be explicitly exported using the `export` keyword. Similarly, to use functionality from other modules, they must be imported using the `import` keyword

## Lexical Scope (kind of Inheritance)

### Explanation

- Lexical scope follows a parent-child relationship, where inner blocks or functions have access to variables declared in their outer blocks or functions
- Imagine you have nested functions. Each inner function has access to variables declared in its outer function, and also in the global scope. However, variables declared inside an inner function are not accessible outside of it


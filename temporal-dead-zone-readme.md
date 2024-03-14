
# Temporal Dead Zone (TDZ)

### Explanation

- Temporal Dead Zone is the space between the variable hosited and until the variable is declared in code
- Temporal Dead Zone is an only applicable for variables declared using `let` and `const`
- Even though variables declared with `let` and `const` are hoisted, those variables can't be used until the variable is declared in code

#### Example

- In the below example, since its a variable declared using `var` it can be accessiable before initialization

![decode-example-image](https://i.ibb.co/VpNBr43/Screenshot-from-2024-03-14-11-38-17.png)

- In the below example, since its a variable declared using `let` / `const` it can't be accessiable before initialization, as they are in Temporal Dead Zone

![decode-example-image](https://i.ibb.co/8DBvtJK/Screenshot-from-2024-03-14-11-39-47.png)

- Once the initialization is completed in code, then they can accessiable as same as other variables

![decode-example-image](https://i.ibb.co/qM0dWjM/Screenshot-from-2024-03-14-11-40-27.png)

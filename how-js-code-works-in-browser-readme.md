
# How Browser Engine understands Javascript code

Below are the processes which includes how the code is converted to machine readable and been executed.

- ### Parser
    Parser is a program which knows Javascript modern syntax and rules, so it   takes the code converts into an seperate Abstract Syntax Tree for each and every line of the code and also it throws an error when it come across an syntax error.
    
- ### Abstract Syntax Tree
    Just like how each element is placed like a tree in the DOM, same tree-like structure is been placed for the parsed Javascript code.

- ### Intrepretor
    Intrepretor translates the code by taking line by line and converts the code into IR byte code (Machine Readable).

- ### Complier
    Complier translates the code by taking all the code at once before the code gets executed.

- ### Just In Time Complier
    Its a mixture of Intrepretor and Complier, which allows the translation and execution in a parelell way which eventually saves a lot of time.

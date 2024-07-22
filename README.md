# MonkeyLang Interpreter

This project is part of the book [**"Writting and interpreter in Go"**](https://interpreterbook.com/). This repository keeps track of my progress through the book

# Language Features

- C-like syntax
- Variable bindings
- Integers and booleans
- Arithmetic expressions
- Built-in functions
- First-class and higher-order functions
- Closures
- String data structure
- Array data structure
- Hash data structure

# Language Syntax

### Assignment:

```monkey
let age = 10 * (20/2);
let myArray = [1, 2, 3, 4, 5];
let someHash = {"name": "Felix", "age": 100}
```

### Accessing Elements:

```monkey
myArray[0]
someHash["name"]
```

### Functions:

```monkey
let add = fn(a,b) { return a + b; };
let add = fn(a,b) { a + b; }

add(1,2);
```

#### **Note:** Monkey also supports higher order functions(functions as arguments)

# Interpreter components

- Lexer
- Parser
- Abstract Syntax Tree
- Internal Object System
- Evaluator

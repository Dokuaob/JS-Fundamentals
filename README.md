# JS-Fundamentals

This project contains basic JavaScript scripts for practice.

## Task 0: First constant, first print

### Objective

Write a script that prints: JavaScript is amazing

### Requirements

- Create a constant variable called `myVar` with the value `"JavaScript is amazing"`
- Use `console.log(...)` to print all output
- Do **not** use `var`

### Usage

Run the script with Node.js:

## Task 1: Multi-language Greeting

### Objective

Write a script that prints:

C is fun
Python is cool
JavaScript is amazing

### Requirements

- Use `console.log(...)` to print each line
- Do **not** use `var`
- Each line should be printed on a new line

### Usage

Run the script with Node.js:

## Task 2: Argument Count Response

### Objective

Write a script that prints a message depending on the number of arguments passed.

### Requirements

- If no arguments are passed: print `No argument`
- If one argument is passed: print `Argument found`
- If more than one argument is passed: print `Arguments found`
- Use `console.log(...)` for all output
- Do **not** use `var`
- Use `process.argv` to access command-line arguments

### Usage

```bash
node 2-arguments.js
# Output: No argument

node 2-arguments.js Hello
# Output: Argument found

node 2-arguments.js Hello World
# Output: Arguments found
```

## Task 3: Print First Argument

### Objective

Write a script that prints the **first argument** passed to it.

### Requirements

- If no argument is passed: print `No argument`
- If one or more arguments are passed: print the **first** one only
- Use `console.log(...)` for all output
- Do **not** use `var`
- Do **not** use `.length`
- Use `process.argv[2]` to access the argument

### Usage

```bash
node 3-value_argument.js
# Output: No argument

node 3-value_argument.js Hello
# Output: Hello

node 3-value_argument.js Hello World
# Output: Hello
```

## Task 4: Concatenate Two Arguments

### Objective

Write a script that prints **two arguments** passed to it in the following format:
<first_argument> is <second_argument>

### Requirements

- Use `console.log(...)` for all output
- Do **not** use `var`
- Missing arguments should print as `undefined`

### Examples

```bash
node 4-concat.js c cool
# Output: c is cool

node 4-concat.js c
# Output: c is undefined

node 4-concat.js
# Output: undefined is undefined
```

## Task 5: Convert Argument to Integer

### Objective

Write a script that prints:

- `My number: <integer>` if the first argument can be converted to an integer
- `Not a number` if it cannot

### Requirements

- Use `console.log(...)` for all output
- Do **not** use `var`
- Do **not** use `try/catch`
- Use `parseInt()` and `isNaN()` for validation

### Examples

```bash
node 5-to_integer.js
# Output: Not a number

node 5-to_integer.js 89
# Output: My number: 89

node 5-to_integer.js "89"
# Output: My number: 89

node 5-to_integer.js 89.89
# Output: My number: 89

node 5-to_integer.js School
# Output: Not a number
```

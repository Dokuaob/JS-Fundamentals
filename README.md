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

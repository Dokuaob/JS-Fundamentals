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

## Task 6: Multi-language Loop

### Objective

Write a script that prints 3 lines using:

- An array of strings
- A loop
- Only one `console.log(...)` call
- No `if/else` statements

### Lines to Print

- C is fun
- Python is cool
- JavaScript is amazing

### Example

```bash
node 6-multi_languages_loop.js
# Output:
# C is fun
# Python is cool
# JavaScript is amazing
```

## Task 7: Multi-C Print

### Description

A Node.js script that prints "C is fun" x times, where x is a command-line argument.

### Requirements

- Use `const`, not `var`
- Use a loop (`for` or `while`)
- Use only 2 `console.log()` statements
- If no argument or invalid, print: `Missing number of occurrences`

### Usage

```bash
node 7-multi_c.js 2
# Output:
# C is fun
# C is fun

node 7-multi_c.js
# Output:
# Missing number of occurrences
```

## Task 8: Print a Square

### Description

This script prints a square made of the character `X`.

### Requirements

- Argument: Size of square (positive integer)
- If missing or invalid: print `Missing size`
- Must use `const` and a loop
- Must only use `console.log(...)`

### Usage

```bash
node 8-square.js 2
# Output:
# XX
# XX

node 8-square.js
# Output:
# Missing size
```

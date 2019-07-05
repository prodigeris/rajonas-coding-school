
# Basic calculator

## Introduction

You just landed your first job in the IT industry.

The boss comes to your desk and personally welcomes you to the company.

You both seem really excited but you sense that the boss wants something urgent from you.

After having a small talk about how bad was the last season of Game Of Thrones,
the boss tells you that they need your coding help ASAP.

You soon find out, that after the recent electric outage, all the calculators in the company suddenly stopped working.

No work in the finance department has been done since. It's a nightmare and the company is losing millions!

You have been assigned to the special coding force task.
The first mission of your team will be to create a calculator for the finance team.

## Background

[You will be provided with some code boilerplate for handling user input.](../../boilerplate/basic-calculator/index.html)


## Exercise
### Level 1 
The calculator will have 3 prompts from the user:

1. The first number to be used in your app.
2. Second number
3. Operation

These prompts will need to be assigned to variables called:

- `firstNumber`
- `secondNumber`
- `operation`

The operation will need to be checked using **conditionals**.
You can use `switch` or `if... else` depending on your taste.

There are **4 valid operations**:

- `multiplication`
- `division`
- `addition`
- `subtraction`

Instead of using `console.log` this to output your result to the console, let's use `alert` and output the result to the user screen.

### Level 2

Capture the unknown operation and `alert` the user that `"Operation 'random' is not allowed!"`

### Level 3
Everyone knows that you cannot divide by zero.
Let the user know that this operation is not allowed, by `alert`ing  `"STOP DOING THAT! You will create a wormhole."`

### Note

Assume that skipped prompts for numbers are `0` and empty string (`""`) for operation.
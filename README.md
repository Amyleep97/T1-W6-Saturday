# Python Term 1 Week 6 Saturday class

# If else Practice activity

# Building a calculator

Build a calculator that takes 3 inputs from the user:
2 inputs as numbers (Floats) for operations and 3rd input to decide which operation they want to perform.

# Lists
Composite Data type, meaning multiple data types can ne stored in one variable.
Each piece is called an element.

# Loops

Like Post Malone describes, "Run Away, but we're runnign in circles"
Used to repeat a block of code multiple times untill a certain condition is met.

DRY  Coding Principle: Don't Repeat Yourself.

Example: Counting coins in your piggy bank

"If" conditions would decide whether or not to run the intended block, whereas, Loops would decide how many times the user wants to run the intended block.

# While loop
While the condition is met, keep excecuting the intended block. If not met, skip the block.

Thing to consider:
    - Program can enter the loop
    - Program can exit the loop (use ctrl c to exit a loop)

## Range
It's a pre-defined function that generates a sequence of numbers.

Useful: Loops for itterating a specific number of times over a sequence of numbers.

range(start (1) ,stop (2),step  (3))

## for loop
for each item in a sequance, excecute the intended statements.

for variable_name in sequance:
    start

## Practice example 1
finding the sum of the first ten numbers (1,2, ...10)

## Practice example 2
Find the largest number in the list
list = [3, 41, 12, 9, 74, 15]

# Loop Control Statements
Control the flow of the loop. terminate the loop early if you want or skip iteration

## Break statement
Terminate loop immediately, moves to the next statement after the loop.

## Continue statement
Skips the rest of the code inside the loop for the current iteration and moves to the next iteration.

# Nested loops
A loop inside another loop! Inception.
Useful for running over multi-dimenional structures, like MATRIX.

## Practice example 1
Print a right-angled triangle pattern of stars. (stars = 5)
*
**
***
****
*****

## Practice example 2
Count the occurance of a letter in a list

# enumerate() function
Used to access the index of the value of the elements of the list.
Use two variables in for loop.
# Programming Assignment 3 - Python Data Analysis Library

This project is a submission for my programming assignment which makes use of Python Data Analysis Library or Pandas. In this project are solutions to 2 problems involving the use of data analysis.

## Problem 1: 

The first problem is a simple problem that requires the user to print the first and last 5 digits of the a given dataframe.

## Solution
Print the first 5 digits using the syntax:

`.head()`

Print the last 5 digits using the syntax:

`.tail()`

## Problem 2:

The second problem requires the user to accomplish the following: <br>
a. Display the first five rows with odd-numbered columns (columns 1, 3, 5, 7...) of cars. <br>
b. Display the row that contains the model of a specific car. <br>
c. Display how many cylinders (‘cyl’) a specific car model has. <br>
d. Determine how many cylinders (‘cyl’) and what gear type (‘gear’) multiple car models have. <br>

## Solution

### Problem 2.A <br>
Splice the given dataframe to only include odd-numbered indices <br>

Get the first five rows of the spliced dataframe using the syntax: <br>
`.head`

### Problem 2.B <br>
Using the `.loc` syntax, specify the specific car model that should be displayed <br>

### Problem 2.C <br>
Using the same syntax, index the specific car model then display only the cylinders ('cyl') <br>

### Problem 2.D <br>
Create a list for the specified car models, this allows the user to check the dataframe for multiple elements <br>

Use `.loc` to index for the given car models and `.isin` to check for each individual model <br>

Display the cylinders ('cyl') and gear type ('gear') <br>

## Version History

v1.0 - Initial upload

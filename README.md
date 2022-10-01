# Overview
## PizzaCalc.s
This PizzaCalc.s assembly program reads in lines of input from the
console. Each line is read in as its own input (using spim’s syscall support for reading in inputs of
different formats). 

The input is a series of pizza stats, where each pizza entry is 3 input lines long. The
first line is a name to identify the pizza (a string with no spaces), the second line is the diameter of the
pizza in inches (a float), and the third line is the cost of the pizza in dollars (another float). After the last
pizza in the list, the last line of the file is the string “DONE”. 

Example:

DominosLarge
\
14
\
7.99
\
DominosMedium
\
12
\
6.99
\
DONE

The pizzas are sorted in descending order of pizza-per-dollar, and in the case of a tie,
ascending order by pizza name. Furthermore, there is no limit on the number of pizza entries.

## recurse.s

This program recursively computes f(N), where N is an integer greater than zero that is input to the program. f(N) = 3*(N-1)+f(N-1)+1. The base case is f(0)=2.

## byseven.s
This program prints out the first N positive integers that are divisible
by 7, where N is an integer that is input to the program. The program prompts the user for the value of N via the console using syscalls. 

### ALL programs follow MIPS calling conventions

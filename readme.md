## Kelvin to Celsius/Fahrenheit
Write a program that prompts the user to input a temperature in units of Kelvin in the main function. The program will then determine degrees in Celsius and Fahrenheit. These calculation must be done in a void function that has 3 parameters: kelvin, celsius, and fahrenheit (the last two parameters being **pass-by-reference**). The main function should print the calculation results.

The formula for the conversions are:

Celsius = Kelvin - 273.15

Fahrenheit = 1.8 x Celsius + 32

Optional:
Add input validation so that a number less than zero cannot be used by the user as an input. Zero is the lowest physical limit a temperature in Kelvin can be.  After displaying the results of the calculations, the program should ask the user if they would like to enter another temperature in Kelvin and exit if they do not choose yes.
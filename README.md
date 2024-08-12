# Basic Arithmetic Operations in Python

## Description
This Python script allows users to perform basic arithmetic operations on two numbers input by the user. The operations include addition, subtraction, multiplication, division, modulus, root calculation, and exponentiation.

## OverView
1. The script prompts the user to enter two numbers. These numbers are input as floating-point values to allow for decimal calculations.
2. The script performs the following operations:
   - **Sum:** Adds the two numbers.
   - **Difference:** Subtracts the second number from the first number.
   - **Product:** Multiplies the two numbers.
   - **Quotient:** Divides the first number by the second number.
   - **Remainder:** Calculates the remainder when the first number is divided by the second number.
   - **Root:** Calculates the n-th root of the first number, where n is the second number.
   - **Power:** Raises the first number to the power of the second number.
3. The results of each operation are then printed to the console.

## Output

- **After running the script, you will see:**
    - Each input value printed on a new line.
    - All input values printed on a single line separated by commas.
    - The data type of each input value.

## Code
```
#input numbers

number1= float(input("Enter First Number: "))
number2= float(input("Enter Second Number: "))

#Basic Operations

sum = number1 + number2
difference = number1 - number2
product = number1 * number2
quotient = number1 / number2
remainder = number1 % number2
root = number1 ** (1/number2)
power = number1 ** number2

# Output
print("Sum = ",sum)
print("Difference = ",difference)
print("Product = ",product)
print("Remainder = ",remainder)
print("Root = ",root)
print("Power = ",power)
```

## Example 

```
Enter First Number: 8
Enter Second Number: 2
Sum =  10.0
Difference =  6.0
Product =  16.0
Quotient =  4.0
Remainder =  0.0
Root =  2.8284271247461903
Power =  64.0
```

## Key
- [Description](#description)
- [Overview](#overview)
- [Output](#output)
- [Code](#Code)
- [Example](#Example)
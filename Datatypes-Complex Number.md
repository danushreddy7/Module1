# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim:
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program:
```
# Reading two integers from the user
real_part = int(input("Enter the real part: "))
imaginary_part = int(input("Enter the imaginary part: "))

# Creating a complex number using the inputs
complex_number = complex(real_part, imaginary_part)

# Printing the complex number, and its real and imaginary parts
print(f"Complex number: {complex_number}")
print(f"Real part: {complex_number.real}")
print(f"Imaginary part: {complex_number.imag}")
```
## Output:
```
Input                           Result
   3                Complex number: (3+4j)
   4                Real part: 3.0
                    Imaginary part: 4.0
```
## Result:
thus the program to read the integers was successful

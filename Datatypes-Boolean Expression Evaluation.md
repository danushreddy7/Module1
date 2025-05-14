
# Ex 1:Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## 💻 Program:
```
# Boolean expressions
print("Boolean Expressions:")
print(f"True and False: {True and False}")   # AND operation
print(f"True or False: {True or False}")     # OR operation
print(f"not True: {not True}")               # NOT operation
print(f"True == False: {True == False}")     # Equality check
print(f"True != False: {True != False}")     # Inequality check

# Arithmetic expressions
print("\nArithmetic Expressions:")
print(f"True + False: {True + False}")       # True is 1, False is 0, so 1 + 0 = 1
print(f"True - False: {True - False}")       # 1 - 0 = 1
print(f"True * False: {True * False}")       # 1 * 0 = 0
print(f"True / False (handled as an error): {True / False}")  # Division by zero error
```

## Output:
```
Input              Result
               Boolean Expressions:
  a            True and False: False
  b            True or False: True
  c            not True: False
  d            True == False: False
  0            True != False: True
-------------------------------------------- 
              Arithmetic Expressions:
  1           True + False: 1
  1           True - False: 1
  a           True * False: 0
  0            True / False (handled as an error): Division by zero
```
## Result:
Thus  program to evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False` is successful



# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
```
def result(a, b):
    modulo = a % b
    print("The result of", a, "%", b, "is:", modulo)
a = int(input("Enter the first number (a): "))
b = int(input("Enter the second number (b): "))
result(a, b)
```
## Output
```
Enter the first number (a): 10
Enter the second number (b): 3
The result of 10 % 3 is: 1
```
## Result
Thus the given program is verified and executed sucessfully

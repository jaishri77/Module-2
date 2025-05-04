# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
f = lambda a, b: a + b

a = int(input("Enter the first number: "))
b = int(input("Enter the second number: "))
print(f(a, b))
```

## Output

```
Enter the first number: 10
Enter the second number: 5
15
```

## Result

The program defines a lambda function to return the sum of two user-provided numbers and prints the result.

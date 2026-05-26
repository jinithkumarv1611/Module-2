# EX-1
# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program 
```python
a = 16
b = bin(a)
print(b)

DEVELOPED BY: JINITH KUMAR V
REGISTER NO: 212225040157
```
## Output
<img width="1167" height="177" alt="image" src="https://github.com/user-attachments/assets/f49fee36-b8b5-42a6-9140-4f7155c62064" />


## Result
Thus the given program executed Successfully.

# EX-2
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
```python
def result(a, b):
    print(a % b)

x = int(input("Enter first number: "))
y = int(input("Enter second number: "))

result(x, y)
```
## Output
<img width="1202" height="278" alt="image" src="https://github.com/user-attachments/assets/f815a222-3e8d-44e2-8a72-4e4ce6fe57f8" />

## Result
Thus the given program executed Successfully.

# EX-3
# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

f = lambda a, b: a + b

print("Sum =", f(a, b))
```

## Output
<img width="1231" height="257" alt="image" src="https://github.com/user-attachments/assets/dca6f627-b9ce-41a0-845a-2a153b554368" />


## Result
Thus the given program executed Successfully.

# EX-4
# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```python
n = int(input("Enter the number of rows: "))

for i in range(n):
    num = 1

    # Print spaces
    for j in range(n - i - 1):
        print(" ", end=" ")

    # Print Pascal Triangle values
    for j in range(i + 1):
        print(num, end="   ")
        num = num * (i - j) // (j + 1)

    print()
```

## Sample Output
<img width="1238" height="467" alt="image" src="https://github.com/user-attachments/assets/45d7216c-d3fe-4262-98d0-81ffaf9bdcd5" />

## Result
Thus the given program executed Successfully.

# EX-5
## Loops in Python: Palindrome Number Checker

## 🎯 Aim
 To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```python
num = int(input("Enter a number: "))

temp = num
rev = 0

while temp > 0:
    rev = (10 * rev) + (temp % 10)
    temp = temp // 10

if rev == num:
    print("Palindrome Number")
else:
    print("Not a Palindrome Number")
```

## Output
<img width="1218" height="402" alt="image" src="https://github.com/user-attachments/assets/0127e594-6cb3-4e38-847c-f0e8b0330d73" />


## Result
Thus the given program executed Successfully.

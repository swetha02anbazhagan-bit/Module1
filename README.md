# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
```
a=int(input("ENTER A NUMBER:"))
if a%2==0:
    print("EVEN")
else:
    print("ODD")
```
## Output
<img width="1919" height="991" alt="Screenshot 2025-10-20 113002" src="https://github.com/user-attachments/assets/e3ad2638-a0a3-4e5a-9230-8a2f479e4d5a" />

## Result
This program efficiently distinguishes even and odd numbers using a simple conditional check and prints the correct label accordingly.



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

## 💻 Program
~~~
a = (0 == True)
b = (False == False)
c = (True + True)
d = (False + 9)

print("a is:", a)
print("b is:", b)
print("c is:",c)
print("d is:",d)
~~~

## Output
<img width="1499" height="988" alt="Screenshot 2025-10-20 114536" src="https://github.com/user-attachments/assets/cd9b8b8e-0b77-42f8-9356-4878c2bfa6ed" />

## Result
The program successfully evaluates boolean and arithmetic expressions involving True and False and displays the correct results.


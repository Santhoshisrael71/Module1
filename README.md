```
# EX 1.1: Conditional Statements in Python: Even or Odd Checker

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
```
a=int(input())
if a%2==0:
    print("EVEN")
else:
    print("ODD")
```
```

## Output
![image](https://github.com/user-attachments/assets/f74a1c2e-fe17-4aca-abf8-7c8c2c65a87e)

## Result
Run the program successfully

```


# Ex 1.2:Datatypes-Boolean Expression Evaluation in Python

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
```
a=(0==True)
b=(False==False)
c=True+True
d=False+9

print("a is",a)
print("b is",b)
print("c:",c)
print("d:",d)
```

## Output
![image](https://github.com/user-attachments/assets/c16a5a39-6f80-4660-acd8-c1bfece88391)

## Result
Run the program successfully
```
-------------------------------------------------------------------------------------------------------------
```
# EX 1.3: Datatypes-Character Literal in Python

## 🎯 Aim
To write a Python program that prints the characters `'E'` and `'H'` using character literals.

## 🧠 Algorithm
1. Print the character `'E'`.
2. Print the character `'H'`.

## 🧾 Program
```
print('E')
print('h')
```
## Output
![image](https://github.com/user-attachments/assets/31f0fc94-c345-43c2-a9ad-3dbb6084c174)


## Result
Run the program successfully
```
-------------------------------------------------------------------------------------------------------------
```
# EX 1.4:🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
```
a=int(input())
b=int(input())
x=complex(a,b)
print(x)
print(x.real)
print(x.imag)


```

## Output
![image](https://github.com/user-attachments/assets/5ea8f15c-50d3-4cf9-b9e3-0f70faa2d086)

## Result
Run the program successfully
```
-------------------------------------------------------------------------------------------------------------
```
# EX 1.5:Datatypes-Read and Print a String in Python

## 🎯 Aim
To write a Python program to read a string from the user and then print it.

## 🧠 Algorithm
1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## 🧾 Program
```
men_stepped_on_the_moon=int(input())
print(men_stepped_on_the_moon)
```
## Output
![image](https://github.com/user-attachments/assets/8ce827a8-798d-4362-a57f-d8372b4b5262)


## Result
Run the program successfully

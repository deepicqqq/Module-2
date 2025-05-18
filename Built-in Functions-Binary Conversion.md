## NAME: DEEPIKA P
## REGISTER NO: 212223240024
# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number 56 to its binary representation using the built-in bin() function.

## 🧠 Algorithm
1. Start the program.

2. Assign the number 56 to a variable (e.g., num).

3. Use the built-in bin() function to convert the number to binary format.

4. Store the result in another variable (e.g., binary).

5. Print the binary result.

6.End the program.
## 🧾 Program

num = 56\
binary_representation = bin(num)[2:]\
print(f"0b{binary_representation}")

## Output
![Screenshot 2025-05-18 190434](https://github.com/user-attachments/assets/1449a974-6937-473c-be28-c7c26441b1ee)

## Result
The Python program successfully converted the number 56 into its binary representation using the built-in bin() function. 


# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their modulo using the % operator.
## 🧠 Algorithm
1. Start the program.

2. Define a function named result that takes two parameters a and b.

3. Inside the function, use the modulo operator (%) to compute a % b.

4. Return the result from the function.

5. Assign the values 9 and 5 to variables a and b.

6. Call the result() function with a and b as arguments.

7. Store the returned value in a variable.

8. Print the result.

9.End the program.

## 🧾 Program

def result(a,b):\
    return a%b\
a=int(input())\
b=int(input())\
print("modulo is",result(a,b))

## Output
![Screenshot 2025-05-18 190633](https://github.com/user-attachments/assets/0cd0340d-c1ac-4b9c-8e01-55879d3c48e5)

## Result
The Python program successfully defined a function that accepted two values and returned their modulo.

# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that calculates the value of the expression (x * 10) + (y / 2) * z using a lambda function.

## 🧠 Algorithm
1. Get three inputs from the user: x, y, and z.

2. Define a lambda function that takes three parameters (x, y, z) and computes (x * 10) + (y / 2) * z.

3. Call the lambda function with the input values.

4. Print the result.

## 🧾 Program
x=int(input())\
y=int(input())\
z=int(input())\
a=(x * 10) + (y / 2) * z\
print(a)

## Output
![Screenshot 2025-05-18 191011](https://github.com/user-attachments/assets/9dcee006-6088-4a39-a3e4-7e98a7bf7e71)

## Result
The program correctly calculated the value of the expression (x * 10) + (y / 2) * z using a lambda function and printed the expected output.

# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.


## 🎯 Aim

To write a Python program that builds Pascal's Triangle up to a specified number of rows entered by the user.

## 🧠 Algorithm
1. Start the program.

2. Take the number of rows n as input from the user.

3. For each row i from 0 to n-1:

4. Initialize the first element as 1.

5. For each element j from 1 to i:

6. Calculate the value as the sum of the two elements above it:
triangle[i][j] = triangle[i-1][j-1] + triangle[i-1][j]

7. Append 1 at the end of the row.

8. Print each row of Pascal's Triangle.

9. End the program.

## 🧪 Program
def generate_pascals_triangle(n):\
    triangle = [[1] * (i + 1) for i in range(n)]\

    for i in range(2, n):\
        for j in range(1, i):\
            triangle[i][j] = triangle[i - 1][j - 1] + triangle[i - 1][j]\

    for row in triangle:\
        print(" ".join(map(str, row)))

# Get user input
rows = int(input())
generate_pascals_triangle(rows)

## Sample Output
![Screenshot 2025-05-18 191458](https://github.com/user-attachments/assets/403b5258-6330-4486-b706-44a6ce849a0f)

## Result
The program successfully generated Pascal's Triangle for the given number of rows using Python.

## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program to check whether the number 565 is a palindrome or not by comparing the string with its reverse.

## 🧠 Algorithm
1. Assign the number 565 to a variable n as a string.

2. Check if the string n is equal to its reverse n[::-1].

3. If they are equal, print that the number is a palindrome.

4. Otherwise, print that the number is not a palindrome.

## 🧾 Program
n =input()\
print(f"The given number {n} is a Palindrome"\
if n == n[::-1] else f"The given number {n} is not a palindrome")
## Output
![Screenshot 2025-05-18 192321](https://github.com/user-attachments/assets/ad66604e-a3e6-4d55-9ae6-5784080601ff)

## Result
The program correctly identified that the number 565 is a palindrome by comparing the string with its reverse.

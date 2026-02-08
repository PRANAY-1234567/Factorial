🔢 Factorial of a Number in JavaScript

📌 Description

This program calculates the factorial of a given number using an iterative (loop-based) approach in JavaScript.

The factorial of a number n is the product of all positive integers from 1 to n.

🧩 Problem Statement

Given a number n:

𝑛
!
=
𝑛
×
(
𝑛
−
1
)
×
(
𝑛
−
2
)
×
.
.
.
×
1
n!=n×(n−1)×(n−2)×...×1

Example:
Input: 5
Output: 120

✅ Code
function factorial(n) {
  let fact = 1;
  for (let i = 1; i <= n; i++) {
    fact *= i;
  }
  return fact;
}

console.log(factorial(5));

🧠 Explanation

The function factorial() takes a number n as input

A variable fact is initialized to 1

A for loop runs from 1 to n

Each value is multiplied with fact

The final value of fact is returned

🖨 Example Output
120

🛠 Concepts Used

JavaScript Functions

for loop

Variables

Mathematical logic

🎯 Use Cases

Beginner JavaScript practice

Interview preparation

Learning loops and functions

Mathematical computations

🚀 Possible Improvements

Add input validation (negative numbers)

Recursive factorial version

Take user input dynamically

Handle large numbers

👨‍💻 Author

Pranay Jadhao

<img width="836" height="611" alt="image" src="https://github.com/user-attachments/assets/83330dc7-dbe0-4d57-92de-4887070981ca" />

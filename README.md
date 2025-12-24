[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Q0bP4nzg)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=22105410&assignment_repo_type=AssignmentRepo)
# 🧮 Marks Calculator – GitHub Autograded Assignment

This is a **graded programming assignment** evaluated automatically using GitHub Actions.

You are required to complete a **marks calculator** using JavaScript by writing logic in the provided function.

---

## 🎯 Learning Objectives

By completing this assignment, you will practice:

- Writing JavaScript functions
- Working with arrays
- Basic arithmetic operations
- Conditional logic (Pass / Fail)
- Submitting code using GitHub

---

## 📂 Repository Structure (DO NOT CHANGE)

marks-calculator/
│
├── src/
│ └── calculator.js ← ✏️ YOU EDIT THIS FILE ONLY
│
├── tests/
│ └── calculator.test.js ← ❌ DO NOT EDIT
│
├── package.json ← ❌ DO NOT EDIT
└── .github/
└── workflows/
└── autograde.yml ← ❌ DO NOT EDIT



⚠️ **Modifying any file other than `calculator.js` may result in a ZERO score.**

---

## ✏️ Your Task

Open the file:

src/calculator.js


You must complete the function:

```js
calculateResult(marks)```


🔢 Function Specification
📥 Input

marks: an array of numbers
Each number represents marks obtained in one subject
Each mark is between 0 and 100

Example:
[80, 90, 70, 60]

📤 Output (Return Value)
The function must return an object with exactly these keys:

{
  total: number,
  percentage: number,
  result: "Pass" | "Fail"
}

🧮 Calculation Rules

1. Total
-Sum of all marks in the array
2. Percentage
-(total / (number of subjects × 100)) × 100
-Must be rounded to the nearest integer
3. Result
-"Pass" if percentage ≥ 40
-"Fail" if percentage < 40


✅ Examples
Example 1
calculateResult([80, 90, 70, 60])

Output:
{
  total: 300,
  percentage: 75,
  result: "Pass"
}

Example 2
calculateResult([10, 20, 30])

Output:
{
  total: 60,
  percentage: 20,
  result: "Fail"
}

🚫 Important Restrictions

❌ Do NOT change the function name

❌ Do NOT print anything using console.log

❌ Do NOT modify test files

❌ Do NOT change return format

✅ Only write logic inside the function

🧪 How Your Code Is Evaluated

Automated test cases run on every push

Each test checks:

Correct total

Correct percentage calculation

Correct rounding

Correct Pass/Fail logic

If any test fails, marks are deducted automatically

📤 Submission Instructions

Write your solution in src/calculator.js

Save the file

Commit your changes

Push to GitHub

Wait for the autograder to run (green ✔️ or red ❌)

🏁 Final Note

This assignment is designed to test logic and correctness, not shortcuts.
Write clean, readable code.

All the best 🚀

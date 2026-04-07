# Task 01 — Variables and Input

## What you need to know
- Variables (strings, integers)
- `input()` to get data from the user
- Type conversion: `int()`, `str()`
- `print()`

---

## Your Task

Write a program that asks the user for the following information:
1. Their **first name**
2. Their **last name**
3. Their **birth year**

Then the program should:
- Print a greeting using their full name
- Calculate their **age** (use the current year: 2026)
- Print: `"Hello [full name], you are [age] years old."`

### Example output
```
Enter your first name: John
Enter your last name: Doe
Enter your birth year: 2005
Hello John Doe, you are 21 years old.
```

---

## Hints
- `input()` always returns a string — convert to `int` when doing math
- To combine first and last name, use a space between them
- Age = current year - birth year

---

## File
Write your solution in `solution.py` in this folder.

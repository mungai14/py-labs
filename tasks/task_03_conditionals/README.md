# Task 03 — Conditionals

## What you need to know
- `if`, `elif`, `else`
- Boolean operators: `and`, `or`, `not`
- Comparison operators: `>`, `<`, `==`, `!=`

---

## Your Task

### Part A — Temperature Checker
Write a program that asks the user to enter a **temperature** (in Celsius).
- If temp > 35: print `"It's very hot, drink water!"`
- If temp is between 20 and 35 (inclusive): print `"Nice weather today."`
- If temp < 20: print `"It's cold, wear a jacket."`

### Part B — Login Check
Write a program that asks for a **username** and a **password**.
- The correct username is `"admin"` and the correct password is `"1234"`
- If both are correct: print `"Access granted. Welcome!"`
- If the username is correct but the password is wrong: print `"Wrong password."`
- If neither is correct: print `"Unknown user."`

### Example output (Part A)
```
Enter temperature: 38
It's very hot, drink water!
```

### Example output (Part B)
```
Enter username: admin
Enter password: 1234
Access granted. Welcome!
```

---

## Hints
- For Part A, think about the order of your `if/elif/else`
- For Part B, you'll need nested conditions or `and`

---

## File
Write your solution in `solution.py` in this folder. Do Part A first, then Part B below it.

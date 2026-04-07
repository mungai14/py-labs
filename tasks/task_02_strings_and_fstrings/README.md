# Task 02 — Strings and f-strings

## What you need to know
- f-strings: `f"Hello {name}"`
- String methods: `.upper()`, `.lower()`, `.replace()`, `.find()`, `.len()`
- Math: `round()`, `abs()`, augmented assignment (`+=`, `-=`)

---

## Your Task

Write a program that:
1. Asks the user for their **name** and a **price** (e.g. price of an item)
2. Stores both in variables
3. Prints the name in **ALL CAPS**
4. Prints the name in **all lowercase**
5. Rounds the price to the nearest whole number and prints:
   `"[NAME], the item costs approximately [rounded price] shillings."`
   Use an f-string for this line.
6. Asks the user to enter a **sentence**, then:
   - Print how many characters it has (`len`)
   - Print the sentence with the word `"bad"` replaced by `"good"`

### Example output
```
Enter your name: Alice
Enter item price: 149.75
Enter a sentence: This is a bad day

ALICE
alice
Alice, the item costs approximately 150 shillings.
Your sentence has 18 characters.
This is a good day
```

---

## File
Write your solution in `solution.py` in this folder.

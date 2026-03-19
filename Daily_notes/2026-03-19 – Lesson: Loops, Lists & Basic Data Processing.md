# 2026-03-19 – Loops, Lists & Basic Data Processing

## Topic

Today I worked on loops, lists, and handling user input in Python. I focused on building lists dynamically, understanding how loops work, and performing basic calculations like sum and mean.

---

## Key Concepts

- A loop (`for i in range(n)`) repeats code multiple times
- `range(n)` controls how many times the loop runs (starts at 0)
- Lists are created with `[]` and filled using `.append()`
- `input()` returns a string → must convert using `int()` or `float()`
- Calculations like sum and mean should be done after the loop
- Indentation defines the structure of loops and conditions
- Avoid using built-in names like `input` as variables

---

## What I Learned

I learned how to create a list using a loop and store user inputs step by step. I now understand the difference between a temporary variable (like `value`) and a list that stores all values.

I also learned how to calculate totals using `sum()` and averages using `sum(list) / len(list)`. It became clear that calculations should happen after the loop is finished, not during.

I understood that `{}` in f-strings is only for displaying values and not related to logic or calculations.

I also learned how to combine two inputs (hours and expenses) into one loop, which is cleaner and more efficient.

---

## Challenges

I had issues with:

- Overwriting variables (turning a list into a number by mistake)
- Using `input` as a variable name, which broke the code
- Indentation errors inside loops
- Using functions incorrectly (e.g. `sum.` instead of `sum()`)
- Understanding why `reversed()` does not return a list directly
- Confusion between `.pop()` (index-based) and `.remove()` (value-based)

---

## Reflection

The session was very helpful and straightforward overall. The main challenge was understanding how multiple lines inside loops interact and keeping track of variables.

I noticed that using autocomplete too much makes things easier but reduces learning, so I need to be more conscious and practice writing things manually.

Jupyter Notebook behavior can be confusing (e.g. variables staying in memory), so restarting the kernel is sometimes necessary.

---

## What I asked ChatGPT today

I asked about:

- How Git works between local and remote
- How loops and `range()` work
- Why `input()` needs type conversion
- Differences between list methods like `.append()`, `.pop()`, `.remove()`
- Why `reversed()` behaves differently
- How to combine lists properly
- Debugging common errors (TypeError, IndentationError)
- How to calculate sum and mean correctly
- How to structure cleaner code with loops

---

## Key Takeaway

Build data first, then analyze it.
Keep variables clearly separated (list vs value).
Indentation defines logic.
Avoid overwriting built-in functions.
Keep code simple and readable.

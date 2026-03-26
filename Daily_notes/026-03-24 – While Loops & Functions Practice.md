# 2026-03-24 – While Loops & Functions Practice

## Topic

- While loops and **condition-based execution**
- Avoiding **infinite loops**
- Loop control with **`break`**, **`continue`**, and **`pass`**
- Writing and using **functions**
- Combining **conditions + functions**

---

## Key Concepts

- A **while loop** runs as long as a condition is **True**
- Syntax:
  ```python
  while condition:
      do something
  ```
- Loop must become **False** → otherwise **infinite loop**
- Loop structure:
  - initialize variable
  - check condition
  - update variable (`i += 1`)
- `break` → exits loop immediately
- `continue` → skips current iteration
- `pass` → placeholder (does nothing)
- Functions:
  - `def function_name(parameters):`
  - `return` → gives back a value
  - `print` → only displays output
- Parameters replace hardcoded values

---

## What I Learned

- While loops are useful when:
  - number of iterations is **unknown**
  - logic depends on a **condition**
- I learned how to:
  - fix infinite loops by updating variables
  - control loops using `break` and `continue`
- I practiced writing functions:
  - simple calculations (multiply by 4)
  - condition checks (`> 5`, ranges)
  - real-world logic (bond calculation)
- I understood:
  - difference between **`return` vs `print`**
  - how to pass values into functions
- I combined:
  - loops + conditions
  - functions + conditions

---

## Important Patterns

### While loop structure

```python
i = 0
while i < 5:
    print(i)
    i += 1
```

### Avoid infinite loop

```python
while condition:
    # must update variable
```

### Function structure

```python
def my_function(x):
    return x * 2
```

### Condition inside function

```python
def check_number(n):
    if n > 5:
        print("bigger")
    else:
        print("smaller")
```

### Real-world logic

```python
def calculate_bond(rent, city):
    if city.lower() == "berlin":
        return rent * 4
    else:
        return rent * 3
```

---

## Challenges

- Creating **infinite loops** by forgetting `i += 1`
- Confusion between:
  - `print()` vs `return`
- Understanding when to use:
  - while loop vs for loop
- Structuring functions correctly
- Thinking step-by-step through conditions
- Mixing up input handling vs function parameters

---

## Reflection

This session focused on combining core programming concepts: **loops, conditions, and functions**.

While loops gave more flexibility but also introduced more risk (especially infinite loops). Functions helped structure logic and make code reusable.

The key improvement is understanding flow:

→ input → condition → logic → output

I’m starting to see how these patterns apply to real-world problems like calculations and data processing.

---

## Agenda / Work Completed

- Fixed an **infinite loop**
- Built while loops for:
  - counting
  - summing numbers
  - searching values (Waldo example)
- Used:
  - `break` to exit loops
  - `continue` to skip iterations
  - `pass` as placeholder
- Wrote functions for:
  - multiplication
  - number comparison
  - range checks
- Implemented real-world example:
  - **rental bond calculation**
- Practiced converting logic into reusable functions

---

## What I asked ChatGPT today

- How to fix infinite loops
- Difference between **while vs for loops**
- How `break` and `continue` behave
- When to use `return` vs `print`
- How to structure functions correctly
- How to apply conditions inside functions
- How to solve real-world logic problems with functions

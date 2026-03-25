Daily_notes/202x-03-20_XX.md

# 2026-03-24 – While Loops & Loop Control

## Topic

- While loops and **condition-based iteration**
- Avoiding **infinite loops**
- Loop control using **`break`**, **`continue`**, and **`pass`**
- Searching and iterating with conditions
- Comparing **while loops vs for loops**

---

## Key Concepts

- While loops iterate as long as a **condition is True**
- Syntax:
  ```python
  while condition:
      do something
  ```
- Loop must become **False** → otherwise **infinite loop**
- Common structure:
  - initialize variable
  - check condition
  - update variable (`i += 1`)
- `break` → **stops loop immediately**
- `continue` → **skips current iteration**
- `pass` → placeholder (does nothing)
- Use while loops when **iterations are unknown**
- Use for loops when **iterations are known**

---

## What I Learned

- While loops allow me to **control execution based on conditions**
- I understood the difference between:
  - `for loop` → fixed iterations
  - `while loop` → dynamic condition
- I learned how to:
  - control loops using conditions
  - stop loops using **`break`**
  - skip logic using **`continue`**
- I understood how **infinite loops happen** and how to fix them
- I practiced:
  - summing numbers
  - searching lists (Waldo example)
  - handling user input loops
- I learned that updating variables is **critical for loop termination**

---

## Challenges

- Creating accidental **infinite loops**
- Forgetting to update loop variable (`i += 1`)
- Understanding when loop condition becomes False
- Mixing up `break` vs `continue`
- Keeping track of index manually (`i`)
- Understanding `while + else`

---

## Reflection

While loops gave me more control compared to for loops because they depend on conditions instead of predefined sequences.

This makes them more flexible but also more error-prone, especially when dealing with infinite loops.

The key takeaway is:

→ initialize → check condition → update variable

This pattern is essential to avoid logical errors and infinite execution.

---

## Agenda / Work Completed

- Fixed an **infinite loop**
- Built a loop to **sum numbers (1–10)**
- Implemented search logic using while (Waldo example)
- Used `break` to exit loops early
- Used `continue` to skip iterations
- Used `while + else` for fallback logic
- Built a **user input validation loop**
- Practiced `pass` as placeholder
- Counted characters using loop + dictionary

---

## What I asked ChatGPT today

- Why infinite loops happen
- How to stop loops correctly
- Difference between **while vs for loops**
- When to use `break` vs `continue`
- How to structure search loops
- How `while + else` works
- How to debug loops step-by-step

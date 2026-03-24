# 2026-03-23 – For Loops & Data Cleaning

## Topic

- For loops with **lists, strings, and dictionaries**
- Control flow using **`if` statements** and **`continue`**
- Iteration tools: **`range()`**, **`zip()`**, **`enumerate()`**
- Basic **data cleaning with string methods**
- Working with **nested lists (list of lists)**

---

## Key Concepts

- For loops iterate over an **iterable** (list, string, dictionary, range)
- `range(start, stop)` → **stop is NOT included**
- `zip()` → combines multiple lists into pairs
- `enumerate()` → returns **index + value**
- Dictionary iteration:
  - default → keys
  - `.values()` → values
  - `.items()` → **key-value pairs**
- `continue` → **skips current iteration**
- `%` operator → used for **even/odd checks**
- String methods for cleaning:
  - `.lower()` → lowercase
  - `.split()` → split text
  - `.endswith()` → check endings
  - `.replace()` + `.strip()` → clean strings

---

## What I Learned

- For loops allow me to **repeat logic over data efficiently**
- I understood how to loop through:
  - list → `for item in list`
  - string → character by character
  - dictionary → keys, values, or both
- I learned how to:
  - combine lists using **`zip()`**
  - track position using **`enumerate()`**
  - filter data using conditions (`if`, `%`, `continue`)
- I understood the difference between:
  - `print()` → output
  - `append()` → store data
- I practiced real data cleaning:
  - lowercase names
  - remove company endings
  - extract email providers
- I now understand how to work with **nested lists**:
  - indexing → `list[0][1]`
  - unpacking → `for name, age, product in customers`

---

## Challenges

- Confusion between **list vs dictionary access**
- Mixing up `[index]` and `["key"]`
- Printing inside vs outside loops
- Understanding how **`continue`** affects execution
- Off-by-one errors with `range()`
- Knowing when to use:
  - `append()` vs `print()`
- Understanding nested structures (list of lists)

---

## Reflection

This session connected multiple important concepts: **loops, conditions, and string operations**.

It became clearer how Python processes data step-by-step and how important it is to follow the **structure of the data correctly**.

It still feels somewhat manual, but I can now see how these patterns are directly used in **real data analytics workflows**, especially for cleaning and transforming datasets.

The biggest improvement is thinking in a structured way:

→ take one item → apply logic → move to the next

---

## Agenda / Work Completed

- Iterated through dictionaries:
  - keys, values, and key-value pairs
- Looping through strings (character iteration)
- Built patterns using loops (triangle exercise)
- Generated sequences using **`range()`**
- Filtered numbers:
  - even (`% 2 == 0`)
  - odd (`% 2 != 0`)
- Combined lists using **`zip()`**
- Skipped values using **`continue`**
- Used **`enumerate()`** to track index + value
- Cleaned customer names using:
  - `.lower()`
  - `.replace()`
- Extracted clean names using **`.endswith()`**
- Extracted email providers using **`.split("@")`**
- Worked with list of lists (customer dataset)
- Used unpacking + enumerate for structured output

---

## What I asked ChatGPT today

- How `continue` works in loops
- Difference between **printing vs storing (`append`)**
- When to use **`zip()` vs `enumerate()`**
- Why `[0]` is needed for list access
- How to clean strings using:
  - `.replace()`
  - `.strip()`
  - `.endswith()`
- How to extract email providers
- How to structure loops for real data tasks
- How to combine indexing + unpacking correctly

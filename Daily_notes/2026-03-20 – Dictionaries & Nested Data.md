# 2026-03-20 – Dictionaries & Nested Data

## Topic

- Dictionaries (key-value pairs)
- Accessing and modifying dictionary data
- Nested dictionaries and lists

---

## Key Concepts

- Dictionaries store data as **key → value pairs**
- Keys must be **unique and immutable** (e.g. string, number)
- Access values using `dict["key"]`
- `.get()` allows safe access without errors
- Dictionaries are **mutable** (can add, change, remove values)
- Nested structures combine **dicts and lists**
- Access pattern:
  - dict → `["key"]`
  - list → `[index]`

---

## What I Learned

- Dictionaries are better than lists when data needs **structure and meaning**
- I understood the difference between:
  - list → ordered values
  - dict → labeled values
- I learned how to:
  - create dictionaries
  - access values using keys
  - add and update entries
- Nested data requires **step-by-step navigation**
- I now understand why `[0]` is needed when accessing lists inside dictionaries

---

## Challenges

- Confusion between **list vs dictionary access**
- Mixing up `[index]` and `["key"]`
- Understanding why `"weather"[0]` is needed
- Thinking values define structure instead of `{}` and `[]`
- Debugging errors like:
  - KeyError
  - NameError
- Keeping track of nested structures

---

## Reflection

The lesson was very practical and important for real data work.  
Dictionaries make data much more structured and readable compared to lists.

The biggest challenge was understanding nested structures (list inside dict inside list), but it started to click once I followed the structure step by step.

This feels very relevant for APIs and real datasets. Still feels a bit manual, but I understand this is the foundation before using tools like pandas.

---

## What I asked ChatGPT today

- Difference between list and dictionary behavior
- Why `[0]` is needed in nested structures
- How to access nested values like `"description"`
- How to add and rename dictionary keys
- Difference between `.pop()` and `del`
- How to structure user input into dictionaries
- How to build list of dictionaries (real dataset structure)
- Debugging variable errors (NameError)
- Understanding keys vs values vs lists

---

## Key Takeaway

- `{}` defines a dictionary, not the value type
- `[]` defines a list → requires indexing
- Always follow the structure step-by-step
- Dictionaries = structured data (very important for DA)

# 2026-03-25 – Functions & Conditional Logic

## Topic

- Writing and using **functions**
- Passing **parameters (inputs)**
- Using **if / elif / else** inside functions
- Difference between **`return` vs `print`**
- Applying functions to **real-world problems**

---

## Key Concepts

- Function structure:
  ```python
  def function_name(parameters):
      return value
  ```
- Functions make code **reusable and structured**
- Parameters replace **hardcoded variables**
- `return` → sends result back
- `print` → only displays output
- Conditional logic:
  - `if` → check condition
  - `elif` → second condition
  - `else` → fallback
- Functions can:
  - calculate values
  - check conditions
  - return results or print messages

---

## What I Learned

- How to convert existing code into a **function**
- How to:
  - pass inputs into functions
  - use conditions inside functions
- I understood the difference between:
  - `return` → reusable result
  - `print` → display only
- I practiced building functions for:
  - calculations (multiply numbers)
  - comparisons (`> 5`)
  - range checks (10–100)
- I applied logic to a real-world example:
  - **rental bond calculation (Berlin vs others)**
- I learned how to make functions more flexible:
  - using `.lower()` for safer comparisons

---

## Important Patterns

### Basic function

```python
def multiply_by_4(n):
    return n * 4
```

### Condition inside function

```python
def check_number(n):
    if n > 5:
        print("bigger")
    else:
        print("smaller")
```

### Range check

```python
def check_range(n):
    if n < 10:
        print("small")
    elif 10 <= n <= 100:
        print("in range")
    else:
        print("big")
```

### Real-world example

```python
def calculate_bond(rent, city):
    if city.lower() == "berlin":
        return rent * 4
    else:
        return rent * 3
```

### Converting code into function

```python
def greet_user(name):
    if name == "Fish":
        print("Hello,", name)
    else:
        print("Oh, well, what is your name then?")
```

---

## Challenges

- Understanding when to use:
  - `return` vs `print`
- Structuring functions correctly
- Passing the correct parameters
- Avoiding hardcoded values
- Thinking in reusable logic instead of one-time code
- Understanding condition flow (`if / elif / else`)

---

## Reflection

This session focused on structuring code using **functions** and combining them with conditional logic.

Functions make code cleaner, reusable, and easier to understand. Compared to previous days, this feels like a step toward writing more “real” programs instead of just isolated logic.

The key improvement is thinking in reusable blocks:

→ input → function → condition → output

---

## Agenda / Work Completed

- Converted existing logic into functions
- Practiced function creation with parameters
- Built functions for:
  - multiplication
  - number comparison
  - range checking
- Implemented **real-world business logic** (bond calculation)
- Practiced condition handling (`if / elif / else`)
- Learned difference between `return` and `print`
- Improved code flexibility (e.g. `.lower()` usage)

---

## What I asked ChatGPT today

- How to structure functions correctly
- Difference between `return` and `print`
- How to pass parameters into functions
- How to apply conditions inside functions
- How to convert existing code into functions
- How to handle real-world logic with functions

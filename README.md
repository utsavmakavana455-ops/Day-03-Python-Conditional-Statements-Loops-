# Day 03 – Python Conditional Statements & Loops 

## 🎯 Learning Objectives

- Understand conditional statements.
- Learn if, elif, and else.
- Understand comparison operators.
- Learn logical operators.
- Practice for loops.
- Practice while loops.
- Understand break, continue, and pass.
- Learn nested loops.

---

## 1. Conditional Statements

Conditional statements allow Python to make decisions.

### If Statement

```python
age = 20

if age >= 18:
    print("You are an adult")
```

### If-Else Statement

```python
age = 16

if age >= 18:
    print("You can vote")
else:
    print("You cannot vote yet")
```

### If-Elif-Else Statement

```python
marks = 85

if marks >= 90:
    print("Grade A")
elif marks >= 80:
    print("Grade B")
elif marks >= 70:
    print("Grade C")
else:
    print("Needs improvement")
```

---

## 2. Comparison Operators

| Operator | Meaning |
|---|---|
| `==` | Equal |
| `!=` | Not equal |
| `>` | Greater than |
| `<` | Less than |
| `>=` | Greater than or equal |
| `<=` | Less than or equal |

### Example

```python
a = 10
b = 20

print(a > b)
print(a < b)
print(a == b)
```

---

## 3. Logical Operators

Python has three main logical operators:

- `and` – Both conditions must be true.
- `or` – At least one condition must be true.
- `not` – Reverses the condition.

### Example

```python
age = 22
has_id = True

if age >= 18 and has_id:
    print("Access granted")
else:
    print("Access denied")
```

---

## 4. For Loops

A for loop repeats code for each item in a sequence.

### Example

```python
fruits = ["Apple", "Banana", "Orange"]

for fruit in fruits:
    print(fruit)
```

### Using Range()

```python
for i in range(1, 11):
    print(i)
```

### Print Even Numbers

```python
for i in range(2, 21, 2):
    print(i)
```

### Calculate Sum

```python
total = 0

for number in range(1, 6):
    total += number

print("Total:", total)
```

---

## 5. While Loops

A while loop repeats as long as its condition is true.

### Example

```python
count = 1

while count <= 5:
    print(count)
    count += 1
```

Output:

```text
1
2
3
4
5
```

---

## 6. Break, Continue and Pass

### Break

Stops the loop immediately.

```python
for i in range(1, 10):
    if i == 5:
        break

    print(i)
```

### Continue

Skips the current iteration.

```python
for i in range(1, 6):
    if i == 3:
        continue

    print(i)
```

### Pass

Acts as a placeholder.

```python
for i in range(5):
    if i == 2:
        pass

    print(i)
```

---

## 7. Nested Loops

A loop inside another loop is called a nested loop.

### Example

```python
for i in range(1, 4):
    for j in range(1, 4):
        print(i, j)
```

### Multiplication Table

```python
number = 5

for i in range(1, 11):
    print(number, "x", i, "=", number * i)
```

---

## 8. Practical Machine Learning Example

Let's classify students based on their marks.

```python
marks = [85, 45, 90, 30, 70, 55]

for mark in marks:

    if mark >= 50:
        print(mark, "Passed")
    else:
        print(mark, "Failed")
```

This example demonstrates how loops and conditions can process multiple records in a dataset.

---

## 9. Coding Exercises

- [ ] Check whether a number is positive, negative, or zero.
- [ ] Check whether a number is even or odd.
- [ ] Print numbers from 1 to 20.
- [ ] Calculate the sum of numbers from 1 to 100.
- [ ] Print the multiplication table of a user-provided number.
- [ ] Print all even numbers between 1 and 50.
- [ ] Count how many students passed using a list of marks.

---

## 10. Key Concepts Summary

| Concept | Purpose |
|---|---|
| if | Check a condition |
| elif | Check another condition |
| else | Execute when conditions are false |
| for | Iterate over a sequence |
| while | Repeat while a condition is true |
| break | Stop a loop |
| continue | Skip an iteration |
| pass | Placeholder statement |

---

## 11. Why Is This Important for Machine Learning?

Conditional statements and loops help me:

- Process large datasets.
- Filter data based on conditions.
- Iterate through records.
- Automate repetitive operations.
- Build data processing logic.

These concepts are essential foundations for working with NumPy, Pandas, and Machine Learning algorithms.

---

## 📚 Day 3 Summary

Today I learned:

- Conditional statements
- Comparison operators
- Logical operators
- For loops
- While loops
- Break, Continue, and Pass
- Nested loops
- Basic dataset processing

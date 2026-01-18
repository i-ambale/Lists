# Exercise: Lists

This exercise focuses on understanding how to create, manipulate, slice, and work with nested lists in Python. Lists are one of the most fundamental data structures and are essential for storing and processing collections of data.

---

## Learning Objectives

By the end of this exercise, you will be able to:

- Create lists using different approaches.
- Manipulate lists by adding, removing, and updating elements.
- Slice lists to access subsets of data.
- Work with nested lists (lists within lists).
- Apply common list methods and built-in functions.

---

## Prerequisites

- Basic knowledge of Python syntax.
- Python installed on your machine or access to a Jupyter Notebook / Google Colab environment.

---

## Topics Covered

### 1. Creating Lists
Examples:
```python
fruits = ["apple", "banana", "cherry"]
numbers = [1, 2, 3, 4, 5]
mixed = ["text", 10, True, 3.5]
```
---
### 2. Manipulating Lists

Adding elements:
```python
fruits.append("orange")
fruits.insert(1, "mango")
```
Removing elements:
```python
fruits.remove("banana")
last_item = fruits.pop()
```
Updating elements:
```python
fruits[0] = "pineapple"
```
### 3. Slicing Lists
```python
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9]

first_three = numbers[:3]
middle = numbers[3:6]
last_two = numbers[-2:]
step_example = numbers[::2]
```
### 4. Working with Nested Lists
```python
matrix = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]

# Accessing elements
element = matrix[1][2]  # Output: 6

# Modifying elements
matrix[0][0] = 10
```
Iterating through a nested list:
```python
for row in matrix:
    for item in row:
        print(item)
```
### Example Exercise Tasks
  1. Create a list of your favorite foods and print it.
  
  2. Add two new foods to the list.
  
  3. Remove one food item from the list.
  
  4. Slice the list to show only the first three items.
  
  5. Create a nested list representing a 3x3 grid and access the center element.
  
  6. Sort a combined list:
```python
conifers = ["pine", "cedar", "fir"]
cycads = ["cycas", "encephalartos"]
    
ordered_plants = conifers + cycads
sorted_plants = sorted(ordered_plants)
print(sorted_plants)
```
### Project Structure
```python
.
├── README.md
├── exercise_lists.py
└── notebooks/
    └── lists_practice.ipynb
```
### How to Run

1. Clone the repository:
```bash
git clone <your-repository-url>
```
2. Navigate to the project directory:
```bash
cd your-repository-name
```
3. Run the Python script:
```bash
python exercise_lists.py
```
Or open the notebook:
```bash
jupyter notebook notebooks/lists_practice.ipynb
```
### Author

Ibrahim Ambale

### License

This project is for educational purposes and is open for learning and practice.



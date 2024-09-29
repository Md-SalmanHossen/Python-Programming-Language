**datatypes** and **variables** in Python:

### 1. **What are Variables?**

Variables in Python are like containers that store data values. You can think of them as labels that hold data. They are essential for creating dynamic programs.

#### Example:
```python
name = "Alice"
age = 25
```
In this example:
- `name` is a variable that stores the string `"Alice"`.
- `age` is a variable that stores the integer `25`.

### 2. **Naming Variables**
- Variables can contain letters, numbers, and underscores (`_`), but cannot start with a number.
- They are **case-sensitive**: `myVariable` and `myvariable` are different variables.
- Use descriptive names that reflect the data they store.

#### Example:
```python
user_name = "John"
user_age = 30
```

### 3. **What are Datatypes?**

Datatypes define the type of data that can be stored in a variable. Python automatically assigns the datatype when a variable is created.

Here are the most common datatypes:

---

### 4. **Basic Data Types in Python**

#### 1. **Integers (`int`)**:
Whole numbers (without decimals).
```python
age = 25
```

#### 2. **Floating-point numbers (`float`)**:
Numbers with decimals.
```python
price = 19.99
```

#### 3. **Strings (`str`)**:
Text or sequence of characters, enclosed in single (`'`) or double (`"`) quotes.
```python
name = "Alice"
```

#### 4. **Booleans (`bool`)**:
Logical values representing `True` or `False`.
```python
is_student = True
is_employed = False
```

---

### 5. **Advanced Data Types in Python**

#### 1. **Lists (`list`)**:
An ordered collection of items, which can be of different types.
```python
fruits = ["apple", "banana", "cherry"]
```

#### 2. **Tuples (`tuple`)**:
Similar to lists, but immutable (cannot be changed).
```python
coordinates = (10, 20)
```

#### 3. **Dictionaries (`dict`)**:
Key-value pairs for storing data.
```python
person = {"name": "John", "age": 30}
```

#### 4. **Sets (`set`)**:
Unordered collection of unique items.
```python
unique_numbers = {1, 2, 3}
```

---

### 6. **Type Conversion (Casting)**

You can convert between different datatypes using Python's built-in functions.

#### Example:
```python
# Converting an integer to a string
age = 25
age_str = str(age)

# Converting a string to an integer
age_input = "30"
age_int = int(age_input)
```

#### Common conversion functions:
- `int()` – converts to integer
- `float()` – converts to float
- `str()` – converts to string
- `bool()` – converts to boolean

---

### 7. **Checking Data Types**

You can check the type of a variable using the `type()` function.

#### Example:
```python
age = 25
print(type(age))  # Output: <class 'int'>

name = "Alice"
print(type(name))  # Output: <class 'str'>
```

---

### 8. **Basic Operations with Variables**

You can perform operations on variables based on their types:

#### 1. **Math Operations on Numbers**:
```python
a = 10
b = 3

# Addition
print(a + b)  # Output: 13

# Subtraction
print(a - b)  # Output: 7

# Multiplication
print(a * b)  # Output: 30

# Division
print(a / b)  # Output: 3.333...

# Integer Division (Floor Division)
print(a // b)  # Output: 3

# Exponentiation (Power)
print(a ** b)  # Output: 1000
```

#### 2. **String Operations**:
```python
# Concatenation
first_name = "John"
last_name = "Doe"
full_name = first_name + " " + last_name
print(full_name)  # Output: John Doe

# Repeating Strings
repeat_text = "Hello " * 3
print(repeat_text)  # Output: Hello Hello Hello
```

---

### 9. **Variable Assignment and Reassignment**

Variables can be reassigned to new values at any point in your program.

#### Example:
```python
x = 5  # Initially, x is 5
x = 10  # Now, x is changed to 10
```

---

### 10. **Best Practices for Variables and Datatypes**

1. **Choose meaningful variable names**: Your code becomes easier to read.
    ```python
    # Not recommended
    x = 5

    # Better
    user_age = 5
    ```

2. **Use consistent naming conventions**: 
   - **Snake_case** is often used for variable names in Python (`my_variable`).
   - **CamelCase** is generally used for class names.

3. **Avoid using reserved keywords** as variable names (like `if`, `for`, `while`, `class`, etc.).

---

### Quick Reference:

| Data Type  | Example           | Description                           |
|------------|-------------------|---------------------------------------|
| `int`      | `age = 25`         | Whole numbers                         |
| `float`    | `price = 19.99`    | Decimal numbers                       |
| `str`      | `name = "John"`    | Text or sequence of characters        |
| `bool`     | `is_valid = True`  | Boolean values (`True`, `False`)      |
| `list`     | `numbers = [1, 2]` | Ordered collection of values          |
| `tuple`    | `coords = (0, 1)`  | Immutable ordered collection          |
| `dict`     | `person = {}`      | Key-value pairs                       |
| `set`      | `s = {1, 2, 3}`    | Unordered collection of unique values |

---

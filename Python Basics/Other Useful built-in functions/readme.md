
# Python Built-in Functions

This document provides an overview of the following Python built-in functions:

- `input()`
- `help()`
- `format()`
- `abs()`

## 1. `input()`

The `input()` function is used to take input from the user. It reads a line from input, converts it into a string, and returns it. This is particularly useful when you need to interact with users by asking for their input.

### **Syntax:**
```python
input([prompt])
```

- **prompt** (optional): A string that is displayed to the user before the input is taken.

### **Example:**
```python
name = input("Enter your name: ")
print(f"Hello, {name}!")
```

### **Usage:**
```python
# Example of input function
age = input("Enter your age: ")
print(f"You are {age} years old.")
```

---

## 2. `help()`

The `help()` function is used to display the documentation of modules, functions, classes, keywords, etc. It is an essential tool for beginners and experienced developers to understand how different functions and modules work.

### **Syntax:**
```python
help([object])
```

- **object** (optional): The object for which you want to see the documentation. If no argument is provided, it enters the interactive help system.

### **Example:**
```python
help(print)
```

### **Usage:**
```python
# Example of help function
help(str.upper)
```

---

## 3. `format()`

The `format()` function formats a given string into a more readable or desired output by embedding variables or values. It's a powerful way to create dynamic and formatted strings.

### **Syntax:**
```python
format(value[, format_spec])
```

- **value**: The value to be formatted.
- **format_spec** (optional): A string specifying the format.

### **Example:**
```python
formatted_string = "Hello, {}. You are {} years old.".format("Alice", 30)
print(formatted_string)
```

### **Usage:**
```python
# Example of format function
number = 123.456789
print("Formatted number: {:.2f}".format(number))
```

---

## 4. `abs()`

The `abs()` function returns the absolute value of a given number. The absolute value is the non-negative value of the number without regard to its sign.

### **Syntax:**
```python
abs(x)
```

- **x**: A number (integer or float) for which the absolute value is to be returned.

### **Example:**
```python
print(abs(-10))  # Output: 10
print(abs(4.5))  # Output: 4.5
```

### **Usage:**
```python
# Example of abs function
negative_number = -25
absolute_value = abs(negative_number)
print(f"The absolute value of {negative_number} is {absolute_value}.")
```

---

## Conclusion

These built-in functions are essential tools in Python for interacting with users, getting help on functions and modules, formatting strings, and working with numbers. Understanding and using these functions effectively can greatly enhance your Python programming skills.

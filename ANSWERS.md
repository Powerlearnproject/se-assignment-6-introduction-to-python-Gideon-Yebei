# Python Basics

Python is a high-level, interpreted programming language known for its simplicity and readability. Some key features include:

- **Easy-to-learn:** Python has a clean and straightforward syntax that makes it accessible for beginners.
- **Versatility:** It supports multiple paradigms (procedural, object-oriented, and functional programming).
- **Extensive libraries:** Python's standard library is vast and includes modules for tasks ranging from web development to scientific computing.
- **Community support:** It has a large and active community, contributing to its rich ecosystem of third-party libraries and frameworks.

**Examples of Python's Effectiveness:**

- **Web Development:** Django and Flask are popular frameworks for building web applications.
- **Data Science:** Libraries like NumPy, Pandas, and Matplotlib make Python ideal for data analysis and visualization.
- **Automation:** Python scripts can automate repetitive tasks such as file handling, data scraping, and system administration.

## Installing Python

- **Windows:**
   1. Download the latest Python installer from [python.org](https://www.python.org/downloads/windows/).
   2. Run the installer and select "Add Python to PATH" during installation.
   3. Open Command Prompt and verify Python installation:

      ```
      python --version
      ```

   4. Set up a virtual environment (optional):

      ```
      python -m venv myenv
      ```

- **macOS/Linux:**
   1. Python is typically pre-installed on macOS and most Linux distributions.
   2. Open Terminal and verify Python installation:

      ```
      python --version
      ```

   3. If not installed, install using package manager (e.g., `brew install python` on macOS).
   4. Set up a virtual environment:

      ```
      python3 -m venv myenv
      ```

## Python Syntax and Semantics

```python
# Simple Hello World program
print("Hello, World!")
```

- **Syntax Elements:**
  - **print():** Function used to output text to the console.
  - **Strings:** Enclosed in quotes (`"Hello, World!"`).
  - **Comments:** Lines starting with `#` are comments and ignored by Python.

## Data Types and Variables

- **Basic Data Types:**
  - **Integer (`int`):** Whole numbers (e.g., `5`, `100`).
  - **Float (`float`):** Decimal numbers (e.g., `3.14`, `2.718`).
  - **String (`str`):** Text enclosed in quotes (e.g., `"Hello"`, `'Python'`).
  - **Boolean (`bool`):** Represents `True` or `False`.

```python
# Variable examples
num1 = 5       # Integer
num2 = 3.14    # Float
name = "Alice" # String
is_active = True  # Boolean

# Printing variables
print(num1)
print(num2)
print(name)
print(is_active)
```

## Control Structures

- **Conditional Statements (if-else):**

   ```python
   # Example of if-else statement
   age = 20
   if age >= 18:
       print("You are an adult.")
   else:
       print("You are a minor.")
   ```

- **Loops (for loop):**

   ```python
   # Example of for loop
   fruits = ["apple", "banana", "cherry"]
   for fruit in fruits:
       print(fruit)
   ```

## Functions in Python

- **Functions:** Functions in Python are blocks of code that perform a specific task. They promote code reuse and modularity.

```python
# Function to calculate sum of two numbers
def calculate_sum(a, b):
    return a + b

# Example of calling the function
result = calculate_sum(3, 5)
print("Sum:", result)  # Output: Sum: 8
```

## Lists and Dictionaries

- **Lists:** Ordered collection of items, accessed by index.
- **Dictionaries:** Unordered collection of key-value pairs, accessed by keys.

```python
# Example of lists
numbers = [1, 2, 3, 4, 5]
print("List:", numbers)
print("First element:", numbers[0])  # Accessing list element

# Example of dictionary
person = {"name": "Alice", "age": 30, "city": "New York"}
print("Dictionary:", person)
print("Age:", person["age"])  # Accessing dictionary value
```

## Exception Handling

- **Exception Handling:** Mechanism to handle runtime errors gracefully.

```python
# Example of try-except-finally
try:
    x = 10 / 0  # Division by zero error
except ZeroDivisionError as e:
    print("Error:", e)
finally:
    print("Cleanup code or final actions")
```

## Modules and Packages

- **Modules:** Python files containing Python definitions and statements.
- **Packages:** Collection of related modules.

```python
# Example of importing and using a module
import math

# Using math module to calculate square root
num = 16
sqrt_num = math.sqrt(num)
print("Square root of", num, "is", sqrt_num)
```

## File I/O

- **Reading from a file:**

```python
# Reading from a file
with open("example.txt", "r") as file:
    content = file.read()
    print("File Content:")
    print(content)
```

- **Writing to a file:**

```python
# Writing to a file
data = ["Apple", "Banana", "Cherry"]
with open("fruits.txt", "w") as file:
    for fruit in data:
        file.write(fruit + "\n")
    print("Data written to file successfully.")
```

## Sources

- [Python Documentation](https://docs.python.org/3/)
- [Real Python](https://realpython.com/)
- [GeeksforGeeks](https://www.geeksforgeeks.org/python-programming-language/)
- [W3Schools Python Tutorial](https://www.w3schools.com/python/)
- [Python.org](https://www.python.org/)
- [Python for Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)
- [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/)
- [Fluent Python](https://www.oreilly.com/library/view/fluent-python/9781491946237/)
- [Python Crash Course](https://nostarch.com/pythoncrashcourse2e)
- [Django Documentation](https://docs.djangoproject.com/en/3.2/)
- [Flask Documentation](https://flask.palletsprojects.com/en/2.0.x/)
- [NumPy Documentation](https://numpy.org/doc/stable/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [PEP 8 -- Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/)
- [Python Virtual Environments: A Primer](https://realpython.com/python-virtual-environments-a-primer/)
- [Python Exceptions: An Introduction](https://realpython.com/python-exceptions/)
- [Python Modules and Packages: An Introduction](https://realpython.com/python-modules-packages/)
- [Python File I/O: An Introduction](https://realpython.com/read-write-files-python/)
- [Python Data Types: Numbers, Strings, and Lists](https://realpython.com/python-data-types/)
- [Python Functions: Overview](https://realpython.com/defining-your-own-python-function/)
- [Python Lists: An Overview](https://realpython.com/python-lists-tuples/)
- [Python Dictionaries: An Overview](https://realpython.com/python-dicts/)
- [Python Basics: A Practical Introduction to Python 3](https://realpython.com/python-basics/)
- [Python Programming Tutorials](https://www.programiz.com/python-programming)

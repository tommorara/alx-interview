# 0x00. Pascal's Triangle

## Background
This project is part of the ALX Interview Preparation curriculum. It focuses on algorithmic thinking using **Pascal's Triangle** as the core problem. The project is designed to help you practice fundamental Python concepts such as lists, loops, and functions.

## Learning Objectives
By completing this project, you should be able to:
- Understand Pascal's Triangle and its properties.
- Create and manipulate lists and list comprehensions.
- Use loops and conditional statements effectively.
- Design clean and efficient Python functions.
- Think about time and space complexity in algorithms.

## Project Requirements
- All Python files must be executable on **Ubuntu 18.04 LTS** using **Python 3.8**.
- No installation of external packages is allowed.
- Each Python file must end with a new line.
- Code must follow PEP8 style guidelines.

## Tasks

### 0. Pascal's Triangle
- **File:** `0-pascal_triangle.py`
- **Function:** `def pascal_triangle(n):`
- **Description:**
  - Returns a list of lists of integers representing the Pascal’s Triangle up to `n` rows.
  - If `n <= 0`, return an empty list.

#### Example Usage:
```bash
$ cat 0-main.py
#!/usr/bin/python3
"""
0-main
"""
pascal_triangle = __import__('0-pascal_triangle').pascal_triangle

def print_triangle(triangle):
    """
    Print the triangle
    """
    for row in triangle:
        print("[{}]".format(",".join([str(x) for x in row])))

if __name__ == "__main__":
    print_triangle(pascal_triangle(5))

$ ./0-main.py
[1]
[1,1]
[1,2,1]
[1,3,3,1]
[1,4,6,4,1]
```

## Repository
- **GitHub repository:** `alx-interview`
- **Directory:** `0x00-pascal_triangle`
- **File to Submit:** `0-pascal_triangle.py`

## Resources
- [What is Pascal’s Triangle](https://en.wikipedia.org/wiki/Pascal%27s_triangle)
- [Pascal’s Triangle - Numberphile](https://www.youtube.com/watch?v=0iMtlus-afo)
- [What are Python Algorithms](https://realpython.com/python-algorithms/)

## Author
ALX Software Engineering Program

---

> "Mathematics is not about numbers, equations, computations, or algorithms: it is about understanding." – William Paul Thurston


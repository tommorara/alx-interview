# 0x02. Minimum Operations

## Project Overview

This project focuses on solving a classic optimization problem using algorithmic techniques. Given a file containing a single character `H`, and two operations available — **Copy All** and **Paste** — the objective is to determine the minimum number of operations required to reach exactly `n` characters.

This is an exercise in understanding fundamental algorithmic strategies like **greedy algorithms**, **prime factorization**, and **dynamic programming**.

---

## Learning Objectives

By the end of this project, you should be able to:

- Break down complex problems using **dynamic programming**
- Apply **prime factorization** for optimization
- Use **greedy approaches** for minimal steps
- Write clean, efficient, and **PEP 8-compliant** Python code
- Understand how to optimize Python scripts

---

## Requirements

- **Language:** Python 3.4.3
- **Environment:** Ubuntu 20.04 LTS
- All files must:
  - Start with the line `#!/usr/bin/python3`
  - Be executable
  - End with a new line
  - Follow PEP 8 (version 1.7.x)
  - Contain documentation and comments

---

## Task

### 0. Minimum Operations

Write a function:

```python
def minOperations(n):
    """Returns the minimum number of operations needed to achieve exactly n H characters."""


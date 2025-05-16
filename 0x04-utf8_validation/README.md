# 0x04. UTF-8 Validation

## Project Description

This project implements a UTF-8 validation algorithm in Python. You will apply your knowledge of bitwise operations, the UTF-8 encoding scheme, and Python programming to determine whether a given data set (list of integers) represents a valid UTF-8 encoding.

## Requirements

* Allowed editors: `vi`, `vim`, `emacs`
* Ubuntu 20.04 LTS environment
* Python 3 interpreter (`python3` version 3.4.3)
* All files must:

  * End with a new line
  * Start with the shebang line: `#!/usr/bin/python3`
  * Be executable (`chmod +x`)
  * Conform to PEP 8 style (version 1.7.x)
* A mandatory `README.md` file at the root of the project

## Repository Structure

```
alx-interview/
└── 0x04-utf8_validation/
    ├── 0-validate_utf8.py    # UTF-8 validation function implementation
    ├── 0-main.py             # Test cases for `validUTF8`
    └── README.md             # Project documentation (this file)
```

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/alx-interview.git
   ```
2. Navigate to the project directory:

   ```bash
   cd alx-interview/0x04-utf8_validation
   ```
3. Ensure the files are executable:

   ```bash
   chmod +x 0-main.py 0-validate_utf8.py
   ```

## Usage

To run the validation tests:

```bash
./0-main.py
```

You should see output similar to:

```
True
True
False
```

## Task

**0. UTF-8 Validation** (mandatory)

* **Function Prototype:** `def validUTF8(data)`
* **Input:** `data` is a list of integers, each integer represents one byte (only the 8 least significant bits are used).
* **Output:** Returns `True` if `data` is a valid UTF-8 encoding, otherwise `False`.
* **UTF-8 Rules:**

  * Characters can be 1 to 4 bytes long.
  * For a 1-byte character, the first bit is `0`.
  * For an n-byte character (n > 1), the first byte starts with n bits set to `1` followed by a `0`, and each of the following bytes starts with `10`.
  * If the data ends prematurely or a byte does not match the required pattern, the encoding is invalid.

## Testing

* Use the provided `0-main.py` to test various cases.
* Add your own test cases by modifying `0-main.py` or creating additional test files.

## Resources

* [Python Bitwise Operators](https://docs.python.org/3/reference/expressions.html#bitwise-operations)
* [UTF-8 Encoding Scheme (Wikipedia)](https://en.wikipedia.org/wiki/UTF-8)
* [Characters, Symbols, and the Unicode Miracle](https://blog.restcase.com/what-are-utf-8-character-sets/)


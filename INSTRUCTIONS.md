## Overview
PyUtils: A simple Python utilities package with helpful functions for strings, numbers, files, and more.

For each of the 6 files in the `pyutils` package, they will have the following functionality:

1. **String Utilities**
- Reverse a string
- Check if a string is a palindrome
2. **Math Utilities**
- Find factorial of a number
- Find the nth Fibonacci number
3. **File Utilities**
- Count the number of lines in a text file
- Find the largest word in a text file
4. **Date & Time Utilities**
- Get today’s date in YYYY-MM-DD format
- Calculate difference between two dates
5. **Data Structure Utilities**
- Flatten a nested list
- Find the most frequent element in a list
6. **Randomization Utilities**
- Generate a random password of given length
- Shuffle a list randomly

### Requirements for each trainee
- Create an issue and wait for approval before working on a specific task
- Trainees are allowed to work on a minimum of 2 utilities
- Write code in class-based structure (each module = one class, with static methods).
- Write unit tests for each functionality.
- Update the README.md with usage examples for their functions.
- When you have fully tested your work, create a PR and request a review (note that you must fork this repo)

### Sample Code Structure
```
class ClassName:
    @staticmethod
    def reverse(text: str) -> str:
        return "yes!"

    @staticmethod
    def is_palindrome(text: str) -> bool:
        return True
```

### Sample Test Code
```
import pytest
from pyutils.strings import StringUtils

def test_reverse():
    assert <your test here>

def test_is_palindrome():
    assert <test case 1>
    assert <test case 2>
```

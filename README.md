# Lab: Linked Lists and Recursion

## Overview

This project demonstrates the use of **linked lists** and **recursion** to manage a simple list of employee IDs. It includes recursive implementations to:

- Sum all node values
- Reverse the list in-place
- Search for a specific value

This lab helps build foundational skills in node-based data structures and recursive problem solving.

---

## Features

- `insert_at_front(data)` – Adds a new node to the front of the list.
- `insert_at_end(data)` – Adds a new node to the end of the list.
- `recursive_sum()` – Returns the sum of all values in the list using recursion.
- `recursive_search(target)` – Checks if a target value exists in the list using recursion.
- `recursive_reverse()` – Reverses the list in-place using recursion.
- `display()` – Prints a string representation of the list.

---

## File Structure

```
Linked-Lists-and-Recursion/
├── linked_list.py          # Node and LinkedList class definitions
├── main.py                 # Manual driver script to run and test methods
├── tests/
│   └── test_linked_list.py # Unit tests using unittest
├── README.md               # Project documentation
```

---

## How to Run

### 1. Clone the Repository

```bash
git clone <your-forked-repo-url>
cd Linked-Lists-and-Recursion
```

### 2. Run Manual Tests

```bash
python3 main.py
```

This will:

- Insert sample data
- Print the original list
- Show the result of `recursive_sum`, `recursive_search`, and `recursive_reverse`

### 3. Run Unit Tests

```bash
python3 -m unittest discover -s tests
```

Expected output:

```
.....
----------------------------------------------------------------------
Ran 5 tests in 0.000s

OK
```

---

## Example Output

```
Original List:
1 -> 2 -> 3 -> None

Sum of all elements (recursive):
6

Searching for 2 (should be True):
True

Searching for 99 (should be False):
False

Reversing list (recursive)...
Reversed list:
3 -> 2 -> 1 -> None
```

---

## Notes

- All recursive methods use a helper function to handle traversal.
- The list is built from custom `Node` objects connected via the `next` attribute.
- Unit tests are written using Python’s `unittest` module.

---

## Author

Andrew Snyder  
Lab: Linked Lists and Recursion
Flatiron School of Software Engineering

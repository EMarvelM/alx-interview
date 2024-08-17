# 0x07. Rotate 2D Matrix

## Algorithm | Python

**Project Duration:**  
- Start Date: Aug 12, 2024, 6:00 AM  
- End Date: Aug 19, 2024, 6:00 AM

This project focuses on implementing an in-place algorithm to rotate an `n x n` 2D matrix by 90 degrees clockwise. The solution requires a solid understanding of matrix manipulation and in-place operations in Python.

## Key Concepts

### Matrix Representation in Python
- **Understanding 2D matrices:** Lists of lists in Python.
- **Accessing & Modifying Elements:** Indexing to manipulate matrix data.

### In-place Operations
- **Modifying the Matrix In-place:** Avoiding extra space usage by altering the original matrix directly.

### Matrix Transposition
- **Transposing a Matrix:** Swapping rows and columns as an initial step in rotation.

### Reversing Rows in a Matrix
- **Reversing Row Order:** A crucial step after transposition to achieve the final 90-degree rotation.

### Nested Loops
- **Iterating Through Matrices:** Using loops within loops to traverse and modify 2D structures.

## Resources

- **Python Official Documentation:**
  - [Data Structures (list comprehensions, nested list comprehension)](https://docs.python.org/3/tutorial/datastructures.html)
  - [More on Lists](https://docs.python.org/3/tutorial/datastructures.html#more-on-lists)
- **GeeksforGeeks:**
  - [Inplace Rotate Square Matrix by 90 Degrees](https://www.geeksforgeeks.org/inplace-rotate-square-matrix-by-90-degrees/)
  - [Transpose a Matrix in a Single Line in Python](https://www.geeksforgeeks.org/transpose-matrix-single-line-python/)
- **TutorialsPoint:**
  - [Python Lists](https://www.tutorialspoint.com/python/python_lists.htm)

## Task

### 0. Rotate 2D Matrix (Mandatory)
Given an `n x n` 2D matrix, rotate it 90 degrees clockwise.

- **Prototype:** `def rotate_2d_matrix(matrix):`
- **Return:** Do not return anything. The matrix must be edited in-place.
- **Assumption:** The matrix will have 2 dimensions and will not be empty.

### Example:

```python
#!/usr/bin/python3
"""
Test 0x07 - Rotate 2D Matrix
"""
rotate_2d_matrix = __import__('0-rotate_2d_matrix').rotate_2d_matrix

if __name__ == "__main__":
    matrix = [[1, 2, 3],
              [4, 5, 6],
              [7, 8, 9]]

    rotate_2d_matrix(matrix)
    print(matrix)
```

#### Expected Output:
```
[[7, 4, 1],
 [8, 5, 2],
 [9, 6, 3]]
```

### Requirements
- Editors: vi, vim, emacs
- Python Version: 3.8.10 (Ubuntu 20.04 LTS)
- File Naming: The first line of all files should be #!/usr/bin/python3
- Style: Your code should use the pycodestyle style (version 2.8.0)
- Modules: Do not import any external modules
- Documentation: All modules and functions must be documented
- Execution: All files must be executable

### Repository
- GitHub Repository: alx-interview
- Directory: 0x07-rotate_2d_matrix
- File: 0-rotate_2d_matrix.py

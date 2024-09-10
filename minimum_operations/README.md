# Minimum Operations

This project focuses on determining the minimum number of operations required to obtain exactly `n` characters in a text file that starts with a single character `H`. The available operations are **Copy All** and **Paste**.

## Task

### 0. Minimum Operations

Create a function `minOperations(n)` that computes the minimum number of operations needed to generate exactly `n` `H` characters in the file.

**Prototype**:
```python
def minOperations(n)

- Returns an integer.
- If `n` is impossible to achieve, return `0`.

**Example**:
```
n = 9
H => Copy All => Paste => HH => Paste => HHH => Copy All => Paste => HHHHHH => Paste => HHHHHHHHH

Number of operations: 6
```

## Usage

```bash
./0-main.py
```

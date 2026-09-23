# Day-106-Descending-Sort
# Python Day 106 - Descending Sort

This program sorts the numbers in a list from largest to smallest using the `sort()` method with `reverse=True`.

## Example

Original list:

```text
[10, 40, 20, 50, 30]
```

Descending list:

```text
[50, 40, 30, 20, 10]
```

## Concepts Used

* List
* `sort()` method
* `reverse=True`
* Descending order
* `print()`

## How It Works

1. A list of numbers is created.
2. The original list is displayed.
3. The `sort()` method is used with `reverse=True`.
4. The numbers are arranged from largest to smallest.
5. The sorted list is displayed.

## Python Code

```python
numbers = [10, 40, 20, 50, 30]

print("Original list:", numbers)

numbers.sort(reverse=True)

print("Descending list:", numbers)
```

## Output

```text
Original list: [10, 40, 20, 50, 30]
Descending list: [50, 40, 30, 20, 10]
```

## Goal

The goal of this project is to understand how to sort a list in descending order using `sort()` and `reverse=True`.

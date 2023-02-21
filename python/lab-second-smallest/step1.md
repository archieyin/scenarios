# scond_smallest

Here's a Python function that first checks if the length of the list 'numbers' is less than 2, and returns None if it is; if not, it uses the walrus operator to find the second smallest value.
The function uses two variables, 'smallest' and 'second_smallest', to keep track of the current smallest and second smallest values, and updates the values of these two variables by iterating through the elements in the list.

```python
def second_smallest(lst):
    if (n:=len(lst)) < 2:
        return 'None'
    else:
        return sorted(lst)[1]
```


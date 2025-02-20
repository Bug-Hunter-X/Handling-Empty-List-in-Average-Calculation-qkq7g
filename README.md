# Python Average Calculator with Empty List Handling

This repository contains a Python function designed to calculate the average of a list of numbers.  It includes specific handling for the scenario where the input list is empty, preventing a common `ZeroDivisionError` that can occur when dividing by zero.

## Function: `calculate_average(numbers)`

The function takes a list of numbers as input.  If the list is empty, it returns 0. Otherwise, it calculates the sum of the numbers and divides by the count to return the average.

## Usage

```python
from calculate_average import calculate_average

my_numbers = [10, 20, 30, 40, 50]
average = calculate_average(my_numbers)
print(f"The average is: {average}")  # Output: The average is: 30.0

empty_list = []
average = calculate_average(empty_list)
print(f"The average is: {average}")  # Output: The average is: 0
```
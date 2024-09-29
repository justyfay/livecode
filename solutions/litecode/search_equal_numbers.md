```python
def search_equal_numbers(numbers: list, result_number):
    for i in range(len(numbers)):
        for j in numbers[i + 1:]:
            if numbers[i] + j == result_number:
                return True
        return False
```
```python
def check_brackets(brackets: str) -> bool:
    open_bracket_counter = 0
    close_bracket_counter = 0

    for bracket in brackets:
        if bracket == "(":
            open_bracket_counter += 1
        if bracket == ")":
            close_bracket_counter += 1
    return True if open_bracket_counter == close_bracket_counter else False
```
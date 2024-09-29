```python
import re


def check_palindrome(word: str) -> bool:
    reformat_word = re.sub("[^A-Za-z0-9]", "", word).lower()
    actual_word = reformat_word[::-1]
    if reformat_word == actual_word:
        return True
    return False

``` 
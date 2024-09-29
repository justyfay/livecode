```python
from collections import defaultdict

d = defaultdict(int)


def decorator(func):
    def wrapper(*args, **kwargs):
        global d
        d[func.__name__] += 1
        print(f"Function '{func.__name__}' has '{d[func.__name__]}' calls.")
        return func(*args, **kwargs)

    return wrapper
```

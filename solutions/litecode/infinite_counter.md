```python
import time


def counter(count: int = 0):
    var: int = 0
    while isinstance(var, int):
        var += 1
        time.sleep(1)
        print(var)
        if count == var:
            break
```
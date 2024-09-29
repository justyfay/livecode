```python
class Solution(object):
    def fib(self, n):
        return n if n <= 1 else self.fib(n - 2) + self.fib(n - 1)
```

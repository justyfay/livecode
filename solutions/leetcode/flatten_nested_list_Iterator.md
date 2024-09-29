```python
class NestedIterator(object):

    def __init__(self, nested_list):
        self.actual_value: int = 0
        self.actual_list = []
        self.iter_run = self.iteration(nested_list)

    def iteration(self, values: list):
        for value in values:
            if isinstance(value, int):
                yield value
            else:
                for sub_value in self.iteration(value):
                    yield sub_value

    def next(self):
        return self.actual_value

    def has_next(self):
        try:
            self.actual_value = next(self.iter_run)
            return True
        except StopIteration:
            return False
```
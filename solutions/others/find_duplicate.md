```python
from collections import defaultdict


class Answer:
    def find_duplicate(self, nums):
        d = defaultdict(int)
        for i in range(len(nums)):
            d[nums[i]] += 1
        return [key for key, value in d.items() if value >= 2][0]
```
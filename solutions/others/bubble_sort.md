```python
class Answer:
    def bubble_sort(self, nums):
        iterations = len(nums) - 1
        for i in range(iterations):
            for j in range(iterations - i):
                if nums[j] > nums[j + 1]:
                    nums[j], nums[j + 1] = nums[j + 1], nums[j]
        return nums
```
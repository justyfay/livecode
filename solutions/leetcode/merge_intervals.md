```python
class Solution(object):
    def merge(self, intervals):
        intervals: list = sorted(intervals, key=lambda x: x[0])
        cnt_intervals: int = len(intervals)
        actual_merge: list = []
        
        if cnt_intervals < 2:
            return intervals
        
        for i in range(cnt_intervals):
            if i + 1 != cnt_intervals and intervals[i][1] >= intervals[i + 1][0] >= intervals[i][0]:
                actual_merge.append([intervals[i][0], intervals[i + 1][1]])
            elif i + 1 != cnt_intervals:
                actual_merge.append(intervals[i + 1])
        return actual_merge
```
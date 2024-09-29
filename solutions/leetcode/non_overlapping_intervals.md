```python
class Solution(object):
    cnt_overlap_intervals = 0

    def erase_overlap_intervals(self, intervals):
        intervals = sorted(intervals, key=lambda x: x[1])
        start = intervals[0][1]
        for i in range(1, len(intervals), 1):
            if intervals[i][1] >= start and intervals[i][0] >= start:
                start = intervals[i][1]
            else:
                self.cnt_overlap_intervals += 1
        return self.cnt_overlap_intervals
```
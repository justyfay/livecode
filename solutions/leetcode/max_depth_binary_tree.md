```python
class Solution(object):
    def maxDepth(self, root):
        if root:
            l = self.maxDepth(root.left)
            r = self.maxDepth(root.right)
            return max(l, r) + 1
        return 0
```
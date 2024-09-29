```python
class Solution(object):
    def inorder(self, root, result):
        if root:
            self.inorder(root.left, result)
            result.append(root.val)
            self.inorder(root.right, result)
        return

    def inorderTraversal(self, root):
        result = []
        if root:
            self.inorder(root , result)
        return result
```
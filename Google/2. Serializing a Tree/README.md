# Problem

Given the root to a binary tree, implement serialize(root), which serializes the tree into a string, and deserialize(s), which deserializes the string back into the tree.

For example, given the following Node class

class Node:</br>
    def __init__(self, val, left=None, right=None):</br>
        self.val = val</br>
        self.left = left</br>
        self.right = right</br>
        
The following test should pass:

node = Node('root', Node('left', Node('left.left')), Node('right'))</br>
assert deserialize(serialize(node)).left.left.val == 'left.left'

# Process

# Trees
### Common Terminology
- **Node  :** A node is the individual item/data that makes up the data structure
- **Root  :** The root is the first/top Node in the tree
- **Left Child :** The node that is positioned to the left of a root or node
- **Right Child :** The node that is positioned to the right of a root or node
- **Edge  :** The edge in a tree is the link between a parent and child node
- **Leaf  :** A leaf is a node that does not contain any children
- **Height:** The height of a tree is determined by the number of edges from the root to the bottommost node


### Traversals
There are two categories of traversals when it comes to trees:  

- **Depth First :**  where we prioritize going through the depth (height) of the tree first.(eg. Pre-order, In-order, Post-order)**(use stack)**
- **Breadth First :** iterates through the tree by going through each level of the tree node-by-node.**(use queue)**

### Binary Trees
- Trees can have any number of children per node
- Binary Trees restrict the number of children to two (hence our left and right children).

### Binary Search Trees
A Binary Search Tree (BST) is a type of tree that does have some structure attached to it. In a BST, nodes are organized in a manner where all values that are smaller than the root are placed to the left, and all values that are larger than the root are placed to the right.

### Searching a BST
Searching a BST can be done quickly, because all you do is compare the node you are searching for against the root of the tree or sub-tree. If the value is smaller, you only traverse the left side. If the value is larger, you only traverse the right side.


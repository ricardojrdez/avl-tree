# avl-tree
Just a Python 3.7 implementation of AVL trees. The implementation makes an extensive use of recursion.

The class AVLNode defines the content of a node of the AVL tree. In particular, you can have nodes with just a key or with a key and an associated value.

The class AVLTree defines an AVL tree structure and its common operations. Current operations supported:

- Addition of a new node (requires a key and optionally, its associated value)
- Removal of a given key
- Visualization of an AVL tree (in pre-order, appending '-', '<', and '>' to indicate the level, left, and right child, respectively)
- Three order traversals. Returns a string containing the order and (optionally)  prints it to stdout 
	- In-order traversal
	- Post-order traversal
	- Pre-order traversal
- Maximum key value (returns the AVLNode)
- Minimum key value (returns the AVLNode)
- Search for a key
- Existence of a key
- Height of the AVL tree
- Number of nodes in the AVL tree

## License

Licensed under the [MIT](LICENSE) license.

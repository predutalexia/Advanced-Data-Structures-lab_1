# Advanced-Data-Structures lab_1

# Binary Search Tree in C++

## Features

- **Insert** a node into the tree
- **Delete** a node (handles all 3 cases: leaf, one child, two children)
- **Search** for a node by value
- **Inorder traversal** — prints all keys in sorted order
- **Minimum / Maximum** — finds the smallest and largest key in the tree


### Deletion Cases
1. **Leaf node** — simply remove it
2. **One child** — replace the node with its child
3. **Two children** — replace the node's key with its in-order successor (smallest key in the right subtree), then delete the successor

## Usage

### Compile

```bash
g++ lab1.cpp -o lab1
```

### Run

```bash
./lab1
```

### Example Output

```
Inorder: 1 3 4 5 6 7 9
After deleting 5: 1 3 4 6 7 9
Minimum: 1
Maximum: 9
```


## Requirements

- g++ compiler (C++11 or later)
- Tested with GCC 13.2.0 via MSYS2 on Windows

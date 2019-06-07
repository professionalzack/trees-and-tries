# Binary Trees
- [Source: Trekhleb's Readme](https://github.com/trekhleb/javascript-algorithms/tree/master/src/data-structures/tree/binary-search-tree)
- - In computer science, **binary search trees** (BST), sometimes called 
ordered or sorted binary trees, are a particular type of container: 
data structures that store "items" (such as numbers, names etc.) 
in memory. They allow fast lookup, addition and removal of 
items, and can be used to implement either dynamic sets of 
items, or lookup tables that allow finding an item by its key 
(e.g., finding the phone number of a person by name).

- [Coding School screenshot](https://drive.google.com/open?id=1FESKCopDso3uPNWluznLdDeq0-ssVV29)

## Complexities
- [Source: Trekhleb's Readme](https://github.com/trekhleb/javascript-algorithms/tree/master/src/data-structures/tree/binary-search-tree)

### Time Complexity

| Access    | Search    | Insertion | Deletion  |
| :-------: | :-------: | :-------: | :-------: |
| O(log(n)) | O(log(n)) | O(log(n)) | O(log(n)) |

### Space Complexity

O(n)

# trees-and-tries
short notes on treesearch

# Tree

A tree is a collection of nodes and edges (connections/lines)

## Characteristics

- Each tree's start node is called the `root node`
- Each node has only one parent node
- Edges in a tree are s called `branches`
- Nodes at the end with no children are called `leaves`
- The longest path from a leaf to the root is `height`

## Usecases

- File storage
- Comment trees
- Calculating the order of operations
- The Document Object Model (DOM)
- Data compression

![tree](https://ga-instruction.s3.amazonaws.com/assets/tech/computer-science/binary-trees-tries/english/binary-tree-3.png)

# Tries

Like a tree, only without the strict rules on Left or Right only

## Characteristics

- Trie is short for `Retrieval` 
- Each trie has a root node
- Each node has a value
- Each node can have references to other nodes
- Almost always store alphabetical data. For instance, value stored in a node is a letter and references are other letters that make up a word.
- Nodes can have properties. For example: 'isWord' on K would tell you a valid word was just spelt (pick)

## UseCases

- Autocomplete in search bars

![trie](https://ga-instruction.s3.amazonaws.com/assets/tech/computer-science/binary-trees-tries/root-node.png)

# AVL Tree

_This is 100% copied word for word from:
[ this github ](https://raw.githubusercontent.com/trekhleb/javascript-algorithms/master/src/data-structures/tree/avl-tree/README.md), which also has a .js file that builds a balances AVL trees_

In computer science, an **AVL tree** (named after inventors 
Adelson-Velsky and Landis) is a self-balancing binary search 
tree. It was the first such data structure to be invented. 
In an AVL tree, the heights of the two child subtrees of any
node differ by at most one; if at any time they differ by 
more than one, rebalancing is done to restore this property.
Lookup, insertion, and deletion all take `O(log n)` time in 
both the average and worst cases, where n is the number of 
nodes in the tree prior to the operation. Insertions and 
deletions may require the tree to be rebalanced by one or 
more tree rotations.

Animation showing the insertion of several elements into an AVL 
tree. It includes left, right, left-right and right-left rotations.

![AVL Tree](https://upload.wikimedia.org/wikipedia/commons/f/fd/AVL_Tree_Example.gif)

AVL tree with balance factors (green)

![AVL Tree](https://upload.wikimedia.org/wikipedia/commons/a/ad/AVL-tree-wBalance_K.svg)

### AVL Tree Rotations

**Left-Left Rotation**

![Left-Left Rotation](http://btechsmartclass.com/data_structures/ds_images/LL%20Rotation.png)

**Right-Right Rotation**

![Right-Right Rotation](http://btechsmartclass.com/data_structures/ds_images/RR%20Rotation.png)

**Left-Right Rotation**

![Left-Right Rotation](http://btechsmartclass.com/data_structures/ds_images/LR%20Rotation.png)

**Right-Left Rotation**

![Right-Right Rotation](http://btechsmartclass.com/data_structures/ds_images/RL%20Rotation.png)

### What's so good? (aka here is a small amount of original writing)

- Insertion can be a pain, but searching is great ( O(_log_N) )
- really good for breadth-first i think :)
- there's something called 'Red Black' trees ? that people think is better
- this is cool: [🌳](https://www.cs.usfca.edu/~galles/visualization/AVLtree.html)


## Tree Trivia

![pants](https://ga-instruction.s3.amazonaws.com/assets/tech/computer-science/binary-trees-tries/english/pants-meme.jpg)

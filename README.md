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

## Tree Trivia

![pants](https://ga-instruction.s3.amazonaws.com/assets/tech/computer-science/binary-trees-tries/english/pants-meme.jpg)

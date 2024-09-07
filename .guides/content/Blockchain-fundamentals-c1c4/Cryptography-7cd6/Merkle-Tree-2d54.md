|||guidance
### Merkle Tree

|||


Fundamental part of Blockchain, it allows for efficiency and security in verifying a large mass of data to validate the integrity of the data content.

In cryptography and computer science, a hash tree or Merkle tree is a tree data structure in which every "leaf" node (a node with no "child" nodes)  is labeled with the cryptographic hash of a data block.  Every other node that is not a leaf is labeled with the cryptographic hash of the labels of its child nodes. A hash tree allows efficient and secure verification of the contents of a large data structure. A hash tree is a generalization of a hash list and a hash chain.

Merkle Tree is a data structure for storing information in large datasets so that the verification of this dataset is efficient.

It contains a tree of summary information about a larger piece of data. Used to check your content.

According to Andreas M. Antonopoulos, in "The Bitcoin Protocol":  
Merkle trees are used to "summarize" and store all the transactions in a block, producing an overall digital fingerprint of the entire set of transactions, providing a very efficient process to verify whether a transaction is included in a block.

![Merkle tree](.guides/img/01/image2.png "Merkle tree")*Image: [Wikipedia](https://commons.wikimedia.org/wiki/File:Bitcoin\_Block\_Data.png), license Creative Commons Attribution-Share-Alike 3.0 Unported*

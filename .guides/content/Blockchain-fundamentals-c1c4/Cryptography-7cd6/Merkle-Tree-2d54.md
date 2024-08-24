### Merkle Tree

Fundamental part of Blockchain, it allows for efficiency and security in the verification of a large mass of data, to validate the integrity of the data content.

In [cryptography](https://en.wikipedia.org/wiki/Cryptography) and [computer science](https://en.wikipedia.org/wiki/Computer\_science), a hash tree or Merkle tree is a [tree](https://en.wikipedia.org/wiki/Tree\_(data\_structure)) data structure in which every "leaf" [node](https://en.wikipedia.org/wiki/Tree\_(data\_structure)\#Terminology) (a node with no "child" nodes)  is labelled with the [cryptographic hash](https://en.wikipedia.org/wiki/Cryptographic\_hash\_function) of a data block.  Every other node that is not a leaf is labelled with the cryptographic hash of the labels of its child nodes. A hash tree allows efficient and secure verification of the contents of a large [data structure](https://en.wikipedia.org/wiki/Data\_structure). A hash tree is a generalization of a [hash list](https://en.wikipedia.org/wiki/Hash\_list) and a [hash chain](https://en.wikipedia.org/wiki/Hash\_chain).  
Source: [Merkle tree \- Wikipedia](https://en.wikipedia.org/wiki/Merkle\_tree)

Merkle Tree is a data structure for storing information in large datasets (dataset) so that the verification of this dataset is efficient.

It contains a tree of summary information about a larger piece of data. Used to check your content.

According to Andreas M. Antonopoulos, in "The Bitcoin Protocol":  
Merkle trees are used to "summarize" and store all the transactions in a block, producing an overall digital fingerprint of the entire set of transactions, providing a very efficient process to verify whether a transaction is included in a block.

![Merkle tree](.guides/img/image2.png)  
Image: [Wikipedia](https://commons.wikimedia.org/wiki/File:Bitcoin\_Block\_Data.png) , license Creative Commons Attribution-Share-Alike 3.0 Unported

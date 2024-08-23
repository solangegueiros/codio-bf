## Basic structure of a blockchain: blocks, transactions and the chain

### Blocks

A block has:

* Transactions  
* Timestamp  
* Hash of the previous block  
* Nonce

A block is similar to a digital container. This container holds a list of transactions, a timestamp, and a unique identifier called a cryptographic hash. Each block also contains the hash of the previous block, effectively linking them together. This linkage ensures the integrity and continuity of the blockchain.

### Transactions

Transactions on blockchain are used for:

* transfer value  
* data:  
  * A message from an address to another  
  * A smart contract deployment  
  * An interaction with a smart contract

### The Chain

* Blocks are linked together in chronological order, forming a chain.  
* The cryptographic hash of the previous block in each block ensures the integrity and immutability of the blockchain.

This structure ensures that once a transaction is added, it becomes a permanent part of the blockchain.

![Blockchain = Chain of Blocks](.guides/img/image1.png)

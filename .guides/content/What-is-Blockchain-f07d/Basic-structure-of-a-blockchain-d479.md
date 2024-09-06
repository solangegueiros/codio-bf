## Basic Structure of a Blockchain: Blocks, Transactions and the Chain

### Blocks

A block has:

* Transactions  
* Timestamp  
* Hash of the previous block  
* Nonce

A block is similar to a digital container. This container holds a list of transactions, a timestamp, and a unique identifier called a cryptographic hash. Each block also contains the previous block’s hash, effectively linking them together. This linkage ensures the integrity and continuity of the blockchain.

### Transactions

Transactions on blockchains are used for:

* Transfer of value  
* Data:  
  * A message from one address to another  
  * A smart contract deployment  
  * An interaction with a smart contract

### The Chain

* Blocks are linked together in chronological order, forming a chain.  
* The cryptographic hash of the previous block in each block ensures the integrity and immutability of the blockchain.

This structure ensures that transactions become a permanent part of the blockchain. 

![Blockchain = Chain of Blocks](.guides/img/image1.png)

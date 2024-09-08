|||guidance
## Interact With Already Published Smart Contracts

|||


The Remix IDE allows you to interact with existing smart contracts that have already been deployed on the Ethereum blockchain. 

You need to have two pieces of information:  
1- The smart contract address  
2- The source code or an interface declaration.

The **At Address** feature in Remix makes it easy to connect to these contracts and call their functions directly from the IDE. 

Using the example Register, you already have the Register source code and the address deployed.  

In the File Explorer, open the smart contract Register source code. 

In the Deploy & Run Transactions session, locate the "At Address" field.  
Paste the contract's address into this field.

![](.guides/img/03/image38.png)

You can try it out using your smart contract deployed before or used this example:  
0x590955E5c7cebC3cbc15ee9B6737953706F6601D

![](.guides/img/03/image39.png)

Click the "At Address" button. Remix will load the smart contract using the source code that was opened.

View Contract Functions: The contract will appear under the "Deployed Contracts" section once loaded.   
You will see a list of all the public and external functions, events, and state variables defined in the contract.

Use GetInfo and SetInfo functions like when you deployed your first smart contract.

![](.guides/img/03/image40.png)

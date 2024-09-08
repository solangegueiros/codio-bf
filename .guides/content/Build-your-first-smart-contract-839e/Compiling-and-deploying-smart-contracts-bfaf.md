|||guidance
## Compiling and Deploying Smart Contracts Using the Remix IDE

### Compiling Your Smart Contract

|||


## Compiling and Deploying Smart Contracts Using the Remix IDE

### Compiling Your Smart Contract

Suppose you had enabled the “auto compile” option. In that case, the smart contract is already compiled, and a green light with the message compilation successful will appear next to the button in the left bar \- Solidity compiler.

![](.guides/img/03/image15.png)

### Confirming If Your Wallet Is Connected to Remix

Go to the Deploy & Run Transactions panel.

Check it out below the Environment dropdown. You should see  
**Sepolia (11155111) network**.

Also, the **Account** will display your MetaMask account address and balance.

![](.guides/img/03/image16.png)

You can publish your contract once your metamask wallet is connected with the Remix IDE. 

### Deploying the Smart Contract

With MetaMask connected, you can deploy your smart contract by clicking the **Deploy** button in the Deploy & Run Transactions panel.

![](.guides/img/03/image17.png)

MetaMask will prompt you to confirm the transaction.   
Review the gas fees and click "Confirm".

![](.guides/img/03/image18.png)

When a smart contract is deployed with Remix, it appears in the left panel under Deploy and Run Transactions.

![](.guides/img/03/image19.png)

Go to the bottom, and your smart contract will appear under the **Deployed Contracts** section.   
You can find the smart contract name: **Register**  
Next to the name is its address.

![](.guides/img/03/image20.png)

Each smart contract created has its unique address in the deployed network. 

Copy the smart contract address and save it.

For example, the Register address created here is   
0x590955E5c7cebC3cbc15ee9B6737953706F6601D

If you close Remix (or the lesson) and open it again, you will lose the smart contract address deployed here.

### Smart contract \- block explorer

You can check out the smart contract on the block explorer as well.

Go to [https://sepolia.etherscan.io/](https://sepolia.etherscan.io/) 

Paste the Register address in the search field in the Sepolia Etherscan.

![](.guides/img/03/image21.png)

You can see some information related to the smart contract, like the transaction where it was created.  
[https://sepolia.etherscan.io/address/0x590955e5c7cebc3cbc15ee9b6737953706f6601d](https://sepolia.etherscan.io/address/0x590955e5c7cebc3cbc15ee9b6737953706f6601d) 

![](.guides/img/03/image22.png)

Note that when a smart contract is created, the TO field is “Contract creation” and used to be the address 0x0, because it is not interacting with another address yet.

Another option to see the transaction on the block explorer is  
Go to Metamask  
Open the last transaction: “Contract creation”.   
Click on “View on block explorer”.

| ![](.guides/img/03/image23.png)  | ![](.guides/img/03/image24.png)  |
| :---- | :---- |

[https://sepolia.etherscan.io/tx/0xfaefe74489e0b2803985ae39b3891189a6b5d2d23d6bae5963e4f32e214c2712](https://sepolia.etherscan.io/tx/0xfaefe74489e0b2803985ae39b3891189a6b5d2d23d6bae5963e4f32e214c2712) 

![](.guides/img/03/image25.png)

This is the transaction made to create the smart contract.

In order to see the smart contract itself, click on the address in the “To” field near the “Created” word.

![](.guides/img/03/image26.png)

|||guidance


|||

## Get an NFT \- Mint an NFT Using A Block Explorer


**Minting an NFT** means creating a unique token on a blockchain. The digital collectible is only stored on the blockchain after minting an NFT.   
It’s important to know what is being stored during the minting process.   
It could be an entire work of art, in which case the entirety of the NFT and its metadata is stored “onchain,” or it could be a reference to information stored offchain in some external URL. Regardless of the data storage, the simplest way to think about minting is as the process of creating an NFT.

### Exploring the NFT on Etherscan

This smart contract address is an NFT:  
0x35EfE940D1216D441f915C11725B7e4Dc089E23C

Let's go to the Sepolia block explorer:  
[https://sepolia.etherscan.io/address/0x35EfE940D1216D441f915C11725B7e4Dc089E23C](https://sepolia.etherscan.io/address/0x35EfE940D1216D441f915C11725B7e4Dc089E23C).

![](.guides/img/04/image17.png)

Go to the “Contract” tab.  
The smart contract was verified on Etherscan, which means that its source code was published, and you can interact with the NFT in the same way that you did with your first smart contract on Remix.

![](.guides/img/04/image18.png)

### Connecting Etherscan with Your Wallet

Go to the tab “Write Contract”.

Over there, you can see all NFT functions that change the blockchain state through transactions.

Click on the button “Connect to web3”.

![](.guides/img/04/image19.png)

Maybe you received a message related to a “beta version feature”. Click “ok” and don't worry about it because we are on testnet.

Select MetaMask.  
![](.guides/img/04/image20.png)  
MetaMask will show a popup window asking permission to connect.

| ![](.guides/img/04/image21.png) Click “Next”. | ![](.guides/img/04/image22.png) Click “Confirm”. |
| :---- | :---- |

Now you can check it out that you are connected, with the green signal and the message “Connected \- Web3”

![](.guides/img/04/image23.png)

### Minting the NFT

Click and expand the function “mint”.

Copy and paste your wallet address in the “to (address)”  field.

Click on “Write”.

![](.guides/img/04/image24.png)  
MetaMask will prompt you to confirm the transaction.   
Review the gas fees and click "Confirm".

![](.guides/img/04/image25.png)

You can view the transaction on Sepolia Etherscan by clicking the button “View your transaction” like this:

![](.guides/img/04/image26.png)

[https://sepolia.etherscan.io/tx/0x3bc2e02ab8fa603a1586dfa59bd939d901d168f2bfd04dd8cf8a5dfb0e3636c7](https://sepolia.etherscan.io/tx/0x3bc2e02ab8fa603a1586dfa59bd939d901d168f2bfd04dd8cf8a5dfb0e3636c7)  
![](.guides/img/04/image27.png)

Congrats\! You minted your first NFT\!

Now, how can you see your NFT?

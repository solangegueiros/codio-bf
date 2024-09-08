|||guidance
## Connecting Remix With Your Wallet

|||


Remix enables users to connect their MetaMask wallet and interact with various networks, making it a powerful tool for deploying and managing smart contracts.

### Open the Deploy & Run Transactions Panel

Open **Deploy & Run Transactions**

### Select the Environment

Using the drop-down menu, you can select an environment to interact with. It will choose the chain you want to deploy and test your contracts.

Choose **Injected Provider \- MetaMask**   
When you select this, Remix will automatically detect MetaMask and prompt MetaMask to connect.

![](.guides/img/03/image6.png)

### Authorize the Connection on MetaMask

MetaMask will pop up a window asking you to allow Remix to connect to your wallet.   
Select the account you want to use and click "Next" and then "Connect".

| ![](.guides/img/03/image7.png)  | ![](.guides/img/03/image8.png)  |
| :---- | :---- |

After connecting, you can deploy and interact with your smart contract on the network selected in MetaMask.

### Confirm Connection

Check it out below the Environment dropdown. You should see  
Sepolia (11155111) network

Once connected, the **Account** field in the Deploy & Run Transactions panel will display your MetaMask account address and balance.

Once your wallet is connected, you can interact automatically with the network selected on the MetaMask Extension. A small reference under the Environment drop-down in Remix will indicate it.

![](.guides/img/03/image9.png)  
Injected Provider showing Sepolia Testnet and Account info

You are now ready to write a Smart Contract and Develop for Web3\!

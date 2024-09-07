|||guidance
## Faucets: obtaining testnet tokens

|||

## Faucets: obtaining testnet tokens

In the context of cryptocurrency, a faucet is a website or application that distributes small amounts of cryptocurrency or tokens to users, typically for free.

To interact with the Sepolia network, you must have some SepoliaETH. Different faucets can be used to get some. Usually, you can claim only a certain amount per day; the amount and regularity will depend on who is providing it.

A faucet is a web application that sends you tokens for a specific blockchain network.  For example, to get Ether testnet tokens, you'd have to choose an Ethereum testnet such as Sepolia.  Then, you'd go to the Sepolia Eth faucet and put in your wallet address so it can send you some tokens.

### Chainlink Testnet Faucet

Using the Chainlink Testnet Faucet, you can request testnet Sepolia ETH tokens.

Go to [https://faucets.chain.link/sepolia](https://faucets.chain.link/sepolia).

Ensure you have selected the Ethereum Sepolia network since this is where you want to receive the testnet ETH.

Click “Connect wallet” in the top right corner so the faucet app can detect the selected network and your wallet address.

Click on “I accept the Chainlink Foundation Terms of Service”.

Select Metamask  
![Chainlink faucet - Terms of Service and Select wallet](.guides/img/02/image12.png "Chainlink faucet - Terms of Service and Select wallet")*Chainlink faucet - Terms of Service and Select wallet*

On Metamask, a pop-up window will appear. 

![Chainlink Faucet - Metamask connection](.guides/img/02/image13.png "Chainlink Faucet - Metamask connection")*Chainlink Faucet - Metamask connection* 
Click on “Next”.

![Chainlink Faucet - Metamask connection permissions](.guides/img/02/image14.png "Chainlink Faucet - Metamask connection permissions")*Chainlink Faucet - Metamask connection permissions*

“Confirm” in the next window.


After accepting the terms for using your metamask information, it will automatically populate the Wallet Address portions of the web form with your wallet.

Select whether you’d like to receive Sepolia testnet ETH and/or Sepolia testnet LINK.

For now, you will use only Sepolia ETH. However, you can also get the token LINK on Sepolia, which you can use in future modules.  

![Chainlink faucet with wallet connected and Sepolia tokens selected](.guides/img/02/image15.png "Chainlink faucet with wallet connected and Sepolia tokens selected")  
*Chainlink faucet with wallet connected and Sepolia tokens selected*

Click on “Verify you’re human.”

To get SepoliaETH, you need to connect with your valid [GitHub](https://github.com/) account.

If you don't have it, you can create a new one at [https://github.com/](https://github.com/).  
This step is necessary to protect against spam requests.

Click on “Continue with GitHub”.

![Chainlink Faucet - Verify you’re human and Continue with GitHub](.guides/img/02/image16.png "Chainlink Faucet - Verify you’re human and Continue with GitHub")*Chainlink Faucet \- Verify you’re human and Continue with GitHub*

Click “Get tokens”. 

The tokens will be transferred from the faucet to the Metamask wallet address you connected to. Wait for the transaction to succeed; you will receive your tokens quickly.

The final result should look like the screenshot below.

![Chainlink Faucet - Tokens received with success](.guides/img/02/image17.png "Chainlink Faucet - Tokens received with success")  
*Chainlink Faucet \- Tokens received with success *

Now you have SepoliaETH in your wallet\!


## Block Explorers

A block explorer is an online tool or web application that allows users to view, search, and track information on a blockchain. It is not the blockchain itself, meaning that if a block explorer is not working, it doesn’t affect the blockchain.

A block explorer can be defined as a “window” into the blockchain, enabling anyone to explore details about transactions, blocks, addresses, and other relevant data in real-time. 

### Some popular block explorers

[Etherscan](https://etherscan.io/) is a widely used block explorer for Ethereum, allowing users to explore transactions, blocks, addresses, and smart contracts on the Ethereum blockchain.

[Blockchain.com Explorer](http://Blockchain.com) is a popular block explorer for Bitcoin and other cryptocurrencies, providing detailed transaction and block data.

[BlockScout](https://www.blockscout.com/) is an open-source and customizable block explorer used by different blockchains.

A block explorer's most notable elements are a search field, information on the latest blocks, and recent transactions.

![Etherscan - search field](.guides/img/02/image18.png "Etherscan - search field")*Etherscan \- search field*


![Etherscan - latest blocks and recent transactions](.guides/img/02/image19.png "Etherscan - latest blocks and recent transactions")*Etherscan \- latest blocks and recent transactions*


## What you can do using a block explorer

### Transaction Tracking

Block explorers allow users to search for specific transactions by entering a transaction ID (TXID) or hash. This feature provides details such as the transaction status (confirmed or pending), the amount of cryptocurrency or token sent, the addresses involved, and when the transaction was processed.

### Block Details

Users can view information about individual blocks, such as the block number, timestamp, size, and the number of transactions it contains. 

Block explorers also show the validator who added the block to the blockchain and the associated block reward.

### Address Lookup

Block explorers enable users to search for blockchain addresses to see their balance and transaction history, including incoming and outgoing transactions, the total amount of cryptocurrency or tokens sent and received, and the current balance.

### Blockchain Analytics

Some block explorers provide additional analytics and insights, such as the overall network hash rate, transaction fees, and historical data trends. These features can be helpful for developers, researchers, and traders who need to analyze blockchain performance.

### Smart Contract Interaction

Block explorers, like Ethereum and other EVM compatibles, often provide tools to interact with and monitor smart contracts on blockchains that support them. 

You can publish the smart contract’s source code to verify your smart contract. After that, users can view it, check the contract balance, and analyze contract events. 

Even if the source code is not published, the block explorer can find similar bytecodes in already published smart contracts and reveal them. 

Some block explorers allow you to connect your wallet and send transactions by calling functions in smart contracts. 

## Exercise \- Check your wallet address on the Block Explorer

On Metamask, copy your wallet address.

![Metamask - Copy wallet address](.guides/img/02/image20 "Metamask - Copy wallet address"]  
*Metamask \- Copy wallet address*

Go to [https://sepolia.etherscan.io/](https://sepolia.etherscan.io/) 

In the search field, paste the wallet address copied from your Metamask account and select the account.

For example, let's check the address 0xB2fbcc0219442945d55f62150C6a3fA0E4D79980

![Search for address 0xB2fbcc0219442945d55f62150C6a3fA0E4D79980 on Etherscan](.guides/img/02/image21.png "Search for address 0xB2fbcc0219442945d55f62150C6a3fA0E4D79980 on Etherscan")*Search for address 0xB2fbcc0219442945d55f62150C6a3fA0E4D79980 on Etherscan*

This is the result  
[https://sepolia.etherscan.io/address/0xb2fbcc0219442945d55f62150c6a3fa0e4d79980](https://sepolia.etherscan.io/address/0xb2fbcc0219442945d55f62150c6a3fa0e4d79980). 

![Sepolia Etherscan - address 0xB2fbcc0219442945d55f62150C6a3fA0E4D79980](.guides/img/02/image22.png "Sepolia Etherscan - address 0xB2fbcc0219442945d55f62150C6a3fA0E4D79980")  
*Sepolia Etherscan \- address 0xB2fbcc0219442945d55f62150C6a3fA0E4D79980*

At the window on the left, you can see that this account has 0.1 ETH and 25 LINK.

![Sepolia Etherscan - Token balances](.guides/img/02/image23.png "Sepolia Etherscan - Token balances")*Sepolia Etherscan \- Token balances*

The “Transactions” tab shows a transaction in which ETH was transferred.

[https://sepolia.etherscan.io/tx/0xfed56d015091edb476a630763170f71fd15bea8f5dfba0d4b32e1f355a44c1b6.png)(https://sepolia.etherscan.io/tx/0xfed56d015091edb476a630763170f71fd15bea8f5dfba0d4b32e1f355a44c1b6) 

![ETH transfer transaction](.guides/img/02/image24.png "ETH transfer transaction")*ETH transfer transaction*

In the “Token Transfer (ERC-20)”, it is possible to check the transaction where the token LINK was transferred.

[https://sepolia.etherscan.io/tx/0xc1c0b580f78bc8657a158671b3aad79506c40843461cae242312bdc1fff034fb](https://sepolia.etherscan.io/tx/0xc1c0b580f78bc8657a158671b3aad79506c40843461cae242312bdc1fff034fb)

![ETH token transfer (ERC-20) transaction](.guides/img/02/image25.png "ETH token transfer (ERC-20) transaction")*ETH token transfer (ERC-20) transaction*

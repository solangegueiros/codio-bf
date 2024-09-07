# BTF-02 \- Wallets and Testnets

## Learning Objectives

LO1: Clarify the purpose and types of digital wallets  
LO2: Install an Ethereum wallet  
LO3: Use testnets, faucets, and block explorers  
LO4: Use a wallet to interact with the Ethereum network

# Purpose and types of digital wallets

People rely on wallets to keep their valuables secure daily, from money to identification. A digital wallet serves a similar purpose in the digital world. It allows us to store various assets, such as crypto assets (digital money), our identity (represented by non-fungible tokens), membership cards, digital certificates, and more.

## Definition and purpose of digital wallets

A digital or crypto wallet is a key manager that allows you to manage your cryptocurrencies. You can check the balance and store, receive, or transfer crypto. Furthermore, they allow you to sign messages, proving that you own an address associated with your wallet. The most common are computer or mobile applications.

Wallets are applications that give you control over your account. “Like your physical wallet, it contains everything you need to prove your identity and handle your assets. Your wallet allows you to sign in to applications, read your balance, send transactions, and verify your identity.” (Ethereum wallets | ethereum.org. https://ethereum.org/ta/wallets/)

Most people use digital wallets to handle their digital assets and identity.

The primary function of a digital wallet is to interact with the blockchain, meaning it does not store value within itself. Instead, the value is stored on the blockchain. 

Your wallet is a tool for interacting with your blockchain account. That means you can swap wallet providers at any time. Many wallets also let you manage several blockchain accounts from one application.

Wallet providers don't have custody of your funds. They only allow you to see your assets and provide management tools.  
Cryptocurrencies and tokens never leave the blockchain. They are just transferred from one address to another.

Resume:

* Key manager used to manage your cryptocurrencies or tokens on blockchain  
* Authorize transactions and interact with web pages or decentralized applications  
* Subscribe to messages demonstrating that you own a wallet address

## Cryptography in digital wallets

A digital wallet is based on public and private keys, which can be generated using a mnemonic phrase. 

### Public key

A public key generates addresses for several blockchains.

These addresses can be shared with anyone who will send you cryptocurrency.

### Private key

The private key, as the name implies, is to be private and must be kept confidential.

Anyone who knows the private key is able to prove they own the cryptocurrency on that account and can send them to others.

The private key gives access to your cryptocurrencies, regardless of which wallet you use. So, even if your computer or smartphone gets compromised, you can still access your funds on another device if you have the corresponding private key (or seed phrase).

**Never share your private keys or a mnemonic phrase. Someone with your private key can perform transactions on your behalf, including spending your tokens.**

### Address

Crypto wallets also include one or more addresses.

An address is an alphanumeric identifier generated based on the public/private keys. It can be defined as a specific "location" on the blockchain to which coins can be sent to.

You can share your address with others to receive funds.

### Mnemonic

It is possible to generate a single address from a key pair, but wallets often use a mnemonic as the basis for generating several key pairs.

A mnemonic is a set of predefined words generated from a list. Usually with 12 or 24 words.

Anyone who knows a mnemonic can access and transfer all cryptos from all addresses generated from this mnemonic.

If you lose your wallet, you can use the mnemonic and set it up again in another application, computer, or cell phone.

You can even use the same mnemonic in different wallets.

**Attention: the mnemonic is the most important part of a wallet\!**

If you forgot or lost your mnemonic, you will have no backup of your wallet.

If something like this happens, but you still have access to the wallet, I strongly recommend transferring all cryptos immediately to another wallet (another mnemonic) before any catastrophe happens to it.

Mnemonic is also known as a:

* seed  
* seed phrase  
* recovery phrase  
* backup phrase

**Never share your mnemonic phrases or private keys. If someone has your mnemonic, they can perform transactions on your behalf, including spending your tokens.**

### Crypto vs bank account

Making an analogy to a bank account:

* The public key represents your account data: bank, branch, and account number.  
* To receive money from someone, you will disclose your account details.  
* The private key is your password. You don't tell anyone and only you can use it to withdraw funds.

There is a difference between cryptos and the banking environment: if a person knows your account details in a bank, they cannot see your balance and transactions.  
However, blockchain is public and transparent, so whoever knows that you are the owner of an address can track your balance and transactions.

Some blockchains are not fully public, they are permissioned, but they will not be covered now.

## Types of wallets: hot wallets, cold wallets, custodial vs non-custodial wallets

### Wallets groups: software, hardware, and paper

Crypto wallets can be classified into three groups: software, hardware, and paper wallets.

#### Software wallet

The majority of crypto wallet providers are software-based.  
It can also be classified into desktop, mobile, and web wallets.

* Desktop: software installed on your computer, which you download and execute locally on your machine.  
* Mobile: a software known by an app installed on your smartphone. These are convenient as they allow you to send and receive crypto using QR codes.  
* Web: there are two types:  
  * Browser extension: installed in your browser.  
  * Web site: accessed through a browser interface without downloading or installing anything.

In this course, web browser extension wallets are used. They store your keys locally, on your computer.

Some service providers hold and manage the private keys on your behalf. Although this may be more convenient for inexperienced users, it's a dangerous practice\! If you don't hold your private keys, you're trusting your money to someone else.

There is a popular phrase related to this:

**Not your keys, not your coins\!**

### Hardware wallet

Hardware wallets are physical, electronic devices that store your keys, generate addresses, and create transactions.

Some use a random number generator (RNG) to generate public and private keys. The keys are then stored on a device that isn't connected to the Internet.

Other hardware wallets can be connected to the Internet only when you are creating and sending a transaction.

Software wallets are more convenient than hardware wallets. However, hardware wallets tend to be the most secure alternative.

If you plan to hold your cryptocurrency for a long time or if you're holding large amounts of it, you should consider using a hardware wallet.

### Paper Wallet

A paper wallet consists of a "wallet" printed out on a piece of paper.

It is a piece of paper on which a crypto address and its private key are physically printed out in the form of QR codes. These codes can then be scanned to execute cryptocurrency transactions.

Paper wallets are useful for understanding the concepts of public and private keys. They are often used in events to teach these first concepts, but their use is now deemed obsolete and unreliable.

### Wallet types: hot or cold

Crypto wallets may also be called hot or cold wallets, depending on their working mechanisms.

#### Hot wallet

A hot wallet is any wallet that is connected to the Internet all the time.

Most software wallets are hot wallets connected to the Internet.

* Online Storage: Hot wallets are connected to the Internet, which makes them more convenient for daily transactions but also makes them more vulnerable to online attacks.  
* Types: These include mobile wallets, desktop wallets, and web wallets.  
* Use Case: Suitable for frequent transactions, blockchain interaction, and active trading. They provide easy access to funds but require robust security measures.

#### Cold wallet

On the other hand, cold wallets do not have an Internet connection. Instead, they use a physical medium to store the keys offline, making them resistant to online hacking attempts.

Hardware storage is a type of cold wallet that is one of the most secure alternatives.

So, cold wallets are a safer alternative to "storing" your coins. Long-term investors or HODLers use this method.

To resume:

* Offline Storage: Cold wallets are not connected to the internet, making them highly secure against online threats such as hacking and malware.  
* Types: Common types include hardware wallets (physical devices like USB sticks) and paper wallets (printed copies of private keys).  
* Use Case: They are ideal for long-term storage of large amounts of cryptocurrency. They are less convenient for frequent transactions but offer maximum security.

### Multisig wallet

A Multisig wallet is a wallet that needs more than one signature (or approval) to send a transaction, such as transferring cryptos.

Some service providers offer shared control of wallets; they can know one key, and you and others can know other keys. It must have more than one key to send a transaction.

It's important to check the technical approach of each wallet before choosing the most suitable for you.

## Security considerations for different wallet types

### Backup Your Seed Phrase or Private Keys

Securely back up your seed phrase or private keys in multiple offline locations to ensure you can recover your wallet if needed.

### Be Aware of Phishing and Scams

Be cautious of phishing attacks and scams. Always verify the authenticity of websites, emails, and apps before entering sensitive information.

### Secure Your Devices

Ensure the devices you use to access your wallet are secure, with up-to-date antivirus software and no malware.

### Use Reputable Wallet Providers

Choose wallets from reputable providers with strong security measures and positive reviews.

### Limit Online Exposure

Use cold or non-custodial wallets for long-term storage of large amounts of cryptocurrency, reducing the risk of online attacks.

### Segregate wallet purposes

Use different wallets for different objectives (e.g., one for everyday transactions, another for long-term storage).

### Conclusion

Each wallet type has its advantages and disadvantages, so it's essential to understand how they work before moving your funds.

Understand the basics of wallet security and stay informed about the latest security threats and best practices.

# Install an Ethereum wallet

## Setting up MetaMask

### Metamask overview

MetaMask is a self-custodial wallet provider supporting transactions in Web3. It's how you interact with the blockchain from inside your web browser (including checking token balances in your account).

Available as a browser extension and as a mobile app, MetaMask equips you with a key vault, secure login, token wallet, and token exchange—everything you need to manage your digital assets.

[A crypto wallet & gateway to blockchain apps | MetaMask](https://metamask.io/)

### Installation

To install MetaMask in your browser (using Chrome for the exercise), go to  
[https://metamask.io/download/](https://metamask.io/download/) 

* 

Select the option to download the browser extension  
![](.guides/img/02/image1.png)Chrome Metamask Extension Highlighted

Click on “Install Metamask for Chrome”.

![](.guides/img/02/image2.png)

You will be redirected to the Chrome browser Web Store, where you can add the extension to your browser  
![](.guides/img/02/image3.png)Chrome Web Store

Click on “Add to Chrome”.

You will need to Accept the MetaMask Permissions and Add the extension  
![](.guides/img/02/image4.png)MetaMask Extension Permissions Popup

Once downloaded and installed, you will see the MetaMask Fox Logo in your extensions popup.

![](.guides/img/02/image5.png)Metamask extension

If you would like MetaMask to always be visible, click the Pin Icon to the left of the Kabab Button. This will make MetaMask easily accessible for the rest of the course. You can toggle this off if you want to revert it later.

### Create a new wallet

If you already have a Wallet (private key or mnemonic phrase), you can **Import an Existing Wallet**.   
For this course, choose “**Create a new wallet**”.

Agree to the Terms and Conditions of MetaMask by  
clicking on “I agree to MetaMask’s Terms of Use”.

If you already have some cryptocurrencies or tokens on mainnet, do NOT use the same wallet during the course or while learning.

Click on the button “Create a new wallet”.  
![](.guides/img/02/image6.png)Selecting Permissions and Creating a New Wallet

### Create a password for MetaMask

The password created here is to unlock this extension in your browser. This password is not the mnemonic/backup phrase to your wallet or your private key. You will retrieve those in the following steps.

Click on “I understand that MetaMask cannot recover this password for me.”

If you forget or lose your password, you can still recover your wallet using the mnemonic/backup phrase saved in the next steps.

![](.guides/img/02/image7.png)Creating a password on Metamask

### Reveal your mnemonic/secret recovery phrase

The “secret recovery phrase” is a 12-word phrase that is the “master key” to your wallet and your funds.

Click on “Secure my wallet (recommended)”.

Save your Mnemonic

![](.guides/img/02/image8.png)Mnemonic reveal

**Record your Mnemonic phrase in a secret, safe, and dry place.**

This is used to recover your account if you lose your password.

**Attention:**  
**The seed phrase is the most important part of a wallet/account\!**  
**If you lose your seed phrase, you can not recover your wallet anymore.**

### Where to save the secret recovery phrase

Write down this 12-word secret recovery phrase and save it in a place you trust and can only access it.

Some options:

* Save in a password manager  
* Store in a safe deposit box  
* Write down and store in multiple secret places

Never, ever share your secret recovery phrase, not even with MetaMask\!

If someone asks for your recovery phrase, they are probably trying to steal your wallet funds.

### Confirm the secret recovery phrase

Write back some words on the next screen to confirm that you saved your secret recovery phrase correctly.

![](.guides/img/02/image9.png)Wallet creation successful

## Securing your wallet: best practices

### Store your secret recovery phrase safely

Write down your Secret Recovery Phrase on paper and store it in a secure, offline location.

To prevent unauthorized access, avoid saving it digitally (e.g., in cloud storage or on your phone).

### Use strong, unique passwords

Create a robust and unique password for your wallet that combines upper and lower-case letters, numbers, and special characters.  
Do not reuse passwords from other accounts.

### Enable two-factor authentication (2FA)

If your wallet supports 2FA, it can be enabled to add an extra layer of security. Use an authentication app rather than SMS-based 2FA for better protection.

### Keep your software updated

Regularly update your wallet software to the latest version to benefit from security patches and improvements. Enable automatic updates if available.

### Be aware of phishing attacks

Always double-check URLs and email addresses to ensure they are legitimate before entering sensitive information.

Do not click on suspicious links or download attachments from unknown sources.

### Use hardware wallets for valuable holdings

Consider using a hardware wallet to store large amounts of cryptocurrency. It provides enhanced security by keeping your keys offline.

Follow the manufacturer's instructions for setup and use.

### Backup your wallet regularly

Regularly backup your wallet and ensure the backups are stored in a secure, offline location. Test your backup periodically to ensure it works correctly.

### Monitor your accounts

Regularly check your wallet and transaction history for any unauthorized activity. Set up alerts if your wallet provider offers them.

### Practice physical security

Keep your computer and devices secure using strong passwords, encryption, and physical security measures. Avoid accessing your wallet from public or shared computers.

### Educate yourself continuously

Stay informed about the latest security practices and threats in the cryptocurrency space.  
Participate in communities and forums to share and gain knowledge about wallet security.

# Testnets, faucets, and block explorers

## Understanding testnets

In [blockchain](https://en.wikipedia.org/wiki/Blockchain) technology, a testnet is an instance of a blockchain that’s powered by the same or a newer version of the underlying software. It is used for testing and experimentation without risk to real funds or the main chain. Testnet [coins](https://en.wikipedia.org/wiki/Cryptocurrency) are separate and distinct from the official (mainnet) coins. They don't have value and can be obtained freely from faucets.  
Source: [Testnet \- Wikipedia](https://en.wikipedia.org/wiki/Testnet)

A testnet is a blockchain to play around. There’s no real money involved.

Each blockchain has its testnets. Some of them have more than one. Ethereum already has some testnets that are deprecated. At present (2024), Ethereum has two active testnets: Sepolia and Holesky.

Both testnets have differences. Sepolia is primarily utilized for decentralized application (DApp) stress tests, smart contract experiments, and other Ethereum Virtual Machine (EVM) functions. Holesky is specifically designed for more technical purposes, which include experimenting with staking designs, testing general infrastructure, and developing protocol-level concepts.

### Enabling testnets on Metamask

The blockchain default setup on Metamask is the Ethereum mainnet.

You can switch which blockchain (defaulting to mainnet Ethereum) you are on, including using testnets.

1. Open your MetaMask Wallet by going to the Extensions tab on Chrome.

![](.guides/img/02/image10]Account Overview screen and Mainnet Ethereum Selected

2. Click on the top left button and then click on the toggle button for **Show test networks**  
   ![](.guides/img/02/image11.png) Top left button dropdown list  
   

Since you are going to be interacting with smart contracts, you are going to use **Sepolia**.

### Sepolia Testnet

Sepolia is the recommended default testnet by Ethereum core developers for smart contract application development. 

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
![](.guides/img/02/image12.png)

On Metamask, a pop-up window will appear. 

| ![](.guides/img/02/image13.png) Click on “Next”. | ![](.guides/img/02/image14.png) and “Confirm” in the next window |
| :---- | :---- |

Chainlink Faucet \- Metamask connection

After accepting the terms for using your metamask information, it will automatically populate the Wallet Address portions of the web form with your wallet.

Select whether you’d like to receive Sepolia testnet ETH and/or Sepolia testnet LINK.

For now, you will use only Sepolia ETH. However, you can also get the token LINK on Sepolia, which you can use in future modules.  
![](.guides/img/02/image15.png)  
Chainlink faucet with wallet connected and Sepolia tokens selected.

Click on “Verify you’re human.”

To get SepoliaETH, you need to connect with your valid [GitHub](https://github.com/) account.

If you don't have it, you can create a new one at [https://github.com/](https://github.com/).  
This step is necessary to protect against spam requests.

Click on “Continue with GitHub”.

![](.guides/img/02/image16.png)Chainlink Faucet \- Verify you’re human and Continue with GitHub

Click “Get tokens”. 

The tokens will be transferred from the faucet to the Metamask wallet address you connected to. Wait for the transaction to succeed; you will receive your tokens quickly.

The final result should look like the screenshot below.

![](.guides/img/02/image17.png)  
Chainlink Faucet \- Tokens received with success 

Now you have SepoliaETH in your wallet\!

## Block Explorers

A block explorer is an online tool or web application that allows users to view, search, and track information on a blockchain. It is not the blockchain itself, meaning that if a block explorer is not working, it doesn’t affect the blockchain.

A block explorer can be defined as a “window” into the blockchain, enabling anyone to explore details about transactions, blocks, addresses, and other relevant data in real-time. 

### Some popular block explorers

[Etherscan](https://etherscan.io/) is a widely used block explorer for Ethereum, allowing users to explore transactions, blocks, addresses, and smart contracts on the Ethereum blockchain.

[Blockchain.com Explorer](http://Blockchain.com) is a popular block explorer for Bitcoin and other cryptocurrencies, providing detailed transaction and block data.

[BlockScout](https://www.blockscout.com/) is an open-source and customizable block explorer used by different blockchains.

A block explorer's most notable elements are a search field, information on the latest blocks, and recent transactions.

![](.guides/img/02/image18.png)  
Etherscan \- search field

![](.guides/img/02/image19.png)Etherscan \- latest blocks and recent transactions

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

![](.guides/img/02/image20]  
Metamask \- Copy wallet address

Go to [https://sepolia.etherscan.io/](https://sepolia.etherscan.io/) 

In the search field, paste the wallet address copied from your Metamask account and select the account.

For example, let's check the address 0xB2fbcc0219442945d55f62150C6a3fA0E4D79980

![](.guides/img/02/image21.png)

This is the result  
[https://sepolia.etherscan.io/address/0xb2fbcc0219442945d55f62150c6a3fa0e4d79980](https://sepolia.etherscan.io/address/0xb2fbcc0219442945d55f62150c6a3fa0e4d79980). 

![](.guides/img/02/image22.png)  
Sepolia Etherscan \- address 0xB2fbcc0219442945d55f62150C6a3fA0E4D79980

At the window on the left, you can see that this account has 0.1 ETH and 25 LINK.

![](.guides/img/02/image23.png)Sepolia Etherscan \- Token balances

The “Transactions” tab shows a transaction in which ETH was transferred.

[https://sepolia.etherscan.io/tx/0xfed56d015091edb476a630763170f71fd15bea8f5dfba0d4b32e1f355a44c1b6.png)(https://sepolia.etherscan.io/tx/0xfed56d015091edb476a630763170f71fd15bea8f5dfba0d4b32e1f355a44c1b6) 

![](.guides/img/02/image24.png)

In the “Token Transfer (ERC-20)”, it is possible to check the transaction where the token LINK was transferred.

[https://sepolia.etherscan.io/tx/0xc1c0b580f78bc8657a158671b3aad79506c40843461cae242312bdc1fff034fb](https://sepolia.etherscan.io/tx/0xc1c0b580f78bc8657a158671b3aad79506c40843461cae242312bdc1fff034fb)

![](.guides/img/02/image25.png)

# Use a wallet to interact with the Ethereum network

## Creating a second account on your wallet

You can add another address to your wallet by highlighting the down carrot.

![](.guides/img/02/image26.png)

Open the “Account1” dropdown menu to show more options.

Select the Add Account button.

![](.guides/img/02/image27.png)

Add Account or Hardware Wallet button.

Select "Add a new account."

![](.guides/img/02/image28.png)

Add account confirmation

Give your wallet a name that you can identify, and then select Create

You can now transact with yourself if you want\!

## Transfers using an Ethereum wallet 

The simplest way to understand the end-to-end transaction process is to send coins to yourself from the first account to the second account just created in the previous step.

First, you must have some test tokens.

If you don't have it, go to the topic lesson **Faucets: obtaining testnet tokens.**

### Send 0.00001 SepoliaETH from Account 1 to Account 2

In your MetaMask extension, you can select the Send button to initiate a transaction.  
![](.guides/img/02/image29.png)

#### MetaMask browser popup

After selecting Send, you will be asked the public address of the account to which you want to send the tokens. 

For this exercise, select the 2nd account created (or the one that doesn't have tokens) to receive the test tokens.

![](.guides/img/02/image30]Example Transaction Builder Screen

You will then be moved to a confirmation screen that has several useful pieces of information: the asset you are trying to send (Token, NFT, etc.), the amount, and the estimated transaction fee.

After entering an amount of SepoliaETH to send to your 2nd wallet, you will see a confirmation screen that shows the amount you are sending, the estimated fee, and a confirmation button. Upon clicking this button, you will initiate the transaction.

![](.guides/img/02/image31.png)Confirmation Screen

While the transaction is reaching finality, you can monitor it in your transaction history at the bottom of your MetaMask Extension.

![](.guides/img/02/image32.png)Pending Transaction History

Once the transaction is complete, you can view more information in your MetaMask extension by selecting the transaction.

![](.guides/img/02/image33.png)Confirmed Transaction

![](.guides/img/02/image34.png)Transaction details

## Using block explorers to check accounts and transactions

You can view the transaction on the block explorer like you did with the faucet transactions.

Click the transaction and use the button “View on block explorer” on the details screen.  
![](.guides/img/02/image35.png)Etherscan Record of the transaction

You can confirm in our second account that they received the sent value of the tokens  
![](.guides/img/02/image36.png)2nd wallet confirmation of tokens

# BTF-03 \- Introduction to Solidity

## Learning Objectives

LO1: Outline Smart Contract Languages  
LO2: Use Remix IDE  
LO3: Create, Compile, and Publish Your First Smart Contract  
LO4: Interact With Smart Contracts

# Smart Contract Languages

[Smart contracts](https://chain.link/education/smart-contracts) are computer programs deployed and executed on a [blockchain](https://chain.link/education-hub/blockchain), operating autonomously once triggered. Once deployed, these contracts are immutable, meaning their code cannot be altered. They function without intermediaries, automatically executing predefined actions when called, making them highly reliable for decentralized applications (dApps).

## Programming Language Concepts

Programming languages allow developers to instruct computers to perform specific tasks. These languages have certain fundamental concepts that are shared across most programming environments.

Programming languages used to be human-readable code, which will be converted to machine-readable code, called bytecode.

## Smart Contract Languages on Ethereum

Ethereum, the pioneering blockchain platform for decentralized applications, supports various smart contract languages designed to create, deploy, and interact with smart contracts. These languages enable developers to write the code that runs on the Ethereum Virtual Machine (EVM), the decentralized computation engine that processes smart contracts.

Solidity, Vyper, and Yul/Yul+ are the primary languages used for Ethereum smart contract development. This course will focus on Solidity.

## Solidity Language

[Solidity](https://soliditylang.org/) is a high-level programming language designed specifically for writing smart contracts on blockchain platforms, most notably on Ethereum, although it is widely used across a range of EVM-compatible blockchains.

Key features of Solidity:

* Object-oriented language influenced by C++, Python, and JavaScript.  
* [Curly-bracket](https://en.wikipedia.org/wiki/List\_of\_programming\_languages\_by\_type\#Curly-bracket\_languages) language, where the characters { and } define statement blocks.  
* Solidity is statically typed, meaning that types (such as uint, string, etc.) are determined at compile time, which helps catch errors early in the development process.  
* Supports inheritance, libraries, and complex user-defined types, among other features.

Solidity is better for new smart contract developers because it comes with built-in protective measures—which can prevent costly mistakes. As the most widely used language in [Web3](https://chain.link/education/web3), Solidity developers have access to more libraries and tooling, better documentation, and increased developer support in forums.

References

* [Solidity docs](https://docs.soliditylang.org/)   
* [Yellow Paper](https://ethereum.github.io/yellowpaper/paper.pdf) 

# Using Remix IDE

The functional basics of creating and deploying your first smart contract.

[Remix](https://remix.ethereum.org/)

![](.guides/img/03/image1.png)

## How Developers and Non-Developers Can Interact With a Blockchain

Both developers and non-developers have various options for interacting with a blockchain. 

Here are some options to engage:

### Blockchain Explorers

Block explorers are portals to blockchains. They usually have a query field where you can look for addresses, blocks, smart contracts, and transactions.

In this lesson, you will use [Etherscan](https://etherscan.io/), a popular Ethereum block explorer. It allows developers and non-developers to search for transactions, view smart contract source code, and monitor the blockchain in real time.

### Remix IDE

[Remix](https://remix.ethereum.org/) is a powerful online IDE (Integrated Development Environment) that allows developers to write, compile, and deploy smart contracts in Solidity. It’s particularly user-friendly for those new to blockchain development. You will use Remix during this course.

## What Is the Remix IDE (Integrated Development Environment)?

[Remix](https://remix.ethereum.org/) has several features that are out of the box and facilitate the quick development of smart contracts. 

In this guide, the IDE's features​​ that will help you get going quickly will be highlighted, but feel free to reference the [documentation](https://remix-ide.readthedocs.io/) for further features, plugins, and community support.

Remix is a web-based Integrated Development Environment (IDE) designed for writing, testing, debugging, and deploying smart contracts on the Ethereum blockchain. Developed by the Ethereum Foundation, Remix is an essential tool for novice and experienced developers building dApps and smart contracts.

Let´s learn some useful Remix parts in this course and configure them.

For this workshop, you will be utilizing:

* File Explorer (Workspaces)  
* Terminal  
* Solidity Compiler  
* Deploy & Run transactions

### File Explorer (Workspaces)

The File Explorer (Workspaces) allows you to view your code's directory/tree structure on the left side of the screen. This portion houses our raw Solidity code; all smart contracts created will appear here.  
When you first open Remix, you will be in the default\_workspace, and some files and folders will already be there.  
You can create workspaces for different projects, but let's stay in the default workspace for now.

![](.guides/img/03/image2.png)  
Default Workspace

## Configuring Remix

### Open Remix

Go to [remix.ethereum.org](https://remix.ethereum.org/) 

### Solidity Compiler

The Solidity Compiler allows us to select when and how the code should be converted from human-readable to machine-readable. 

**Open the Solidity Compiler:** On the left sidebar, click the "Solidity Compiler" icon, which looks like a small S.

![](.guides/img/03/image3.png)

It is helpful to enable the **auto-compile** in order to compile smart contracts automatically while editing in Remix.

![](.guides/img/03/image4.png)Compiler Tab with Auto Compile enabled

**Your settings are saved\!** Once you’ve enabled “auto compile” or made any update, Remix will remember these settings for your session. There’s no need to save manually; your settings will be applied as you work.

### Deploy & Run Transactions

After compiling the source code, this tab allows you to easily publish the smart contract to the testnet and interact with the functions in our smart contract.

In the left sidebar of Remix, click on the "Deploy & Run Transactions" icon, which looks like an Ethereum diamond.

![](.guides/img/03/image5.png)

## Connecting Remix With Your Wallet

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

# Create, Compile, and Publish Your First Smart Contract

Let's create a smart contract, check if the compilation is successful, and publish your first smart contract\!

## How Developers and Non-Developers Can Create a Basic Smart Contract

You can publish a smart contract even if you are not a developer\!  
You are not creating the smart contract from zero; you will “copy and paste” the code and understand the commands and what part does. If you are not a developer, it probably will not be easy to make some changes in the smart contract, but you can do other courses later to become a smart contract developer.

When you create a smart contract, publish it, and interact with it, you understand blockchain in practice, and this will make a difference as a blockchain architect or project manager, for example.

The Remix IDE is the quickest and most efficient way to deploy a basic smart contract. It offers a clean, user-friendly interface that’s easy to configure and use.

## Create Your First Smart Contract

Go to the **File Explorer** in Remix; you will be in the “Default Workspace”. 

### Creating Register.sol

Right-click and add a new file called Register.sol  
![](.guides/img/03/image10.png)

**The .sol extension denotes solidity files.**

![](.guides/img/03/image11.png)Register.sol created

A new file will open on the right portion of the screen. In this section of the IDE, you can paste the following code, which creates a smart contract called "Register."

Copy the following smart contract code.

// SPDX-License-Identifier: MIT  
pragma solidity 0.8.19;

contract Register {  
    string private info;  
     
    function getInfo() public view returns (string memory) {  
        return info;  
    }

    function setInfo(string memory \_info) public {  
        info \= \_info;  
    }  
}

And paste it on the right side.  
![](.guides/img/03/image12.png)

You may see a popup window with the “Pasted Code Alert” message.  
![](.guides/img/03/image13.png)

Be careful when copying and pasting code. Make sure you fully understand this code before deploying or interacting with it.   
If you connect Remix with a wallet with real funds and interact with some code on Remix without knowing what the code can do, you can put your wallet at risk. In a worst-case scenario, you could lose all your money.  
 

For now, it is not a problem because you are using only testnets on this course, so there are no real funds.

![](.guides/img/03/image14.png)  
Register.sol created

This smart contract has:

\* A variable \`info\` to store a string  
\* A function \`getInfo()\` to return the string stored at variable info  
\* A function \`setInfo()\` to change the string stored at variable info

## Solidity Concepts: Language Version and Smart Contract Structure

Let's break down this Solidity code line by line.

// SPDX-License-Identifier: MIT

// denotes a comment in Solidity.  
Having a comment in the first line informing the license type is a good practice.

This line specifies the license under which the code is distributed.   
The SPDX-License-Identifier is a standard way to declare open-source licenses in smart contracts.   
MIT refers to the MIT License, a permissive free software license.

pragma solidity 0.8.19;

The pragma directive specifies the Solidity compiler version.

contract Register {

Here is the contract declaration, including the name, called Register.   
Everything between the braces {} will be the smart contract code.  
A contract in Solidity is similar to a class in object-oriented programming; it contains functions and state variables.

string private info;

This is a declaration of a state variable named info.  
The info variable has the type string and will store some string data.  
State variables are data that will be stored on the blockchain.  
The private keyword means that this variable can only be accessed by functions within this contract. The info variable will store some string data.

function getInfo() public view returns (string memory) {

This line declares a public function named getInfo that returns a string.   
The view keyword indicates that this function will not modify the state of the contract.   
The returns (string memory) specify that the function returns a string stored in memory.  
Everything between the braces {} will be executed when the function is called.

return info;

This line returns the value stored in the info variable.   
Since info is a private variable, this function provides a way to read its value outside the contract.

function setInfo(string memory \_info) public {

This line declares a public function, setInfo, that takes a parameter \_info of type string memory.   
The memory keyword indicates that this string is a temporary value that exists only during the function's execution.   
This function will be used to set or update the info variable.  
Everything between the braces {} will be executed when the function is called.

info \= \_info;

This line assigns the value passed to the function (\_info) to the state variable info.   
It effectively updates the stored string in the contract.

### Register.sol Summary

This contract, Register, is a simple Solidity contract that allows storing and retrieving a single string.   
It has a private state variable info, a public function getInfo to read the value of info, and another public function setInfo to update the value of info.

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

# Interact With Smart Contracts

After you have deployed a contract using the Remix IDE, you can interact with its functions directly on Remix.

## Interacting With the Smart Contract Created Before

Calling Read-Only Functions  
Functions that don’t require a transaction (view or pure functions) can be called directly without cost. Simply click on the function, input any required parameters, and click "Call" to execute the function. The result will be displayed in the console.  
Sending Transactions:   
For functions that alter the state of the contract (write functions), you’ll need to send a transaction. After inputting the required parameters, click "Transact".  
MetaMask (or your chosen provider) will pop up a window to confirm the transaction. Review the gas fees and click "Confirm" to execute the function.

Go to the smart contract deployed, located under the **Deployed Contracts** section. 

Click on the symbol **\>** to expand the details of the smart contract **Register.**

You can see two buttons, **getInfo** and **setInfo**, corresponding to the functions created in our smart contract\!

![](.guides/img/03/image27.png)

### GetInfo

The blue buttons are functions that are read-only. They do not change anything stored on the Blockchain, so you do not need to expend gas when using them.

Functions that don’t require a transaction (view or pure functions) can be called directly without cost.   
Simply click on the button with the function name: “GetInfo”.   
The result will be displayed in the console.

It has not stored any info in the smart contract yet so the result will be… nothing\!  
![](.guides/img/03/image28.png)

### SetInfo

The orange buttons are functions that alter the state of the smart contract (write functions), creating a transaction sent using the wallet connected to Remix, in our case, Metamask.

Each interaction will trigger a MetaMask confirmation pop-up, where you must confirm the transaction.

Let's write “Chainlink Certifications” and click on “setInfo”.

![](.guides/img/03/image29.png)

MetaMask will prompt you to confirm the transaction.   
Review the gas fees and click "Confirm".

![](.guides/img/03/image30.png)

### GetInfo (Again)

After the transaction is confirmed, call the “getInfo” function again.

![](.guides/img/03/image31.png)

Now you have the information stored on Blockchain\!

### Can the Information Be Updated?

Related to smart contracts, blockchains are immutable, which means that you can not update the source code.   
If you change anything in the source code, you must send a new transaction and deploy the smart contract again, creating a new smart contract with a new address.

But related to the data stored in the smart contract, it depends on the source code implemented.  
Regarding the Register, anyone can call the function “setInfo” again anytime.  
It means that YES, you can update the information 🙂

Let´s update the information to “Blockchain Fundamentals Certification”.

![](.guides/img/03/image32.png)

Click “SetInfo” again, wait for the transaction to be confirmed, and check it out on “getInfo”.

![](.guides/img/03/image33.png)

If you check out the smart contract on the block explorer, you can see that the “setInfo” function was called twice: 

![](.guides/img/03/image34.png)

Here, you have all the smart contract history and can audit any transaction\!

Let´s get more information about a transaction.

* Open the top setInfo transaction.  
* Scroll down to “More Details”.  
* Click on “ \+ Click to show more”.

![](.guides/img/03/image35.png)

It is possible to see that this transaction was the “setInfo” function call.

![](.guides/img/03/image36.png)

Click on “Decode Input Data”

Now you can see exactly what was stored in the smart contract\!

![](.guides/img/03/image37.png)

Even though the info variable is private, the transactions are public, and you can monitor a smart contract and see its content.  
It can be avoided by using cryptography, but it is an advanced topic not covered in this course.

## What is ABI (Application Binary Interface)?

You interacted with the smart contract deployed because you have the source code available.

You can interact with any smart contract already deployed in a blockchain network if you have two pieces of information:  
1- The smart contract address  
2- The ABI (Application Binary Interface)

The ABI, or Application Binary Interface, defines how to interact with a smart contract.   
It includes information about the contract's functions, inputs and outputs, events, and other interaction points.  
The ABI is the standard way to interact with smart contracts in the Ethereum ecosystem, both from outside the blockchain and for contract-to-contract interaction.

## Interact With Already Published Smart Contracts

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

Pinning smart contracts

If you “pin” the Register when you close the Remix session and return, the address will be saved, and you will find the smart contract again in the “Pinned Contracts” section.

![](.guides/img/03/image41.png)

 

# The End

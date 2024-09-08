# BTF-04 \- Tokenized Assets

## Learning Objectives

LO1: Outline tokenization concepts on blockchain  
LO2: Describe token standards  
LO3: Interact with ERC20 tokens and NFTs on testnet  
LO4: Identify tokens use cases

# Tokenization Concepts in Blockchain

## What Is Tokenization and What Are Its Benefits?

[Tokenization](https://chain.link/education/asset-tokenization) is the process of representing an asset's ownership rights as digital tokens stored on a blockchain. These tokens act like digital certificates of ownership and can represent many assets, including physical, digital, fungible, and non-fungible items. Because they are stored on a blockchain, tokenized assets allow owners to maintain custody over them securely, often through a crypto wallet.

The benefits of tokenization are substantial. It offers a decentralized, trust-minimized alternative to traditional products, investment vehicles, and services. Using blockchain technology, tokenization makes assets more valuable, accessible, and useful. It enhances the liquidity of traditionally illiquid assets and provides greater accessibility to investment opportunities that were previously difficult to access. Additionally, tokenization brings increased transparency regarding ownership and ownership history while reducing administrative costs associated with trading, such as those related to management, issuance, and intermediaries. Importantly, tokenization enables assets that previously could not participate in the [decentralized finance (DeFi)](https://chain.link/education/defi) ecosystem to do so, unlocking new potential through asset-backed composability.

If you’d like a deep dive into the tokenization megatrend, read this industry report with contributions from BCG, 21Shares, Paxos, Backed, and Chainlink: [The Definitive Guide to Tokenized Assets](https://blog.chain.link/definitive-guide-to-tokenized-assets/).

## Why Tokenize on a Blockchain?

Tokenizing assets on a blockchain refers to representing ownership or rights to real-world or digital assets as digital tokens on a blockchain. This process has several benefits and is becoming increasingly popular across various industries. 

Here are some key reasons for tokenizing assets on a blockchain:

### Increased Liquidity

**24/7 trading**: Tokenized assets can be traded on blockchain-based platforms around the clock, without the constraints of traditional market hours, increasing market accessibility and liquidity.

**Fractional ownership**: Tokenization allows assets to be divided into smaller parts, enabling fractional ownership. This can significantly increase liquidity, particularly for traditionally illiquid assets like real estate, art, or collectibles, by allowing a larger pool of investors to participate.

### Improved Accessibility

**Global reach**: Blockchain’s decentralized nature allows anyone with Internet access to invest in tokenized assets, eliminating geographical barriers and expanding the potential asset market.

**More affordable investment values**: By dividing assets into smaller tokens, tokenization makes it easier for a broader range of investors to participate in previously inaccessible markets.

### Enhanced Transparency and Security

**Smart contracts**: Tokenized assets are powered by [smart contracts](https://chain.link/education/smart-contracts), which automatically enforce the terms of agreements, reducing the need for intermediaries and ensuring that transactions are carried out as intended.

**Immutable records**: Blockchain technology ensures that the ownership history of tokenized assets is transparently recorded and cannot be altered, reducing the risk of fraud and enhancing trust among participants.

### Efficiency and Cost Reduction

**Reduced intermediaries**: Tokenization can streamline processes by reducing the need for intermediaries (e.g., brokers, escrow services), lowering transaction costs, and speeding up transactions.

**Automated Processes**: Smart contracts can automate complex processes such as dividend distribution, voting, and compliance checks, reducing administrative costs and human error.

### Transparency and Compliance

**Real-time monitoring**: Blockchain technology allows real-time tracking and monitoring of tokenized assets, making it easier for stakeholders to verify transactions.

**Regulatory compliance**: Tokenization can enhance compliance with regulatory requirements by embedding compliance rules directly into the tokens or smart contracts. This ensures that only eligible investors can participate and that transactions are automatically recorded for auditing purposes.

### Flexibility and Customization

**Programmable assets**: Tokens can be programmed to include specific rights, restrictions, or conditions, allowing for the creation of highly customizable financial instruments that can meet the particular needs of issuers and investors.

**Dynamic use cases**: Tokenized assets can be used in various ways beyond traditional trading, such as collateral in decentralized finance (DeFi), voting in governance systems, or access to digital services.

### Increased Trust and Security

**Decentralization**: [Blockchain](https://chain.link/education-hub/blockchain)’s decentralized nature reduces the risk of single points of failure, making tokenized assets more secure.

**Ownership verification**: Blockchain provides a clear, immutable record of ownership that all parties can easily verify. This reduces disputes and ensures that ownership claims are accurate.

### Asset Tokenization Examples

* **Real-world asset tokenization**—Real-world assets like fiat currency, equities, T-bills, credit, commodities, carbon credits, intellectual property, and fine art can be tokenized and stored on a blockchain. Gold bullion warrants and house deeds are bearer assets that give the holder a claim over a real-world asset. The main difference from legacy bearer assets is that physical asset tokenization enables assets to be stored, traded, and used as collateral across blockchain networks. ‍  
* **Digital asset tokenization**—Tokenizing assets that only exist in digital form on a blockchain network is critical to Web3, especially for use cases such as representing DAO governance rights and [cross-chain assets](https://chain.link/education-hub/cross-chain-tokenized-assets). Because they’re entirely digital, tokenized assets stored on a blockchain enable the owner to hold the asset outright rather than owning a claim on the underlying asset. ‍  
* **In-game asset tokenization**—A subset of digital asset tokenization, in-game assets used in GameFi projects or [metaverses](https://chain.link/education/metaverse), such as skins, weapons, or in-game currencies, can be represented as tokenized assets.

# Token Standards

## Standard Concepts

A standard in technology and engineering is a set of agreed-upon norms, rules, or guidelines that specify how something should be designed, implemented, or used.   
Standards are developed to ensure consistency, compatibility, and interoperability across different systems, products, or services.

A standard is not an obligation to be followed; it is a choice\!  
But if you say that your token follows a standard, other people will expect to find specific functions in your token, and you should declare them, even if you do not implement their definitions.

## Fungible and Non-Fungible Tokens

### Fungible Tokens

Assets with fungibility mean that each unit is identical, interchangeable, and divisible. Fungible assets like the US dollar, bitcoin, and even company reward points are used every day. 

Fungible tokens are interchangeable, and each unit has an identical value and function. Making them ideal for use in financial transactions, as currency, or in trading and settlement. Their fungibility ensures that each token is equal in value and function to any other token of the same type, which is fundamental to their role in the digital economy.

### Non-Fungible Tokens (NFTs)

Non-fungible assets mean that each unit is unique from one to another. 

An [NFT (non-fungible token)](https://chain.link/education/nfts) is a digital token with a unique, one-of-a-kind identifier that differentiates it from any other blockchain token.

An NFT is a unique digital asset representing ownership or proof of authenticity of a specific item or content, typically stored on a blockchain. 

NTFs cannot be exchanged on a like-for-like basis because they can have different values.  
The unique NTF properties, such as indivisibility, interoperability, and verifiability, make them a powerful tool for various applications, such as digital art, collectibles, [music](https://chain.link/education-hub/music-nfts), media, gaming pieces, domain names, or other unique assets.

## Token Standards and Their Purposes: ERC-20, ERC-721 (NFTs)

Token standards are rules or guidelines that define how tokens are created, managed, and interacted with on a blockchain. These standards ensure compatibility across different platforms and wallets, making it easier for developers to build and users to interact with tokens. 

Two of the most widely used token standards on the Ethereum blockchain are ERC-20 and ERC-721.

### ERC-20

[ERC-20](https://ethereum.org/en/developers/docs/standards/tokens/erc-20/) is the most common standard for creating fungible tokens on the Ethereum blockchain.   
It defines a set of rules and functionalities a smart contract must implement to create and manage tokens compatible with the Ethereum ecosystem.  
ERC-20 tokens are primarily used to create cryptocurrencies, utility tokens, and other digital assets where uniformity is essential.

Key characteristics of ERC-20 tokens:

**Fungibility**: ERC-20 tokens are fungible, meaning each token is identical and interchangeable with any other token of the same type. This makes them suitable for use as a medium of exchange, a unit of account, or a store of value.

**Interoperability**: Because ERC-20 is a standard, any token that follows this standard can be easily integrated with other Ethereum-based applications, including wallets, exchanges, and dApps. This ensures that ERC-20 tokens are widely compatible within the Ethereum ecosystem.

**Divisibility**: ERC-20 tokens can typically be divided into smaller units, allowing for precise transactions. For example, a token might have 18 decimal places, meaning the most minor and indivisible part is the 18th decimal place.

**Smart contract-based**: ERC-20 tokens are created and managed by smart contracts on the Ethereum blockchain. These contracts handle the creation, transfer, and management of the tokens according to the rules defined in the contract.

#### Smart Contract Definition

If a smart contract implements the following methods and events, it can be called an ERC-20 token contract. Once deployed, it will be responsible for keeping track of the tokens created on Ethereum.  
If a token is an ERC-20 token, it must have the following functions and events. Even if they are not implemented, they must be declared.

From [EIP-20](https://eips.ethereum.org/EIPS/eip-20):

**Functions:**

1. **`totalSupply`**:  
   * Returns the total supply of tokens that exist.  
2. **`balanceOf(address account)`**:  
   * Returns the balance of tokens for a specific address.  
3. **`transfer(address recipient, uint256 amount)`**:  
   * Transfers a specified token amount from the sender’s account to another account.  
4. **`approve(address spender, uint256 amount)`**:  
   * Approves a spender to transfer up to a specified amount of tokens on behalf of the owner.  
5. **`allowance(address owner, address spender)`**:  
   * Returns the remaining number of tokens that the spender is allowed to spend on behalf of the owner.  
6. **`transferFrom(address sender, address recipient, uint256 amount)`**:  
   * Transfers tokens from one account to another, typically used in conjunction with `approve` and `allowance` to manage delegated transfers.

**Events:**

* **`Transfer(address indexed from, address indexed to, uint256 value)`**:  
  * Emitted when tokens are transferred, including zero-value transfers.  
* **`Approval(address indexed owner, address indexed spender, uint256 value)`**:  
  * Emitted when the approve function sets an `approval`.

### ERC-721

ERC-721 is the standard for creating non-fungible tokens (NFTs) on the Ethereum blockchain.   
Unlike ERC-20, ERC-721 tokens are unique and cannot be exchanged one-to-one. 

Each ERC-721 token represents a distinct asset, making this standard ideal for digital art, collectibles, real estate, and other assets where uniqueness and individuality are essential.

Key characteristics of ERC-721: 

**Non-fungible**: Each ERC-721 token is unique, with a distinct identifier (usually a `uint256` token ID). This uniqueness differentiates ERC-721 tokens from ERC-20 tokens, where each unit is identical.

**Ownership**: ERC-721 tokens track ownership of specific assets. The standard includes functions to transfer ownership, approve others to transfer tokens on your behalf, and query ownership details.

**Metadata**: ERC-721 tokens can include metadata that describes the assets they represent. This metadata is often a URI (Uniform Resource Identifier) that points to additional data, such as digital artwork, game items, or other unique items.

**Interoperability**: As a standard, ERC-721 ensures that any tokens created using this standard can be recognized and used by other smart contracts, wallets, and applications that support ERC-721, enabling a broad ecosystem for NFTs.

#### Smart Contract Definition

If a smart contract implements the following methods and events, it can be called an ERC-721 token contract. Once deployed, it will be responsible for keeping track of the tokens created on Ethereum.  
If a token is an ERC-721 token, it must have the following functions and events. Even if they are not implemented, they must be declared.

From [EIP-721](https://eips.ethereum.org/EIPS/eip-721):

**Functions:**

**`balanceOf(address owner)`**: Returns the number of tokens owned by a specific address.

**`ownerOf(uint256 tokenId)`**: Returns the owner of a specific token by its ID.

**`safeTransferFrom(address from, address to, uint256 tokenId)`**: Safely transfers token ownership from one address to another, ensuring the recipient can handle ERC-721 tokens.

**`transferFrom(address from, address to, uint256 tokenId)`**: Transfers token ownership without safety checks (not recommended for general use).

**`approve(address to, uint256 tokenId)`**: Approves another address to transfer a specific token on behalf of the owner.

**`getApproved(uint256 tokenId)`**: Returns the address approved for a specific token.

**`setApprovalForAll(address operator, bool approved)`**: Approves or removes an operator as authorized to manage all of the sender's assets.

**`isApprovedForAll(address owner, address operator)`**: Checks if an operator is approved to manage all assets of a specific owner.

**Events**:

**`Transfer(address from, address to, uint256 tokenId)`**: Emitted when ownership of a token changes.

**`Approval(address owner, address approved, uint256 tokenId)`**: Emitted when the approval for a specific token is set or changed.

**`ApprovalForAll(address owner, address operator, bool approved)`**: Emitted when the approval status for all tokens owned by an address is set or changed.

# Interact With ERC20 Tokens and NFTs on Testnet

Make sure you have MetaMask installed on your browser or mobile device. The lesson “Wallets and Testnets” covers this.

## Add a Popular ERC-20 token (LINK/USDC) to the MetaMask Wallet on a Testnet

1. Open up MetaMask.

![][image1]

2. At the bottom window, click on the tab **“Tokens”.**

**![][image2]**

3. Click **“+ Import tokens”**.

![][image3]

4. Add the LINK token contract address on Sepolia:

***0x779877A7B0D9E8603169DdbD7836e478b4624789***  
See the [LINK Token Contracts](https://docs.chain.link/resources/link-token-contracts) page to find the addresses for different testnets.

5. Paste the token contract address into MetaMask in the Token contract address field. 

![][image4]

6. The token symbol and decimals of precision will auto-populate. Click the “Next” button.

7. Your balance for this token will appear in MetaMask. Click on “Import” to add this token to your MetaMask.

![][image5]

8. Confirm that the token appears in the tab “Tokens”.

![][image6]

## Get Tokens in a Faucet

Ensure you have some testnet LINK tokens on Sepolia to execute the next step.

If you don't have the token yet, go to [https://faucets.chain.link/sepolia](https://faucets.chain.link/sepolia).  
Review the “Chainlink Testnet Faucet” topic in the “Wallets and Testnets” lesson if you do not know how to do it.

## Send Tokens From One Account to Another One

1. **Access MetaMask:** Click the MetaMask extension icon in your browser or open the MetaMask mobile app.

![][image7]

2. **Select the account:** Ensure you’re on the account to which you want to send tokens.

![][image8]

3. **Navigate to the tokens tab:** In MetaMask, go to the "Tokens" tab to see the list of tokens available in your wallet.

![][image9]

4. **Select the token:** Click on the specific token you want to send. We will use the LINK token in this lesson.

![][image10]

5. **Click "Send"**: After selecting the token, click the "Send" button, which will prompt you to enter the recipient’s address.

![][image11]

6. **Enter the recipient’s address:** Paste the account's wallet address to which you want to send the tokens. Double-check the address to ensure it’s correct, as blockchain transactions are irreversible.

![][image12]

7. **Enter the amount:** Specify the number of tokens you wish to send. You can also choose to send the maximum amount by clicking "Use Max." Let’s send 5 LINK to the other wallet.

![][image13]

8. **Review the transaction details:** Before finalizing, review all the transaction details, including the recipient's address, token amount, and gas fees.

![][image14]

9. **Click "Confirm":** Once everything looks correct, click "Confirm" to initiate the transaction.

![][image15]

10. **Wait for confirmation:** The transaction will be validated and included in a block. You can view the transaction status in the "Activity" tab in MetaMask. Depending on network congestion, it may take a few seconds to a few minutes.

![][image16]

## Get an NFT \- Mint an NFT Using A Block Explorer

**Minting an NFT** means creating a unique token on a blockchain. The digital collectible is only stored on the blockchain after minting an NFT.   
It’s important to know what is being stored during the minting process.   
It could be an entire work of art, in which case the entirety of the NFT and its metadata is stored “onchain,” or it could be a reference to information stored offchain in some external URL. Regardless of the data storage, the simplest way to think about minting is as the process of creating an NFT.

### Exploring the NFT on Etherscan

This smart contract address is an NFT:  
0x35EfE940D1216D441f915C11725B7e4Dc089E23C

Let's go to the Sepolia block explorer:  
[https://sepolia.etherscan.io/address/0x35EfE940D1216D441f915C11725B7e4Dc089E23C](https://sepolia.etherscan.io/address/0x35EfE940D1216D441f915C11725B7e4Dc089E23C).

![][image17]

Go to the “Contract” tab.  
The smart contract was verified on Etherscan, which means that its source code was published, and you can interact with the NFT in the same way that you did with your first smart contract on Remix.

![][image18]

### Connecting Etherscan with Your Wallet

Go to the tab “Write Contract”.

Over there, you can see all NFT functions that change the blockchain state through transactions.

Click on the button “Connect to web3”.

![][image19]

Maybe you received a message related to a “beta version feature”. Click “ok” and don't worry about it because we are on testnet.

Select MetaMask.  
![][image20]  
MetaMask will show a popup window asking permission to connect.

| ![][image21] Click “Next”. | ![][image22] Click “Confirm”. |
| :---- | :---- |

Now you can check it out that you are connected, with the green signal and the message “Connected \- Web3”

![][image23]

### Minting the NFT

Click and expand the function “mint”.

Copy and paste your wallet address in the “to (address)”  field.

Click on “Write”.

![][image24]  
MetaMask will prompt you to confirm the transaction.   
Review the gas fees and click "Confirm".

![][image25]

You can view the transaction on Sepolia Etherscan by clicking the button “View your transaction” like this:

![][image26]

[https://sepolia.etherscan.io/tx/0x3bc2e02ab8fa603a1586dfa59bd939d901d168f2bfd04dd8cf8a5dfb0e3636c7](https://sepolia.etherscan.io/tx/0x3bc2e02ab8fa603a1586dfa59bd939d901d168f2bfd04dd8cf8a5dfb0e3636c7)  
![][image27]

Congrats\! You minted your first NFT\!

Now, how can you see your NFT?

## Interact With an NFT Marketplace on a Testnet

Some decentralized marketplaces allow you to see NFT collections, buy, sell, trade, and see the NFTs you own. One of them is [OpenSea](https://opensea.io/).

OpenSea has become a popular site in the NFT ecosystem, attracting creators and collectors and playing a significant role in encouraging the adoption of NFTs and blockchain technology.

We are on Sepolia Testnet, and OpenSea is also available on some testnets.

### Connection With OpenSea

To view your NFTs on OpenSea, follow these steps:

Go to [https://testnets.opensea.io/](https://testnets.opensea.io/).

Click on the “Login” button located at the top right corner.

![][image28]

Select Metamask.

![][image29]

MetaMask will show a popup window asking permission to connect.

| ![][image30] Click “Next”. | ![][image31] Click “Confirm”. |
| :---- | :---- |

Now, you have a signature request to accept the OpenSea Terms of Service ([https://opensea.io/tos](https://opensea.io/tos)) and Privacy Policy ([https://opensea.io/privacy](https://opensea.io/privacy)).

![][image32]

![][image33]

On MetaMask, read the message. Scroll down until the end, and click “Confirm”.

This request will not trigger a blockchain transaction or cost gas fees.

**Access Your Profile**  
Profile icon: Once your wallet is connected, click on your profile icon in the top right corner (the icon may display your wallet address or a profile picture if you've set one up).  
Profile page: You'll be taken to your profile page to see all the NFTs associated with the connected wallet.

![][image34]

### View Your NFTs

You'll see a section labeled "Collected" on your profile page.  
The section "Collected" displays all your NFTs in the connected wallet.   
You can browse through your NFTs, which will be categorized by collection or project.

![][image35]

You found your NFT\!

### Explore NFT Details

Click on the NFT to open a new page and see all details.

![][image36]

# Identify Token Use Cases

## Fungible Token Use Cases

### Real-World Asset Tokenization

Real-world assets like fiat currency, equities, T-bills, credit, commodities, carbon credits, intellectual property, and fine art can be tokenized and stored on a blockchain. Gold bullion warrants and house deeds are bearer assets that give the holder a claim over a real-world asset. The main difference from legacy bearer assets is that physical asset tokenization enables assets to be stored, traded, and used as collateral across blockchain networks. ‍

### Digital Asset Tokenization

Tokenizing assets that only exist in a digital form on a blockchain network is critical to Web3, especially for use cases such as representing DAO governance rights and cross-chain assets. Because they’re entirely digital, tokenized assets stored on a blockchain enable the owner to hold the asset outright rather than owning a claim on the underlying asset. ‍

### In-Game Asset Tokenization

A subset of digital asset tokenization, in-game assets used in GameFi projects or metaverses, such as skins, weapons, or in-game currencies, can be represented as tokenized assets.

## Stablecoins

Stablecoins are tokens designed to maintain a stable value relative to a specific asset or basket of assets, typically a fiat currency like the US dollar or euro, or a commodity like gold.

Unlike cryptocurrencies, such as Bitcoin or Ethereum, which can experience significant price volatility, stablecoins aim to provide price stability, making them more suitable for everyday transactions, savings, and as a store of value.

Some stablecoins:

* **Tether (USDT):** One of the oldest and most widely used stablecoins, Tether is pegged to the U.S. dollar at a 1:1 ratio.  
* **USD Coin (USDC):** Another popular stablecoin, USDC, is also pegged to the U.S. dollar and is known for its transparency and regular audits.  
* **USDS:** Unlike USDT and USDC, USDS is a decentralized stablecoin collateralized by other cryptocurrencies rather than fiat currency, and real-world assets.  
* **PAXG (Paxos Gold)**: Pegged to the price of gold, issued by Paxos.

## NFT Use Cases

### Digital Art NFTs

One of the most recognized NFT use cases is tokenized ownership of digital artwork. By tokenizing their work, artists can monetize their craft and tap into a global market of potential customers who only need an Internet connection to purchase it. Unlike traditional art marketplaces, which are often opaque, value-extracting, limited in discoverability, and require significant listing fees, NFTs can be listed on global, permissionless online marketplaces. They can even provide creators revenue from all secondary sales.

An example of NFT art that made headlines is the famous digital artist Beeple. His piece “[Everydays: The First 5000 Days,](https://onlineonly.christies.com/s/beeple-first-5000-days/beeple-b-1981-1/112924)” a collage of 5,000 images that took 12+ years to create, was tokenized as an NFT on Ethereum and sold for over $69M. Using the popular ERC-721 token standard, Beeple could monetize his digital artwork and establish cryptographic proof that the specific NFT was the official copy. Beeple’s artwork is only one of thousands of digital art collections released and sold worldwide as NFTs.

### Collectibles

Collectibles: NFTs can represent unique collectibles, such as trading cards, virtual pets, or rare in-game items.

Similar to collecting physical trading cards or mail stamps, NFTs empower a new type of digital collectible. Collectors can buy digital objects they deem valuable or signal their support for a specific company, brand, game, or artist. Unlike physical collectibles that can be slow to transport and expensive to maintain, NFTs have no such restraints as they are entirely digital, transferrable in seconds, and never degrade in quality.  
Some of the most recognized NFT collectibles are [CryptoPunks](https://www.larvalabs.com/cryptopunks), an algorithmically generated collection of 10,000 unique 8-bit-style characters, so no two characters are exactly alike. CryptoPunks were some of the first NFTs ever created and were given away for free. They continue to attract users who want to own an original piece of NFT history.  
Collectible NFTs are increasingly used as profile pictures on social media platforms like X and Discord. Doing so provides a powerful signaling mechanism where individuals can display their interest in an NFT collection and join a community of like-minded individuals.

### Gaming

NFTs are a foundational component of [blockchain-based video games](https://blog.chain.link/nft-games/) because they allow unique in-game items to be tokenized, tracked, and transferred in a non-custodial manner. With traditional online video games, centralized publishers have complete control over the distribution, ownership, and attributes of in-game items that often determine the value of certain characters and game outcomes. If the publisher shuts down, users lose access to all the game items they potentially spent hours, days, weeks, or even longer acquiring.

NFTs ensure users have complete control over their game items and enable entirely new gaming possibilities. This includes the creation of an interoperable metaverse—where the items from one game can be used and traded in another, and even marketplaces for [lending and renting](https://blog.chain.link/nft-lending-renting-blockchain-games/) various game NFTs. 

The implementation of gaming NFTs varies across games, from tokenizing cosmetic skins in MOBA and FPS games and characters in MMORPGs to creating general community membership NFTs that provide holders with early access to new game features, governance power to help shape a game’s direction, and more.

In-game assets: NFTs can represent unique in-game items, such as weapons, skins, or characters, which players can trade or sell outside the game environment.

Virtual real estate: Players can own and trade virtual land or properties within a game, creating a virtual economy.

### Real Estate

NFTs can also represent ownership of real-world assets like real estate to introduce additional liquidity into traditionally fragmented markets. [Tokenizing real estate](https://chain.link/education-hub/tokenized-real-estate) increases the efficiency of transferring ownership and provides a single source of truth around the authenticity and provenance of a specific property. The concept of [tokenizing real-world assets](https://chain.link/education-hub/how-to-tokenize-an-asset) can be expanded to include many asset types, such as physical paintings, government documents, certifications, and diplomas.

While still in the early stages, real-world assets tokenized as NFTs enable several new possibilities, from revenue-generating real-estate tokens backed by rental income to issuing digital credentials without needing a physical document counterpart. They can also digitize existing records like educational diplomas and intellectual property contracts, leading to more credentials transparency and new forms of automation.

### Fractional Ownership

Investors can buy fractions of a property, making real estate investment more accessible and liquid.

### Intellectual Property

Patents and trademarks: NFTs can be used to tokenize intellectual property rights, making it easier to license, transfer, and enforce these rights.

### Identity verification

Digital identities: NFTs can be used to create verifiable digital identities, which can be used for secure access to online services or as proof of identity.

### Event Tickets

Ticketing: NFTs can represent event tickets, ensuring authenticity and preventing fraud. These tickets can be easily transferred or resold on secondary markets.

### Supply Chain

Product provenance: NFTs can track products' origin and history, ensuring transparency and authenticity in the supply chain.

# The End

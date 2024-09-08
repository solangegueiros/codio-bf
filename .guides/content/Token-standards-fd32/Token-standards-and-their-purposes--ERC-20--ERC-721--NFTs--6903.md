|||guidance
## Token Standards and Their Purposes: ERC-20, ERC-721 (NFTs)

|||


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

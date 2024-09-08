|||guidance
## Token Standards and Their Purposes: ERC-20, ERC-721 (NFTs)

### ERC-20

#### Smart Contract Definition
|||


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

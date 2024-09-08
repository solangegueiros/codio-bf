|||guidance

## Create Your First Smart Contract

|||


Go to the **File Explorer** in Remix; you will be in the “Default Workspace”. 

### Creating Register.sol

Right-click and add a new file called Register.sol  
![](.guides/img/03/image10.png)

**The .sol extension denotes solidity files.**

![](.guides/img/03/image11.png)Register.sol created

A new file will open on the right portion of the screen. In this section of the IDE, you can paste the following code, which creates a smart contract called "Register."

Copy the following smart contract code.

```solidity
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
```

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


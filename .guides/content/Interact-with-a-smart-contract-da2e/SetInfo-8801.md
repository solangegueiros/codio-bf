|||guidance

### SetInfo

|||


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

|||guidance

### Monitoring the smart contract on the block explorer

|||

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

### Cryptographic Keys

There are two types of cryptographic keys:

* symmetric keys (single-key encryption)  
* asymmetric keys (public key cryptography)

Asymmetric keys are used in Blockchain.

### Public Key and Private Key in Blockchain

Public key cryptography provides a mechanism to secure and validate information between two parties securely and safely. The public key is linked to a corresponding private key. A public key is a publicly available cryptographic artifact that allows users to encrypt information that only you can decrypt. 

Example workflow: 

* Alice has a message she would like to send you.   
* Alice can use your public key to encrypt the message.   
* That message can now only be decrypted with the corresponding private key linked to the public key.

Cryptography:

* Anyone can encrypt a message using the recipient's public key.  
* Only the private key owner can decrypt messages encrypted with the corresponding public key.

Authentication:

* Only the private key owner can sign/authorize transactions (digital signature).  
* The public key confirms the sender's identity, verifying that the private key holder sent the message.

||| warning
**Make sure to avoid giving away your private key, as users can decrypt your messages and sign transactions in your name.**

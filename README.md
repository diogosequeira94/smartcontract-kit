## SmartContract-Kit 101

### Smart Contracts
Self executing sets of instructions, without 3rd parties and they come to life on the blockchain.

### Oracles
Are devices that bring data into a blockchain, or executes some kind of external computation. 

### Chainlink
Allows for unlimited smart contract customization

Dapp = Decentralized Application. It's usually an application which combines multiple smartcontracts 

### Keys:

- Private Key: Only known to the key holder, it's used to "sign" transactions. (password to digitally sign).

- Public Key: Anybody can verify that the signature is ours.

- Signing a transaction:

A "one way" process. Someone with a private key signs a transaction by their private key being hashed with ther transaction data.

Anyone can then verify this new transaction hash with your public key.

### Functions:

Making a function call or calling a variable, makes a transaction in the blockchain, thats why it takes a little bit of gas.

- View: Means that we want to read state off the blockchain, we are not making a state change. (Blue color)

- Pure: Purely do some kind of math. (Blue color)

### Keywords

In solidity there are more or less 2 ways of storing information: memory / storage

- Memory: Data will only be stored during the execution of the function.
- Storage: Data will persist even after the function is executed.
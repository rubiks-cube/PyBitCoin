# PyBitCoin  
A basic implementation of a blockchain using Python.

## Features:  
- Wallets generation using Public/Private key encryption  
- Generation of transactions with RSA encryption  
- Possibility of adding multiple nodes to the blockchain
- Proof of Work (PoW)  
- Simple conflict resolution between nodes
- Frontend for users to generate wallets and send coins

## Dependencies:  
- Python 3.6
- Flask  
- PyCrypto
 
 ## Running the code
 - A blockchain node can be started by executing the following command: python node.py --port 3000
 - Another node can be started by executing same command in another terminal window with different port which is not in use e.g. 8888
 - Frontend can be accessed in the browser by going to localhost:3000 and localhost:8888

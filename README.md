# -Hashstack_assignment
Overview

A scalable multi-signature wallet contract, which requires a minimum of 60% authorisation by the signatory wallets to perform a transaction.
Access registry contract that stores the signatories of this multi-sig wallet by address.
This access registry contract has its own admin. Capable of adding, revoking, renouncing, and transfer of signatory functionalities.

Goerli Testnet Network 
Contract address: 0xf3D440Ef6a0404db33b14D91f819bb3C3A80227e 

 Deployement 
Installation and testing
Install global dependencies:

npm install -g truffle
Install local dependencies:

npm install
To run the tests:

Make sure ganache is running a testnet.
trufflle migrate
truffle test

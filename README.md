# solidity-rent-manager
This project contains an implementation of a simple smart contract built in Solidity to simulate a decentralize Rent Manager application. It handles the registration of hosts and guests in the network and manages the assignment and payment of invoices between said hosts and guests.

# How to Run the Project
To run the program, download the Foundry toolset used to test Solidity applications. Then, use the following command:
```
forge test.
```

# Code Organization
The code relevant to the application implementation is located in `src/RentManager.sol`. The file contains a variety of functions, some of which were implemented by me, to handle user registration and invoice processing.

The file `test/RentManager.t.sol` contains seven test cases used to test that the application works as expected.
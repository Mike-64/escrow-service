# Escrow Service
This is a demo of a blockchain-based Escrow Service. The core logic is inside the EscrowService smart contract written in Solidity.
The web application provides a friendly UI to interact with the smart contract.

## Author - Michael Francis

## Web UI

#### Buyer
Using the Buyer interface buyers can set an agent address, the escrow condition and transfer funds to the smart contract.

#### Agent
Using the Agent interface elected agent can either release or revert funds (based on whether the previously set condition is met or not).

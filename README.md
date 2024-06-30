Project Title
Ganit Smart Contract

Description
The Ganit smart contract provides basic arithmetic operations and state management capabilities on the Ethereum blockchain using Solidity. It includes functions to set and retrieve a number, and pure functions for arithmetic operations like addition, subtraction, multiplication, and division. The contract ensures that division by zero is handled with a require statement.

Getting Started
Installing
This project is a Solidity smart contract and doesn't require installation in the traditional sense. You can interact with it on an Ethereum-compatible blockchain platform.

Executing program
To interact with the Ganit smart contract:

Deploying the Contract: Deploy the contract on a blockchain platform that supports Solidity smart contracts, such as Ethereum.

Interacting with Functions:

Use setNumber(uint256 _number) to set the value of number.
Use getNumber() to retrieve the stored number.
Use add(uint256 a, uint256 b), subtract(uint256 c, uint256 d), multiply(uint256 e, uint256 f), and divide(uint256 g, uint256 h) for performing arithmetic operations.
Help
Common Issues: Ensure you are interacting with the contract on an Ethereum-compatible network (like a testnet or mainnet). Handle errors related to division by zero by ensuring the divisor is greater than zero.
Authors
Created by Raja Kumar
Contact: @rajapusaho@gmail.com
License
This project is licensed under the MIT License. See the LICENSE.md file for details.

SPDX-License-Identifier
MIT

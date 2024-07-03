# **ETH Beginner - Metacrafter Course**
Welcome to the ETH Beginner project repository! This repository contains the assignments and challenges completed as part of the Metacrafter course, focusing on blockchain and smart contracts using the Ethereum platform. Here, you will find a collection of code and resources to help you understand and explore the fundamentals of blockchain technology and Ethereum development.

## **MyToken**
A simple ERC20-like token contract with basic mint and burn functionalities.

## **Description**
MyToken is a Solidity-based smart contract that implements a basic token with minting and burning capabilities. The contract maintains a public record of the token name, abbreviation, and total supply. It also includes a mapping to track the balances of different addresses. The mint function allows tokens to be created and added to a specified address, while the burn function allows tokens to be destroyed from a specified address, ensuring that the address has sufficient tokens to burn.

## Getting Started

## Installing
To get started with MyToken, you need to have a Solidity development environment set up. You can use tools like Remix, Truffle, or Hardhat. Here, we will use Remix for simplicity.
Open Remix.
Create a new file named MyToken.sol and paste the following code:

## Executing program
How to deploy and interact with the contract:

Compile the contract:
Click on the "Solidity Compiler" tab.
Ensure the compiler version is set to 0.8.26.
Click on the "Compile MyToken.sol" button.
Deploy the contract:

Click on the "Deploy & Run Transactions" tab.
Ensure the environment is set to "JavaScript VM".
Click on the "Deploy" button.

Interact with the deployed contract:
After deployment, you will see the deployed contract under "Deployed Contracts".
Expand the deployed contract to see available functions: tokenName, tokenAbbrv, totalSupply, balances, mint, and burn.

## Example Interactions:
Mint tokens:
Input the address (e.g., 0x...) and the value (e.g., 100) in the mint function and click "transact".
Check the balance using the balances function by inputting the same address.

Burn tokens:
Input the address (e.g., 0x...) and the value (e.g., 50) in the burn function and click "transact".
Check the balance again using the balances function.
Help

## Common issues and solutions:
Issue: Unable to mint tokens.
Solution: Ensure you are providing a valid address and a positive value for minting.
Issue: Unable to burn tokens.

## Resources
Here are some helpful resources to deepen your understanding of blockchain, Ethereum, and smart contracts:
Ethereum Documentation Solidity Documentation Ethereum Stack Exchange OpenZeppelin Contracts Web3.js Documentation Truffle Framework

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.


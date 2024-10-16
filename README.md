# Solidity-Project

This program is a simple token contract written in Solidity. It allows users to mint and burn tokens. The token is called "EXTRALIFE" with the abbreviation "XLF". It demonstrates basic concepts of token management, such as maintaining a balance for each user and adjusting the total supply.

## Description

The program is a Solidity smart contract that implements a token system with minting and burning functionality. The contract has public variables that store the token's name, abbreviation, and total supply. It also uses a mapping to keep track of balances associated with different addresses. Users can mint new tokens to increase their balance and the total supply, or burn tokens to reduce their balance and the total supply. The burn function includes a conditional to ensure users cannot burn more tokens than they own.

## Getting Started

### Installing

* To use this contract, you need a Solidity development environment such as [Remix](https://remix.ethereum.org/) or a local environment like [Hardhat](https://hardhat.org/) or [Truffle](https://trufflesuite.com/).
* Ensure that your development environment supports Solidity version 0.8.26.
* No modifications are needed for the contract file itself.

### Executing program

To deploy and interact with the contract, follow these steps:

1. Open the contract in your preferred Solidity IDE (e.g., Remix).
2. Compile the contract using Solidity version 0.8.26.
3. Deploy the contract on a local Ethereum network (e.g., using Remix's JavaScript VM) or an external testnet.
4. After deployment, you can call the `mint` and `burn` functions.

## Help

If you encounter issues with deploying or running the contract, ensure that:
* Your environment supports Solidity 0.8.26.
* The total supply and balances are correctly updated after minting or burning tokens.
* You are not attempting to burn more tokens than are available in the balance.

## Authors

ItsGreyToday

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

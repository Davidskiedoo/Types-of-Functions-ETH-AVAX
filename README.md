# Types-of-Functions-ETH-AVAX
Overview 
This is a simple ERC20 token smart contract called `MyToken` implemented in Solidity. The contract allows for minting, burning, and transferring tokens. It inherits from the OpenZeppelin ERC20 contract.

## Requirements
- Solidity compiler version 0.8.25
- OpenZeppelin contracts library

## Usage
To use this smart contract, follow these steps:
1. Deploy the `MyToken` contract, providing the desired name, symbol, and initial supply.
2. Use the `mint` function to mint tokens and distribute them.
3. Use the `burn` function to burn tokens.
4. Use the standard ERC20 `transfer` function to transfer tokens between addresses.

## Smart Contract Details 
- `MyToken`: The main contract implementing the ERC20 token functionality.
- `constructor`: Initializes the token with a name, symbol, and initial supply.
- `onlyOwner`: Modifier to restrict access to certain functions to only the contract owner.
- `mint`: Function to mint new tokens, accessible only by the contract owner.
- `burn`: Function to burn tokens.
- `transfer`: Overridden ERC20 function to transfer tokens between addresses.

## Authors
David Joshua B. Bucol

## License
This project is licensed under the MIT License - see the LICENSE.md file for details

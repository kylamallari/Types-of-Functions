# Types-of-Functions

NewToken is a simple ERC-20 token smart contract written in Solidity. It extends the OpenZeppelin ERC20 and Ownable contracts, providing basic functionalities for token creation, minting, transferring, and burning.

## Features

- ERC-20 compliant: Implements the ERC-20 standard for seamless integration with decentralized applications and exchanges.
- Minting: Only the contract owner can mint new tokens, ensuring controlled token supply.
- Ownership: The contract includes the Ownable functionality from OpenZeppelin, allowing easy management of ownership rights.

## Getting Started

### Usage

1. Deploy the contract:

   - Deploy the contract using Remix or your preferred development environment.
   - Set the initial supply during deployment.

2. Mint Tokens:

   - Call the `mintTokens` function to mint new tokens. Only the owner can perform this action.

3. Transfer Tokens:

   - Use the `transferTokensTo` function to transfer tokens to another address.


4. Burn Tokens:

   - Burn tokens with the `burnTokens` function.


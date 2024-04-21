
# ERC20 Token and Vault Solidity Smart Contracts

## Description:
This project contains Solidity smart contracts for an ERC20 token and a vault. These contracts are designed to be deployed on the Ethereum blockchain.

The ERC20 token contract implements the ERC20 standard, providing a fungible token with functionalities like transfer, approval, and allowance.

The vault contract acts as a secure storage solution for managing the tokens. It allows users to deposit and withdraw tokens, while ensuring the security and integrity of the stored assets.

## ERC20 Token Contract:
The ERC20 token contract implements the following standard functions:
- `totalSupply()`: Returns the total supply of tokens.
- `balanceOf(address account)`: Returns the token balance of a specified account.
- `transfer(address recipient, uint256 amount)`: Transfers tokens from the caller's account to the recipient.
- `approve(address spender, uint256 amount)`: Approves a spender to spend tokens on behalf of the caller.
- `allowance(address owner, address spender)`: Returns the amount of tokens approved for spending by a specific address.
- `transferFrom(address sender, address recipient, uint256 amount)`: Transfers tokens from one address to another, with approval.

## Vault Contract:
The vault contract implements the following functionalities:
- `deposit(uint256 amount)`: Allows users to deposit tokens into the vault.
- `withdraw(uint256 amount)`: Allows users to withdraw tokens from the vault.
- `getBalance()`: Returns the balance of tokens stored in the vault.

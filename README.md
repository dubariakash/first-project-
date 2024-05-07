
## Overview

This repository contains Solidity smart contracts for an ERC20 token and a vault to manage the tokens. ERC20 is a standard interface for fungible tokens on Ethereum, while the vault contract serves as a secure way to manage and control access to the tokens.

## Contracts

### ERC20Token.sol

This contract implements the ERC20 standard interface for a fungible token on the Ethereum blockchain. It includes functions to transfer tokens, approve spending limits, and check balances.

#### Functions:

- `transfer`: Transfer tokens from the caller's address to another address.
- `transferFrom`: Transfer tokens from one address to another, given approval.
- `approve`: Approve another address to spend tokens on behalf of the caller.
- `allowance`: Check the amount of tokens approved for a specific address to spend.
- `balanceOf`: Get the token balance of a specific address.

### Vault.sol

The Vault contract provides a secure way to manage ERC20 tokens. It allows depositing, withdrawing, and transferring tokens while enforcing access control rules.

#### Functions:

- `deposit`: Deposit tokens into the vault.
- `withdraw`: Withdraw tokens from the vault.
- `transfer`: Transfer tokens from the vault to another address.
- `setPermission`: Set permissions for specific addresses to deposit, withdraw, or transfer tokens.
- `hasPermission`: Check if an address has permission for specific actions.

## License

This project is licensed under the [MIT License](LICENSE).


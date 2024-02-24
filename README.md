**ERC20 Token and Vault Solidity Contracts**

Welcome to our repository housing Solidity contracts designed for ERC20 tokens and a vault system, meticulously crafted to facilitate secure deposits and withdrawals of tokens.

### Contracts Overview

1. **ERC20.sol**: This contract embodies the ERC20 token standard, offering core functionalities such as token transfers, approval mechanisms for designated spenders, and token minting/burning capabilities.

2. **Vault.sol**: Serving as a secure storage facility, the vault contract allows users to deposit ERC20 tokens, generating shares representing ownership. These shares can be redeemed for tokens upon withdrawal, ensuring an accurate representation of deposited assets.

### Deployment Guidelines

Deploying these contracts is a straightforward process:

1. Deploy ERC20.sol, providing essential parameters like token name, symbol, and initial supply.
2. Deploy Vault.sol, passing the address of the ERC20 token contract to its constructor.

### Utilization

Once deployed, users can interact with the contracts as follows:

- **ERC20 Token**: Facilitates token transfers, approvals, and token minting/burning.
- **Vault**: Enables secure deposits of tokens, issuing shares in return. Shares can be redeemed for tokens upon withdrawal, maintaining an accurate representation of deposited assets.

## Author

Kushal Manj

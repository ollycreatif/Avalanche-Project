# Solidity Token and Vault Contract

This project contains a basic implementation of an ERC20 token and a vault contract for handling token deposits and withdrawals.

## Description

This project includes two Solidity smart contracts:

1. **ERC20 Contract**: A standard implementation of an ERC20 token with minting and burning capabilities.
2. **Vault Contract**: A contract that interacts with the ERC20 token to facilitate deposits and withdrawals using a share-based mechanism.

The ERC20 contract allows for basic token operations including transfer, approval, minting, and burning. The Vault contract enables users to deposit tokens in exchange for shares and withdraw tokens by redeeming shares.

## Getting Started

### Installing

To use these contracts, you will need:

- A Solidity development environment such as [Remix IDE](https://remix.ethereum.org/) or [Truffle Suite](https://www.trufflesuite.com/truffle).
- An Ethereum wallet such as [MetaMask](https://metamask.io/) for deployment.

1. Copy the Solidity code for the `ERC20` contract and `Vault` contract into separate `.sol` files in your Solidity development environment.
2. Compile the contracts to ensure there are no syntax errors.

### Executing Program

To deploy and interact with these contracts:

1. **Deploy ERC20 Contract**:
    ```bash
    # In Remix IDE or Truffle, deploy the ERC20 contract
    ```

2. **Deploy Vault Contract**:
    - Provide the address of the deployed ERC20 contract when deploying the Vault contract.

3. **Interact with ERC20 Contract**:
    - Mint tokens using the `mint` function.
    - Transfer tokens using the `transfer` function.
    - Approve allowances and transfer tokens on behalf of others.

4. **Interact with Vault Contract**:
    - Deposit tokens to the vault using the `deposit` function.
    - Withdraw tokens from the vault using the `withdraw` function.

## Help

For common issues or problems:

- Ensure that the ERC20 token contract address is correctly provided when deploying the Vault contract.
- Check for sufficient token balance before attempting to deposit or withdraw.

If you encounter issues with compiling or deploying, consult the [Solidity documentation](https://docs.soliditylang.org/) or seek help on community forums such as [Ethereum Stack Exchange](https://ethereum.stackexchange.com/).

## Authors

- [Sheriff Oladimeji]  
  [@ollycreatif]

## License

This project is licensed under the [MIT License](LICENSE.md) - see the LICENSE.md file for details.

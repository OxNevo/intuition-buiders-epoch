
# TRUSTFI Token

**TRUSTFI (TFI)** is an ERC20 token deployed on the **Intuition Testnet**. This repository contains the full Solidity source code for the token, ready for deployment, verification, and further development.

## Deployed Contract

- **Intuition Testnet Address:** 0x529ee84055AD757e23786776A7f87f5F7EF673FA

## Token Details

- **Name:** TRUSTFI  
- **Symbol:** TFI  
- **Decimals:** 18  
- **Initial Supply:** 1,000,000 tokens  
- **Owner:** Deployer of the contract  
- **Network:** Intuition Testnet  

## Features

- Standard ERC20 functionality (transfer, approve, transferFrom, allowance)  
- Owner-only mint function to create additional tokens if needed  
- Fully flattened and verified-ready Solidity code  

## Contract Code

The contract code is contained in [`TRUSTFI.sol`](./contracts/TRUSTFI.sol). It includes:

- ERC20 implementation from OpenZeppelin  
- Ownable contract for ownership control  
- Context and IERC20 interface for compatibility  

## Deployment & Verification

- **Compiler Version:** 0.8.30  
- **Optimization:** OFF  
- **License:** MIT  
- **Verification:** Use Solidity Single File option on Intuition Testnet explorer  

## Usage

1. Import the token into MetaMask using the deployed contract address.  
2. Transfer tokens or interact with the contract using Remix or any Web3 interface.  
3. Use the `mint` function only if you are the owner to issue additional tokens.  

## License

This project is licensed under the **MIT License**. See the [LICENSE](./LICENSE) file for details.

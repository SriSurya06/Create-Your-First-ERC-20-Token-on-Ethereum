# Create-Your-First-ERC-20-Token-on-Ethereum
# MyToken (MTK)

## Overview
MyToken is a simple ERC-20 compatible token built on Ethereum for learning purposes.

## Token Details
- **Name**: MyToken
- **Symbol**: MTK
- **Decimals**: 18
- **Total Supply**: 1,000,000 MTK

## Features
- ✅ Standard ERC-20 implementation
- ✅ Transfer tokens between addresses
- ✅ Approve and transferFrom functionality
- ✅ Event emission for transparency
- ✅ Balance tracking

## How to Deploy
1. Open RemixIDE
2. Create new file `MyTask.sol`
3. Paste the contract code
4. Compile with Solidity 0.8.x
5. Deploy with desired total supply

## How to Use
### Check Balance
```solidity
balanceOf("0x5B38Da6a701c568545dCfcB03FcB875f56beddC4") → returns 999994000000000000000000

transfer("0xAb8483F64d9C6d1EcF9b849Ae677dD3315835cb2", 1000000000000000000) → returns true

approve("0xAb8483F64d9C6d1EcF9b849Ae677dD3315835cb2", 5000000000000000000) → returns true

transferFrom("0x5B38Da6a701c568545dCfcB03FcB875f56beddC4", "0x4B20993Bc481177ec7E8f571ceCaE8A9e22C02db", 5000000000000000000) → returns true


# Degen Gaming ERC-20 Token - DegenWiz

## Overview

Welcome to the Degen Gaming ERC-20 Token project, known as DegenWiz. This smart contract is built on the Ethereum blockchain and is designed to facilitate a gaming ecosystem where players can earn, transfer, redeem, and burn tokens. The project is named "Degen" with the symbol "DGN."

## Functionality

### Minting new tokens
- The platform allows the owner to mint new tokens, which can be distributed as rewards to players.

### Transferring tokens
- Players have the ability to transfer their tokens to other addresses within the network.

### Redeeming tokens
- Players can redeem their tokens for various in-game items available in the store.

### Checking token balance
- Players can check their token balance at any time to keep track of their rewards.

### Burning tokens
- Any token holder can burn their tokens if they are no longer needed.

### Reward Items
- The contract introduces a list of reward items, such as ARMOUR, InvisibleCloak, and MagmaWand, which players can gain by spending tokens.

### Token Details
- Token Name: Degen
- Token Symbol: DGN

## Smart Contract Details

### Contract Name
- DegenWizz

### Author
- whitewizardd

### Dependencies
- OpenZeppelin's ERC20 and Ownable contracts

### Functions

1. **Mint Degen Token**
   - `mintDegenToken(uint256 amount)`: Mint a specified amount of Degen tokens (onlyOwner).
   - `mintDegenToken(address[] memory players, uint256 amount)`: Mint tokens for multiple players (onlyOwner).

2. **Transfer Degen Token**
   - `transferDegenToken(address _to, uint256 _amount)`: Transfer Degen tokens to another address.

3. **Burn Degen Token**
   - `burnDegenToken(uint256 _amount)`: Burn a specified amount of Degen tokens.

4. **Check Token Balance**
   - `getDegenTokenToken()`: Get the Degen token balance of the caller.

5. **Reward Items**
   - `gainRewardItems(RewardItems item)`: Allow players to gain reward items by spending tokens.

6. **Withdraw Funds**
   - `withdrawFunds()`: Allow the owner to withdraw funds from the contract.

## Testing

To ensure the contract's functionality, follow these steps:

1. Mint tokens using `mintDegenToken` functions.
2. Transfer tokens using `transferDegenToken`.
3. Burn tokens using `burnDegenToken`.
4. Check token balance with `getDegenTokenToken`.
5. Redeem items with `gainRewardItems`.
6. Withdraw funds using `withdrawFunds`.

## Deployment

1. Deploy the contract to the Avalanche Fuji Testnet.
2. Verify the smart contract on Snowtrace.

## Usage

Integrate the Degen Gaming ERC-20 Token (DegenWiz) into your gaming ecosystem by interacting with the contract on the Avalanche network.

## Important Note

Ensure that you are the owner of the contract when minting tokens and withdrawing funds.

Thank you for choosing Degen Gaming ERC-20 Token for your gaming project! Feel free to reach out if you have any questions or need further assistance.# DegenToken

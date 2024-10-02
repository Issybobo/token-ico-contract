### IsraelToken and TokenICO Smart Contract
Overview
 This repository contains two smart contracts:

IsraelToken (ISL): An ERC-20 token built with OpenZeppelin.
 TokenICO: Manages the Initial Coin Offering (ICO) for IsraelToken.
IsraelToken Contract
Token Name: IsraelToken
 Symbol: ISL
 Initial Supply: 1 ISL token (minted to contract deployer)
The contract uses OpenZeppelin’s ERC-20 standard with basic functions like transfer, balanceOf, and approve.

 TokenICO Contract
Owner Functions:
 Update token address and sale price.
Withdraw tokens and transfer Ether.
 Public Functions:
 buyTokens: Users can purchase tokens by sending the appropriate amount of Ether.
 getTokenDetails: View token information.

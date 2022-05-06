# Uniswap

Uniswap is a low-cost [decentralized exchange](/concepts/decentralized-exchange.md) utilising an [Automated Market Maker](/concepts/automated-market-maker.md) to allow users to swap tokens based on the Ethereum chain without requiring a third-party.

## Chains

Uniswap is currently deployed to the following chains:

- Ethereum
- Optimism (July 2021)
- Arbitrum (August 2021)

## Versions

### Version 1

The first version was a proof-of-concept released in November 2018 and is now deprecated.

This version allowed only users to directly swap between ETH and ERC-20 pairs; a swap from one ERC-20 token to another one required the user to perform two swaps within the transaction - into, and then out of, ETH. This incurred extra gas fees, and the risk of slippage on both trades.

### Version 2

The second version was released in March 2020.

This introduced the ability to pool liquidity directly between two ERC-20 tokens, allowing for stablecoin pairs to be swapped with minimal slippage.

### Version 3

The third version was released in March 2021.

This version allows for concentrated liquidity to be deployed; with pool providers able to set the exact trade ranges they wish to operate in. This efficiently focuses the liquidity into specific price regions, greatly reducing slippage for swaps of stable pairs and allowing liquidity providers to claim a higher share of fees by maximising the depth of their deposits.

## Links

- <https://app.uniswap.org/#/swap>

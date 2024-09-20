# Uniswap Interface and Testing

This repository contains the interface for interacting with the Uniswap V2 Router and the tests that were conducted on it. The Uniswap V2 Router is a key component of the Uniswap decentralized exchange protocol, allowing users to swap tokens, add liquidity, and remove liquidity.

## Interface Methods

### `swapExactTokensForTokens`
This method allows users to swap an exact amount of input tokens for as many output tokens as possible, along a specified path.

### `swapTokensForExactTokens`
This method allows users to swap tokens such that the exact amount of output tokens is received, along a specified path.

### `swapTokensForExactETH`
This method allows users to swap tokens for an exact amount of ETH, along a specified path.

### `addLiquidity`
This method allows users to add liquidity to a pair of tokens.

### `removeLiquidity`
This method allows users to remove liquidity from a pair of tokens.

### `swapExactETHForTokens`
This method allows users to swap an exact amount of ETH for as many output tokens as possible, along a specified path.

## Testing

The following tests were conducted to ensure the functionality of the Uniswap V2 Router interface:

1. **Swap Exact Tokens For Tokens Test**
   - Verified that the correct amount of output tokens is received when swapping an exact amount of input tokens.

2. **Swap Tokens For Exact Tokens Test**
   - Verified that the correct amount of input tokens is used when swapping for an exact amount of output tokens.

3. **Swap Tokens For Exact ETH Test**
   - Verified that the correct amount of input tokens is used when swapping for an exact amount of ETH.

4. **Add Liquidity Test**
   - Verified that liquidity is correctly added to a pair of tokens.

5. **Remove Liquidity Test**
   - Verified that liquidity is correctly removed from a pair of tokens.

6. **Swap Exact ETH For Tokens Test**
   - Verified that the correct amount of output tokens is received when swapping an exact amount of ETH.

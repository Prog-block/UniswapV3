# UniswapV3

Uniswap is a decentralized exchange (DEX). And thus aims to be an alternative to centralised exchanges. It is based on various smart contracts, which enable the exchange of tokens. Currently there are 3 versions of Uniswap. This repo deals with the third version i.e UniswapV3.

### Code Comprehension: 

This project helped me to develop a deep understanding of this complex codebase by analyzing and comprehending it. This project also provided valuable insights into the inner workings of decentralized exchanges.

### New Features

- Concentrated liquidity: This feature allows liquidity providers (LPs) to specify price ranges for their funds to be used as liquidity. This means that instead of providing liquidity across the entire price spectrum (like in V2), LPs in V3 can ‘concentrate’ their liquidity at specific price points. This leads to optimized capital efficiency, potentially offering LPs higher returns.

- Flexible Fees: V3 introduced a flexible fee structure, where LPs can set their fees based on the perceived risk of the token pairs they provide liquidity for. Three fee tiers — 0.05%, 0.30%, and 1% — can be chosen based on expected pair volatility.

- Improved Price Oracle: V3 made further improvements to the price oracle introduced in V2, providing more accurate and granular data.


### Tooling:

Foundry is used to compile and test the contracts.

### Commands:

Contracts can be compiled with:
```bash
forge build
```

Tests can be deployed with:
```bash
forge test
```

Enjoy building✌️

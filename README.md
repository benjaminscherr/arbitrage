# Arbitrage

Develop a system to monitor transactions on EVM enabled blockchains (currently tested for Ethereum, Polygon, and Binance Smart Chain) to detect arbitrage opportunities, calculate profitability, and execute a flash loan to trade the price descrepency.

## Key Components

1) NodeJS listenting to detect transactions on trading pairs for AMM DEX's, and alert of a arbitrage opporunity that is profitable.
2) Solidity smart contracts, to call the flash loan, and execute the buy of a token on one exchange and sale of the token on a seperate exchange

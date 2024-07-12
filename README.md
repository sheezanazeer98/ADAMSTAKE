# ADAMSTAKE Solidity Smart Contract

This Solidity smart contract implements ADAMSTAKE, allowing users to stake tokens for defined periods to earn rewards. It includes features like multiple staking plans with varying APYs, unique staker tracking, and integrations with stake and reward tokens. The contract ensures secure arithmetic operations using the SafeMath library.

## Features

- Stake tokens with customizable plans and durations.
- Earn rewards based on Annual Percentage Yield (APY).
- Track individual staking records and total staked amounts.
- Owner-managed functions for token management and ownership transfer.

## Installation

```shell
npx hardhat compile
npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js --network localhost
```

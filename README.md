# AirSwap contracts

Solidity implementation of **peer-to-peer token swaps** on Ethereum: `Exchange` settlement and `AirSwapToken`.

Part of my blockchain portfolio — classic **atomic swap / P2P exchange** patterns with Truffle tooling and security review artifacts under `audits/`.

## Structure

- `contracts/Exchange.sol` — swap execution
- `contracts/AirSwapToken.sol` — token logic
- `test/` — exchange, expiration, and trade scenarios

## Requirements

- Node.js
- Truffle

## Test

```bash
truffle test
```

## References

Upstream lineage: [airswap/contracts](https://github.com/airswap/contracts)

**Maintainer:** [Muhammad Sibghat Ullah](https://github.com/SibghatUllah1997)

<!-- gully-header:start -->
<p align="center">
  <a href="https://gullychain.xyz">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset=".github/assets/gullychain-badge-dark.png">
      <img alt="Powered by GullyChain" src=".github/assets/gullychain-badge-light.png" width="360" height="96">
    </picture>
  </a>
</p>

<p align="center"><b>The social chain where your profile is your wallet. Arbitrum Orbit L3, testnet chain 485590.</b></p>

<p align="center">Liquidity mining contract for Gully Swap pools.</p>

<p align="center">
  <a href="https://gullychain.xyz"><img src="https://img.shields.io/badge/gullychain.xyz-01D9FA?style=for-the-badge&labelColor=000000&logo=googlechrome&logoColor=000000" alt="Website"></a>
  <a href="https://docs.gullychain.xyz"><img src="https://img.shields.io/badge/Docs-0A0F1A?style=for-the-badge&labelColor=000000&logo=readthedocs&logoColor=01D9FA" alt="Docs"></a>
  <a href="https://t.me/GullyChain"><img src="https://img.shields.io/badge/Telegram-0A0F1A?style=for-the-badge&labelColor=000000&logo=telegram&logoColor=26A5E4" alt="Telegram"></a>
  <a href="https://discord.com/invite/tY2ErsNNBp"><img src="https://img.shields.io/badge/Discord-0A0F1A?style=for-the-badge&labelColor=000000&logo=discord&logoColor=5865F2" alt="Discord"></a>
  <a href="https://x.com/Gully_Labs"><img src="https://img.shields.io/badge/@Gully__Labs-0A0F1A?style=for-the-badge&labelColor=000000&logo=x&logoColor=white" alt="X"></a>
</p>

<p align="center"><sub>A Gully Chain fork of <a href="https://github.com/Uniswap/v3-staker">Uniswap/v3-staker</a>, maintained by <a href="https://gullylabs.xyz">Gully Labs</a>. It is used under its GPL-3.0 licence; the upstream LICENSE, copyright and attribution notices are kept unchanged. The upstream README follows below as published. Not affiliated with or endorsed by Uniswap.</sub></p>

---
<!-- gully-header:end -->

# uniswap-v3-staker

This is the canonical staking contract designed for [Uniswap V3](https://github.com/Uniswap/uniswap-v3-core).

## Deployments

Note that the v1.0.0 release is susceptible to a [high-difficulty, never-exploited vulnerability](https://github.com/Uniswap/v3-staker/issues/219). For this reason, please use the v1.0.2 release, deployed and verified on Etherscan:

| Network          | Explorer                                                                                 |
| ---------------- | ---------------------------------------------------------------------------------------- |
| Mainnet          | <https://etherscan.io/address/0xe34139463bA50bD61336E0c446Bd8C0867c6fE65>                  |
| Arbitrum One     | <https://arbiscan.io/address/0xe34139463bA50bD61336E0c446Bd8C0867c6fE65>                   |
| Optimism         | <https://optimistic.etherscan.io/address/0xe34139463bA50bD61336E0c446Bd8C0867c6fE65>       |
| Base | <https://basescan.org/address/0x42be4d6527829fefa1493e1fb9f3676d2425c3c1> |

⚠️DEPRECATED⚠️: For historical verification purposes only, the staker at tag v1.0.0 was deployed at the address: `0x1f98407aaB862CdDeF78Ed252D6f557aA5b0f00d`

## Links

- [Contract Design](docs/Design.md)

## Development and Testing

```sh
yarn
yarn test
```

## Gas Snapshots

```sh
# if gas snapshots need to be updated
$ UPDATE_SNAPSHOT=1 yarn test
```

## Contract Sizing

```sh
yarn size-contracts
```


<!-- gully-footer:start -->
---

<p align="center">
  <a href="https://gullylabs.xyz">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset=".github/assets/powered-by-gully-labs-dark-2x.png">
      <img alt="Powered by Gully Labs" src=".github/assets/powered-by-gully-labs-light-2x.png" width="254" height="64">
    </picture>
  </a>
</p>
<!-- gully-footer:end -->

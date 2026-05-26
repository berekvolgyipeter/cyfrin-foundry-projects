# EVM smart-contract portfolio

Reference implementations of EVM patterns, built as project exercises from the Cyfrin Updraft [Foundry Fundamentals](https://updraft.cyfrin.io/courses/foundry) and [Advanced Foundry](https://updraft.cyfrin.io/courses/advanced-foundry) curricula (instructor: Patrick Collins). Where deployed, the contracts live only on public testnets (Sepolia / zkSync Sepolia) — built to learn, not for contest submissions.

## Contents

| Concept                       | Repo                                                                                                          | Notes                                                                              |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| ERC-4337 account abstraction  | [account-abstraction](https://github.com/berekvolgyipeter/cyfrin-advanced-foundry-account-abstraction)        | Minimal EVM smart wallet (alt-mempool AA) and a minimal zkSync wallet (native AA)  |
| CCIP cross-chain messaging    | [ccip-rebase-token](https://github.com/berekvolgyipeter/cyfrin-advanced-foundry-ccip-rebase-token)            | Cross-chain linear-interest rebase token                                           |
| Governor DAO                  | [dao](https://github.com/berekvolgyipeter/cyfrin-advanced-foundry-dao)                                        | Simple contract governed by an OpenZeppelin Governor DAO                           |
| ERC-20                        | [erc20](https://github.com/berekvolgyipeter/cyfrin-advanced-foundry-erc20)                                    | Manual ERC-20 implementation alongside an OpenZeppelin-based token                 |
| Merkle airdrop                | [merkle-airdrop](https://github.com/berekvolgyipeter/cyfrin-advanced-foundry-merkle-airdrop)                  | Airdrop contract gated by a Merkle proof and an EIP-712 signed claim               |
| ERC-721                       | [nft](https://github.com/berekvolgyipeter/cyfrin-advanced-foundry-nft)                                        | Basic NFT using IPFS metadata and a flippable on-chain SVG NFT                     |
| Chainlink VRF lottery         | [smart-contract-lottery](https://github.com/berekvolgyipeter/cyfrin-foundry-smart-contract-lottery)           | Provably-fair raffle using Chainlink VRF and Automation                            |
| USD-pegged stablecoin         | [defi-stablecoin](https://github.com/berekvolgyipeter/cyfrin-advanced-foundry-defi-stablecoin)                | Exogenously collateralized, algorithmically stabilized, USD-pegged stablecoin      |
| UUPS upgradeable proxy        | [uups](https://github.com/berekvolgyipeter/cyfrin-advanced-foundry-uups)                                      | Universal Upgradeable Proxy Standard pattern                                       |

Each sub-repo has its own Foundry setup and tests; most also include deployment scripts.

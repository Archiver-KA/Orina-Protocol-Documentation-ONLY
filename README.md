# Orina Protocol Public Documentation

![Orina Protocol public documentation cover](./assets/images/orina-banner-github.jpg)

Orina Protocol is a settlement layer for bilateral commerce. Its Atomic Transaction Protocol (ATP) helps two independent parties move a transaction through an explicit lifecycle and reach one final settlement outcome.

This public repository is intentionally outcome-focused. It describes what the protocol is meant to provide for users, integrators, grant reviewers, and ecosystem partners without publishing private implementation details, internal runbooks, source-level contract mechanics, formal artifacts, bytecode, or wallet automation design material.

## Overview Video

[![Orina Protocol Overview](https://img.youtube.com/vi/Ct0x9zTfylQ/hqdefault.jpg)](https://youtu.be/Ct0x9zTfylQ)

## Public Documentation Intent

This repository is the approved public reference set for Orina Protocol outcome documentation. It is suitable for:

- grant and ecosystem applications,
- public project review,
- partner intake,
- early integration orientation,
- high-level tokenomics review,
- selected testnet address verification.

It is not a source-code repository, deployment repository, audit report, or production approval package.

## Why Orina Exists

Digital commerce still depends on trusted intermediaries. Whether parties are exchanging assets, paying for services, purchasing goods, or coordinating automated systems, settlement often depends on centralized platforms, escrow providers, or manual dispute resolution.

These approaches increase cost, reduce transparency, and create single points of failure. Orina replaces trust with deterministic settlement rules executed directly by protocol.

## What Orina Does

Orina standardizes the settlement path for bilateral transactions:

- Agreement: both parties accept programmable settlement conditions before execution.
- Asset commitment: the transaction value or deliverable is committed to the flow.
- Condition verification: agreed conditions, deadlines, and dispute paths are evaluated.
- Deterministic settlement: the transaction reaches exactly one canonical final outcome.

## Core Principles

- Deterministic Settlement: every transaction reaches exactly one final state.
- Trust-Minimized: neither party needs to trust the other.
- Programmable Conditions: settlement logic is defined before execution.
- Composable: marketplaces, wallets, AI systems, and enterprise applications can integrate Orina.
- Permissionless: anyone can build on the protocol.

## Where Orina Can Be Used

| Area | Examples |
| --- | --- |
| Commerce | Goods, service payments, procurement, cross-border transactions |
| Financial | OTC trading, escrow, asset exchange |
| AI Economy | AI agent commerce, autonomous payments, machine-to-machine settlement |
| Assets | Digital assets, physical assets, tokenized assets |

## What Orina Is Not

Orina is not a marketplace, escrow provider, or payment gateway. It is a settlement protocol that marketplaces, AI agents, wallets, and commerce platforms can integrate as infrastructure.

## Documentation

| Topic | Link |
| --- | --- |
| Project profile | [docs/project-profile.md](./docs/project-profile.md) |
| Protocol outcomes | [docs/protocol-outcomes.md](./docs/protocol-outcomes.md) |
| Public use cases | [docs/use-cases.md](./docs/use-cases.md) |
| ORI tokenomics | [docs/tokenomics.md](./docs/tokenomics.md) |
| Hybrid DAO | [docs/hybrid-dao.md](./docs/hybrid-dao.md) |
| Public testnet addresses | [docs/testnet-addresses.md](./docs/testnet-addresses.md) |
| Security and readiness | [docs/security-and-readiness.md](./docs/security-and-readiness.md) |
| Formal and audit status | [docs/formal-and-audit-status.md](./docs/formal-and-audit-status.md) |
| Public disclosure boundary | [docs/public-disclosure-boundary.md](./docs/public-disclosure-boundary.md) |
| Official links | [docs/official-links.md](./docs/official-links.md) |
| Grant summary | [docs/grant-summary.md](./docs/grant-summary.md) |

## Public ATP Testnet Addresses

| Network | Chain ID | Primary ATP contract |
| --- | ---: | --- |
| <img src="./assets/network-logos/bnb.png" width="20" alt="BNB Chain" /> BSC Testnet | `97` | `0x18E1C8ab257FAf16Ec8257A9715d07661194150B` |
| <img src="./assets/network-logos/base.png" width="20" alt="Base" /> Base Sepolia | `84532` | `0x6d132Ba2327573c4e6f97a2167dCddb8059C4d14` |
| <img src="./assets/network-logos/arbitrum.png" width="20" alt="Arbitrum" /> Arbitrum Sepolia | `421614` | `0x5863f25A8250EBe20Bd1E3d04FD796081Fc3D72E` |
| <img src="./assets/network-logos/ethereum.png" width="20" alt="Ethereum" /> Ethereum Sepolia | `11155111` | `0x6d132Ba2327573c4e6f97a2167dCddb8059C4d14` |
| <img src="./assets/network-logos/optimism.svg" width="20" alt="Optimism" /> Optimism Sepolia | `11155420` | `0x6d132Ba2327573c4e6f97a2167dCddb8059C4d14` |
| <img src="./assets/network-logos/avalanche.png" width="20" alt="Avalanche" /> Avalanche Fuji | `43113` | `0x6d132Ba2327573c4e6f97a2167dCddb8059C4d14` |
| <img src="./assets/network-logos/worldchain.svg" width="20" alt="World Chain" /> World Chain Sepolia | `4801` | `0x6d132Ba2327573c4e6f97a2167dCddb8059C4d14` |

Only these primary ATP addresses are published in this repository. Additional deployment details remain outside the public documentation boundary unless separately approved by the project owner.

## Official Links

| Resource | Link |
| --- | --- |
| Website | https://www.orina.io/ |
| Runtime app | https://app.orina.io/ |
| Whitepaper | https://whitepaper.orina.io/ |
| X / Twitter | https://x.com/Orina_official |
| Discord | https://discord.gg/vythc6X9qF |
| Telegram | https://t.me/orinaofficial |
| Public docs | https://github.com/Archiver-KA/Orina-Protocol-Documentation-ONLY |

## License

This repository is published under a read-only documentation license. You may view and reference the material, but you may not modify, redistribute, republish, sublicense, or create derivative works from it without written permission. See [LICENSE.md](./LICENSE.md).

## Production Status

The listed deployments are testnet evidence only. Mainnet deployment requires final production controls, governance review, independent security review, and owner approval.

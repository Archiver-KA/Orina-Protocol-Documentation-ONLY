# Hybrid DAO

---
date: 2026-07-02
status: Public fee-governance summary
---

This page summarizes the intended Hybrid DAO fee-governance model for Orina Protocol. It is a public economics and governance reference, not a legal opinion, investment recommendation, or production activation notice.

This page is adapted from the earlier Orina DAO fee-governance draft and keeps the same public boundary: settlement correctness remains separate from fee economics, while U.S. securities-law wording is handled conservatively.

## Model Summary

The Hybrid DAO model separates settlement correctness from fee economics.

ATP remains the authority for transaction lifecycle, escrow outcome, release, refund, dispute boundary, and final settlement record. DAO governance applies around the protocol fee layer after a transaction reaches the completed settlement path.

## Hybrid DAO Model

Orina uses a Hybrid DAO structure:

- Protocol contracts enforce deterministic ATP settlement.
- Fee policy is governed as an economic layer around completed transactions.
- DAO-facing allocation may fund published ecosystem programs where objective eligibility, timing, claim, exclusion, and jurisdiction rules have been approved.
- Platform retained protocol fees remain available for protocol development, infrastructure, operations, security, integrations, and reserves.

The DAO should not be described as a discretionary settlement authority. It does not override user escrow, reverse finalized transactions, or decide individual dispute outcomes unless a future public contract scope explicitly grants a narrow role.

## Public Design Principles

| Principle | Public meaning |
| --- | --- |
| Settlement first | DAO governance does not redefine ATP finality or alter active transaction outcomes. |
| Bounded fee governance | Governance applies to fee policy and ecosystem allocation, not private transaction custody. |
| Transparent allocation | DAO-facing allocation should be observable, program-specific, and rule-based before activation. |
| Prospective changes | Fee policy changes should apply prospectively unless a published contract and disclosure framework says otherwise. |
| Legal boundary | DAO allocation is not equity, dividend, revenue share, passive yield, or ownership in Orina. |

## Completed Transaction Fee Schedule

The intended completed-transaction fee schedule is:

| Payment rail | Completed transaction fee | Basis points |
| --- | ---: | ---: |
| ORI | 1% | 100 bps |
| USDT | 2% | 200 bps |
| USDC | 2% | 200 bps |
| Supported stablecoins | 2% | 200 bps |

The lower ORI fee path is intended to align ORI utility with protocol usage. Stablecoin rails use the higher fee path. Testnet and beta references are not production fee guarantees.

## Protocol Fee Allocation

The public target model splits completed-transaction protocol fees equally:

| Allocation | Share of protocol fee | Public purpose |
| --- | ---: | --- |
| Platform retained protocol fee | 50% | Protocol development, infrastructure, operations, security, integrations, and reserves. |
| DAO ecosystem allocation | 50% | Governance-scoped ecosystem programs, usage incentives, transparency tooling, grants, or other approved ORI-aligned initiatives. |

This allocation is a policy target for fee economics. DAO-facing activation requires published rules for eligibility, timing, claim mechanics, exclusions, jurisdictional limits, and any applicable vesting or lockup conditions. It should not be described as a dividend, revenue share, passive yield, equity interest, or ownership claim in Orina or any operating entity.

## U.S. Securities-Law Boundary

DAO allocation language should be drafted conservatively because U.S. securities analysis may consider whether a crypto-asset transaction includes an investment contract or another securities interest.

The public reference set for this boundary includes:

| Reference | Public relevance |
| --- | --- |
| [Securities Act of 1933, Section 2(a)(1), 15 U.S.C. 77b(a)(1)](https://www.law.cornell.edu/uscode/text/15/77b) | Defines "security" under the Securities Act, including investment contracts. |
| [Securities Exchange Act of 1934, Section 3(a)(10), 15 U.S.C. 78c(a)(10)](https://www.law.cornell.edu/uscode/text/15/78c) | Defines "security" under the Exchange Act. |
| [SEC v. W.J. Howey Co., 328 U.S. 293 (1946)](https://www.govinfo.gov/app/details/USREPORTS-328/USREPORTS-328-293) | Investment-contract analysis reference commonly used in U.S. securities-law review. |
| [SEC DAO Report of Investigation, Release No. 81207, July 25, 2017](https://www.sec.gov/files/litigation/investreport/34-81207.pdf) | SEC report addressing DAO token analysis under federal securities laws. |
| [SEC Release No. 33-11412 / 34-105020, effective March 23, 2026](https://www.sec.gov/rules-regulations/2026/03/s7-2026-09) | SEC interpretation regarding certain crypto assets and transactions involving crypto assets. |
| [CFTC Press Release 9198-26](https://www.cftc.gov/PressRoom/PressReleases/9198-26) | CFTC statement joining the SEC interpretation and describing CFTC administration of the CEA consistent with that interpretation. |

For Orina public materials:

- ORI should be described as a protocol coordination and utility token, not as stock, equity, a profit right, or an ownership interest.
- DAO allocation should be described as a governance-scoped ecosystem allocation, not an automatic holder dividend or revenue-share entitlement.
- Any program funded from the DAO allocation must publish objective participation rules before activation and must avoid promising profit from the managerial or entrepreneurial efforts of others.
- Public materials should avoid suggesting that holding ORI alone gives a claim on platform income, assets, treasury property, or legal ownership.
- Any token sale, DAO-funded program, jurisdiction-specific offer, or secondary-market communication requires separate legal review before publication or activation.
- Nothing in this page is legal advice, a registration analysis, or a conclusion that any token sale, DAO program, or secondary-market transaction is outside securities laws.

## Example Fee Outcomes

| Gross transaction | Payment rail | Protocol fee | Platform 50% | DAO allocation 50% | Seller net before other costs |
| ---: | --- | ---: | ---: | ---: | ---: |
| 10,000 ORI | ORI | 100 ORI | 50 ORI | 50 ORI | 9,900 ORI |
| 10,000 USDT | USDT | 200 USDT | 100 USDT | 100 USDT | 9,800 USDT |
| 10,000 USDC | USDC | 200 USDC | 100 USDC | 100 USDC | 9,800 USDC |

These examples illustrate protocol fee economics only. They do not include gas costs, third-party payment costs, exchange-rate effects, taxes, off-chain service charges, or jurisdiction-specific withholding rules.

## Governance Scope

DAO fee governance may cover:

- DAO fee recipient or ecosystem allocation routing where governance-controlled routing is activated,
- supported fee rails and fee parameter updates within approved constraints,
- ORI holder allocation policy where a published program activates it,
- treasury reporting and fee transparency dashboards,
- incentive programs tied to verified protocol usage,
- ecosystem grants and transparency tooling,
- published ORI-aligned initiatives with objective eligibility rules.

Governance actions should be observable, versioned, and applied prospectively. Fee changes should not be represented as retroactive changes to already-finalized transaction economics unless the relevant contract and disclosure framework explicitly support that behavior.

## Boundary Conditions

- DAO governance does not custody per-transaction escrow while a transaction is active.
- DAO governance does not redefine ATP finality.
- DAO governance does not replace the protocol settlement layer.
- DAO allocation does not imply equity, dividends, revenue-share entitlement, shareholder rights, creditor rights, or legal ownership of the platform.
- Any DAO-funded program must define eligibility, timing, exclusions, and claim mechanics before launch.

The purpose of the Hybrid DAO model is to preserve ATP as deterministic settlement infrastructure while allowing governance to direct a bounded ecosystem allocation around completed-transaction fees.

## Public Wording Guide

Use:

- "Hybrid DAO fee-governance model"
- "DAO ecosystem allocation"
- "completed-transaction protocol fee"
- "governance-scoped ecosystem programs"
- "settlement correctness remains with ATP"
- "objective eligibility and claim rules required before activation"

Avoid:

- "dividend"
- "revenue share entitlement"
- "equity"
- "ownership interest"
- "profit right"
- "passive yield"
- "guaranteed return"
- "DAO controls user escrow"
- "DAO can reverse finalized transactions"

# Hybrid DAO

---
date: 2026-07-02
status: Public fee-governance summary
---

This page summarizes the intended Hybrid DAO fee-governance model for Orina Protocol. It is a public economics and governance reference, not a legal opinion, investment recommendation, or production activation notice.

## Model Summary

The Hybrid DAO model separates settlement correctness from fee economics.

ATP remains the authority for transaction lifecycle, escrow outcome, release, refund, dispute boundary, and final settlement record. DAO governance applies around the protocol fee layer after a transaction reaches the completed settlement path.

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

DAO-facing programs require published rules before activation, including eligibility, timing, claim mechanics, exclusions, jurisdiction limits, and any applicable lockup or vesting conditions.

## Example Fee Outcomes

| Gross transaction | Payment rail | Protocol fee | Platform 50% | DAO allocation 50% | Seller net before other costs |
| ---: | --- | ---: | ---: | ---: | ---: |
| 10,000 ORI | ORI | 100 ORI | 50 ORI | 50 ORI | 9,900 ORI |
| 10,000 USDT | USDT | 200 USDT | 100 USDT | 100 USDT | 9,800 USDT |
| 10,000 USDC | USDC | 200 USDC | 100 USDC | 100 USDC | 9,800 USDC |

These examples illustrate protocol fee economics only. They do not include gas costs, third-party payment costs, exchange-rate effects, taxes, off-chain service charges, or jurisdiction-specific withholding rules.

## Governance Scope

Hybrid DAO governance may cover:

- supported fee rails and fee parameter updates within approved constraints,
- DAO ecosystem allocation policy,
- treasury reporting and fee transparency dashboards,
- ecosystem grants and usage incentive programs,
- published ORI-aligned initiatives tied to verified protocol usage.

Governance should not be described as a discretionary settlement authority. It does not override user escrow, reverse finalized transactions, or decide individual dispute outcomes unless a future public contract scope explicitly introduces that power.

## Public Wording Guide

Use:

- "Hybrid DAO fee-governance model"
- "DAO ecosystem allocation"
- "completed-transaction protocol fee"
- "governance-scoped ecosystem programs"
- "settlement correctness remains with ATP"

Avoid:

- "dividend"
- "revenue share entitlement"
- "equity"
- "passive yield"
- "guaranteed return"
- "DAO controls user escrow"
- "DAO can reverse finalized transactions"

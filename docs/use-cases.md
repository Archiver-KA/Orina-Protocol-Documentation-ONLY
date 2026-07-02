# Public Use Cases

---
date: 2026-07-02
status: Public outcome use-case reference
---

Orina Protocol is intended to serve applications that need reliable settlement outcomes for transactions involving two independent parties.

## Marketplace Settlement

Marketplaces can use ATP as a common transaction finality layer while keeping their own listing, discovery, reputation, messaging, and fulfillment systems.

Public outcome:

- funds are associated with a specific transaction,
- the transaction follows a defined state path,
- timeout and dispute boundaries are explicit,
- the final result is release or refund.

## Digital Goods and Services

Applications that sell digital goods, services, access rights, or deliverable work can use the protocol to separate commercial settlement from platform-specific business logic.

Public outcome:

- buyer and seller expectations are represented by protocol states,
- settlement does not rely only on informal platform policy,
- the application can present a consistent transaction record to both parties.

## Partner Applications

Wallets, dashboards, commerce frontends, and ecosystem tools can integrate around selected public ATP deployments to present transaction status, public settlement evidence, and completion outcomes.

Public outcome:

- third-party applications can observe a common settlement lifecycle,
- user experience can vary without changing the protocol outcome,
- integrations can be evaluated against selected testnet addresses.

## Automation-Ready Commerce

Software-assisted commerce interfaces can build around ATP outcomes while keeping private automation design outside public documentation.

Public outcome:

- authorization remains bounded by user intent and protocol policy,
- settlement authority remains with ATP,
- automation-facing applications can target clear release, refund, timeout, and dispute outcomes.

## Ecosystem and Grant Fit

For ecosystems and grant programs, Orina is positioned as shared settlement infrastructure rather than a single isolated marketplace. Funding or partner support can help move the protocol from public testnet evidence toward network-specific integration, independent review, documentation maturity, and production readiness.

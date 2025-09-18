# Zimbabwe Digital Dollar (ZDD)

![Zimbabwe Flag](https://upload.wikimedia.org/wikipedia/commons/6/6a/Flag_of_Zimbabwe.svg)

## Overview
The **Zimbabwe Digital Dollar (ZDD)** is a USD-pegged stablecoin initiative designed to provide a secure, transparent, and programmable form of digital currency for Zimbabwe. The project leverages blockchain technology to create a **Zimbabwean Stablecoin dollar–backed digital currency** that ensures compliance with international standards (ERC-3643) while supporting financial inclusion, cross-border trade, and monetary stability.

This repository hosts:
- Smart contract drafts
- Research documents
- Regulatory and economic analyses
- Security and contribution policies

---

## Disclaimer
The Zimbabwe Digital Dollar (ZDD) is **not affiliated with, endorsed, or sanctioned by the Reserve Bank of Zimbabwe (RBZ) or the Government of Zimbabwe**. ZDD is an independently developed digital currency initiative. Users should conduct their own due diligence and comply with local laws and regulations before interacting with or using ZDD.

---

## Executive Summary
The Zimbabwe Digital Dollar (ZDD) is a USD-pegged stablecoin designed to provide a secure, transparent, and programmable digital currency for Zimbabwean citizens, businesses, and government institutions. ZDD addresses Zimbabwe’s historical monetary instability by offering a fully USD-backed stablecoin that can be used for everyday transactions, payroll, government disbursements, cross-border remittances, and enterprise treasury operations. Its programmable architecture supports smart contract functionality, enabling automated payments and transparent financial workflows.

### Key Features

| Feature | Description |
|---------|-------------|
| USD Peg | 1:1 USD peg with fully verified reserves |
| KYC/AML | Tiered KYC/AML compliance for enhanced regulatory adherence |
| Smart Contract | Enterprise-grade architecture with multisig governance and timelocked upgrades |
| Transparency | Proof-of-reserve oracles and on-chain audit trails |
| Scalability | Gas-optimized and designed for high-volume usage |

ZDD aims to empower Zimbabwe’s digital economy, reduce reliance on informal financial systems, and provide a globally recognized, stable, and programmable digital currency platform.

---

## Repository Contents
- `README.md` → Project overview and guidance
- `ZDD_SMART_CONTRACT_SHORT.md` → Draft short version of ZDD smart contract
- `ZIMBABWE_ANALYSIS.md` → In-depth economic and regulatory analysis
- `CONTRIBUTION.md` → Contribution and community policy
- `SECURITY.md` → Security reporting policy
- `CHANGELOG.md` → Placeholder for future version tracking

---

## Features
- **Stable Value**: Pegged to USD and backed by verified reserves
- **Compliance Ready**: Built on ERC-3643 with identity and transfer restrictions
- **Transparency**: On-chain proof-of-reserves verification
- **Cross-Border Utility**: Usable for remittances and trade across SADC and beyond
- **Programmable Finance**: Smart contracts support payments, subscriptions, and automated workflows
- **Tiered KYC**: Mini-KYC for wallets above $500, full KYC for higher tiers
- **Governance**: Timelocked contract upgrades, multisig administrative control
- **Scalable**: Gas-optimized for high-volume transactions
- **Auditability**: Full on-chain history for regulators and auditors

---

## Getting Started

### Prerequisites
- Node.js v18+
- Hardhat 2.26+
- Ethers.js 6.x
- Solidity 0.8.20

### Setup
    git clone https://github.com/<your-org>/zdd.git
    cd zdd
    npm install

### Compile Contracts
    npx hardhat compile

### Run Tests
    npx hardhat test

---

## Contribution Policy
This is a **stablecoin project**. For regulatory, compliance, and governance reasons, this repository does **not accept direct contributions** from the public.

### What You Can Do
- Report **documentation errors** or clarity issues
- Suggest **research materials** relevant to Zimbabwe’s economy and regulation
- Provide **non-technical feedback** on adoption and use cases

### What You Cannot Do
- Submit code pull requests
- Modify or extend the smart contracts
- Change compliance logic or deployment structure

### Maintainers
- **Simon Kapenda** — Creator of ZDD, Namibia Digital Dollar (NADD), Angola Digital Kwanza (AOAk), and CillarCoin (https://cillar.io)
- **Abba Platforms Inc** — Responsible for maintenance and ongoing support

---

## Security Policy

### Reporting a Vulnerability
If you discover a security vulnerability in the ZDD smart contracts or supporting code, please report it responsibly:

- **Do NOT open a public GitHub issue** for security vulnerabilities
- Contact the core team at: [security@zddollar.io]
- Include a detailed description and steps to reproduce the issue

### Scope
- Smart contracts (`ZDD.sol` and related contracts)
- Supporting libraries in this repository
- Off-chain compliance and governance logic documented here

### Response
- Aim to respond to security reports within **72 hours**
- Valid reports will be acknowledged and investigated immediately
- Fixes will be prioritized and disclosed responsibly

### Responsible Disclosure
Avoid exploiting vulnerabilities or sharing them publicly until patches are released

---

## License
This project is licensed under the **MIT License**. See the LICENSE file for details

---

# Changelog
This file is a **placeholder for future change tracking**. Updates, new features, and version history will be documented here as the project evolves.

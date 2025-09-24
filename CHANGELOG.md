# Changelog

All notable changes to the Zimbabwe Digital Dollar (ZDD) project will be documented in this file. The format follows [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [v1.1.1] - 2025-09-24
### README Refinement Update

**README.md**
- Fixed raw markdown formatting issue before the "Compile Contracts" section to ensure consistent preview rendering.
- Ensured README stays in pure raw markdown format without switching to preview mid-document.
- Deep-checked and preserved all existing content without truncation.
- Maintained original structure and wording while adding formatting improvements.

---

## [v1.1.0] - 2025-09-24
### Deployment & Documentation Update

**Deployment**
- Successfully deployed the Zimbabwe Digital Dollar (ZDD) smart contract on the Binance Smart Chain (BSC) Testnet.
- Added deployed contract addresses:
  - Proxy Contract: `0x93b2eFFC896fC3f3789c493972fe585A2C02B108`
  - Implementation Contract: `0x0197c9e1ed52dd74d9d3978A9dbe98408a59266f`
- Verified implementation contract on BSC Testnet Explorer: [View on BSCScan](https://testnet.bscscan.com/address/0x0197c9e1ed52dd74d9d3978A9dbe98408a59266f#code)
- Linked proxy to implementation for upgradeable contract architecture.

**Documentation**
- Updated **README.md** to include deployment details, contract addresses, and BSC Testnet explorer links.
- Added license badges for improved professionalism and clarity.
- Preserved all existing README content to maintain documentation continuity.

**Maintenance**
- Added deployment verification steps to project documentation for transparency.
- Ensured changelog follows [Keep a Changelog](https://keepachangelog.com/en/1.0.0/) format.

---

## [v1.0.0] - 2025-09-18
### Initial Release

**Repository Setup and Documentation**
- Created full project structure for ZDD repository
- Added **README.md**:
  - Project overview and vision
  - Executive Summary with key features
  - Stablecoin technical architecture overview
  - Disclaimer clarifying ZDD is independent and not affiliated with the Reserve Bank of Zimbabwe
  - Instructions for setup, compilation, and running tests
  - Repository contents overview

**Legal and Licensing**
- Added **LICENSE.md** using MIT License
- Added **CONTRIBUTION.md**:
  - Clarifies no public contributions to smart contracts
  - Provides guidance for non-technical feedback
  - Includes **security@zddollar.io** as official contact for reporting errors or concerns
- Added **SECURITY.md**:
  - Responsible vulnerability reporting procedures
  - Scope of coverage (smart contracts, libraries, governance logic)
  - Response and disclosure guidelines
  - Contact email: **security@zddollar.io**

**Research and Analysis**
- Added **ZIMBABWE_ANALYSIS.md**:
  - Comprehensive country analysis (population, economy, currency usage, remittance flows)
  - Opportunity for ZDD adoption in domestic and cross-border trade
  - Historical monetary instability and market gap analysis

**Smart Contract**
- Added **ZDD_SMART_CONTRACT_SHORT.md**:
  - Draft of ZDD smart contract
  - ERC-3643 compliant, USD-pegged stablecoin architecture
  - Tiered KYC/AML logic and proof-of-reserves
  - Placeholder for enterprise-grade governance features

**Formatting and Standards**
- All files generated in **pure raw Markdown** for easy GitHub copy-paste
- Tables, code blocks, and examples fully preserved
- Ensured no truncation or condensation of content
- Indented code blocks for commands and scripts to maintain Markdown integrity

**Future placeholders**
- **CHANGELOG.md** initialized for tracking future versions
- Smart contract, governance, and feature updates to be documented here

---

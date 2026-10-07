<div align="center">

#  Web3 Security Research & Audit Portfolio

*Independent Smart Contract Vulnerability Analysis, DeFi Threat Modeling, & Foundry Exploit PoCs*

[![Solidity](https://img.shields.io/badge/Solidity-%23363636.svg?style=for-the-badge&logo=solidity&logoColor=white)](https://soliditylang.org/)
[![Foundry](https://img.shields.io/badge/Foundry-FF4F00?style=for-the-badge&logo=foundry&logoColor=white)](https://book.getfoundry.sh/)
[![Security](https://img.shields.io/badge/Focus-Smart%20Contract%20Auditing-blue?style=for-the-badge)](https://github.com/)

</div>

---

##  About This Repository
Welcome to my centralized hub for smart contract security research. This repository archives independent case studies, deep-dive vulnerability analyses, and isolated Proof-of-Concepts (PoCs) built using **Foundry**. 

All write-ups are carefully structured to showcase threat modeling, root-cause identification, and robust remediation strategies for EVM-based protocols.

---

##  Vulnerability Index & Write-ups

| # | Vulnerability Title | Vector / Category | Impact Level | Target Component | Write-up Link |
|:-:|:---|:---|:---|:---|:---|
| **01** | **Analyzing Stale Oracle Vulnerabilities** | Oracle Logic & Price Feeds | <kbd>High / Medium</kbd> | Yield-Bearing Vaults | [View Report](./reports/stale-oracle.md) |
| **02** | *Coming Soon...* | - | - | - | - |

---

##  Security Toolkit & Methodology
* **Foundry (Forge & Cast):** Local fork testing, state fuzzing, and deterministic exploit simulation.
* **Static & Dynamic Analysis:** Deep review of `latestRoundData()`, low-level calls, access control, and trust boundaries.
* **Remediation Engineering:** Designing strict defensive layers (e.g., `MAX_DELAY` thresholds, slippage protection, and circuit breakers).

---

##  Connect & Collaborate
Interested in security research, smart contract auditing, or protocol reviews? Let's connect!
* **GitHub:** [@agunggrh](https://github.com/agunggrh)
* **Platform:** HackerOne / Independent Researcher

---
<div align="center">
  <i>"Securing the decentralized future, one block at a time."</i>
</div>

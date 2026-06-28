# 0xBerberSec

Smart Contract Security Researcher focused on DeFi, cross-chain messaging, invariant analysis, and proof-of-concept development.

I review Solidity/EVM, Rust/Soroban, and DeFi protocol logic with a focus on state-machine correctness, lifecycle invariants, configuration safety, liquidation flows, and runtime execution guarantees.

## Highlights

- 1 validated Code4rena Low finding
- Validated finding: LayerZero Stellar Endpoint, runtime DVN budget mismatch
- QA research: Jupiter Lend branch lifecycle invariant weakness
- PoC-driven methodology using Foundry, Rust/Soroban tests, fork testing, and manual code review

## Validated Findings

| Protocol | Contest | Severity | Finding | Link |
| --- | --- | --- | --- | --- |
| LayerZero | Stellar Endpoint | Low, validated | ULN302 accepts DVN configurations valid during validation but non-executable at runtime under Soroban budget limits | [S-1284](https://code4rena.com/audits/2026-04-layerzero-stellar-endpoint/submissions/S-1284) |

## Security Research

| Protocol | Type | Status | Link |
| --- | --- | --- | --- |
| Jupiter Lend | Code4rena QA Report | Public QA Research | [S-757](https://code4rena.com/audits/2026-02-jupiter-lend/submissions/S-757) |

## Research Portfolio

- [LayerZero Stellar Endpoint - Runtime DVN budget mismatch](https://github.com/0xBerberSec/smart-contract-security-audits/tree/main/audits/layerzero-stellar-endpoint)
- [Jupiter Lend - QA Research](https://github.com/0xBerberSec/smart-contract-security-audits/tree/main/audits/jupiter-lend-qa)

## Expertise

- DeFi lending and liquidation flows
- Cross-chain messaging and endpoint configuration
- Protocol invariants and state-machine safety
- Runtime validation mismatch analysis
- Proof-of-concept development
- Fork-based and unit-test validation
- Manual line-by-line review

## Technologies

- Solidity / EVM
- Rust / Soroban
- Foundry
- Hardhat
- Code4rena competitive audits
- Fork testing and transaction trace analysis

## Contact

- GitHub: [0xBerberSec](https://github.com/0xBerberSec)
- Code4rena: [0xBerberSec](https://code4rena.com/@0xBerberSec)

## Current Focus

Building a public audit portfolio with validated findings, QA reports, and reproducible PoCs. All public claims in this profile are kept factual and verifiable.

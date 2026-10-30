# 0xBerberSec

**Independent Smart Contract Security Researcher**

**Injective Peggy Bridge — 1 Medium finding validated by Code4rena · 21st place in the competition.**
[Official profile](https://code4rena.com/@0xBerberSec) · [Competition results](https://code4rena.com/audits/2026-02-injective-peggy-bridge)

I focus on DeFi accounting, authorization boundaries and state transitions: how assets move, which assumptions protect them, and where those assumptions can fail.

### How I audit

**Value Flow → Security Invariants → Targeted Tests → Counter-Tests → Economic Impact Qualification**

I map contracts, dependencies and trusted actors before tracing the paths that move value. I turn protocol assumptions into measurable invariants, build focused experiments and compare suspicious behavior with control cases. An apparent gain needs an explanation of who funds it, who can obtain it and under which conditions.

Audit-OS is my research workspace for protocol maps, hypotheses, tests, traces and conclusions. I use scripts and Codex to assist analysis and test construction; generated output requires verification against source code and execution evidence.

### Technical focus

- Vault, LP and reward accounting; shares, balance deltas and epoch snapshots.
- Authorization, signed policies and contract state transitions.
- Foundry and Hardhat testing, local fork simulations and trace analysis.
- Targeted research with Rust/Soroban, Solana/Anchor and Cairo tooling.

### Reproduce the method

The [audit portfolio](https://github.com/0xBerberSec/smart-contract-security-audits) includes an original, deliberately vulnerable refund-escrow lab: source, Foundry tests, counter-tests, correction, regression checks and actual local execution records. It demonstrates a known vulnerability class on a teaching contract, separately from my Code4rena result and private protocol research.

### Work and evidence

Start with the [audit portfolio](https://github.com/0xBerberSec/smart-contract-security-audits): the verified competition record, audit methodology, testing practices and disclosure-safe investigation overviews. Independent research is distinguished from platform validation. Technical material is shared only when disclosure rights are established.

**Available for paid, scoped private audit collaborations and technical evaluations.**

Contact: [GitHub](https://github.com/0xBerberSec) · [Code4rena](https://code4rena.com/@0xBerberSec)

# QCoin – NovaCoin Cross-Repository Integration

This document outlines the strategic and technical connection between the two repositories:

- **qcoin** repo: Rune economy, Wizard Q, NovaRune, creative/ritual layer
- **novacoin** repo: Base settlement layer, genesis blockchain, staking, gas

## Key Integration Points

1. **NovaRune Bridge** (see docs/novarune-bridge.md)
2. **Shared Nexus Orchestration** — Single live Nexus instance coordinates both layers
3. **Agent Economy** — AI swarms earn and spend across both systems
4. **Prototype Funding** — NovaCoin for base milestones, runes for specific utilities
5. **Governance** — Potential future unified or bridged governance

## Recommended Workflow
- Keep rune-specific logic in qcoin repo
- Keep base chain logic in novacoin repo
- Use this novacoin repo for cross-layer design docs
- Nexus acts as the glue and real-time coordinator

This dual-repo structure allows clean separation while maintaining tight integration through Nexus and the bridge.
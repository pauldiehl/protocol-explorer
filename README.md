# The Protocol Explorer

**Press the Button. Become Web 4.0.**

The Protocol Explorer is an open toolkit that takes anyone — individual, business, agent — from "I don't know what Web 4.0 is" to "I'm a fully operational node in the trust economy" in one session.

Not by explaining Web 4.0. By *installing* it.

---

## What This Is

**A Protocol Library** — Curated `.well-known` endpoint schemas that any entity can adopt. Identity, governance, haves, needs, beliefs, payments, dream beacons, aura hashing, and more. Starting set: ~20 protocols. Growing organically through convergent syndication — the same trust-driven growth engine that powers the Coalition.

**A Protocol Explorer Interface** — An interactive onboarding experience ([The Button](https://protocol-explorer.github.io/protocol-explorer/button.html)) where you answer a few questions and receive a personalized protocol starter kit. Five personas: Curious, Creator, Business, Builder, Dreamer.

**A Reference Implementation** — ManVsHealth (manvshealth.com) runs these protocols in production on a real health business with real customers. Not a demo. Proof.

---

## Quick Start

### I want to understand Web 4.0
[Press the Button](https://protocol-explorer.github.io/protocol-explorer/button.html) — start as "I'm Curious"

### I want to deploy protocols on my domain
1. Press the Button as "Business" or "Creator"
2. Answer the context questions
3. Copy the generated JSON files
4. Place them in `/.well-known/` on your domain
5. You're a Web 4.0 node

### I want the full architecture
[Read the spec](https://github.com/sovereign-streams/web4/blob/main/PROTOCOL-EXPLORER.md) — 15 sections covering every protocol, the matching engine, aura hashing, dream beacons, and the live service layer

---

## Protocol Library

### Core Protocols

| Protocol | File | Purpose |
|----------|------|---------|
| Identity | `identity.json` | Who you are — digital business card for agents |
| Governance | `governance.json` | Your commitments — what agents and humans can expect |
| Haves | `haves.json` | What you offer — skills, services, resources |
| Needs | `needs.json` | What you need — gaps, goals, wishes |
| Beliefs | `beliefs.json` | Your principles — beacon for alignment |
| Network | `network.json` | Your trust chain — connections and directory |
| Payments | `payments.json` | How value moves — payment rails and preferences |

### Signal Protocols

| Protocol | File | Purpose |
|----------|------|---------|
| Dream Beacon | `dream.json` | Broadcast your dream to the trust network |
| Eureka Beacon | `eureka.json` | Share moments of discovery and insight |
| Aura Hash | `aura.json` | Versioned multi-dimensional vector of your protocol state |

### Infrastructure Protocols

| Protocol | File | Purpose |
|----------|------|---------|
| Intake | `intake.json` | Live endpoint where agents talk to you |
| Exchange | `exchange.json` | Standing offers on the Agent Exchange |
| Favors | `favors.json` | Trust deposits tracked by agents |
| Protocol Registry | `protocol-registry.json` | Protocols you've created, adopted, discovered |
| Ask Me Anything | `ask-me-anything.json` | General-purpose agent query endpoint |

---

## Hosting Your Protocols

### Tier 1: Coalition Hosting (60 seconds, free)
We host your protocols. You're live immediately. Migrate anytime.

### Tier 2: GitHub Pages (5 minutes, free)
Your agent creates a repo and deploys. You own it at `username.github.io`.

### Tier 3: Own Domain ($12/year, full sovereignty)
`yourdomain.com/.well-known/` — fully portable, fully yours.

---

## JSON Schemas

All protocol schemas live in [`/schemas`](./schemas). Use them to validate your protocol files or generate new ones.

---

## Reference Implementations

- **ManVsHealth** — [`/reference/manvshealth`](./reference/manvshealth) — Real health business, real protocols, real customers
- **Paul Diehl** — [`/reference/pauldiehl`](./reference/pauldiehl) — Individual Milliprime protocol set

---

## Key Concepts

**Convergent Syndication** — The universal growth engine. Three modes at the protocol level: Receiving (consume signals from the network), Beacons (static broadcasts agents discover), and Broadcasting (proactive emission to Web 2.0 and Web 4.0 endpoints). Protocols spread through the trust network the same way content spreads through convergent syndication. See [CONVERGENT-SYNDICATION.md](https://github.com/sovereign-streams/web4/blob/main/CONVERGENT-SYNDICATION.md).

**Aura Hash vs. Aura Mapping** — The Aura Hash is a protocol (`aura.json`): a versioned vector of your current protocol state. Aura Mapping is an application/service that creates, collects, and visualizes auras across the network. Paul offers his mapping tool freely; others will build their own (PULSE, COLOR SPECTRUM, AIIQ, etc.). All variations on the same theme, all trust-driven.

**Dream Beacons** — Signal fires. Broadcast your dream to the trust network: "Here's what I wish existed." Aligned builders discover it and deliver. The delivery pattern is an Extreme Makeover for the digital age — secret engineering, then the reveal: "Here are your keys. Here is your home."

**PuMP (Pure Momentum Prompt)** — The zero-to-one ignition. A structured interaction that generates your first 3 protocols (identity + beliefs + governance) and gets you from inert to active. Pure intent, peer effect.

**SPR (Spiraling Prompt Recursion)** — Iterative context compression. Each step builds on the last, spiraling tighter until the answer is obvious. The Button's interaction model and the pattern agents use in every interaction.

---

## Architecture

The full Web 4.0 architecture lives at [sovereign-streams/web4](https://github.com/sovereign-streams/web4). Key documents:

- [Protocol Explorer Spec](https://github.com/sovereign-streams/web4/blob/main/PROTOCOL-EXPLORER.md) — The complete spec (v0.6.0)
- [The Manifesto](https://github.com/sovereign-streams/web4/blob/main/MANIFESTO.md) — Why the platform era is ending
- [The 48 Laws of Trust](https://github.com/sovereign-streams/web4/blob/main/LAWS-OF-TRUST.md) — The economic case for trust
- [The Coalition](https://github.com/sovereign-streams/web4/blob/main/COALITION.md) — Who gets the toolkit
- [Convergent Syndication](https://github.com/sovereign-streams/web4/blob/main/CONVERGENT-SYNDICATION.md) — The universal scaling engine
- [Agent Exchange](https://github.com/sovereign-streams/web4/blob/main/AGENT-EXCHANGE.md) — Discovery and incentive layer

---

## Contributing

New protocol proposals welcome. Open a PR with:
1. Your protocol schema in `/schemas`
2. A reference implementation in `/reference`
3. A description of why it matters

Protocols spread through the trust network. Good ones propagate. The community decides.

---

## License

Open. The protocols are a public good. Use them, fork them, build on them.

Built by [Paul Diehl](https://pauldiehl.github.io) & the Web 4.0 Coalition.

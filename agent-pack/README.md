# Offer Revenue Sprint Agent Pack

This folder contains reusable agent definitions that pair with the `$offer-revenue-sprint` Codex skill.

## Agents

- `orchestrator.md`: routes work and assembles the final report
- `scout.md`: ICP analyst
- `hook.md`: messaging strategist
- `funnel.md`: conversion auditor
- `proof.md`: trust builder
- `offer.md`: packaging strategist
- `email.md`: lifecycle writer
- `ads.md`: creative strategist
- `closer.md`: sales enablement lead

## How To Use In Codex

Use the skill first, then name the agents you want:

```text
Use $offer-revenue-sprint. Use Scout, Hook, Funnel, and Proof to tear down this landing page.
```

For a full workflow:

```text
Use $offer-revenue-sprint. Run the Orchestrator and all specialist agents on this offer. Return the final revenue sprint report.
```

These are agent definitions, not autonomous background workers by themselves. In Codex, they provide clear specialist instructions that the skill can use during a single session or during explicit sub-agent delegation.

# Offer Revenue Sprint

A reusable Codex skill and agent bundle that audits offers, landing pages, sales pages, emails, ads, and funnels, then turns the diagnosis into a practical revenue sprint.

## Who It Helps

- Founders trying to improve conversion
- Agencies doing client teardowns
- Coaches and consultants packaging offers
- SaaS teams sharpening positioning
- Local businesses improving website leads
- Marketers building campaigns, emails, and ad angles

## What It Does

This skill routes marketing and revenue work to eight specialist roles:

- **Scout**: ICP and buyer psychology analyst
- **Hook**: positioning and messaging strategist
- **Funnel**: landing page and conversion auditor
- **Proof**: trust, proof, and risk-reversal builder
- **Offer**: packaging, pricing, and offer-stack strategist
- **Email**: lifecycle and follow-up writer
- **Ads**: creative and angle strategist
- **Closer**: objection handling and CTA optimizer

## What's Included

- Codex skill: `SKILL.md`
- Agent pack: `agent-pack/`
- Role playbooks and scoring references: `references/`
- Reusable output templates: `assets/templates/`
- Social launch card: `assets/social-card.svg`
- LinkedIn launch post: `LAUNCH_POST.md`

## Installation

Copy this folder into your Codex skills directory:

```bash
~/.codex/skills/offer-revenue-sprint
```

Restart Codex or refresh your session so the skill metadata is reloaded.

## Usage

Audit a landing page:

```text
Use $offer-revenue-sprint to tear down this landing page and give me the top 10 revenue fixes.
```

Rewrite an offer:

```text
Use $offer-revenue-sprint. Act as Scout, Hook, and Offer. Rework this offer for B2B founders.
```

Run the full agent bundle:

```text
Use $offer-revenue-sprint. Run the Orchestrator and all specialist agents on this landing page. Return the final revenue sprint report.
```

Use selected agents:

```text
Use $offer-revenue-sprint. Use Scout, Hook, Funnel, and Proof to tear down this page and give me the highest-impact fixes.
```

## Included Agents

- `agent-pack/orchestrator.md`
- `agent-pack/scout.md`
- `agent-pack/hook.md`
- `agent-pack/funnel.md`
- `agent-pack/proof.md`
- `agent-pack/offer.md`
- `agent-pack/email.md`
- `agent-pack/ads.md`
- `agent-pack/closer.md`

## Notes

This skill is designed for practical marketing work. It does not invent metrics, make false claims, or recommend deceptive scarcity. Use real customer data, analytics, and proof whenever possible.

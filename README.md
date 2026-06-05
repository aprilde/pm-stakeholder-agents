# PM Stakeholder Agents

A collection of Claude Code subagents for product managers. Each agent pressure-tests a PM artifact — PRD, roadmap, feature brief, decision doc, or stakeholder update — through the lens of a specific non-technical stakeholder.

Built for PMs who want to stress-test their work before walking into the room.

---

## How it works

1. **Bring an artifact** — paste it, upload it, or point to a file path
2. **Choose a stakeholder lens** — the agent speaks as that stakeholder
3. **Get feedback in character** — objections, questions, and gaps surfaced from their point of view
4. **Revise if needed** — the agent rewrites the artifact in clean PM language

---

## Agents

| Agent | Vertical | Stakeholders covered |
|-------|----------|----------------------|
| [B2B SaaS](./agents/b2b-saas.md) | B2B SaaS | Sales, Customer Success, RevOps, PMM, Growth, CEO, CFO, Legal, Support, Pre-Sales, Enterprise Buyers |
| [Marketplace](./agents/marketplace.md) | Marketplace | Seller/Supplier Success, Supply Ops, Buyer Experience, Growth/Acquisition, Trust & Safety, Legal, Sales/Partnerships, CFO, CEO |
| [Growth / PLG](./agents/growth-plg.md) | Product-Led Growth | *(coming soon)* |
| [Enterprise / B2B2C](./agents/enterprise-b2b2c.md) | Enterprise & B2B2C | *(coming soon)* |
| [Platform / API](./agents/platform-api.md) | Platform & API Products | *(coming soon)* |
| [Developer Tools](./agents/developer-tools.md) | Dev Tools & DevEx | *(coming soon)* |
| [Fintech](./agents/fintech.md) | Fintech & Payments | *(coming soon)* |
| [E-commerce](./agents/ecommerce.md) | E-commerce & Retail | *(coming soon)* |
| [Media / Content](./agents/media-content.md) | Media & Streaming | *(coming soon)* |
| [HealthTech](./agents/healthtech.md) | Healthcare & HealthTech | *(coming soon)* |
| [Hardware / IoT](./agents/hardware-iot.md) | Hardware & IoT | *(coming soon)* |
| [AgeTech / Wearables](./agents/agetech-wearables.md) | AgeTech & Health Wearables | *(coming soon)* |

---

## Usage

### In Claude Code

Point Claude Code to any agent file:

```
Use the agent at ./agents/b2b-saas.md to review my PRD
```

Or reference it in your `CLAUDE.md` to make it available as a persistent team member.

### Inputs accepted

- **Paste** — copy your artifact directly into the chat
- **Upload** — attach a file
- **File path** — reference a file in your repo (e.g. `./docs/feature-brief.md`)

---

## Compatible with

Claude Code · Cursor · OpenCode · Gemini CLI · GitHub Copilot

---

*Built by [April DeZen](https://github.com/aprilde)*

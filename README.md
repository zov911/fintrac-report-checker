# FINTRAC Report Checker: "Do I need to report this?"

**Live demo:** https://zov911.github.io/fintrac-report-checker/

A free, instant checker for Canadian reporting entities. Answer six questions about a cash, crypto or wire transaction and see which FINTRAC reports are required, plus the exact filing deadline on a calendar.

## What it covers

| Report | Trigger | Deadline |
|---|---|---|
| Large Cash Transaction Report (LCTR) | ≥ $10,000 cash received, incl. the 24-hour rule | 15 calendar days |
| Large Virtual Currency Transaction Report (LVCTR) | ≥ $10,000 in crypto received | 5 working days |
| Electronic Funds Transfer Report (EFTR) | International EFT ≥ $10,000 (FEs, MSBs, casinos) | 5 working days |
| Casino Disbursement Report (CDR) | Casino payout ≥ $10,000 | 15 calendar days |
| Suspicious Transaction Report (STR) | Suspected ML, TF or sanctions evasion, at any amount | As soon as practicable |
| Listed Person or Entity Property Report | Property linked to a listed person or group | Immediately |

The checker also handles the 24-hour aggregation rule, exemptions for financial-entity and public-body clients, the crypto travel rule (≥ $1,000), overdue warnings, and the 2024–2025 reporting-entity expansions (mortgage sector, real estate developers, and the new MSB categories).

## Why it exists

Compliance questions like "do I need to report this?" are high-intent searches. A tool that answers them instantly builds trust and generates qualified leads for AML consultancies, RegTech vendors and compliance software.

## Tech

A single `index.html`: vanilla JS, automatic light/dark mode, accessible form controls, and no dependencies.

> Educational tool, not legal advice. Not affiliated with FINTRAC. Always confirm with [FINTRAC's official guidance](https://fintrac-canafe.canada.ca/).

**Related:** [FINTRAC Fines Calculator](https://zov911.github.io/fintrac-fines-calculator/)

---

## Want a tool like this for your business?

I build compliance checkers, calculators and lead-gen tools for RegTech and professional-services firms.

**Reach out → [zov911.com](https://zov911.com)**

© zov911. All rights reserved.

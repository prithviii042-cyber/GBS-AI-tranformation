# Interactive Proposal — AI-Enabled Enterprise Transformation (RCPL RFP TR/2026/002)

A single, self-contained **interactive HTML proposal** responding to Reliance Consumer
Products Limited's RFP for a 12–15 month integrated AI-enabled enterprise transformation.

## View it

Open **`index.html`** in any modern browser. No build step, no dependencies, no internet —
everything (CSS, JavaScript, data) is embedded in the one file. **Everything is in this
one file.**

## What's interactive

| Section | Interaction |
|---|---|
| **Top nav** | Sticky, smooth-scroll, active-section highlight, scroll progress bar, mobile menu |
| **Operating Model** | Click the 5 archetype tiles (A4 System-Governed is the target, with its lever config); click the agency ladder L1→L5; hover the readiness→workstream linkage |
| **Delivery Plan** | Click any of the 4 phases to expand a Part A / Part B / governance detail panel (each tagged with its agency level) |
| **Principles** | Click any of the 8 principle cards to expand |
| **Mobilisation** | Step through the 90-day plan (3 stages) |
| **Scope of Work** | Tab between **Part A** (A1–A11) and **Part B** (B1–B11) workstreams |
| **AI Factory** | Click the 8-stage pipeline; filter the 100+ use-case explorer by domain (live count) |
| **Capability Transfer** | 4 KT gates with an animated progress bar; 4 governance guardrails |
| **Scorecard** | Technical evaluation criteria mapped to sections with weight bars |
| Throughout | Scroll-reveal animations, hover cards; print-friendly (expands all tabs/panels) |

## Structure (maps to RFP Volume 1)

1. Executive Summary · 2. **Strategic Foundation** (operating model → System-Governed
archetype, agency ladder, readiness linkage) · 3. Engagement Model (single firm, Part A +
Part B, one PMO) · 4. Integrated Delivery Plan + Principles + Mobilisation · 5. Scope of
Work (Part A / Part B tabs) · 6. The AI Factory (pipeline + explorer) · 7. Team · 8. Case
Studies · 9. Capability Transfer + Guardrails + Governance · 10. Technical Evaluation Map

## The strategic spine

The proposal is anchored on the **EY / FP&A Trends 2026** operating-model framework,
targeting the **A4 System-Governed ("system-driven") archetype** — governed autonomy under
strong governance. The whole 12–15 month programme is framed as the journey up the
**agency ladder** (L1 human-initiated → L5 governed autonomy), built on **six readiness
dimensions**. See `DELIVERY-APPROACH.md` §0 for the full write-up.

## Companion documents

- `DELIVERY-APPROACH.md` — the detailed delivery methodology (feeds the Volume 1 sections)
- `APPROACH-NOTE.md` — the internal bid-preparation strategy

## ⚠ Placeholders to complete before submission

Replace before submitting — search the file for `NOVARETH` and `placeholder`:
- **Firm name** — currently `NOVARETH Advisory` (nav, footer)
- **Team CVs** — named Partner, Engagement Director, Part A / Part B / workstream leads
- **Case studies** — 3 real recent Indian FMCG references with actual metrics
- **Any quoted metric** — savings %, case-study timelines, use-case value sizing

## Editing / adding content

The page is data-driven where it counts — edit these JS arrays near the bottom of `index.html`:
- `ARCH` — the five operating-model archetypes
- `AGENCY` — the five agency-ladder levels
- `WAVES` — the four delivery phases (Part A / Part B / governance items + agency tag)
- `PRI` — the eight operating principles
- `STEPS` — the 90-day mobilisation stages
- `USECASES` — the AI use cases (`{dom, t, d, type}`)
- `PIPE` — the AI-factory pipeline stages · `GATES` / `GUARDS` — transfer gates & guardrails
- Everything else is plain HTML sections you can edit directly.

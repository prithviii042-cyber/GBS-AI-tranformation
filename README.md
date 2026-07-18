# Interactive Proposal — AI-Enabled Enterprise Transformation (RCPL RFP TR/2026/002)

An interactive, single-file HTML proposal responding to Reliance Consumer Products Limited's
RFP for a 12–15 month integrated AI-enabled enterprise transformation.

## View it

Open `index.html` in any modern browser. No build step, no dependencies — everything
(CSS, JavaScript, data) is embedded in the one file.

## What's interactive

| Section | Interaction |
|---|---|
| **Top nav** | Sticky, smooth-scroll, active-section highlight, scroll progress bar, mobile menu |
| **Delivery Plan** | Click any of the 4 phases to expand a detail panel (process / digital / governance columns) |
| **Scope of Work** | Tab between **Part A** (A1–A11) and **Part B** (B1–B11) workstreams |
| **AI Factory** | Filter the 100+ use-case pipeline by domain; live count updates |
| **Scorecard** | Technical evaluation criteria mapped to proposal sections with weight bars |
| Throughout | Scroll-reveal animations, hover cards; print-friendly (expands all tabs/panels) |

## Structure (maps to RFP Volume 1)

1. Executive Summary · 2. Engagement Model (single firm, Part A + Part B, one PMO) ·
3. Integrated Delivery Plan (4 phases) · 4. Scope of Work (Part A / Part B tabs) ·
5. The AI Factory · 6. Team Composition · 7. Case Studies · 8. Capability Transfer ·
9. Technical Evaluation Map

## ⚠ Placeholders to complete before submission

The following are **placeholder content** and must be replaced by the bidding firm with real data:

- **Firm name** — currently `NOVARETH Advisory` (nav, footer)
- **Team CVs** — named Partner, Engagement Director, and Part A / Part B / workstream leads
- **Case studies** — 3 real recent Indian FMCG references with actual metrics
- **Any quoted metric** (savings %, timelines in case studies, use-case value sizing)

Search the file for `NOVARETH` and `placeholder` to find the spots.

## Adding more screenshots / content

The proposal is data-driven where it counts:
- Timeline phases live in the `PHASES` array (JS, near the bottom of `index.html`)
- Use cases live in the `USECASES` array — add objects with `{dom, t, d, type}`
- Everything else is plain HTML sections you can edit directly.

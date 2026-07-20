# Project Context & Handoff — EY Proposal for RCPL

> Single-source context dump. Upload this anywhere (new chat, another tool) to continue
> the work without re-deriving history. Last updated by the working session that built the
> interactive proposal.

---

## 1. What this is

An **interactive HTML proposal** — a single self-contained file — that **EY** is submitting
in response to a **Reliance Consumer Products Limited (RCPL)** RFP for an **AI-Enabled SSC
Transformation**. It is the visual/interactive companion to the formal Volume 1 (Technical)
submission.

- **Client:** Reliance Consumer Products Limited (RCPL) — USD 2.5 Bn+ Indian FMCG enterprise, 5 BUs (Beverages is the anchor BU).
- **Bidder:** EY (single integrated partner).
- **RFP ref:** TR/2026/002.
- **Engagement:** 12–15 month integrated transformation, single consulting partner, two streams under one PMO.
- **Deliverable in this repo:** `index.html` (everything is in this one file).

---

## 2. The RFP in brief

- **Two streams (single firm):**
  - **Stream 1 / Part A — Process, Org, SSC & Change** (scope items A1–A11): SSC design across 10 towers, ~85 process re-designs to L5, org design, change, SOX-equivalent audit readiness.
  - **Stream 2 / Part B — Digital, Data & AI** (scope items B1–B11): enterprise architecture, ERP modernisation (S/4HANA-class), data lakehouse (Databricks-class), AI/GenAI/agentic factory (100+ use cases), automation, cybersecurity, DPDP Act 2023. **Part B Phase 1 (Digital Design, M0–6) is mandatory; Phase 2 execution PM is optional.**
- **Four phases (overlapping waves):**
  1. **Foundation & Design** — M0–M3
  2. **Lighthouse + Build Wave 1** — M2–M6
  3. **Transform + Scale Wave 2** — M5–M12
  4. **Complete + Stabilise** — M9–M15
- **10 SSC towers:** F&A, HR, Procurement, Supply Chain Planning, Transportation/Logistics (TMS), Order Management, Pricing, Master Data Management, Analytics, IT Service Desk.
- **Volume 1 submission requirements (the section structure the client wants — page limits exist in the RFP but are NOT shown in our proposal):**
  1. Executive Summary
  2. Integrated Delivery Plan (timeline, waves, dependencies, risk, governance)
  3. Stream 1 Approach (SSC design, process re-engineering, org design, change)
  4. Stream 2 Approach (AI/GenAI roadmap & factory, data lakehouse, ERP, automation)
  5. Team Composition (named CVs — Partner, Engagement Director, Stream Leads)
  6. Case Studies (min 3 — recent Indian FMCG, integrated, <18 months)
  7. Capability Transfer Plan (KT milestones, mixed-team model, exit readiness)
- **Technical evaluation weights (60% of total):** Integrated capability 25% · 12–15 month delivery plan 20% · AI/automation depth 15% · Team strength 15% · Reference quality 15% · Methodology/tools 10%.

---

## 3. The strategic spine (our differentiated POV)

**Operating-model anchor — EY / FP&A Trends Group, *FP&A Operating Model Trends Research 2026*.**
We apply its design logic enterprise-wide across the SSC scope. The framework has four building blocks:
five **design levers** → one of five **archetypes** → six **readiness dimensions** → a five-level **agency ladder**.

- **Target archetype: A4 — System-Governed Design** ("system-driven"): governed autonomy, where systems initiate work at scale under strong governance. It is the only archetype reaching full autonomy — matching RCPL's 100+ agentic-AI ambition. Its prescribed path ("phased deployment starting with lower-risk, high-volume processes") **is** the RFP's Lighthouse-then-Transform wave strategy.
- **A4 lever configuration:** Role & Mandate = L5 Value Architect · Placement = System-led · Scope = Decision-System Design · Process standardisation = System-led/continuous · Sourcing = Platform/managed services.
- **Six readiness dimensions** (built first, before autonomy scales): Data Quality · Technology Enablement · Process Discipline · Governance & Decision Rights · Roles & Skills · Cultural Readiness. Each maps to specific A/B workstreams (the "linkage" interactive).
- **Agency ladder — IMPORTANT REFRAME:** RCPL already has a capable-but-fragmented tech stack, so Level 1 is **not** "zero".
  - **L1 Fragmented (as-is)** — capable systems, but siloed and manual-heavy (today).
  - **L2 Structured & modernised** — SSC designed, processes standardised, tech stack modernised/integrated, data foundation laid (Foundation + Lighthouse, M0–6). *This is why Foundation is front-loaded.*
  - **L3 System-assisted** — copilots/analytics; first 15–20 AI live (Build Wave 1, M2–6).
  - **L4 Supervised autonomy** — agentic within guardrails, human oversight (Transform Wave 2, M5–12).
  - **L5 Governed autonomy** — autonomous at scale under governance (Complete, M9–15).
- **Four autonomy guardrails** (mandatory beyond L3): Reversibility · Anomaly alerts · Independent checks · Named override.
- **Transform in Flight** — Lighthouse lifts simple/high-volume processes to prove the SSC + lock savings; Transform waves move redesigned+automated processes once (no double-move, no "lift junk then fix junk").
- **Eight delivery principles:** design-first/build-parallel · readiness-before-autonomy · one integrated design authority · Transform-in-Flight · fusion pods (40% RCPL FTE) · thin-slice to production early · governed velocity · exit-ready by design.

---

## 4. Repository & Git

- **Repo:** `prithviii042-cyber/gbs-ai-tranformation`
- **Working branch:** `claude/interactive-html-proposal-rfp-ysf607`
- **Base branch:** `main` (created as an empty root; the repo started empty)
- **Open PR:** #1 (`claude/interactive-html-proposal-rfp-ysf607` → `main`)
- **Note:** GitHub's default branch may still be the feature branch (artifact of first push to an empty repo) — can be switched to `main` in repo Settings.

### Files
| File | Purpose |
|---|---|
| **`index.html`** | The complete single-file interactive proposal (all 7 Volume-1 sections + appendix). This is the deliverable. |
| `DELIVERY-APPROACH.md` | Detailed delivery methodology (§0 operating model, waves, workstream methods, AI factory, governance, risks) — feeds the written Volume 1. |
| `APPROACH-NOTE.md` | Internal bid-preparation strategy (win themes, response plan, roles, schedule, risks). |
| `README.md` | How to view/edit the proposal; the JS data arrays; placeholders. |
| `HANDOFF.md` | This file. |

---

## 5. `index.html` — structure & interactivity

Single self-contained file (inline CSS + JS, no dependencies, no network). Sections map 1:1 to the RFP Volume 1 requirements.

| Section (id) | Content | Interactive elements |
|---|---|---|
| Hero | EY brand, "AI-Enabled SSC Transformation", contents grid | — |
| §1 Executive Summary (`#s1`) | Integrated capability · 12–15 month confidence · FMCG India credentials | — |
| §2 Integrated Delivery Plan (`#s2`) | Operating model, agency ladder, **timeline**, dependencies, principles, mobilisation, risk table, governance, guardrails | **Archetype chooser** (5 tiles, A4 target), **agency ladder** (L1–L5), **Gantt timeline** (Stream 1 & 2 swimlanes, phase-coloured bars, click for activities, ◆ sync points, dependency cards), **readiness linkage** (hover), **principles** (expand), **mobilisation** stepper |
| §3 Stream 1 Approach (`#s3`) | POV-led SSC content | 5 **design POVs** + 6-D disposition strip, **10-tower deep-dive** (click a tower → FTE share, automation %, SSC/retained split, KPIs, wave), benchmarks, 5 anti-patterns, collapsible A1–A11 scope |
| §4 Stream 2 Approach (`#s4`) | POV-led digital content | 5 **architecture POVs**, **7-layer reference architecture** (click a layer), **RPA/ML/GenAI/Agentic pattern selector**, **AI factory** pipeline + **use-case explorer** (filter), value chains, collapsible B1–B11 scope |
| §5 Team Composition (`#s5`) | Named leaders (Partner, Eng Director, Stream Leads, etc.) | — |
| §6 Case Studies (`#s6`) | 3 FMCG India references | — |
| §7 Capability Transfer (`#s7`) | 4 KT gates + mixed-team + exit readiness | gate cards + progress bar |
| Appendix (`#appendix`) | Evaluation-criteria → section map | — |

### JS data arrays (edit these to change content — near the bottom of `index.html`)
- `ARCH` — 5 operating-model archetypes (A4 is `target:true`).
- `AGENCY` — 5 agency-ladder levels (reframed; L1 = fragmented as-is).
- `LINK_SRC` / `LINK_DST` — readiness dimensions → workstream build blocks.
- `PH`, `GANTT` (`.s1` / `.s2` bars with `act[]`), `SYNCS`, `DEPS` — the timeline (Gantt bars, sync points, dependencies). Bar month math: `grid-column: (start+2) / (end+2)` over a 15-month grid.
- `PRI` — 8 delivery principles.
- `STEPS` — 90-day mobilisation (3 stages).
- `TOWERS` — 10 SSC towers (Stream 1 deep-dive).
- `LAYERS` — 7 reference-architecture layers (Stream 2).
- `PATTERNS` — RPA / ML / GenAI / Agentic selector (Stream 2).
- `PIPE` — 8-stage AI factory pipeline. `USECASES` — AI use cases (`{dom,t,d,type}`).
- `GUARDS` — 4 guardrails. `GATES` — 4 KT gates.

### Design system
- Palette: navy `#0f1f38` / `#152741`, gold `#c79a4b` / `#e0c283`, paper `#f6f4ef`, cyan `#3aa6c9`, good-green `#2f8f6a`. EY yellow used only in the logo wordmark (`#ffe600` on `#2e2e38`).
- Phase colours (timeline): Foundation `#3a6ea8` · Lighthouse `#3aa6c9` · Transform `#c79a4b` · Complete `#2f8f6a`.
- Fonts: system sans (Segoe UI stack). Fully responsive; print-friendly.

---

## 6. Key decisions & their rationale (change history)

1. Built as a **single self-contained HTML** (was briefly two files; merged on request).
2. Restructured strictly to the **seven Volume 1 submission requirements**; extras folded into the right required section (operating model + timeline → §2; AI factory → §4); evaluation map moved to an appendix.
3. **Stream 1 & 2 rewritten from RFP-verbatim to POV-led** credibility content (the client flagged that echoing the scope back was weak). RFP scope lists retained in collapsible "compliance" panels.
4. **Benchmarks are illustrative FMCG ranges, clearly labelled** — to be replaced with EY's proprietary figures.
5. **Rebranded to EY**; renamed to **"AI-Enabled SSC Transformation"**; **removed page-count mentions** (client didn't want page compliance shown).
6. **Agency ladder reframed** so L1 reflects RCPL's existing-but-fragmented stack (not a blank slate), justifying the front-loaded Foundation.
7. **Timeline upgraded** from phase cards to an interactive **two-stream Gantt** with phase colour-coding, click-to-expand activities, cross-stream sync points and a dependencies panel.

---

## 7. Placeholders to replace before submission

Search `index.html` for `placeholder` and these:
- **EY logo** — currently a styled-text "EY" wordmark; swap for the official EY brand asset.
- **Team CVs** — real named Partner, Engagement Director, Stream 1/2 Leads, etc. (currently role placeholders).
- **Case studies** — 3 real recent Indian FMCG references + real metrics.
- **All benchmark numbers** — cost-to-serve %, automation %, FTE productivity, forecast accuracy, value chains (currently illustrative ranges).

---

## 8. Open items / suggested next steps

- **Full EY re-skin** — palette is still navy/gold; option to move to EY yellow/black throughout.
- **100+ use-case annexe** — value-sized, BU-sequenced, agency-tagged (currently 16 illustrative in the explorer).
- **Integrated business case** — YoY savings glide path (A11 + B11), reconciled to a (future) Volume 2 commercial.
- **Apply the detailed-activity treatment to mobilisation / add a "today" marker to the Gantt.**
- **Real content swap** for all placeholders in §7.

---

## 9. How to continue

1. Open `index.html` in a browser to view; edit the JS data arrays (§5) to change content.
2. Keep working on branch `claude/interactive-html-proposal-rfp-ysf607`; PR #1 is open to `main`.
3. Commit messages in this project end with a `Co-Authored-By` / `Claude-Session` trailer (optional).
4. This file + `DELIVERY-APPROACH.md` + `APPROACH-NOTE.md` together carry the full narrative and methodology if you need to regenerate or extend anything.

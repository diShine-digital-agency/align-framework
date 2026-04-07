# Infrastructure

This document describes the methodology stack, tooling, and architectural principles behind the ALIGN framework.

---

## Strategy stack

- **Methodology engine:** the 5-phase ALIGN process (Assess, Link, Integrate, Generate, Navigate).
- **Core KPIs:** Narrative Coherence Score™, Brand Momentum Index, and Conversion Variance.
- **Reporting format:** markdown-based strategic briefs designed for asynchronous review and organizational alignment.
- **Tooling:** all templates, guides, and interactive tools are included in this repository — no external dependencies required.

---

## Tools and assets

The repository contains three categories of materials:

### Templates (`templates/`)

Fillable markdown documents that produce the deliverables for each ALIGN phase:

| File | Phase | Output |
| :--- | :--- | :--- |
| `01-assess-narrative-scorecard.md` | Assess | Narrative Coherence Score™ (0–100) |
| `narrative-audit-interview-guide.md` | Assess | Customer validation insights (20 questions) |
| `02-link-narrative-blueprint.md` | Link | Strategic Narrative Blueprint™ |
| `03-integrate-framework-selection.md` | Integrate | Framework selection decision + element mapping + Pixar Pitch |
| `04-generate-content-matrix.md` | Generate | Content Narrative Matrix |
| `05-navigate-measurement-dashboard.md` | Navigate | Narrative KPI Dashboard (9 metrics) |

### Guides (`guides/`)

Reference documents that explain the "why" behind each phase:

| File | Purpose |
| :--- | :--- |
| `how-to-use-this-framework.md` | Step-by-step deployment guide covering all five phases, ownership, and rationale |
| `framework-comparison-matrix.md` | Detailed comparison of five B2B storytelling frameworks (Hero's Journey, StoryBrand, PAS, Pixar Pitch, JTBD) |
| `narrative-audit-technical-analysis.md` | Psychological principles (behavioral economics, narrative theory) behind each interview question |
| `faq.md` | Frequently asked questions about the framework, templates, and tools |

### Interactive tool (`tools/`)

| File | Purpose |
| :--- | :--- |
| `align-navigator.html` | A self-contained, single-file interactive tool that runs in the browser. It walks users through all five phases with guided forms, live scoring, auto-save via local storage, and one-click markdown export. No installation, server, or internet connection required. |

### Diagrams (`assets/`)

Visual diagrams are stored as both source files and rendered images:

| Source file | Format | Description |
| :--- | :--- | :--- |
| `align-framework-overview.d2` | D2 | ALIGN phases overview diagram |
| `heros-journey-b2b.mmd` | Mermaid | Hero's Journey adapted for B2B, mapped to ALIGN tools |
| `narrative-architecture.mmd` | Mermaid | Before/Villain/Guide/After transformation model, mapped to ALIGN tools |

Each source file has a corresponding `.png` render used in the documentation.

---

## Strategic architecture: narrative-led growth

Standard growth strategies often focus on top-of-funnel volume. The ALIGN framework uses narrative coherence as the primary growth lever.

- **Reduced friction.** A coherent story shortens sales cycles and accelerates internal decision-making.
- **Authenticity at scale.** By starting with customer reality (Phase 1), the resulting narrative stays grounded in truth rather than assumptions.
- **Operational alignment.** ALIGN ensures that branding, product, and sales all pull in the same narrative direction.

---

## Data handling

Strategic audits often involve sensitive business data. When using these templates in a real engagement:

- All scorecard data should remain local to the organization's strategic repository.
- Customer interviews should be conducted under NDA, with findings synthesized into anonymized themes before wider distribution.
- The ALIGN Navigator stores all data in the browser's local storage. Nothing is sent to any server. Users can export a JSON backup and clear their session at any time.

---

## Technology choices

The framework is intentionally technology-light:

- **Markdown** for all templates and guides — editable in any text editor, rendered natively by GitHub, compatible with any documentation platform.
- **HTML/CSS/JavaScript** for the ALIGN Navigator — a single file with no external dependencies, no build step, and no framework. It runs offline in any modern browser.
- **D2 and Mermaid** for diagram source files — diagram-as-code formats that can be version-controlled alongside the documentation.

There is no build system, no CI pipeline, and no package dependencies. This is a deliberate design choice: the framework should be usable by anyone who can open a text editor or a web browser.

---

## Author

Strategic vision by [Kevin Escoda](https://kescoda.com).
Developed for [diShine Digital Agency](https://dishine.it) (Milan, Italy).

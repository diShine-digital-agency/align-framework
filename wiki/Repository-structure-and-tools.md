# Repository structure and tools

The ALIGN framework repository is hosted at [github.com/diShine-digital-agency/align-framework](https://github.com/diShine-digital-agency/align-framework). It is a documentation-only repository containing markdown templates, reference guides, an interactive HTML tool, and diagram source files. There is no build system, no CI pipeline, and no package dependencies.

This is a deliberate design choice. The framework should be usable by anyone who can open a text editor or a web browser. Every file in the repository is either a markdown document or a standalone HTML file. Nothing requires compilation, installation, or an internet connection to use.

This page documents the repository layout, explains what each file and directory contains, and describes how to work with the templates and tools.

---

## Repository overview

The repository contains the following categories of content:

- **Root-level documentation.** Standard project files — readme, license, changelog, contributing guidelines, code of conduct, security policy, glossary, and infrastructure notes.
- **Templates.** Six markdown files corresponding to the five ALIGN phases plus a customer validation interview guide. These are the working documents you copy and fill in for each engagement.
- **Guides.** Four reference documents that explain the methodology, compare storytelling frameworks, describe the psychology behind the interview questions, and answer frequently asked questions.
- **Tools.** A single interactive HTML file — the ALIGN Navigator — that provides a guided, browser-based experience covering all five phases.
- **Assets.** Diagram source files (D2 and Mermaid) and their rendered PNG outputs.

---

## Directory structure

```
align-framework/
├── README.md                                ← Project overview and framework summary
├── LICENSE                                  ← MIT license
├── CHANGELOG.md                             ← Version history (Keep a Changelog format)
├── CONTRIBUTING.md                          ← How to contribute
├── CODE_OF_CONDUCT.md                       ← Community standards (Contributor Covenant)
├── SECURITY.md                              ← Vulnerability reporting policy
├── GLOSSARY.md                              ← Key terms defined
├── INFRASTRUCTURE.md                        ← Methodology stack and architecture
│
├── templates/
│   ├── 01-assess-narrative-scorecard.md     ← Phase 1: Narrative Coherence Scorecard™
│   ├── 02-link-narrative-blueprint.md       ← Phase 2: Strategic Narrative Blueprint™
│   ├── 03-integrate-framework-selection.md  ← Phase 3: Framework Selection Workbook
│   ├── 04-generate-content-matrix.md        ← Phase 4: Content Narrative Matrix
│   ├── 05-navigate-measurement-dashboard.md ← Phase 5: Narrative KPI Dashboard
│   └── narrative-audit-interview-guide.md   ← Customer validation interview guide
│
├── guides/
│   ├── how-to-use-this-framework.md         ← Step-by-step user guide
│   ├── framework-comparison-matrix.md       ← Five frameworks compared
│   ├── narrative-audit-technical-analysis.md ← Psychology behind the interview questions
│   └── faq.md                               ← Frequently asked questions
│
├── tools/
│   └── align-navigator.html                 ← Interactive ALIGN Navigator (open in browser)
│
└── assets/
    ├── align-framework-overview.d2          ← ALIGN phases diagram (D2 source)
    ├── align-framework-overview.png         ← ALIGN phases diagram (rendered)
    ├── heros-journey-b2b.mmd               ← Hero's Journey B2B adaptation (Mermaid source)
    ├── heros-journey-b2b.png               ← Hero's Journey B2B adaptation (rendered)
    ├── narrative-architecture.mmd           ← Before/Villain/Guide/After model (Mermaid source)
    └── narrative-architecture.png           ← Before/Villain/Guide/After model (rendered)
```

---

## Root-level files

| File | Purpose |
| :--- | :--- |
| [`README.md`](https://github.com/diShine-digital-agency/align-framework/blob/main/README.md) | Project overview, the five-phase summary, repository structure, scientific references, and links to all templates and guides. This is the entry point for anyone discovering the repository. |
| [`LICENSE`](https://github.com/diShine-digital-agency/align-framework/blob/main/LICENSE) | MIT license. The framework is free to use, modify, and distribute. |
| [`CHANGELOG.md`](https://github.com/diShine-digital-agency/align-framework/blob/main/CHANGELOG.md) | Version history following the [Keep a Changelog](https://keepachangelog.com/) format. Each release documents what was added, changed, or removed. |
| [`CONTRIBUTING.md`](https://github.com/diShine-digital-agency/align-framework/blob/main/CONTRIBUTING.md) | Guidelines for contributors — how to fork, branch, make changes, and open pull requests. Describes what makes a good contribution and what types of contributions are welcome. |
| [`CODE_OF_CONDUCT.md`](https://github.com/diShine-digital-agency/align-framework/blob/main/CODE_OF_CONDUCT.md) | Community standards based on the Contributor Covenant. |
| [`SECURITY.md`](https://github.com/diShine-digital-agency/align-framework/blob/main/SECURITY.md) | Vulnerability reporting policy. |
| [`GLOSSARY.md`](https://github.com/diShine-digital-agency/align-framework/blob/main/GLOSSARY.md) | Definitions of key terms used throughout the repository. Intended for readers who are not familiar with strategic storytelling terminology. Also available as a wiki page: [Glossary](Glossary). |
| [`INFRASTRUCTURE.md`](https://github.com/diShine-digital-agency/align-framework/blob/main/INFRASTRUCTURE.md) | Documents the methodology stack, architecture decisions, and the technology choices behind the repository. |

---

## Templates

The `templates/` directory contains the six working documents that form the core of the ALIGN methodology. Each template corresponds to a specific phase and produces a defined output. Templates are designed to be copied, renamed for the engagement (e.g., `01-assess-acme-corp.md`), and filled in section by section.

### 01-assess-narrative-scorecard.md

- **Phase:** [Phase 1: Assess](Phase-1-Assess).
- **Purpose:** Quantifies the current state of a company's narrative across four dimensions — Narrative Consistency, Message Hierarchy, Emotional Resonance, and Competitive Differentiation.
- **How it works:** The user gathers core marketing and sales materials (homepage, about page, primary sales deck, three recent case studies, three recent email campaigns) and scores each dimension from 0 to 5 against a defined rubric.
- **Output:** A Narrative Coherence Score™ (0–100) that serves as the quantitative baseline for the entire engagement.
- **Repository link:** [`templates/01-assess-narrative-scorecard.md`](https://github.com/diShine-digital-agency/align-framework/blob/main/templates/01-assess-narrative-scorecard.md).

### 02-link-narrative-blueprint.md

- **Phase:** [Phase 2: Link](Phase-2-Link).
- **Purpose:** Connects business strategy to narrative architecture. This blueprint is the foundational document that dictates what you say, why you say it, and how it positions you in the market.
- **How it works:** The user defines the strategic context (core business objective, target audience, paradigm shift), maps the customer transformation journey (Before State to After State), identifies the Villain, and constructs a Pixar Pitch and elevator pitch.
- **Output:** A Strategic Narrative Blueprint™ — the reference document for all subsequent storytelling.
- **Repository link:** [`templates/02-link-narrative-blueprint.md`](https://github.com/diShine-digital-agency/align-framework/blob/main/templates/02-link-narrative-blueprint.md).

### 03-integrate-framework-selection.md

- **Phase:** [Phase 3: Integrate](Phase-3-Integrate).
- **Purpose:** Bridges the gap between the Strategic Narrative Blueprint and actual content production. Helps the user choose the right structural "skeleton" for the narrative and map blueprint elements onto it.
- **How it works:** A diagnostic scoring matrix evaluates the go-to-market motion across five dimensions (deal complexity, market maturity, primary objective, buyer psychology, product nature). The score determines whether to use StoryBrand/PAS, a hybrid architecture, or the full Hero's Journey. The user then maps blueprint elements onto the selected framework's stages.
- **Output:** A framework selection decision and a customized narrative architecture.
- **Repository link:** [`templates/03-integrate-framework-selection.md`](https://github.com/diShine-digital-agency/align-framework/blob/main/templates/03-integrate-framework-selection.md).

### 04-generate-content-matrix.md

- **Phase:** [Phase 4: Generate](Phase-4-Generate).
- **Purpose:** Translates the Strategic Narrative Blueprint into a concrete content plan. Maps messages to channels and buyer journey stages while maintaining narrative consistency.
- **How it works:** The user maps each journey stage (Awareness, Consideration, Decision, Retention) to the relevant narrative element, selects the content format, defines the core message, and assigns a key metric.
- **Output:** A Content Narrative Matrix and a core content assets checklist.
- **Repository link:** [`templates/04-generate-content-matrix.md`](https://github.com/diShine-digital-agency/align-framework/blob/main/templates/04-generate-content-matrix.md).

### 05-navigate-measurement-dashboard.md

- **Phase:** [Phase 5: Navigate](Phase-5-Navigate).
- **Purpose:** Provides a measurement framework for tracking narrative impact. Connects storytelling metrics to revenue outcomes so that strategic storytelling is not vulnerable to budget cuts.
- **How it works:** The user establishes baselines, sets targets, and tracks metrics across three categories: Narrative Consistency (message pull-through rate, content coherence score), Emotional Resonance (message clarity score, engagement depth, qualitative sentiment), and Business Impact (sales cycle velocity, win rate, CAC, NRR).
- **Output:** A Narrative KPI Dashboard with defined metrics, targets, and measurement tools.
- **Repository link:** [`templates/05-navigate-measurement-dashboard.md`](https://github.com/diShine-digital-agency/align-framework/blob/main/templates/05-navigate-measurement-dashboard.md).

### narrative-audit-interview-guide.md

- **Phase:** Used alongside [Phase 1: Assess](Phase-1-Assess), specifically during Step 1.2 (external validation).
- **Purpose:** A structured qualitative research instrument containing 20 interview questions designed to validate the internal scorecard results against real customer perception.
- **How it works:** The user interviews 5–7 recent wins and 3–5 recent losses using the question guide. Questions are organized into four sections: Status Quo and Trigger, Search and Villain, Decision and Guide, and Transformation and Advocacy. Each question includes analysis notes explaining what to listen for.
- **Output:** Customer validation data that reveals the gap between internal narrative assumptions and external market reality.
- **Reference companion:** The [narrative audit technical analysis](https://github.com/diShine-digital-agency/align-framework/blob/main/guides/narrative-audit-technical-analysis.md) explains the psychological principles (Status Quo Bias, Loss Aversion, Anchoring, Curse of Knowledge, Peak-End Rule) behind each question.
- **Repository link:** [`templates/narrative-audit-interview-guide.md`](https://github.com/diShine-digital-agency/align-framework/blob/main/templates/narrative-audit-interview-guide.md).

---

## Guides

The `guides/` directory contains four reference documents. Unlike templates, guides are not meant to be copied and filled in. They provide context, explanation, and instruction that supports the template work.

### how-to-use-this-framework.md

- **Purpose:** A step-by-step user guide that explains the correct sequence for working through the ALIGN framework. Covers what to do at each phase, who should own each step, and the strategic rationale behind every tool.
- **When to use it:** Read this first if you are new to the framework. It provides the complete workflow from Phase 1 through Phase 5, including which templates to use, in what order, and what leadership involvement is required.
- **Repository link:** [`guides/how-to-use-this-framework.md`](https://github.com/diShine-digital-agency/align-framework/blob/main/guides/how-to-use-this-framework.md).

### framework-comparison-matrix.md

- **Purpose:** A detailed comparison of five B2B storytelling frameworks: Hero's Journey (Campbell/Vogler), StoryBrand (Miller), PAS (Problem–Agitation–Solution), Pixar Pitch, and Jobs-to-Be-Done (JTBD).
- **When to use it:** During [Phase 3: Integrate](Phase-3-Integrate), after scoring the diagnostic matrix. This guide helps you understand the strengths, weaknesses, and ideal contexts for each framework before making your selection.
- **Repository link:** [`guides/framework-comparison-matrix.md`](https://github.com/diShine-digital-agency/align-framework/blob/main/guides/framework-comparison-matrix.md).

### narrative-audit-technical-analysis.md

- **Purpose:** A deep technical analysis of the psychological principles behind each of the 20 interview questions in the narrative audit. Explains why each question is phrased the way it is, what cognitive biases it targets, and how to interpret responses.
- **When to use it:** Before conducting customer validation interviews in [Phase 1: Assess](Phase-1-Assess). Understanding the underlying psychology (Status Quo Bias, Loss Aversion, Anchoring, Curse of Knowledge, Peak-End Rule) helps interviewers recognize significant responses and probe appropriately.
- **Repository link:** [`guides/narrative-audit-technical-analysis.md`](https://github.com/diShine-digital-agency/align-framework/blob/main/guides/narrative-audit-technical-analysis.md).

### faq.md

- **Purpose:** Answers common questions about the framework — what it is, who it is for, how to get started, what the ALIGN Navigator is, and how it differs from other methodologies.
- **When to use it:** When you have a specific question or need a quick orientation before working through the full step-by-step guide.
- **Repository link:** [`guides/faq.md`](https://github.com/diShine-digital-agency/align-framework/blob/main/guides/faq.md).

---

## The ALIGN Navigator

The ALIGN Navigator is a self-contained, single-file interactive HTML tool located at [`tools/align-navigator.html`](https://github.com/diShine-digital-agency/align-framework/blob/main/tools/align-navigator.html). It provides a guided, browser-based experience that walks users through all five ALIGN phases with live scoring, form fields, and automatic recommendations.

Key characteristics:

- **Single file.** One HTML file containing all markup, styles, and logic. No external dependencies, no frameworks, no CDN links.
- **Runs offline.** Open it directly from the file system in any modern browser. No server or internet connection required.
- **Auto-saves.** All entered data is stored in the browser's local storage. Users can close the browser and resume where they left off.
- **Exports results.** One-click markdown export for sharing results as a document. JSON backup and restore for full session data portability.

The Navigator follows the same methodology and sequence as the markdown templates. It is an alternative interface, not a separate methodology. For a detailed user guide covering all features, see the [ALIGN Navigator guide](ALIGN-Navigator-guide).

---

## Diagrams

The `assets/` directory contains diagram source files and their rendered PNG outputs. Diagrams are version-controlled alongside the documentation so that changes to the source files and their renders are tracked together.

| Source file | Format | Description | Rendered output |
| :--- | :--- | :--- | :--- |
| `align-framework-overview.d2` | [D2](https://d2lang.com/) | Visual overview of the five ALIGN phases and how they connect. | `align-framework-overview.png` |
| `heros-journey-b2b.mmd` | [Mermaid](https://mermaid.js.org/) | The 12-stage Hero's Journey adapted for B2B contexts. Used in the framework comparison guide and the Integrate phase. | `heros-journey-b2b.png` |
| `narrative-architecture.mmd` | [Mermaid](https://mermaid.js.org/) | The Before/Villain/Guide/After narrative model. Visualizes the core transformation structure used in the Strategic Narrative Blueprint. | `narrative-architecture.png` |

To modify a diagram, edit the source file (`.d2` or `.mmd`) and re-render the PNG. D2 diagrams are rendered using the [D2 CLI](https://d2lang.com/tour/install). Mermaid diagrams can be rendered using the [Mermaid CLI](https://github.com/mermaid-js/mermaid-cli) or any editor with Mermaid support.

---

## Technology choices

The repository uses three technologies, each chosen for a specific reason:

- **Markdown.** All templates, guides, and documentation are written in markdown. Markdown is portable, readable in any text editor, renders natively on GitHub, and does not require any tooling to use. This ensures the framework is accessible regardless of platform, operating system, or toolchain.
- **HTML.** The ALIGN Navigator is a single HTML file with embedded CSS and JavaScript. HTML was chosen because it runs in any browser without installation or compilation. Using a single file with no external dependencies means the tool works offline and does not require a build step.
- **D2 and Mermaid.** Diagram source files use declarative diagram languages (D2 for the framework overview, Mermaid for the journey and architecture diagrams). These are text-based formats that can be version-controlled, diffed, and reviewed alongside the documentation. Pre-rendered PNGs are included so that diagrams display correctly on GitHub without requiring rendering tools.

The repository has zero external dependencies. There is no `package.json`, no `requirements.txt`, no build system, and no CI pipeline. This is intentional: the framework should work for anyone who can open a text editor or a web browser.

---

## How to use the templates

1. **Clone or download the repository.** You can clone the repository using Git, download it as a ZIP file from GitHub, or simply copy individual template files.
2. **Copy the template you need.** Each template is a self-contained markdown file. Copy it and rename it for your engagement (e.g., `01-assess-acme-corp.md`).
3. **Fill in section by section.** Each template includes instructions, rubrics, or prompts within its sections. Work through them sequentially. Do not skip ahead — each phase builds on the output of the previous one.
4. **Use any markdown editor.** The templates work in any text editor, markdown application, or directly on GitHub. No specific tooling is required.
5. **Follow the recommended sequence.** Start with Phase 1 (Assess) and proceed through Phase 5 (Navigate). The [step-by-step user guide](https://github.com/diShine-digital-agency/align-framework/blob/main/guides/how-to-use-this-framework.md) explains the sequence, ownership, and rationale for each phase.

If you prefer a guided experience instead of raw markdown files, the [ALIGN Navigator](ALIGN-Navigator-guide) covers the same sequence in an interactive browser-based format.

---

## Contributing

The ALIGN framework is open source under the MIT license. Contributions that improve clarity, accuracy, or usefulness are welcome. The repository accepts:

- Language and clarity improvements — better phrasing, simpler explanations, fixed typos.
- New templates or guides — additional phase materials, industry-specific playbooks, or translations.
- Bug fixes for the ALIGN Navigator — rendering issues, scoring errors, browser compatibility problems.
- Diagram updates — improvements to the D2 or Mermaid source files.

For full guidelines on how to contribute — including forking, branching, formatting standards, and the pull request process — see [`CONTRIBUTING.md`](https://github.com/diShine-digital-agency/align-framework/blob/main/CONTRIBUTING.md) in the repository root.

For broader context on the methodology and how contributions fit into the framework, see [The ALIGN framework](The-ALIGN-framework).

---

## See also

- [The ALIGN framework](The-ALIGN-framework) — what ALIGN is, why it exists, and how its five phases connect.
- [ALIGN Navigator guide](ALIGN-Navigator-guide) — how to use the interactive browser-based tool.
- [Phase 1: Assess](Phase-1-Assess) — narrative ecosystem mapping and the Narrative Coherence Score™.
- [Phase 2: Link](Phase-2-Link) — strategic-narrative alignment and the Strategic Narrative Blueprint™.
- [Phase 3: Integrate](Phase-3-Integrate) — framework selection, customization, and narrative architecture.
- [Phase 4: Generate](Phase-4-Generate) — content ecosystem development and the Content Narrative Matrix.
- [Phase 5: Navigate](Phase-5-Navigate) — implementation, measurement, and the Narrative KPI Dashboard.
- [Glossary](Glossary) — definitions of all terms used across the framework and this wiki.

---

← Back to [Home](Home)

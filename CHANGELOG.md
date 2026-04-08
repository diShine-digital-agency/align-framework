# Changelog

All notable changes to the ALIGN Strategic Storytelling Framework will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [Upcoming]

*   Industry-specific narrative playbooks (SaaS, Professional Services, Manufacturing).
*   Slide deck template for the Strategic Narrative Blueprint presentation.

---

## [1.3.0] — 2026-04-08

### Added

*   `wiki/` — comprehensive GitHub Wiki (31 pages) covering the ALIGN methodology, scientific foundations, strategic storytelling principles, AI compliance, and reference materials. Pages are organized in six sections: the framework (7 pages), the repository (2 pages), strategic storytelling (9 pages), the science (6 pages), AI compliance (3 pages), and reference (2 pages), plus sidebar and footer navigation.
*   `.github/workflows/sync-wiki.yml` — GitHub Actions workflow that automatically syncs wiki source files from the `wiki/` directory to the repository's GitHub Wiki on push to `main` or via manual dispatch.

### Wiki pages

**The framework:**
*   `wiki/Home.md` — wiki landing page with organized navigation to all 31 pages.
*   `wiki/The-ALIGN-framework.md` — what ALIGN is, why it exists, and how its five phases connect.
*   `wiki/Phase-1-Assess.md` — narrative ecosystem mapping and the Narrative Coherence Score™.
*   `wiki/Phase-2-Link.md` — strategic-narrative alignment and the Strategic Narrative Blueprint™.
*   `wiki/Phase-3-Integrate.md` — framework selection, customization, and narrative architecture.
*   `wiki/Phase-4-Generate.md` — content ecosystem development and the Content Narrative Matrix.
*   `wiki/Phase-5-Navigate.md` — implementation, measurement, and the Narrative KPI Dashboard.

**The repository:**
*   `wiki/Repository-structure-and-tools.md` — what each file does and how the repo is organized.
*   `wiki/ALIGN-Navigator-guide.md` — how to use the interactive browser-based tool.

**Strategic storytelling:**
*   `wiki/What-is-strategic-storytelling.md` — definitions, historical roots, and the five elements of a strategic narrative.
*   `wiki/The-psychology-of-persuasion-through-narrative.md` — narrative transportation, the Elaboration Likelihood Model, Cialdini's principles, and ethical boundaries.
*   `wiki/Corporate-communications-and-narrative-strategy.md` — how strategic storytelling applies across investor relations, internal comms, crisis comms, and employer branding.
*   `wiki/Storytelling-best-practices-for-B2B.md` — practical, actionable guidance for B2B narrative implementation.
*   `wiki/Brand-positioning-through-narrative.md` — how narrative structure creates defensible market positioning.
*   `wiki/Content-strategy-and-narrative-consistency.md` — maintaining narrative coherence across content operations and channels.
*   `wiki/Storytelling-across-the-buyer-journey.md` — mapping narrative elements to awareness, consideration, decision, and retention stages.
*   `wiki/Case-study-storytelling.md` — structuring case studies as narratives rather than feature demonstrations.
*   `wiki/Internal-narrative-alignment.md` — aligning sales, marketing, product, and leadership around a shared strategic narrative.

**The science:**
*   `wiki/The-neuroscience-of-strategic-storytelling.md` — neural coupling, brain synchronization, and why stories outperform feature lists.
*   `wiki/Behavioral-economics-in-B2B-decisions.md` — cognitive biases that shape buying behavior and how strategic narratives leverage them.
*   `wiki/Storytelling-frameworks-compared.md` — Hero's Journey, StoryBrand, PAS, Pixar Pitch, and JTBD compared in depth.
*   `wiki/The-narrative-audit-methodology.md` — the psychology behind the 20-question customer validation interview.
*   `wiki/B2B-narrative-architecture.md` — how to structure narratives for complex business environments.
*   `wiki/Measuring-narrative-impact.md` — KPIs, attribution, and connecting storytelling to revenue.

**AI compliance:**
*   `wiki/AI-compliance-in-corporate-communications.md` — overview of regulations affecting AI-assisted content creation.
*   `wiki/EU-AI-Act-and-strategic-storytelling.md` — how the EU AI Act (Regulation 2024/1689) applies to narrative and content operations.
*   `wiki/AI-generated-content-disclosure-and-ethics.md` — FTC guidelines, transparency obligations, and best practices.

**Reference:**
*   `wiki/Glossary.md` — definitions of all terms used across the framework and this wiki.
*   `wiki/References-and-further-reading.md` — academic papers, books, and regulatory sources cited throughout this wiki.

### Changed

*   `wiki/AI-compliance-in-corporate-communications.md` — fixed incorrect ALIGN phase names ("Audit, Landscape, Insight, Generate, Narrate" corrected to "Assess, Link, Integrate, Generate, Navigate") and corrected phase descriptions.
*   `wiki/Phase-4-Generate.md`, `wiki/Storytelling-frameworks-compared.md`, `wiki/The-narrative-audit-methodology.md` — replaced marketing fluff language ("powerful") with precise, factual alternatives.

---

## [1.2.0] — 2026-04-07

### Added

*   `SECURITY.md` — responsible disclosure policy for vulnerability reporting.
*   `CODE_OF_CONDUCT.md` — dedicated community standards document, adapted from the Contributor Covenant.
*   `GLOSSARY.md` — definitions of all key terms (framework, storytelling, business, and technical) for non-specialist readers.
*   `guides/faq.md` — frequently asked questions covering getting started, tools, methodology, and contributing.
*   `.github/ISSUE_TEMPLATE/bug-report.md` — structured bug report template.
*   `.github/ISSUE_TEMPLATE/feature-request.md` — structured feature request template.
*   `.github/ISSUE_TEMPLATE/config.yml` — issue template configuration with contact link.
*   `.github/pull_request_template.md` — pull request template with phase checklist and writing standards reminder.

### Changed

*   `README.md` — version updated to 1.2.0; removed "homemade" phrasing; integrated the ALIGN Navigator naturally into each phase description (consolidated tool listings per phase instead of a separate callout); added glossary and FAQ links; fixed repository structure tree to include diagram source files (`.d2`, `.mmd`), new documents (`CODE_OF_CONDUCT.md`, `SECURITY.md`, `GLOSSARY.md`, `guides/faq.md`); applied sentence case to all headings for consistency.
*   `INFRASTRUCTURE.md` — expanded from a brief overview to a comprehensive document covering all templates, guides, the ALIGN Navigator tool, and diagram assets in structured tables; added technology choices section explaining the intentional zero-dependency architecture; added data handling note for the ALIGN Navigator's local storage.
*   `CONTRIBUTING.md` — added guidance on accessibility and audience awareness; linked to the new `CODE_OF_CONDUCT.md` instead of inline code of conduct section; added "Types of contributions" section; updated issue reporting to reference the new GitHub issue templates.
*   `guides/how-to-use-this-framework.md` — version updated to 1.2.0; added ALIGN Navigator as an alternative tool reference in every phase step; added links to glossary and FAQ in the navigation footer; applied sentence case to all headings.
*   `guides/framework-comparison-matrix.md` — version updated to 1.2.0; removed "dramatically transform" marketing language from the opening paragraph.
*   All template files — version numbers updated to 1.2.0.
*   `guides/narrative-audit-technical-analysis.md` — version updated to 1.2.0.
*   `CHANGELOG.md` — moved "Upcoming" section to the top (per Keep a Changelog convention); cleaned up completed items; added v1.2.0 entry.

### Added

*   `tools/align-navigator.html` — a self-contained, single-file interactive tool that walks users through all five ALIGN phases in the browser. Includes the full Narrative Coherence Scorecard with live scoring and interpretation, the Strategic Narrative Blueprint worksheet, the framework selection diagnostic with automatic recommendation, a Pixar Pitch builder, the content narrative matrix planner, and a KPI dashboard setup. All data is auto-saved in local storage and can be exported as a markdown report or backed up as JSON.
*   `.gitignore` — added standard ignore rules for OS files, editor directories, and temporary files.
*   `CONTRIBUTING.md` — contribution guidelines covering fork/branch/PR workflow, writing standards, and issue reporting.

### Changed

*   `README.md` — updated to version 1.1.0; removed duplicate "Getting Started" section that repeated the "How to Use" content; tightened language throughout (replaced "powerful" with "effective," removed filler words); added `tools/` and `CONTRIBUTING.md` to the repository structure diagram.
*   `INFRASTRUCTURE.md` — rewritten for clarity: removed internal tool references (Prismo, diShine Dashboard) that are not part of the public repository; cleaned up section headings (removed emoji, used sentence case); improved data handling guidance.
*   All template and guide files — version numbers aligned to 1.1.0; minor language tightening (removed "truly" filler in the measurement dashboard, replaced "powerful asset" with "effective asset" in the scorecard interpretation).
*   `CHANGELOG.md` — v1.1.0 entry added.

---

## [1.0.5] — 2026-04-06

### Changed

*   `assets/align-framework-overview.d2` and `.png` — framework overview diagram fully updated to reflect v1.0.4 content: all 9 tools are now listed within their respective phase boxes (① Narrative Coherence Scorecard, ② Narrative Audit Interview Guide, ③ Technical Analysis in Phase A; ④ Strategic Narrative Blueprint in Phase L; ⑤ Framework Selection Workbook, ⑥ Framework Comparison Matrix, ⑦ Pixar Pitch Synthesis in Phase I; ⑧ Content Narrative Matrix in Phase G; ⑨ Narrative KPI Dashboard in Phase N); a "Start Here" entry node pointing to the user guide has been added;
*   `assets/heros-journey-b2b.mmd` and `.png` — Hero's Journey diagram rebuilt to map each of the 12 journey stages to the specific ALIGN tool and Interview Guide question range that corresponds to it; the five ALIGN phases are now shown as grouped subgraphs framing the journey stages;
*   `assets/narrative-architecture.mmd` and `.png` — narrative architecture diagram updated to show the ALIGN tool that feeds each section (Scorecard + Interview Guide feed the Before State; Blueprint + Interview Guide Q6–Q10 feed the Villain; Framework Selection Workbook feeds the Unique Mechanism; KPI Dashboard and Content Matrix feed the After State);
*   `README.md` — updated to version 1.0.5;
*   `CHANGELOG.md` — v1.0.5 entry added.

---

## [1.0.4] — 2026-04-06

### Added

*   `guides/how-to-use-this-framework.md` — A comprehensive step-by-step user guide that maps the full ALIGN journey across five phases: (1) Assess (Narrative Coherence Scorecard + customer interviews); (2) Link (Strategic Narrative Blueprint with executive team); (3) Integrate (framework selection scoring matrix + element mapping + Pixar Pitch synthesis); (4) Generate (Content Narrative Matrix mapped to buyer journey stages); (5) Navigate (9-metric KPI dashboard with A/B testing guidance). Each step names the responsible owner (Founder, Head of Marketing, Content Team, RevOps) and explains the strategic and psychological rationale behind the action.

### Changed

*   All 8 template and guide files — a contextual "Framework Navigation" footer has been added to each file, identifying which ALIGN phase and step it belongs to and linking back to the step-by-step user guide;
*   `README.md` — updated to version 1.0.4; "How to Use This Framework" section added after the Why section and before the 5 Phases; repository structure block updated to include the user guide; Getting Started section updated with a link to the full guide;
*   `CHANGELOG.md` — v1.0.4 entry added.

---  

## [1.0.3] — 2026-04-06

### Added

*   `guides/narrative-audit-technical-analysis.md` — a detailed technical analysis of the psychological principles behind each of the 20 Narrative Audit interview questions. Covers Status Quo Bias and Loss Aversion (Section 1), Cognitive Framing and the Identifiable Villain Effect (Section 2), Authority Bias and the Halo Effect (Section 3), and the Peak-End Rule and Identity Shift (Section 4). Includes 13 academic references.

### Changed

*   `README.md` — updated to version 1.0.3; technical analysis added to the repository structure, Phase 3 (Integrate) description, and getting-started guide.

---

## [1.0.2] — 2026-04-06

### Added

*   `templates/narrative-audit-interview-guide.md` — a 20-question structured qualitative research guide for validating the Strategic Narrative Blueprint against real customer perception. Organized into four sections (Status Quo & Trigger, Search & Villain, Guide & Unique Mechanism, Transformation & After State), each question includes an *Analysis Note* explaining the cognitive bias or narrative element being tested and how the answer should inform the blueprint.

### Changed

*   `templates/03-integrate-framework-selection.md` — Phase 3 workbook substantially expanded with a five-dimension scoring matrix (replacing the previous three-question diagnostic) and a Hybrid Architecture recommendation for scores in the 12-18 range;
*   `README.md` — updated to version 1.0.2, Phase 1 (Assess) description updated to include customer validation, Narrative Audit guide added to the repository structure and getting-started guide.

---

## [1.0.1] — 2026-04-06

### Added

*   `templates/03-integrate-framework-selection.md` — the Phase 3 (Integrate) Framework Selection & Customization Workbook, including a three-part diagnostic for selecting the right primary framework (StoryBrand vs. Hero's Journey), element-mapping worksheets for both frameworks, and a Pixar Pitch synthesis exercise with a worked example.

### Changed

*   `README.md` — updated to version 1.0.1, added Phase 3 workbook to the repository structure, phase description, and getting-started guide.

---

## [1.0.0] — 2026-04-06

### Added

*   Initial public release of the ALIGN Strategic Storytelling Framework;
*   `templates/01-assess-narrative-scorecard.md` — the Narrative Coherence Scorecard™ (0-100 scoring system across four dimensions);
*   `templates/02-link-narrative-blueprint.md` — the Strategic Narrative Blueprint™ with Before/After state mapping, Villain definition, and Message Hierarchy;
*   `templates/04-generate-content-matrix.md` — the Content Narrative Matrix mapping messages to channels and journey stages;
*   `templates/05-navigate-measurement-dashboard.md` — the Narrative KPI Dashboard with 9 metrics, formulas, benchmarks, and tools;
*   `guides/framework-comparison-matrix.md` — a detailed comparison of five B2B storytelling frameworks (Hero's Journey, StoryBrand, PAS, Pixar Pitch, JTBD) with a decision matrix;
*   `assets/align-framework-overview.png` — visual diagram of the five ALIGN phases;
*   `assets/heros-journey-b2b.png` — B2B adaptation of the 12-stage Hero's Journey;
*   `assets/narrative-architecture.png` — the Before/Villain/Guide/After transformation model.

---

## [1.1.0] — 2026-04-06

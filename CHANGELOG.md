# Changelog

All notable changes to the ALIGN Strategic Storytelling Framework will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [1.1.0] — 2026-04-06

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

## [Upcoming]

*   Phase 3 (Integrate) worksheet: ~~a guided framework selection and customization workbook~~ *(released in v1.0.1)*;
*   A "Narrative Audit" interview guide with 20 customer validation questions: ~~pending~~ *(released in v1.0.2)*;
*   Step-by-step user guide: ~~pending~~ *(released in v1.0.4)*;
*   Interactive ALIGN navigator tool: ~~pending~~ *(released in v1.1.0)*;
*   Industry-specific narrative playbooks (SaaS, Professional Services, Manufacturing);
*   Slide deck template for the Strategic Narrative Blueprint presentation.

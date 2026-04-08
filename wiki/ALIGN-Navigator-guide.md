# ALIGN Navigator guide

The ALIGN Navigator is a self-contained, single-file interactive HTML tool that walks users through all five phases of the [ALIGN framework](The-ALIGN-framework) in the browser. It requires no installation, no server, and no internet connection. Open the file, work through each phase, and export the results when finished.

The tool is located at [`tools/align-navigator.html`](https://github.com/diShine-digital-agency/align-framework/blob/main/tools/align-navigator.html) in the repository.

---

## What the Navigator does

The Navigator provides a guided, browser-based interface for completing the same methodology that the markdown templates cover. Instead of copying and filling in separate markdown files, the user works through tabbed sections in a single HTML page with live scoring, form fields, and automatic calculations.

The Navigator covers the full ALIGN sequence:

1. **[Phase 1: Assess](Phase-1-Assess).** The Narrative Coherence Scorecard with live scoring across all four dimensions (Narrative Consistency, Message Hierarchy, Emotional Resonance, Competitive Differentiation). Scores are calculated automatically as you adjust each slider, and the interpretation updates in real time.
2. **[Phase 2: Link](Phase-2-Link).** The Strategic Narrative Blueprint worksheet. Fill in the strategic context, customer transformation journey, Villain definition, and Pixar Pitch through structured form fields.
3. **Phase 3: Integrate.** The framework selection diagnostic with automatic recommendation. Score your go-to-market motion across five dimensions and receive a framework recommendation (StoryBrand/PAS, hybrid architecture, or Hero's Journey) based on your total score.
4. **Phase 4: Generate.** The Content Narrative Matrix planner. Map journey stages to narrative elements, content formats, core messages, and key metrics.
5. **Phase 5: Navigate.** The KPI Dashboard setup. Define baselines, targets, and measurement tools for each narrative metric category.

---

## Features

The Navigator includes the following capabilities:

- **Live scoring and interpretation.** The Phase 1 scorecard calculates the Narrative Coherence Score™ automatically as inputs change. Score interpretation (critical, needs work, solid, strong) updates in real time.
- **Structured form fields.** Each phase presents labelled input fields, text areas, and scoring sliders. The interface guides the user through each section in the correct order.
- **Framework selection diagnostic.** The Phase 3 diagnostic matrix calculates a total score and provides an automatic framework recommendation based on the scoring interpretation defined in the methodology.
- **Pixar Pitch builder.** Phase 2 includes structured fields for constructing the Pixar Pitch format ("Once upon a time… Every day… One day… Because of that… Until finally…").
- **Content Narrative Matrix planner.** Phase 4 provides a structured interface for mapping journey stages to narrative elements, formats, and messages.
- **KPI Dashboard setup.** Phase 5 provides fields for defining baselines, targets, and measurement approaches for each metric in the Narrative KPI Dashboard.
- **Auto-save via browser local storage.** All entered data is automatically saved to the browser's local storage as the user types. Closing the browser or navigating away does not lose progress. Returning to the file later resumes from where the user left off.
- **Markdown export.** A one-click export function generates a formatted markdown document containing all completed sections. This output can be saved as a `.md` file, pasted into a project wiki, or shared with team members.
- **JSON backup and restore.** Full session data can be exported as a JSON file for backup purposes. The JSON file can be imported later to restore a complete session, including all scores, form inputs, and selections.

---

## How to use it

### Getting started

1. **Download or clone the repository.** Clone the repository with `git clone https://github.com/diShine-digital-agency/align-framework.git`, or download it as a ZIP file from GitHub. You only need the file `tools/align-navigator.html` — but cloning the full repository gives you access to the templates and guides as well.
2. **Open the file in a browser.** Open `tools/align-navigator.html` in any modern browser (Chrome, Firefox, Safari, Edge). You can open it directly from your file system — no web server is needed.
3. **Work through each phase tab.** The Navigator presents phase tabs across the top. Start with Phase 1 (Assess) and proceed sequentially. Each phase builds on the output of the previous one.

### Working through the phases

- Click each phase tab to navigate between sections.
- Fill in the form fields, adjust score sliders, and enter text in the text areas as prompted.
- Data saves automatically as you type. There is no save button — everything is persisted to local storage in real time.
- Completed phases are indicated in the navigation bar.

### Exporting results

- **Markdown export.** Click the export button to generate a markdown document containing all your completed work. Copy the output or save it as a `.md` file.
- **JSON backup.** Export a JSON file containing the full session data. This file includes all form inputs, scores, and selections. Use it to back up your work or transfer it to another browser or device.
- **JSON restore.** Import a previously exported JSON file to restore a complete session. This overwrites the current local storage data for the Navigator.

---

## Data handling

All data entered into the Navigator stays in the browser. The tool uses the browser's local storage API to persist data between sessions. No data is sent to any server, no network requests are made, and no third-party scripts are loaded.

Local storage data is stored under a key specific to the Navigator. Users can clear their data at any time by using the browser's built-in mechanism for clearing site data, or by using the clear/reset function within the Navigator itself.

The Navigator contains no analytics, no tracking pixels, and no external resources. It is a fully offline, self-contained tool.

---

## Navigator vs. markdown templates

Both the Navigator and the markdown templates follow the same ALIGN methodology. They cover the same phases, produce the same outputs, and use the same scoring rubrics and diagnostic criteria. The choice between them depends on how you prefer to work.

| Aspect | Navigator | Markdown templates |
| :--- | :--- | :--- |
| Interface | Guided browser UI with tabs, form fields, and live scoring. | Raw markdown files opened in any text editor. |
| Setup | Open one HTML file in a browser. | Copy and rename individual template files. |
| Scoring | Automatic calculation and interpretation. | Manual calculation following the rubric. |
| Data persistence | Auto-saved in browser local storage. | Saved as files on disk. |
| Export | One-click markdown or JSON export. | The file itself is the output. |
| Portability | Per-browser, per-device (use JSON backup to transfer). | Files can be shared, versioned, and stored anywhere. |
| Flexibility | Structured fields; follows the prescribed format. | Full control over formatting, layout, and additional notes. |
| Collaboration | One person works in the browser; export to share. | Files can be shared via Git, email, or any file-sharing mechanism. |

You can use both approaches together. A common workflow is to start with the Navigator for initial exploration and scoring, then export the results to markdown for documentation, review, and long-term storage. The exported markdown follows the same structure as the templates, so it integrates naturally into a project repository.

---

## Browser compatibility

The Navigator works in any modern browser that supports HTML5, CSS3, and ES6 JavaScript. This includes current versions of:

- Google Chrome.
- Mozilla Firefox.
- Apple Safari.
- Microsoft Edge.

No browser plugins, extensions, or special configurations are required. The tool uses standard web APIs (local storage, DOM manipulation, file download via Blob URLs) that are supported across all major browsers.

---

## Limitations

The Navigator has the following limitations by design:

- **Local storage is per-browser and per-device.** If you switch to a different browser or a different computer, your saved data does not carry over automatically. Use the JSON backup and restore feature to transfer data between browsers or devices.
- **Local storage has size limits.** Browsers typically allow 5–10 MB of local storage per origin. For the Navigator's use case (text form data and scores), this is more than sufficient. However, if local storage is cleared by the browser (e.g., due to storage pressure on mobile devices), data may be lost. Use JSON backup for important sessions.
- **Single-user tool.** The Navigator is designed for one person working through the framework at a time. There is no built-in collaboration, commenting, or multi-user functionality. For team collaboration, export the results to markdown and use shared document workflows.
- **No version history.** The Navigator does not track changes over time. Each save overwrites the previous state. If you need to preserve snapshots of your work at different stages, export JSON backups at each milestone.
- **Offline only.** The tool is intentionally offline. There is no cloud sync, no account system, and no way to access your data from a URL. This is a privacy feature, not a limitation — but it does mean the user is responsible for backing up their own data.

---

## See also

- [Repository structure and tools](Repository-structure-and-tools) — what each file does and how the repository is organized.
- [The ALIGN framework](The-ALIGN-framework) — what ALIGN is, why it exists, and how its five phases connect.
- [Phase 1: Assess](Phase-1-Assess) — narrative ecosystem mapping and the Narrative Coherence Score™.
- [Phase 2: Link](Phase-2-Link) — strategic-narrative alignment and the Strategic Narrative Blueprint™.
- [Phase 3: Integrate](Phase-3-Integrate) — framework selection, customization, and narrative architecture.
- [Phase 4: Generate](Phase-4-Generate) — content ecosystem development and the Content Narrative Matrix.
- [Phase 5: Navigate](Phase-5-Navigate) — implementation, measurement, and the Narrative KPI Dashboard.
- [Glossary](Glossary) — definitions of all terms used across the framework and this wiki.

---

← Back to [Home](Home)

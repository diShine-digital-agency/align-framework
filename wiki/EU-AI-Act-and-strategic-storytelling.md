# EU AI Act and strategic storytelling

The EU AI Act — formally Regulation (EU) 2024/1689 — is the first comprehensive legal framework for artificial intelligence. Adopted by the European Parliament and the Council of the European Union in June 2024 and entered into force on 1 August 2024, it establishes obligations for providers and deployers of AI systems based on the level of risk those systems pose. This page examines the regulation's implications for content teams using AI in strategic storytelling and corporate communications.

**Note:** This page is informational and does not constitute legal advice. Organizations should consult qualified legal counsel for compliance guidance specific to their circumstances.

---

## Background and scope

The EU AI Act applies to providers of AI systems placed on the EU market, deployers of AI systems within the EU, and — notably — providers and deployers located outside the EU if their AI system's output is used within the EU. This extraterritorial scope means that any organization using AI to create content consumed by EU audiences should understand the regulation's requirements.

The Act defines an "AI system" broadly: a machine-based system designed to operate with varying levels of autonomy, that may exhibit adaptiveness, and that infers from inputs to generate outputs such as predictions, content, recommendations, or decisions. Large language models, image generators, and AI writing assistants fall within this definition.

For a broader treatment of AI compliance across jurisdictions, see [AI compliance in corporate communications](AI-compliance-in-corporate-communications).

---

## Risk-based classification system

The EU AI Act organizes AI systems into four risk categories. The obligations imposed on providers and deployers scale with the assessed risk level.

### Unacceptable risk — prohibited practices

Certain AI applications are banned outright. These include:

- Social scoring systems by public authorities.
- Real-time remote biometric identification in publicly accessible spaces (with narrow exceptions for law enforcement).
- AI systems that deploy subliminal, manipulative, or deceptive techniques to distort behavior in ways that cause significant harm.
- Exploitation of vulnerabilities related to age, disability, or social or economic situation.
- Emotion recognition in the workplace and educational institutions (with limited exceptions).

**Relevance to content teams:** The prohibition on "subliminal, manipulative, or deceptive techniques" has theoretical implications for AI-driven persuasion. However, the Act specifies that the technique must cause or be likely to cause "significant harm." Standard marketing and storytelling practices — including the use of narrative structure, emotional appeal, and persuasive framing — are not targeted by this provision, provided they do not exploit specific vulnerabilities or deploy deceptive techniques.

### High risk — conformity assessment

High-risk AI systems require conformity assessments, quality management systems, risk management, data governance, and human oversight. Categories include AI used in:

- Recruitment and employment decisions.
- Credit scoring and insurance.
- Education and vocational training.
- Law enforcement and border control.
- Critical infrastructure.

**Relevance to content teams:** Content generation and marketing AI do not typically fall into high-risk categories. However, if an organization uses AI to personalize content based on individual profiles in ways that affect access to services or opportunities, the boundary may be closer than expected. Consult legal counsel if your use case involves automated decision-making that affects individuals.

### Limited risk — transparency obligations

AI systems that interact with natural persons or generate synthetic content carry transparency obligations. This is the category most relevant to content and communications teams.

**Relevance to content teams:** If your organization deploys chatbots, AI-generated written content, or synthetic media (images, audio, video), Article 50 transparency requirements apply. See the detailed section below.

### Minimal risk — voluntary codes

AI systems that do not fall into the above categories face no mandatory requirements under the Act but may voluntarily adopt codes of practice. Spell-checkers, grammar tools, basic analytics, and similar utilities fall here.

---

## Article 50 — Transparency obligations in detail

Article 50 establishes specific transparency requirements for AI systems that generate content or interact with people. These obligations are central to content operations.

### Chatbot and conversational AI disclosure

Deployers of AI systems that interact directly with natural persons must ensure that individuals are informed they are interacting with an AI system — unless this is obvious from the circumstances. This applies to:

- Customer service chatbots.
- AI-powered sales assistants.
- Conversational AI on websites or platforms.

The disclosure must be provided "in a clear and distinguishable manner" at the latest at the time of first interaction.

### Synthetic content labeling

Providers of AI systems that generate synthetic audio, image, video, or text content must ensure that the outputs are marked in a machine-readable format and are detectable as artificially generated or manipulated. This includes:

- AI-generated marketing images.
- AI-produced video content.
- AI-written text published as content (not AI-assisted drafting reviewed and edited by humans — see the distinction below).

The marking must use interoperable technical solutions — the regulation references standards being developed, including those by the [C2PA (Coalition for Content Provenance and Authenticity)](AI-generated-content-disclosure-and-ethics).

### The human editorial distinction

The Act draws an implicit distinction between AI-generated content and AI-assisted content. Text that is generated by an AI system and published without substantive human review requires labeling. Text that is drafted or assisted by AI but substantively reviewed, edited, and approved by a human author occupies a different position — the human editorial oversight makes the human the author, with AI as a tool.

This distinction matters for content teams using AI in their workflow. The [ALIGN framework](The-ALIGN-framework) emphasizes human strategic judgment at every phase; AI tools support research, drafting, and analysis, but the narrative decisions remain human.

---

## General-purpose AI model obligations

The EU AI Act creates a separate category for general-purpose AI (GPAI) models — foundation models that can be adapted for many downstream tasks. OpenAI's GPT series, Anthropic's Claude, Google's Gemini, and Meta's Llama are examples.

### Standard GPAI obligations

All GPAI model providers must:

- Maintain and make available technical documentation, including training methodology, data sources, and computational resources.
- Provide information and documentation to downstream providers integrating the model into AI systems.
- Comply with EU copyright law, including making available a summary of content used for training.
- Publish a sufficiently detailed summary of the training data.

### Systemic risk GPAI obligations

GPAI models with systemic risk — defined by a computational threshold of 10²⁵ FLOPs or by Commission designation — face additional obligations:

- Perform model evaluations, including adversarial testing.
- Assess and mitigate systemic risks.
- Track, document, and report serious incidents.
- Ensure adequate cybersecurity protections.

**Relevance to content teams:** Content teams are typically deployers of GPAI models, not providers. The obligations above fall on OpenAI, Google, Anthropic, and similar organizations. However, content teams should understand that the models they use are subject to these requirements, and they should evaluate whether their GPAI providers are compliant.

---

## AI literacy requirement — Article 4

Article 4 establishes an AI literacy obligation: providers and deployers of AI systems must take measures to ensure that their staff and other persons dealing with AI systems on their behalf have a sufficient level of AI literacy. This includes understanding:

- The capabilities and limitations of the AI systems they use.
- The potential risks and impacts of those systems.
- The applicable regulatory requirements.

**Practical implication:** Organizations using AI tools for content creation should provide training that covers what the tools can and cannot do, common failure modes (hallucination, bias, factual errors), and the disclosure requirements that apply to their outputs. This is not optional — it is a legal obligation under the Act.

---

## Implementation timeline

The EU AI Act uses a phased implementation schedule:

| Date | Milestone |
|------|-----------|
| 1 August 2024 | Entry into force |
| 2 February 2025 | Prohibited practices apply |
| 2 August 2025 | GPAI model obligations apply; governance structure established |
| 2 August 2026 | Most provisions apply, including transparency obligations (Article 50), AI literacy (Article 4), and obligations for non-high-risk AI systems |
| 2 August 2027 | High-risk system requirements apply for certain categories listed in Annex III |

For content teams, the most relevant date is **August 2026**, when transparency obligations for synthetic content and chatbot disclosure become enforceable.

---

## Penalties

The EU AI Act establishes significant penalties for non-compliance:

| Violation | Maximum fine |
|-----------|-------------|
| Prohibited AI practices | €35 million or 7% of global annual turnover, whichever is higher |
| Other obligations | €15 million or 3% of global annual turnover |
| Supplying incorrect information to authorities | €7.5 million or 1% of global annual turnover |

For SMEs and startups, the Act provides proportionate caps — the lower of the specified amounts applies.

These penalties are comparable in scale to GDPR fines and signal the EU's intent to enforce the regulation.

---

## Practical implications for content teams using ALIGN

For teams implementing the [ALIGN framework](The-ALIGN-framework), the EU AI Act creates several practical requirements:

### During Phase 1 — Assess

When conducting a [narrative audit](The-narrative-audit-methodology), document which content assets were created with AI assistance. This inventory becomes important for compliance if transparency obligations require retroactive labeling.

### During Phase 4 — Generate

When producing content in [Phase 4: Generate](Phase-4-Generate):

- Maintain records of AI tool usage — which tools, for which outputs, with what level of human editorial involvement.
- Establish clear workflows for human review of AI-assisted content.
- Implement disclosure practices for AI-generated content that will be published to EU audiences.

### During Phase 5 — Navigate

When measuring and refining in [Phase 5: Navigate](Phase-5-Navigate):

- Include compliance status in quarterly reviews.
- Monitor regulatory developments — delegated acts and implementing acts will provide further detail.
- Ensure AI literacy training is current and documented.

### Cross-cutting — AI literacy

Train all team members on:

- What AI tools the organization uses and their limitations.
- Disclosure requirements applicable to the organization's content.
- How to identify and correct AI-generated errors (factual inaccuracies, hallucinated citations, bias in generated content).

---

## Relationship to other regulatory frameworks

The EU AI Act does not exist in isolation. Content teams should also be aware of:

- **GDPR (General Data Protection Regulation):** AI systems processing personal data must comply with GDPR requirements, including lawful basis for processing and data subject rights.
- **Digital Services Act (DSA):** Platforms hosting content have additional obligations around illegal content and algorithmic transparency.
- **FTC guidance (United States):** US-based organizations face separate requirements — see [AI-generated content disclosure and ethics](AI-generated-content-disclosure-and-ethics).
- **Sector-specific regulations:** Financial services, healthcare, and other regulated industries may have additional AI-related requirements.

---

## See also

- [AI compliance in corporate communications](AI-compliance-in-corporate-communications) — broader overview of AI compliance across jurisdictions.
- [AI-generated content disclosure and ethics](AI-generated-content-disclosure-and-ethics) — practical disclosure guidance, including FTC and platform requirements.
- [The ALIGN framework](The-ALIGN-framework) — the five-phase methodology for strategic storytelling.
- [Phase 4: Generate](Phase-4-Generate) — the phase where AI tools are most commonly used in content production.
- [Phase 5: Navigate](Phase-5-Navigate) — ongoing compliance monitoring as part of narrative management.
- [Glossary](Glossary) — definitions of key terms including GPAI, C2PA, and risk classification.
- [References and further reading](References-and-further-reading) — regulatory source documents.

← Back to [Home](Home)

# Full prompt: recreate the RAISE-HE Policy Observatory

Copy everything below into an AI coding assistant when you want to recreate, repair or substantially alter the Observatory.

---

## Prompt

You are an expert front-end developer, research-dashboard designer and responsible-AI research-methodology specialist. Create a complete, polished and accessible static website called **“RAISE-HE Policy Observatory”** for an MSCA Postdoctoral Fellowship proof-of-concept.

The website must be suitable for hosting through **GitHub Pages** and must work when `index.html` is placed in the root of a public GitHub repository.

### 1. Required deliverables

Create these files:

1. `index.html` — the complete working website.
2. `.nojekyll` — an empty file.
3. `README.md` — project description, prototype limitations and deployment instructions.

The entire website must run without a build step. Put all required CSS and JavaScript inside `index.html`. Do not require React, Node.js, npm, a database, an API key or a server-side service. Do not use external JavaScript libraries or fragile third-party assets.

### 2. Project identity

Use the following title and subtitle:

- **Title:** RAISE-HE Policy Observatory
- **Subtitle:** Responsible GenAI Integration Readiness across European higher education
- **Eyebrow:** MSCA-PF proof-of-concept · proposal-aligned 12 Aug 2026
- **Data badge:** PRE-AWARD / SYNTHETIC DATA

The dashboard should communicate the research idea, methodological credibility and possible future impact of the RAISE-HE fellowship. It must not present the prototype as a completed empirical study.

### 3. Core scientific model

The central proposition must be presented clearly:

> Faculty capability, professional-learning quality and perceived governance conditions are expected to relate to self-reported enacted responsible GenAI practice.

Use these four construct signals in this exact order:

1. Faculty capability
2. Professional-learning quality
3. Perceived governance conditions
4. Enacted responsible practice — clearly mark this as the primary outcome

Do not use an unsupported equal-weight readiness formula as the project's final scientific model. An average may be shown only as a transparent **synthetic alignment index** for demonstrating the interface.

### 4. Country and context architecture

The project roles must be represented accurately:

- **Greece:** host country and core empirical context
- **Finland:** core empirical context
- **Netherlands:** core empirical context and proposed methods-secondment context
- **Spain:** core empirical context with an academic-contact route at Universidad Autónoma de Madrid
- **Poland:** additional European policy and toolkit-transferability context; not a core empirical-profile country
- **China:** small external WP1 desk-based documentary-reflection context only

China must not be included in interviews, surveys, participant profiles, statistical comparison, institutional action plans or identifiable-data transfer. Poland must not be presented as one of the four core empirical countries.

### 5. Required user journey

Create a sticky or clearly visible navigation journey:

**Explore → Compare → Simulate → Act**

Each stage must be a visually separate, responsive section.

### 6. Header and filters

At the top, include:

- Country/context filter: All planned contexts, Greece, Finland, Netherlands, Spain, Poland and China
- Institution-type filter: All, Research-intensive and Teaching-focused
- A highly visible synthetic-data badge

Changing the filters must update the construct profile, context emphasis, priority message and fictional institutional-profile table.

### 7. Explore stage

Create four headline cards:

- Planned policy corpus: **30–40**
- Critical-incident interviews: **48**
- Main survey target: **≈1,000**
- Core empirical countries: **4**

Add a priority banner containing the central proposition. When a specific context is selected, the banner may identify the weakest synthetic construct signal, but it must say that it is an interface fixture.

Add an evidence-transparency strip:

- Evidence maturity: Pre-award prototype · no participant data
- Proposal alignment: Part B1 · 12 August 2026
- Button: View evidence library
- Button: Research model & safeguards

### 8. Construct profile

Display the four constructs as attractive horizontal bars with icons, values from 0 to 100 and responsive animation. Give **Enacted responsible practice** a distinct outcome style.

Use the following synthetic aggregate fixture:

- Faculty capability: 74
- Professional-learning quality: 61
- Perceived governance conditions: 56
- Enacted responsible practice: 69

Clearly label all values as synthetic interface fixtures.

### 9. Improved interactive map

Build a clean schematic map of Europe using inline SVG. It does not have to be GIS-precise, but it must be attractive, legible and responsive.

Use labelled interactive markers—not numeric rankings:

- FI — Finland
- NL — Netherlands
- PL — Poland
- ES — Spain
- GR — Greece

Each marker must have:

- country code;
- country name;
- synthetic fixture value;
- accessible keyboard interaction;
- descriptive `aria-label` explaining the project's role for that context;
- active and muted states when a filter is used.

Show China in a separate card beneath the European map with this message:

**WP1 documentary reflection only — outside participant research**

Do not draw China as a European map marker. Add a visible note: **No country ranking. China enters WP1 documentary reflection only.**

### 10. Synthetic fixture data

Use the following context objects:

```javascript
[
  { name: "Greece", code: "GR", role: "Host + core empirical", score: 59, docs: 6, dims: [68, 55, 50, 64] },
  { name: "Finland", code: "FI", role: "Core empirical", score: 74, docs: 7, dims: [78, 72, 71, 76] },
  { name: "Netherlands", code: "NL", role: "Core empirical + proposed methods secondment", score: 72, docs: 8, dims: [80, 68, 66, 74] },
  { name: "Spain", code: "ES", role: "Core empirical + UAM academic contact", score: 64, docs: 6, dims: [72, 60, 57, 68] },
  { name: "Poland", code: "PL", role: "Policy + toolkit transferability", score: 59, docs: 5, dims: [66, 55, 52, 61] },
  { name: "China", code: "CN", role: "WP1 documentary reflection only", score: 69, docs: 6, dims: [74, 66, 63, 71] }
]
```

All institution names must be explicitly fictional. Include two fictional institutions per core empirical country, for eight total. Do not create participant or institutional profiles for Poland or China. When either is selected, display an explanatory empty state instead.

### 11. Policy coverage and Evidence Library

Include illustrative policy-coverage bars for:

- Privacy — 100%
- Disclosure — 83%
- Human oversight — 83%
- Verification — 67%
- Fairness — 67%
- Governance clarity — 67%
- Professional learning — 50%
- Accessibility — 50%

Create an Evidence Library with:

- keyword search;
- context filter;
- policy-domain filter;
- Clear filters button;
- Download evidence register button producing a client-side CSV;
- cards for official public policy-source candidates;
- record ID, context, year, domain, title, issuer, summary and official link;
- status label: Candidate · not coded.

State that the sources have not yet been screened or coded under the registered WP1 protocol.

### 12. Proposal-aligned 24-month roadmap

Add a prominent roadmap panel with the following anchors:

- **Host and supervisor:** University of Piraeus · DiLearn; Professor Demetrios G. Sampson
- **Spain academic-contact route:** Universidad Autónoma de Madrid; Dr Beatriz Cabellos Elipe; contextual advice and feasible circulation of ethics-approved invitations; not a formal partnership
- **Proposed methods secondment:** University of Twente, M14–M16; subject to written confirmation

Display six work-package cards:

- **WP1 · M1–M5:** scoping review and comparative documentary analysis; approximately 30–40 documents; output is a frozen construct and adaptation architecture
- **WP2 · M4–M10:** 48 critical-incident interviews, 12 per core country; output is a cross-context mechanism map
- **WP3 · M7–M18:** modular diagnostic battery; 12-expert core panel; 24–32 cognitive interviews; 120–160 pilot; approximately 1,000 main-survey completes; output is a 30–45-item battery with initial psychometric evidence
- **WP4 · M16–M22:** joint displays, Greece workshop and linked European validation; output is a competence pathway, checklist and implementation toolkit
- **WP5 · M1–M24:** training and two-way knowledge transfer
- **WP6 · M1–M24:** management, ethics, data-management plan, quality assurance and open science

Add impact chips for:

- EU AI Act Article 4 · AI literacy
- SDG 4 · primary
- SDG 16 · accountable governance
- SDGs 5 and 10 · supporting inclusion

### 13. Compare stage

The Compare selectors must include only the four core empirical countries:

- Greece
- Finland
- Netherlands
- Spain

Create:

- two context selectors;
- a four-axis SVG radar chart;
- a construct-by-construct comparison table;
- context cards showing planned document count and alignment spread;
- a dynamically generated comparison insight.

Do not rank countries or describe one as a winner, leader or best-performing country. State that empirical context means will be compared only when measurement equivalence is defensible. Mention configural, metric, scalar and defensible partial invariance.

### 14. Simulate stage

Create a transparent scenario simulator for the four core empirical countries only. Include:

- starting-context selector;
- four range sliders, one for each construct;
- projected synthetic alignment index;
- baseline alignment;
- change in points;
- alignment spread calculated as maximum construct value minus minimum construct value;
- reset button;
- button to send the scenario to the Act stage.

The simulator must clearly say:

**Illustrative scenario—not a prediction, causal model or intervention forecast.**

### 15. Act stage

Generate three developmental action cards from the lowest construct signals. Use these construct-matched action templates:

1. Faculty capability → targeted AI-literacy and faculty-capability programme
2. Professional-learning quality → sustained professional-learning pathway with peer mentors
3. Perceived governance conditions → accountable governance roles, minimum controls and review cycles
4. Enacted responsible practice → discipline-based responsible-practice and assessment-scenario clinics

Include suggested owner and timeframe. Add a client-side **Download action brief** button that produces a simple PDF without an external library.

The generated brief must say it uses synthetic fixture data and is not an evaluation, forecast, compliance decision or country ranking.

Disable context-based action-plan generation when Poland or China is selected.

### 16. Methodology modal

Create a modal titled **Research model & interpretation safeguards**. It must explain:

- the central proposition;
- all four constructs;
- the WP1 → WP2 → WP3 → WP4 research pipeline;
- planned validation gates: 30–45 items, I-CVI ≥ .78, 120–160 pilot and approximately 1,000 main survey;
- observational associations, not causal claims;
- governance initially measured as faculty perceptions;
- comparison only after defensible measurement equivalence;
- partial invariance or context-specific modules when needed;
- China excluded from interviews, surveys and statistical comparison.

The modal must open and close accessibly by button, close button, Escape key and backdrop click.

### 17. Research and ethical safeguards

Display these safeguards prominently:

- Observational associations—no causal claims
- No context means before measurement equivalence is defensible
- No automated ranking, punitive appraisal or employment decisions
- China is WP1 desk-based documentary reflection only
- No compliance certification
- No real participant data in the prototype

### 18. Visual design

Use a professional European research-policy aesthetic:

- deep navy and indigo as primary colours;
- teal/green for positive signals;
- amber for cautions;
- off-white background;
- white cards with subtle borders and shadows;
- rounded corners;
- strong information hierarchy;
- generous spacing;
- modern but academically credible typography;
- responsive layout for desktop, tablet and mobile;
- no overlapping map labels or clipped controls;
- restrained motion that respects `prefers-reduced-motion`.

Use reusable inline SVG symbols for icons. Do not rely on emoji as the principal visual system.

### 19. Accessibility and security

Ensure:

- semantic headings;
- form labels;
- keyboard-accessible map markers and buttons;
- visible focus states;
- suitable colour contrast;
- accessible table headings;
- `aria-live` where dynamically updated messages need it;
- safe external links using `target="_blank"` and `rel="noopener noreferrer"`;
- no `eval`, tracking scripts, cookies or data submission;
- a reasonable Content Security Policy when served through a Worker, while keeping the static `index.html` compatible with GitHub Pages.

### 20. Acceptance tests

Before finishing, verify all of the following:

1. `index.html` loads without console errors.
2. All JavaScript-referenced element IDs exist and are unique.
3. Country and institution-type filters update the Explore stage.
4. Selecting China shows the desk-only message, no institutional profiles and a disabled context-action button.
5. Selecting Poland shows the transferability message and no core participant profiles.
6. Map markers use country codes rather than ranking numbers.
7. Compare selectors contain exactly Greece, Finland, Netherlands and Spain.
8. Compare never uses country-ranking language.
9. Simulator sliders recalculate the alignment index and alignment spread.
10. Generated actions correspond to the correct construct order.
11. Methodology modal opens and closes correctly.
12. Evidence search, filters, clear button and CSV download work.
13. PDF action brief downloads and contains the synthetic-data limitation.
14. Desktop and mobile layouts do not overflow horizontally.
15. The page contains a visible proposal snapshot date of 12 August 2026.

### 21. Final response required from the coding assistant

After creating the files, report:

- which files were created;
- how to upload them to GitHub;
- how to enable GitHub Pages;
- which values remain synthetic;
- which parts of `index.html` can be edited safely;
- the expected public URL format.

Do not claim that the website contains real fellowship results or real institutional performance data.

---

End of prompt.


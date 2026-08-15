# RAISE-HE Policy Observatory

An interactive, proposal-aligned proof-of-concept for the MSCA-PF project **RAISE-HE: Responsible GenAI Integration Readiness in Higher Education**.

The Observatory follows the user journey:

**Explore → Compare → Simulate → Act**

## Important status

- This is a **pre-award interface prototype**.
- All displayed scores, profiles and institutions are **synthetic fixtures**.
- No participant-level data have been collected or displayed.
- The prototype is not a compliance certificate, causal model, country ranking or staff-appraisal system.

## Proposal-aligned research architecture

- **Core empirical countries:** Greece, Finland, the Netherlands and Spain.
- **Poland:** policy and toolkit-transferability context.
- **China:** WP1 desk-based documentary reflection only; no interviews, surveys, statistical comparison or identifiable-data transfer.
- **Primary quantitative outcome:** self-reported enacted responsible GenAI practice.
- **Explanatory construct areas:** faculty capability, professional-learning quality and perceived governance conditions.

## Repository files

- `index.html` — complete website, CSS, JavaScript, synthetic fixtures and interactions.
- `.nojekyll` — prevents GitHub Pages from processing the static site through Jekyll.
- `FULL_RECREATION_PROMPT.md` — complete prompt for recreating or altering the Observatory with an AI coding assistant.
- `UPLOAD_INSTRUCTIONS.md` — step-by-step GitHub and GitHub Pages instructions.

## Technology

The website is intentionally build-free:

- HTML5
- CSS3
- Vanilla JavaScript
- Inline SVG map and icons
- Client-side CSV and PDF generation
- No framework, package manager, API key or external JavaScript dependency

## Local preview

Open `index.html` directly in a browser, or run a simple local web server in the folder:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages URL

After deployment, the usual address will be:

`https://YOUR-GITHUB-USERNAME.github.io/raise-he-policy-observatory/`

See `UPLOAD_INSTRUCTIONS.md` for the full process.

## Safe customization

The main editable datasets are near the bottom of `index.html`:

- `dimensionMeta`
- `contexts`
- `aggregate`
- `profiles`
- `coverage`
- `evidenceSources`
- `actionTemplates()`

Keep the synthetic-data notices visible until real data have been ethically collected, quality-checked and approved for publication.


# RAISE-HE Policy Observatory

A proposal-aligned implementation prototype for **RAISE-HE: Responsible GenAI Integration Readiness in Higher Education**.

The public page demonstrates scope control, research architecture, implementation readiness and a compact exact robust-WLSMV feasibility audit. It does **not** publish participant data, country scores, institutional comparisons or rankings.

## Current scope

| Context | Bounded role |
| --- | --- |
| Greece | Host, coordination hub and core empirical context; University of Piraeus pilot-validation workshop |
| Spain | Core empirical context |
| Denmark | Core empirical context |
| Estonia | Core empirical context |
| Netherlands | University of Twente CoDE reviews at M6/M9/M12 and methods secondment at M14–M16 only |
| Ireland | University of Galway contextual and toolkit-transferability feedback only |

The Netherlands and Ireland have no participant quota and are not additional empirical comparison contexts.

## Study architecture

- Respondent-level multi-domain alignment model
- 48 critical-incident interviews
- Approximately 1,000 main-survey completes
- Target 32-item core battery with four eight-item domains and five response categories
- Robust ordinal CFA/WLSMV, measurement-invariance gates and institution-clustered inference
- No latent context means without scalar or defensible partial invariance

## Feasibility evidence

The website reports the completed 150-replication exact robust-WLSMV audit:

- 50 replications per best/base/stress case
- 30 primary-effect and 20 null runs per case
- unequal group sizes, realistic ordinal thresholds/loadings, 5–10% missingness and ICC .02–.08
- convergence, inadmissibility among converged solutions, loading coverage, Type-I error and power for the primary capability × professional-learning interaction

The published rates are empirical Monte Carlo estimates, not guarantees. The stress case is a decision boundary rather than evidence of universal feasibility.

## Repository files

- `index.html` — complete responsive website, styles and interactions
- `data/wlsmv-feasibility.json` — machine-readable compact audit results and interpretation limits
- `.nojekyll` — serves the repository as a static GitHub Pages site
- `FULL_RECREATION_PROMPT.md` — current specification for rebuilding or extending the site
- `UPLOAD_INSTRUCTIONS.md` — GitHub Pages deployment notes

## Local preview

Open `index.html` directly, or run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Technology and privacy

The site uses semantic HTML, CSS and small vanilla-JavaScript enhancements. It has no framework, external dependency, API key, tracking, cookies, form submission or personal-data collection.

## Public URL

<https://arif0336gif.github.io/raise-he-policy-observatory/>


# Current recreation brief: RAISE-HE Policy Observatory

Use this brief to recreate or extend the GitHub Pages prototype without reintroducing superseded proposal content.

## Product goal

Create a polished, accessible, build-free static website titled **RAISE-HE Policy Observatory**. Its purpose is to evidence implementation readiness for an MSCA-PF proposal, not to mimic completed empirical results.

The website must run from a root-level `index.html` with embedded CSS and vanilla JavaScript. Do not require a framework, package manager, server, API key, external library or analytics service.

## Non-negotiable public-data boundary

Do not display or generate:

- synthetic or empirical country scores;
- country-to-country performance comparisons;
- institutional scores, profiles or rankings;
- league tables, readiness indices or automated priorities;
- participant-level data;
- causal predictions, compliance certification or staff-appraisal outputs.

The page may publish verified study-design parameters and actual Monte Carlo audit results, provided all uncertainty and denominators remain visible.

## Current country roles

Use exactly these roles:

1. **Greece** — host, coordination hub and core empirical context; include the University of Piraeus pilot-validation workshop.
2. **Spain** — core empirical context.
3. **Denmark** — core empirical context.
4. **Estonia** — core empirical context.
5. **Netherlands** — methodological support only: confirmed University of Twente CoDE reviews at M6, M9 and M12 and confirmed M14–M16 methods secondment. No Dutch participant quota.
6. **Ireland** — bounded University of Galway contextual and toolkit-transferability feedback only. No Irish fieldwork, participant quota, statistical comparison or identifiable-data transfer.

Do not add any other country to the empirical or Observatory scope.

## Scientific model

Describe RAISE-HE as a **respondent-level multi-domain alignment model**. Institutional clustering is a design and inference feature, not an institution-level causal effect.

Show this conceptual sequence:

- faculty capability;
- professional learning;
- perceived governance conditions;
- responsible AI integration readiness;
- self-reported enacted responsible practice.

Show context and diversity as a cross-cutting layer. Preserve the wording that the model estimates observational associations.

## Headline parameters

- Four core empirical contexts
- 48 critical-incident interviews
- Approximately 1,000 main-survey completes
- **Target 32-item core battery**, four domains with eight five-category ordinal items each

Do not restore the superseded 30–45-item output.

## Exact robust-WLSMV audit

Publish this compact table without changing denominators:

| Case | Group n | λ / missing / ICC | Convergence | Inadmissible among converged | Loading 95% coverage | H2 power β=.12 | Type-I |
| --- | --- | --- | ---: | ---: | ---: | ---: | ---: |
| Best | 250/250/250/250 | .75 / 5% / .02 | 100.0% (50/50) | 0.0% | 95.3% | 100.0% (n=30) | 5.0% (n=20) |
| Base | 280/260/240/220 | .65 / 7% / .04 | 100.0% (50/50) | 0.0% | 94.4% | 83.3% (n=30) | 0.0% (n=20) |
| Stress | 240/225/215/200 | .55 / 10% / .08 | 70.0% (35/50) | 0.0% | 93.0% | 68.4% (n=19) | 6.2% (n=16) |

Required interpretation:

- The audit used 30 β=.12 and 20 null runs per case, 150 total.
- Stress-case downstream denominators include only testable estimands.
- Maximum observed Monte Carlo SE is 11.5 percentage points for power and 12.5 points for Type-I error.
- Zero inadmissibility among converged solutions does not guarantee final-CFA success.
- The base case supports an approximately 1,000-person target only conditionally, for an interaction near β=.12.
- Stress conditions trigger additional recruitment, a simpler model or narrower claims.
- Pilot-calibrated thresholds, loadings and missingness will be re-simulated before preregistration.

The audit covers configural, metric and scalar conditions. Invariance decisions must combine robust WLSMV model comparisons, changes in fit and prespecified item diagnostics. Slopes remain context-specific if metric comparability fails; latent means require scalar or defensible partial invariance.

## Confirmed implementation inputs

Create four clearly bounded cards:

- University of Twente CoDE reviews at M6/M9/M12 → dated review memos and response log.
- University of Twente M14–M16 methods secondment → ordinal CFA, invariance, simulation calibration and reproducible R workflows.
- University of Piraeus pilot-validation workshop → dated item decisions, revisions and rationale.
- University of Galway contextual/toolkit feedback → dated feedback note and documented response; no Irish empirical sample.

## Required safeguards

State prominently:

- no public country or institutional scores;
- no context means before defensible measurement equivalence;
- no causal claims;
- no compliance certification;
- no punitive appraisal or employment use;
- no substantive public interpretation before human verification.

## Interaction and accessibility

Useful interactions include evidence-register search/filtering, responsive navigation, active-section navigation, print styling and CSV download of the exact audit. They must not calculate a readiness score.

Use semantic headings, labelled buttons, keyboard-visible focus, sufficient colour contrast, responsive tables and layouts, and `prefers-reduced-motion` where animation is added. Do not use tracking, cookies, `eval` or data submission.

## Acceptance checks

Before delivery, verify:

1. All required element IDs are unique and every JavaScript selector resolves.
2. The public page names only the six current contexts and gives each the correct bounded role.
3. The target battery is 32 items everywhere.
4. Twente is confirmed, with M6/M9/M12 reviews and M14–M16 secondment.
5. Piraeus and Galway activities and their verifiable outputs are visible.
6. The WLSMV table matches the machine-readable source exactly.
7. No score, comparison, ranking, fictional institution or synthetic country profile remains.
8. The page is usable on desktop and mobile without horizontal page overflow.
9. The footer or status panel carries the current proposal-alignment date.

## Release 0.3 additions

- Display the four empirical contexts separately from the Netherlands and Ireland support roles.
- Add an initial official-source register with issuer, year, source type, relevance, official URL and a “protocol candidate; not yet coded” boundary.
- Include six source records: two EU sources and one national source for Greece, Spain, Denmark and Estonia.
- Provide machine-readable register data without coding, scores or comparisons.
- Show best/base/stress results as visual scenario cards while preserving the complete exact table and denominators.
- Label the base case as the planning assumption and the stress case as the escalation boundary.
- Add an M6/M9/M12/M14–M16 methods-review timeline.
- Add researcher, supervisor, host, release and update metadata.
- Add a reproducibility section that distinguishes the current aggregate release from the complete executable archive planned for preregistration.
- Include a checksum manifest, canonical metadata, favicon, sitemap, robots file and professional 404 page.
- Keep body text at 16 px or larger and table text at 14 px at normal browser scale.

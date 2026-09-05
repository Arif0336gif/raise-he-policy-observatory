# RAISE-HE feasibility audit record

**Release:** 0.3  
**Published:** 5 September 2026  
**Public status:** aggregate pre-submission design audit

This record documents the evidence currently exposed by the RAISE-HE Policy Observatory. It separates the completed aggregate feasibility audit from the final pilot-calibrated executable archive planned for preregistration.

## Design represented in the public audit

- Four groups and four respondent-level factors
- Target 32-item core battery, with eight five-category ordinal items per factor
- Best-case, base-case and stress-case conditions
- Unequal group sizes, realistic thresholds and loadings, 5–10% missingness, and ICC sensitivity from .02 to .08
- Configural, metric and scalar multi-group CFA conditions
- Convergence, inadmissibility among converged solutions, loading coverage, Type-I error, and power
- Primary interaction: capability × professional learning

The recorded estimator configuration used exact robust WLSMV, theta parameterisation, standardised latent variables, ordered indicators and pairwise treatment of ordinal missingness. The recorded feasibility environment used `lavaan` 0.6-21 with a fixed audit seed of 20260904.

## Exact compact results

| Case | Group n | λ / missing / ICC | Convergence | Inadmissible among converged | Loading coverage | H2 power β=.12 | Type-I |
| --- | --- | --- | ---: | ---: | ---: | ---: | ---: |
| Best | 250/250/250/250 | .75 / 5% / .02 | 100.0% (50/50) | 0.0% | 95.3% | 100.0% (n=30) | 5.0% (n=20) |
| Base | 280/260/240/220 | .65 / 7% / .04 | 100.0% (50/50) | 0.0% | 94.4% | 83.3% (n=30) | 0.0% (n=20) |
| Stress | 240/225/215/200 | .55 / 10% / .08 | 70.0% (35/50) | 0.0% | 93.0% | 68.4% (n=19) | 6.2% (n=16) |

Each case used 30 primary-effect and 20 null replications, for 150 total. Stress-case downstream denominators include only testable estimands. The maximum observed Monte Carlo standard error was 11.5 percentage points for power and 12.5 points for Type-I error.

## Primary estimand

The primary H2 estimand is the capability × professional-learning coefficient in a country-fixed-effects regression of within-context-standardised WLSMV factor scores, adjusted for perceived governance, with CR1 institution-clustered inference and df=G−1.

## Decision rules

- The base case conditionally supports a target near 1,000 for an interaction around β=.12.
- The stress case is an escalation boundary: it triggers additional recruitment, a simpler measurement model or narrower claims.
- Metric failure keeps slopes context-specific.
- Latent context means require scalar or defensible partial invariance.
- Robust model comparisons, change in fit and prespecified item diagnostics are considered together.

## Integrity limits

The current website publishes aggregate scenario results and their machine-readable summary. It does **not** represent a complete executable replication archive as already public. Zero inadmissibility among converged solutions does not establish guaranteed feasibility or admissibility for the final CFA.

Before preregistration, the simulation will be rerun using pilot-calibrated thresholds, loadings and missingness. The resulting release will freeze executable scripts, dependency versions, replication-level outputs, seeds, convergence diagnostics and an archived analysis plan.

## Public files

- [Aggregate WLSMV results](../data/wlsmv-feasibility.json)
- [Initial official-source register](../data/policy-evidence-register.json)
- [SHA-256 integrity manifest](manifest.json)

The checksum manifest verifies the exact public data files in this release.

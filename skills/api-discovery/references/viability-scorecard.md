# API viability scorecard

Score each category 0-2 (0=poor, 1=partial, 2=strong).

1. Lifecycle confidence
- Officially active, roadmap clear, no immediate deprecation risk.

2. Auth and access
- Feasible OAuth/API key flow, permissions/scopes are practical.

3. Data coverage fit
- Required fields available with acceptable quality and granularity.

4. Operational reliability
- Quotas/rate limits/failure modes are manageable.

5. Tooling maturity
- SDK/docs/examples sufficient to implement and maintain.

6. Fallback readiness
- Export/unofficial/manual fallback available if API breaks.

## Interpretation
- 10-12: API-first is reasonable
- 7-9: Hybrid recommended
- 0-6: Avoid/defer; use fallback-first

## Required note
Always include assumptions and unknowns that could change the score.

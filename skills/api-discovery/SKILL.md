---
name: api-discovery
description: Evaluate whether a third-party data source can be integrated reliably by checking API lifecycle status, auth model, data coverage, limits, SDK/tooling, and fallback options. Use when deciding “can/should we integrate this source now?” for ETL/data-product pipelines.
---

# API Discovery

Use this skill to make integration decisions quickly and safely.

## Workflow

1. Define target use case
- Source, required data fields, expected freshness, and acceptable risk.

2. Collect evidence
- Prioritize official docs/changelogs.
- Capture API status (active/deprecated/sunset), auth requirements, scopes, and quotas.
- Note platform constraints (Android-only, app-only, region, account tier).

3. Check data-fit
- Map required fields to available API/export fields.
- Mark gaps as hard blockers vs acceptable compromises.

4. Score integration viability
- Use `references/viability-scorecard.md`.
- Produce a score with explicit assumptions.

5. Recommend path
- Choose one:
  - API-first
  - Export-first
  - Hybrid (API primary + export fallback)
  - Defer
- Include a short implementation plan and fallback trigger.

## Output format

- **Decision**: one line
- **Evidence**: 4–8 bullets (facts)
- **Risks**: 2–4 bullets
- **Plan**: immediate next 3 steps
- **Fallback**: concrete backup path
- **Sources**: links

## Guardrails

- Don’t treat community blogs as final truth without primary-source confirmation.
- If lifecycle status is unclear, default to hybrid/fallback-safe design.
- Prefer migration-safe abstractions over source-specific lock-in.

## References

- `references/viability-scorecard.md`
- `references/source-checklist.md`

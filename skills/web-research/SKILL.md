---
name: web-research
description: Research topics on the public web using links and lightweight extraction, then produce decision-ready summaries with explicit sources. Use when the user asks for internet research, article/doc comparison, API viability checks, migration planning, source credibility checks, or “read these links and recommend an approach.”
---

# Web Research

Use this skill to turn web content into actionable decisions fast.

## Workflow

1. Clarify the decision target in one line
- Example: “Decide if Google Fit API is viable for a new ingestion connector in 2026.”

2. Gather sources
- If links are provided, fetch those first.
- If search tool is available, collect 3–8 sources max.
- Prefer official docs/changelogs/releases over blog summaries.

3. Extract and verify
- Pull only the sections relevant to the decision.
- Capture exact facts: dates, deprecations, auth constraints, quotas, compatibility.
- Cross-check important claims across at least 2 sources where possible.

4. Synthesize
- Provide:
  - What is true now
  - What is uncertain
  - Recommended decision
  - Risk and fallback path

5. Output format
- Keep short and decision-focused.
- Include a compact “Sources” list with URLs.
- If confidence is low, state that explicitly and list what evidence is missing.

## Quality bar

- Prefer primary sources (vendor docs, API references, official announcements).
- Time-bound claims (“deprecated in 2026”) must include source link.
- Separate facts from inference.
- Don’t over-collect; stop when evidence is sufficient for a clear recommendation.

## Research patterns for data projects

- API viability check: auth model, lifecycle/deprecation, rate limits, data coverage, export fallback.
- Integration strategy: primary path + fallback path + migration-safe abstraction.
- Tooling decision: compare by setup complexity, local-first fit, and observability support.

## References

- Use `references/source-triage.md` for a quick reliability rubric and decision template.

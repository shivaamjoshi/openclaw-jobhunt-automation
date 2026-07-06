# Source triage rubric

## Reliability order
1. Official product docs / deprecation notices / changelogs
2. Official SDK docs / API reference pages
3. Maintainer repos/issues
4. Community posts/tutorials

## Minimum evidence set (API decision)
- Lifecycle status (active/deprecated/sunset + timeline)
- Auth flow and required credentials
- Data coverage needed by the use case
- Operational limits (quota/rate/latency)
- Fallback path (export/unofficial adapter/manual import)

## Decision template
- **Decision:** <adopt / avoid / adopt-with-fallback>
- **Why:** 2-4 bullet facts
- **Risks:** 2-3 bullets
- **Fallback:** concrete path
- **Revisit trigger:** what new info would change decision

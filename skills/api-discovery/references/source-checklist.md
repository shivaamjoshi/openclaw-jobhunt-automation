# Source discovery checklist

## Must capture
- API lifecycle status (active/deprecated/sunset + dates)
- Auth mechanism and required credentials/scopes
- Endpoints/data types relevant to your use case
- Rate limits/quotas/latency expectations
- Historical/backfill capability
- Data freshness model (push/pull/batch)
- Terms/compliance constraints

## For mobile health sources
- Health Connect compatibility status
- OS/app version dependencies
- Source attribution fields (origin package/provider)
- Timestamp + timezone consistency

## Decision output
- Recommendation: API-first / Export-first / Hybrid / Defer
- Confidence: High / Medium / Low
- Fallback trigger: explicit condition to switch path

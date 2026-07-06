# OpenClaw Jobhunt Automation Portfolio Prep

This repository is a **portfolio-prep workspace** for showcasing custom agent skills and workflow integrations built around **OpenClaw** and the open-source **career-ops** project.

## Credits / Upstream Projects

### OpenClaw
[OpenClaw](https://github.com/openclaw/openclaw) is the underlying open-source agent framework used to run skills, workflows, messaging, browser automation, and tool-driven orchestration.

**Important:** I did **not** build OpenClaw itself. This repo is intended to showcase the **custom skills, workflow design, and integrations** I built **on top of** OpenClaw.

### career-ops
[career-ops](https://github.com/santifer/career-ops) is an open-source repo for job search operations, role tracking, and application workflow support.

**Important:** I did **not** build career-ops itself. My work used career-ops as an adjacent/open-source foundation in a broader OpenClaw-powered job-hunt automation workflow.

### qmd
[qmd](https://tobi.lutke.com) is a third-party tool that I integrated via an OpenClaw skill wrapper.

**Important:** I did **not** build qmd. The work included here is the **integration layer / skill wrapper** around qmd, not authorship of the underlying tool.

---

## What this repo contains

This folder currently contains selected OpenClaw skills copied from a separate private workspace into a clean portfolio-prep directory for review.

### Original workflow designs by me
These represent my own skill/workflow design work:

- `skills/api-discovery/`
  - A workflow for evaluating whether a third-party data source can be integrated reliably.
  - Focus areas include API lifecycle status, authentication model, data coverage, rate limits, tooling, and fallback options.

- `skills/web-research/`
  - A workflow for structured public-web research using links and lightweight extraction.
  - Focused on producing decision-ready summaries with explicit sourcing.

### Integration work by me around an existing third-party tool
- `skills/qmd/`
  - An OpenClaw skill wrapper/integration for the external `qmd` tool.
  - This should be understood as **integration work**, not authorship of qmd itself.

---

## Why this exists

The goal of this repo is to prepare a clean public-facing portfolio example of:
- custom OpenClaw skill authoring,
- workflow/system design for research and integration tasks,
- practical agent-tool orchestration,
- and selected job-hunt automation related extensions built around existing open-source tooling.

This is **prep work only**. It was assembled from a separate private workspace into an isolated folder so the contents can be reviewed, sanitized, and selectively published later if desired.

---

## Current contents

```text
skills/
  api-discovery/
    SKILL.md
    references/
      source-checklist.md
      viability-scorecard.md
  qmd/
    SKILL.md
    _meta.json.example
    .clawhub/
      origin.json.example
  web-research/
    SKILL.md
    references/
      source-triage.md
```

---

## Privacy / sanitization notes

This folder is intended to exclude:
- agent memory files
- logs
- private workspace root files
- secrets/tokens
- non-example config files

Sanitized `.example` metadata files are included where relevant instead of real config/registry metadata.

---

## Status

This repository has **not** been initialized with git here, **not** committed, and **not** pushed. It is meant for manual review before any public release decisions are made.

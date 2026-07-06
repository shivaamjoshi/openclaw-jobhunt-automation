# OpenClaw Jobhunt Automation Portfolio

This repository is a **portfolio workspace** showcasing custom agent skills and workflow integrations built around **OpenClaw** and the open-source **career-ops** project.

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

This repository contains selected OpenClaw skills published from a private workspace into a clean portfolio directory.

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

This repository showcases the published version of these skills. The contents have been reviewed, sanitized, and made public for display.

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

This repository is initialized, committed, and published as a public repository. It showcases the current working version of these custom skills and integrations.

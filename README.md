# 0918

2026-09-18 workspace for GitHub Plugin and maintenance workflow trials.

## Purpose

This repository is a clean place to organize work that should not be mixed into older archive repositories.

Initial intended uses:

- GitHub Plugin operation checks
- Dashboard / Agent maintenance notes
- Read-only investigation summaries
- Candidate change notes before formal release or deployment

## Working Rules

For Dashboard / Agent related work:

- Treat server-side state as the source of truth.
- Do not call a file delivered or deployed unless server-side validation is complete.
- Keep timeout, unknown, not executed, excluded, and confirmed states separate.
- Record evidence, test results, checksums, and deployment status before release decisions.

## Structure

- `docs/` - reusable documentation and workflow notes
- `maintenance/` - maintenance logs and investigation summaries
- `release/` - release candidates, validation notes, and delivery records
- `scripts/` - helper scripts that are safe to share

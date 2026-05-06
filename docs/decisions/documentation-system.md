# Documentation System Decision

## Decision

Use a layered documentation system:

- canonical lessons in `course-modules/`
- concise dashboards at the repository root
- semantic supporting docs under `docs/`
- compressed memory in `CONTEXT_SNAPSHOT.md`

## Reasoning

The workspace must support both study and future chat continuity. A layered structure keeps long notes available while making it easy to restart quickly.

## Consequence

Every meaningful content update should check whether it affects:

- root summaries
- glossary terms
- revision questions
- progress status
- context snapshot

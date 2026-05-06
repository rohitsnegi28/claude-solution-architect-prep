# Prompts

Use these prompts to keep the repository self-maintaining across future chats.

## Resume This Workspace

```text
Read README.md, CONTEXT_SNAPSHOT.md, TODO.md, CHANGELOG.md, and ARCHITECTURE.md.
Then summarize the current learning workspace state, open tasks, and the best next action.
Keep the answer concise and do not duplicate existing docs.
```

## Add New Lesson Notes

```text
Convert these rough notes into a lesson file under the correct course module.
Use this structure: Topic Overview, Learning Outcomes, Key Concepts, Architecture / Solution Design Connection, Exam-Focused Takeaways, Likely Questions, Quick Revision Notes, Gaps To Review.
Then update LEARNINGS.md, GLOSSARY.md if terms changed, TODO.md, CHANGELOG.md, and CONTEXT_SNAPSHOT.md.
Avoid duplicating long explanations already present elsewhere.
```

## Generate Revision Questions

```text
Using the current course module, generate exam-style questions grouped by topic.
Include concise answers only where they clarify a concept.
Prioritize weak or high-yield areas from TODO.md and docs/progress/status.md.
```

## Refresh Context Snapshot

```text
Compress the current repository state into CONTEXT_SNAPSHOT.md.
Preserve architecture, decisions, constraints, progress, open tasks, and durable learning concepts.
Remove conversational details and redundant explanations.
```

## Documentation Maintenance Check

```text
Audit the repository for stale docs, duplicate explanations, missing links, and outdated progress.
Make minimal edits that improve clarity and continuity.
Update CHANGELOG.md and CONTEXT_SNAPSHOT.md with durable changes.
```

# Decisions

## Accepted

### D001: Treat Lessons as Canonical Source

Course lesson files in `course-modules/` are the primary source of truth. Root files and `docs/` pages summarize, connect, and compress those lessons.

Reason: this avoids duplicate long explanations and makes updates easier.

### D002: Use Root Files as Fast Dashboards

The required root files provide immediate orientation for new chats and quick revision sessions.

Reason: future work should start quickly without rereading the full repository.

### D003: Use `CONTEXT_SNAPSHOT.md` as Durable Memory

Long chat context should be compressed into `CONTEXT_SNAPSHOT.md` after meaningful changes.

Reason: the user wants each new chat to resume from the last useful state.

### D004: Keep Learning Material Beginner-Friendly

Learning summaries should explain concepts plainly before adding architecture or exam language.

Reason: the repository is both an exam prep system and a personal learning course.

## Proposed

- Add one module per major Claude Solution Architect topic as new source material arrives.
- Add spaced-repetition checklists after the first full exam pass.

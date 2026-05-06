# Context Snapshot

## Project State

This repository is a Claude Solution Architect exam preparation workspace. It currently contains one full course module: `course-modules/ai-fluency/`, with 11 lessons covering AI Fluency, the Four Ds, generative AI fundamentals, LLM capabilities and limitations, prompting, discernment, diligence, and synthesis.

## Purpose

The repo should function as both:

- a production-grade Markdown knowledge base; and
- a structured learning course for revision and interview-style preparation.

## Current Architecture

- `course-modules/` stores canonical lesson notes.
- `reference/` stores broad reusable exam aids.
- Root files provide fast orientation and project memory.
- `docs/` organizes supporting material by purpose: architecture, features, learning, revision, decisions, progress, prompts, and troubleshooting.

## Durable Decisions

- Lessons are the source of truth.
- Root docs are dashboards and compressed summaries.
- Long context should be preserved in this file, not in chat history.
- Learning explanations should stay beginner-friendly and concise.
- Avoid duplicate long explanations across files.

## Core Learning Memory

AI Fluency means effective, responsible human-AI collaboration. The key framework is the Four Ds:

- Delegation: decide the human/AI work split.
- Description: communicate goals, context, constraints, process, and desired behavior.
- Discernment: evaluate output, reasoning, and collaboration quality.
- Diligence: act ethically, transparently, safely, and accountably.

The three modes of AI use are automation, augmentation, and agency. More autonomy means more need for oversight.

## Open Work

- Add Claude product/platform-specific content when available.
- Add concrete solution architecture examples.
- Expand glossary with Claude and cloud architecture terms.
- Create progress-based revision drills after the next study pass.

## Maintenance Instruction

On future changes, update the most relevant lesson or doc page first, then refresh `TODO.md`, `CHANGELOG.md`, and this snapshot. Keep changes semantic and short.

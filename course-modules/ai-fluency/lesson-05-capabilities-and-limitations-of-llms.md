# Lesson 05: Capabilities and Limitations of LLMs

## Topic Overview

This lesson explains what LLMs like Claude can do well and where they need human oversight. Effective AI collaboration requires understanding both strengths and limitations, similar to learning how to work with a new colleague.

## Learning Outcomes

By the end of this lesson, I should be able to:

- Identify common capabilities of LLMs.
- Explain major limitations such as hallucinations and knowledge cutoffs.
- Understand why LLM outputs need critical review.
- Connect AI strengths with human judgment and ethical oversight.

## Capabilities of LLMs

### Versatility

LLMs can perform many different language and reasoning tasks without task-specific retraining.

Examples:

- Drafting emails.
- Summarizing reports.
- Translating languages.
- Explaining complex concepts.
- Brainstorming and refining ideas.

### Context Retention

Modern models can maintain the thread of a conversation and use previous details to build more relevant responses.

### Tool Integration

Some models can connect to tools or external sources, such as web search, file processing, code execution, or business systems. This can increase usefulness but also requires controls and monitoring.

## Limitations of LLMs

### Knowledge Cutoff

Models may not know events or information after their training cutoff unless connected to current external sources.

### Hallucinations

Models can produce confident but incorrect information because they generate based on learned patterns rather than guaranteed fact verification.

### Context Window Limits

A model can only process a limited amount of information at one time. Very long documents or conversations may exceed this working memory.

### Non-Deterministic Behavior

LLMs are probabilistic. The same prompt can produce different answers across runs.

### Complex Reasoning Challenges

Models are improving, but they can still struggle with multi-step math, logic, or tasks requiring exact reasoning.

## Architecture / Solution Design Connection

For enterprise use, architects should design around LLM limitations:

- Add validation for important outputs.
- Use retrieval or tools for current and factual information.
- Keep humans in the loop for high-risk decisions.
- Break large tasks into smaller steps when context is limited.
- Log, monitor, and test AI behavior for reliability.

## Exam-Focused Takeaways

- LLMs are versatile but not infallible.
- Hallucination is a core risk.
- Knowledge cutoff limits current awareness.
- Context windows limit how much information can be processed at once.
- AI should be combined with human critical thinking, judgment, and ethical oversight.

## Likely Questions

1. What are common capabilities of LLMs?
2. What is a hallucination?
3. What is a knowledge cutoff?
4. Why can LLMs give different answers to the same prompt?
5. Why is human oversight still required?

## Quick Revision Notes

- Strengths = versatile, fast, conversational, tool-connected.
- Limits = cutoff, hallucinations, context window, variability, reasoning errors.
- Best use = AI speed + human judgment.

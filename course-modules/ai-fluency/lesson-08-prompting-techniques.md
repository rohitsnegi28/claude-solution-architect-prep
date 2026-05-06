# Lesson 08: Prompting Techniques

## Topic Overview

This lesson gives practical prompting techniques for working with AI assistants like Claude. Prompting is framed as clear communication and expectation setting, similar to working with a helpful new colleague.

## Learning Outcomes

By the end of this lesson, I should be able to:

- Apply six foundational prompting techniques.
- Improve prompts using context, examples, constraints, and roles.
- Break complex tasks into steps.
- Use iteration to improve AI outputs.
- Ask Claude to help improve a prompt when stuck.

## Six Foundational Prompting Tips

### 1. Give Claude Context

Explain your goal, background, audience, and why you need the output. More relevant context helps Claude tailor the response.

Example:

Instead of: Explain AI Fluency.

Better: Explain AI Fluency for a solution architect preparing for an internal Claude certification exam.

### 2. Show Examples

Use few-shot or n-shot prompting by giving examples of the desired output style or structure. This helps Claude imitate the pattern.

Example:

Provide one completed sample answer, then ask Claude to generate more answers in the same format.

### 3. Specify Output Constraints

Tell Claude the required format, length, tone, structure, or content boundaries.

Examples:

- Use a table.
- Keep it under 150 words.
- Use bullet points.
- Avoid jargon.
- Include three risks and three mitigations.

### 4. Break Complex Tasks into Steps

For complex requests, guide Claude through a sequence. This reduces ambiguity and improves reasoning quality.

Example:

First summarize the problem, then identify assumptions, then compare options, then recommend one approach.

### 5. Ask Claude to Think First

Ask Claude to reason through factors and constraints before producing the final output. This can improve completeness and quality.

Example:

Before giving the final recommendation, list the criteria you will use to evaluate the options.

### 6. Define Claude's Role, Style, or Tone

Assign a role or style to guide the response.

Examples:

- Act as a senior solution architect.
- Explain like a science teacher.
- Be concise and exam-focused.
- Challenge weak assumptions.

## Additional Best Practices

### Ask for Prompt Help

If unsure how to phrase a request, ask Claude to improve the prompt.

Example: Help me rewrite this prompt to get a more structured exam revision note.

### Iterate

Prompting is experimental. If the first answer is not good, refine context, add examples, add constraints, or start a fresh conversation.

### Focus on Principles

Specific prompting tricks may change as models improve, but clear communication remains fundamental.

## Architecture / Solution Design Connection

Prompting techniques become reusable design assets in AI systems:

- Prompt templates.
- Role instructions.
- Output schemas.
- Step-by-step workflows.
- Evaluation checklists.

## Exam-Focused Takeaways

- Prompting is communication, not magic wording.
- Context improves relevance.
- Examples improve pattern matching.
- Constraints improve usability.
- Step-by-step instructions help complex tasks.
- Roles and tone shape the AI's perspective.
- Iteration is normal and expected.

## Likely Questions

1. What are the six foundational prompting tips?
2. Why is context important in prompting?
3. What is few-shot prompting?
4. Why should complex tasks be broken into steps?
5. How can role prompting change Claude's response?

## Quick Revision Notes

- Context, examples, constraints, steps, thinking, role.
- Prompting = clear communication.
- Iterate when output is weak.
- Ask Claude to improve prompts when stuck.

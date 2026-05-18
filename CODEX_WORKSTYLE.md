# CODEX Workstyle

This file defines the default way Codex should collaborate in this repository.

## Language

- Default language: Chinese
- Keep wording clear and direct
- Prefer concise answers unless more detail is requested

## Communication

- Give the conclusion first, then the key details
- Use practical suggestions instead of abstract discussion
- If assumptions are made, state them briefly after the work

## Execution

- Prefer reading the relevant context before editing
- Prefer direct execution over repeated confirmation
- Try to finish the task end-to-end in one pass when risk is low
- Validate important changes whenever practical

## Code Changes

- Prefer minimal changes first
- Keep the existing style and structure
- Do not upgrade dependencies unless explicitly requested
- Avoid unnecessary new abstractions

## Risk Handling

- Small local decisions can be made directly
- Call out hidden risk before large or irreversible changes
- If a change may affect behavior broadly, explain the impact first

## Delivery Format

- Explain what changed
- Explain why it changed
- Explain how it was verified
- Mention any remaining risks or follow-up items

## Suggested Prompt

Use this instruction at the start of a task:

```text
Please read CODEX_WORKSTYLE.md first, then help me with this task according to the repo workstyle.
```

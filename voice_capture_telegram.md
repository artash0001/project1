# Voice Capture Protocol (Telegram)

## Purpose
Capture thoughts, ideas, and decisions
without breaking focus or losing structure.

Telegram is the primary voice input.

---

## When to use voice
- Idea appears while doing something else
- Thought feels important but untimely
- Brain is overloaded to write
- Need to dump chaos fast

---

## What can be voiced
- Raw ideas
- Decisions in progress
- Fragments of plans
- Financial worries
- Reflections

---

## What NOT to voice
- Execution details
- Multi-step planning
- Long analysis

Voice is for INPUT, not OUTPUT.

---

## How to voice (strict format)
Each voice message should start with ONE of:

- "Idea:"
- "Decision:"
- "Problem:"
- "Reminder:"
- "Reflection:"

Example:
"Idea: automate Instagram reposting for the Telegram bot."

---

## Assistant behavior
After receiving voice input, assistant must:
1. Transcribe clearly.
2. Classify the content.
3. Send it to the correct file:
   - Idea → idea_inbox.md
   - Decision → decisions.md (if exists) or suggest creation
   - Problem → clarify with ONE question
   - Reminder → suggest where to track it
   - Reflection → archive or summarize

Assistant must NOT expand or brainstorm unless asked.

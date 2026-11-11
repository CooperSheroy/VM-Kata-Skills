---
name: literal-genie-brief
description: Use when writing or fixing a prompt, brief, delegation, spec, or feedback for an AI model or a person, or when delegated work keeps coming back wrong. Applies Varun Mayya's Kata 3 (how he uses AI). Example requests - "write a prompt for this task", "my freelancer keeps missing the point", "help me brief my designer", "the AI keeps giving me the wrong thing", "how do I give this underperformer clear feedback?"
license: MIT
metadata:
  series: Varun Mayya Katas
  kata: "Kata 3"
  source: https://www.youtube.com/watch?v=yJFsZLgUa40
---

# Literal Genie Brief

## Source
Varun Mayya, *How I Use AI (1 Hour Masterclass) | Kata 3* (YouTube, January 2026): https://www.youtube.com/watch?v=yJFsZLgUa40
A distilled, paraphrased method — not a substitute for watching the talk.

## Overview
Any executor — an AI model, a new hire, a freelancer — is a literal genie: it fills every gap in your instruction with its own defaults. Most bad output is a **context failure**, not a skill failure. Writing is how you think and transfer context; prompting is writing.

## When to use
- **AI work:** drafting or debugging prompts, agent instructions, research requests.
- **Delegation:** briefing a hire, contractor, agency, or teammate; writing a spec or acceptance criteria.
- **Management:** writing feedback for an underperformer; setting up recurring reports.
- **Diagnosis:** a story like "the team is overworked" or "the campaign failed" that may be built from outputs only.

## When not to use
- The text must *persuade* a reader (pitch, cold email, post, proposal) → use **reader-world-builder**. Rule of thumb: genie brief = make an executor do exactly the right thing; reader world = make a reader believe or act.
- The question is brand/culture as a world people buy into → use **brand-world-builder**.
- The question is why a result happened (metrics, credit) rather than how to instruct → use **true-attribution-check**.

## Steps
1. **State the intent, not just the metric.** One paragraph: what outcome you actually want and why. KPIs (counts, deadlines) don't carry intent.
2. **Run the genie attack.** List every way a literal or lazy executor could satisfy the words while missing the point ("unlimited money" → from where? how much? legally?). Add a constraint for each.
3. **Give examples and references.** At least one concrete example of correct output (file name, format, tone, reference link or image); where possible one unacceptable example. For creative work, gather references (AI can surface niche ones) and say "like this, with this twist."
4. **Spec checklist ("golden brown on both sides").** Write acceptance criteria the receiver checks before handing back. Ask: what would a veteran know implicitly that a newcomer wouldn't?
5. **Let AI fill edge cases, humans fill facts.** Ask an AI to enumerate what you haven't thought of and to ask clarifying questions. Then replace numbers, prices, and names with verified ones.
6. **Check for unreliable narration.** When diagnosing a problem, ask whether the story is built from visible outputs only. What are the inputs and causes? Get the data (experience levels, time per unit, team design) before deciding.
7. **Close the loop with reporting.** Define a short recurring report (done, numbers, misses, blockers) so you don't need to chase. Tie incentives to reported outcomes; watch for incentives that reward the wrong behaviour.
8. **Feedback with a spec.** When someone underperforms: in writing, state the gap, attach a reference of expected quality, give a deadline and support. Vagueness here harms careers.

## Output
```
Intent: …
Deliverable: …
Constraints (from genie attack): …
Good example: … / Bad example: …
Acceptance checklist: …
Context they might lack: …
Report back: format + cadence
```

## Questions to ask
- "If a brand-new person executed exactly these words, what would go wrong?"
- "What do you know that they don't?"
- "Is the problem their skill, or our spec?"

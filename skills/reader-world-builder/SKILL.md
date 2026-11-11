---
name: reader-world-builder
description: Use when writing anything meant to persuade or move a reader (cold email, pitch, investor update, post, proposal, landing page, script) or when an AI prompt keeps returning generic, average output. Applies Varun Mayya's related, unlabelled lecture "Best Skill to Learn in 2026" - not official Kata 5. Example requests - "rewrite this cold email so it lands", "make my pitch more convincing to investors", "my LinkedIn post sounds generic", "help me write a proposal for this client", "ChatGPT keeps giving me bland copy"
license: MIT
metadata:
  series: Varun Mayya Katas (related lecture)
  kata: "Unlabelled related lecture (not official Kata 5)"
  source: https://www.youtube.com/watch?v=uBWcK3KzJjY
---

# Reader World Builder

## Source
Varun Mayya, *Best Skill to Learn in 2026 (AI Can't Replace This)* (YouTube, February 2026): https://www.youtube.com/watch?v=uBWcK3KzJjY
This lecture is **not labelled a Kata and is not in the official Katas playlist**. It is included as a related thinking tool, not as official Kata 5 (which had not been found as of November 2026). A distilled, paraphrased method — not a substitute for watching the talk.

## Overview
Writing runs a program in the reader's mind. Success is measured by what they *hear*, not what you said. Either fit into the world they already live in and shift the frame, or build a new world that is consistent and easy to enter. Prompting is the same: you constrain a model into a small universe with explicit rules.

## When to use
- **Sales / fundraising:** cold emails, pitches, decks' narrative, investor updates.
- **Career:** cover letters, outreach to a hiring manager, a promotion case.
- **Content:** posts, scripts, landing pages that feel generic or don't convert.
- **AI output quality:** a model keeps returning averaged, bland text.

## When not to use
- The goal is to get an executor (AI or person) to *do a task correctly* — a brief, spec, delegation, or feedback → use **literal-genie-brief**. Tie-break: reader world = change what a reader believes or does; genie brief = remove ambiguity for whoever executes.
- The goal is a whole brand, community, or culture as a believable world → use **brand-world-builder**. Tie-break: one piece of writing to one reader → this skill; an ongoing world many people inhabit → brand-world-builder.
- The pitch is to a wealthy or powerful buyer and the real question is what they value → start with **blink-into-the-buyer**, then write with this skill.

## Steps
1. **Map the reader's world.** Who exactly is reading? What identity do they hold about themselves? What do they already believe, fear, want? What words do they use (in-group language)?
2. **Choose a strategy.** *Fit + shift:* their world almost accepts your idea → start inside it. *New world:* the idea has no home yet → you'll need a prototype, examples, and consistent rules.
3. **Build atomic agreements.** Write 2–4 simple, non-controversial statements the reader will nod to. Build the specific problem on top of them.
4. **Frame shift.** Once agreement is established, introduce your view in *their* vocabulary (e.g., "go-to-market," not "content," for an investor).
5. **Make it concrete.** Replace each abstract claim with a short true story or example: who, what changed, measurable result. With no examples, show a prototype.
6. **Cognitive hospitality pass.** Ordinary words, short sentences, needless words removed. Remove anything the reader would strongly reject before they're bought in. Check internal consistency.
7. **Resolution.** Release the tension you created: your idea is the way out, with one clear next step.

**For AI prompts**
1. Define the universe: role, audience, goal, constraints ("laws").
2. Give positive examples and at least one "don't do this" example (e.g., banned patterns).
3. Specify the specifics you want (segment, region, style) — vagueness returns averages.
4. If output is generic, add more laws or examples, not more adjectives.

## Output
The reader map (identity, beliefs, vocabulary), chosen strategy, atomic agreements, the rewritten piece, and a short note on which lines were cut or changed and why.

## Ethics check
Persuasion techniques can manipulate. Only claim true things; don't fabricate identity, results, or credentials.

## Questions to ask
- "What will the reader think in the first five seconds?"
- "Which line would make them stop agreeing?"
- "Where's the concrete story?"

## Worked example
*A freelance data analyst is cold-emailing the operations head of a regional logistics firm.* Draft opened with "I'm a data analyst with 5 years of Python and SQL experience."
- Reader world: ops head thinks in on-time delivery, fuel cost, and driver hours; sees "data analyst" as an IT expense.
- Strategy: fit + shift.
- Atomic agreements: "Late deliveries cost you twice — the refund and the repeat order." "Your dispatch team already has more data than time."
- Frame shift in their vocabulary: "I find the routes and shifts where late deliveries cluster," not "I build dashboards."
- Concrete: "For a 40-truck fleet, this cut late drops by about a fifth in two months" (only if true for the sender).
- Resolution: "Want me to run it on one month of your dispatch logs, free, and show you the three worst routes?"

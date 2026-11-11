---
name: resolution-project-manager
description: Use when planning or running a large, uncertain project where the method, market, or cost isn't fully known, or when deciding whether to hire, outsource, buy tools, automate, or scale a team for it. Applies Varun Mayya's Kata 12 (how he manages projects end to end). Example requests - "help me plan this new product launch", "we don't know if this will work, how do we structure it?", "should I hire or outsource for this?", "when should we scale the team?", "how do I set kill criteria for this experiment?"
license: MIT
metadata:
  series: Varun Mayya Katas
  kata: "Kata 12"
  source: https://www.youtube.com/watch?v=mwQhnZ32CeE
---

# Resolution Project Manager

## Source
Varun Mayya, *How I Manage Projects End To End (1 Hour Masterclass) | KATA 12* (YouTube, August 2026): https://www.youtube.com/watch?v=mwQhnZ32CeE
A distilled, paraphrased method — not a substitute for watching the talk.

## Overview
Start with a low-resolution plan and team; let both sharpen through fast experiments. Separate known work from unknown work. Don't scale structure until the shape is stable.

## When to use
- **Product / venture:** launching something new where market or method is unknown.
- **Project management:** structuring departments, a minimum viable team, vertical slices, decision deadlines.
- **Resourcing:** hire vs outsource vs tool vs train; technology-investment math.
- **Scaling:** deciding whether the project's shape is stable enough to grow the team.

## When not to use
- The plan exists and the problem is bloat — too many features, tools, or initiatives → use **simplicity-filter**. Tie-break: resolution = *structure unknown work*; simplicity = *cut what's unnecessary*.
- Choosing *which* venture bet to make in the first place → use **bootstrap-bet-engine**.
- Team friction or misaligned incentives → use **coordination-cost-audit**.

## Steps
1. **Admit the resolution.** Write what you know vs. don't (market size, user appetite, method, cost). If much is unknown, avoid long fixed plans.
2. **Department map.** List the distinct problems the project must solve. Each is a department (not yet a role). One person per department = **minimum viable team**.
3. **Tag each department.** *Sure shot:* method known → scale with money/hires. *R&D:* method unknown → cheap experiments, fast feedback loops (see work live), leader attention, low cost per unit. Prioritise R&D on what's hard to catch up later; defer natural advantages.
4. **Vertical slice.** Define a small, end-to-end, usable slice (a 5–10 minute demo, one complete flow). Iterate alphas on it, then beta with real users.
5. **Decision deadline per experiment.** Before each release, define three outcomes and thresholds: continue / one more test / shut down. Example thresholds: ~50% of target users like it; a stated purchase-intent proxy (e.g., 5–6%) — treat as proxies and calibrate later.
6. **Sourcing choice per role (pick one).** (1) Existing person in-house; (2) invest in technology; (3) outsource temporarily (short, well-defined); (4) hire permanently (budget 3–4 months to land someone); (5) train internally with a part-time external mentor (slowest; when talent doesn't exist).
7. **Technology investment math.** Time one unit by hand × total units needed (+ buffer) vs. tool/automation cost. Trust the numbers only after quality is validated by users.
8. **Shared state.** As the team grows, create one visible source of truth: per-item status across departments, references/mood boards for anything visual. Simple custom tools (AI-built) are fine.
9. **Scale gate.** "How likely is it that we'll need to redraw the shape?" If meaningful, don't scale yet. Pivoting a large team means returning to department heads and letting people go.
10. **Codify.** When the shape stabilises, the org chart (people with the taste and muscle memory) is the playbook; future similar projects can start at full resolution.

## Output
Resolution statement, department map with sure-shot/R&D tags, minimum viable team, slice plan, decision thresholds, sourcing per role, tech math, scale-gate verdict.

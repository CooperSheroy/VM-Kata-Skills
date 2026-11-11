# Varun Mayya Kata Skills (unofficial)

Seventeen reusable [Agent Skills](https://agentskills.io/specification) distilled from Varun Mayya's **Kata** talk series on YouTube. Each skill turns one talk into a decision procedure an AI agent (or a person) can run: when to use it, the steps, scorecards and kill rules, and a defined output.

- Official Katas playlist: https://www.youtube.com/playlist?list=PLSAVyiM48sqvzLBEbPqD8TZpfu5UyzO9t
- Channel: https://www.youtube.com/@VarunMayya

> **Unofficial.** This project is not made, endorsed, or reviewed by Varun Mayya, AEOS / Aeos Labs, or Aevy TV. The methods are paraphrased, condensed, and may contain errors. They are not a substitute for the talks — watch the originals.

## Coverage and gaps (as of 11 November 2026)

- **Kata 5 was not found** on the channel or in the official playlist. `reader-world-builder` comes from a related lecture, *Best Skill to Learn in 2026*, which is **not labelled a Kata and is not official Kata 5**.
- **Kata 14 is inferred.** *Why Belief Matters More Than Power & Money* sits in the official playlist after Kata 13 and calls itself a Kata, but its title has no number.
- **Katas 15 and 16** had not been released.

See [INDEX.md](INDEX.md) for titles, dates, links, and other uncertainties.

## Skills

| Skill id | Source | Use it when… |
|---|---|---|
| `varun-mayya-thinking` | Series synthesis (router) | You want the general operator stance, or aren't sure which Kata applies |
| `bootstrap-bet-engine` | Kata 1 | Starting or growing a venture with little/no funding; raise vs bootstrap; picking bets |
| `coordination-cost-audit` | Kata 2 | A growing team is slowing down, misaligned, or losing morale |
| `literal-genie-brief` | Kata 3 | Writing prompts, briefs, specs, delegation, or feedback; work keeps coming back wrong |
| `scouter-competence-read` | Kata 4 | Judging someone's real credibility (or your own); stuck planning instead of attempting |
| `social-safety-regulator` | Secret Kata #1 | Fearful or political teams; feedback taken personally; self-criticism under pressure |
| `reader-world-builder` | Related unlabelled lecture (not Kata 5) | Persuasive writing — cold emails, pitches, posts — or generic AI copy |
| `true-attribution-check` | Kata 6 | Explaining why something worked/failed; single-metric attribution; credit |
| `decide-and-commit` | Kata 7 | Feeling lost; torn between options; too many projects at once |
| `champr-hiring-lens` | Kata 8 | Evaluating a candidate, designing interviews, retention, or getting hired |
| `risk-staging-playbook` | Kata 9 | Weighing a specific risky move and how to stage it |
| `lightning-catcher-distribution` | Kata 10 | Building audience/inbound; content or marketing "not working yet" |
| `simplicity-filter` | Kata 11 | New feature/process/tool proposals; bloated plans; busy-but-slow teams |
| `resolution-project-manager` | Kata 12 | Running an uncertain project; hire vs outsource vs tool; when to scale |
| `blink-into-the-buyer` | Kata 13 | Selling to or partnering with wealthy/powerful people; ownership vs income |
| `belief-to-behavior` | Kata 14 (inferred) | Goal chosen but not acted on; conviction fading after rejection |
| `brand-world-builder` | Secret Kata #2 | Building a brand, community, or culture as a world people believe |

Each `SKILL.md` has a **When not to use** section with tie-breaks to its siblings (e.g. scouter vs CHAMPR, decide vs belief vs risk), and the router skill lists them all.

## Install

Every skill is a folder containing a `SKILL.md` with YAML frontmatter (`name`, `description`). Copy each **folder** — not just the file — so the path ends in `<skills-dir>/<skill-id>/SKILL.md`. You can install all 17 or only the ones you want; `varun-mayya-thinking` works best alongside the others.

### Claude Code
- **Project:** copy into `.claude/skills/` in your repo
  ```bash
  mkdir -p .claude/skills && cp -R varun-mayya-kata-skills/skills/* .claude/skills/
  ```
- **Personal (all projects):** copy into `~/.claude/skills/`
  ```bash
  mkdir -p ~/.claude/skills && cp -R varun-mayya-kata-skills/skills/* ~/.claude/skills/
  ```
- **As a plugin:** the repo includes `.claude-plugin/plugin.json` with skills in the default `skills/` folder, so you can load it locally with `claude --plugin-dir ./varun-mayya-kata-skills` or add it to your own plugin marketplace.

### Cursor
- **Project:** copy into `.cursor/skills/`
  ```bash
  mkdir -p .cursor/skills && cp -R varun-mayya-kata-skills/skills/* .cursor/skills/
  ```
- **Personal:** copy into `~/.cursor/skills/`.

### Codex and other Agent Skills–compatible tools
- **Codex (repo):** copy into `.agents/skills/` at your repo root (or any folder Codex scans).
- **Codex (personal):** copy into `~/.agents/skills/`.
- **Anything else that loads Agent Skills:** point it at, or copy into, a `skills/` directory so each skill sits at `skills/<skill-id>/SKILL.md`.

Restart the agent (or start a new session) if new skills don't show up.

### Using them
Ask naturally — "should I quit my job to do this full time?", "score this candidate", "rewrite this cold email", "which Kata applies here?". Agents choose a skill from its `description`; you can also name it ("use champr-hiring-lens").

## Files

- `skills/<id>/SKILL.md` — the 17 skills.
- `INDEX.md` — talk inventory, dates, video links, skill mapping, gaps and uncertainties.
- `thinking-synthesis.md` — how the series reasons across talks.
- `.claude-plugin/plugin.json` — optional Claude Code plugin manifest.
- `LICENSE` — MIT.

No transcripts, captions, or verbatim talk text are included.

## License and disclaimer

The skill text in this repository is an original distillation, released under the [MIT License](LICENSE). The talks themselves, their titles, and all associated content remain the property of their author and the relevant YouTube rights holders.

Not affiliated with Varun Mayya, AEOS / Aeos Labs, or Aevy TV. Methods are paraphrased and may be imperfect; watch the talks for the full context. Nothing here is medical, legal, or financial advice — thresholds, ratios, and benchmarks quoted are directional heuristics from the talks, not verified figures.

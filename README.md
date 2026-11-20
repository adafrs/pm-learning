# Building Positive Influence as a Solo Nonprofit PM

A small, source-checked library of practical articles for **the only product manager at a small nonprofit**: someone with no PM team, a thin budget, an Executive Director to report to, a board, program staff, volunteers, beneficiaries and funders, who wants to build influence in a positive, ethical way.

Every article cites real, opened-and-checked sources, tests its advice against critiques and counter-evidence, and ends with an **AI study prompt** you can paste into Claude (or another assistant) to be quizzed on what you read. See [METHODOLOGY.md](METHODOLOGY.md) for how sources were chosen and checked.

## The articles

| # | Article | What you'll get | Evidence |
|---|---|---|---|
| 1 | [Influence Without Authority](articles/01-influence-without-authority.md) | Which influence tactics actually work (and which backfire upward), the "currencies" model, coalitions | Moderate |
| 2 | [Stakeholder Mapping and Managing Up](articles/02-stakeholder-mapping-and-managing-up.md) | Mapping ED, board, staff, funders and beneficiaries; working with your ED; "no surprises" | Moderate |
| 3 | [Trust and Psychological Safety](articles/03-trust-and-psychological-safety.md) | Trust as the base of lasting influence; making it safe to raise problems; blameless reviews | Moderate |
| 4 | [Prioritization and Saying "Not Now"](articles/04-prioritization-and-saying-no.md) | Mission-tied criteria, RICE, cost of delay, Now/Next/Later, the four-part "not now" | Moderate |
| 5 | [Continuous Discovery with Beneficiaries](articles/05-continuous-discovery-with-beneficiaries.md) | Using evidence from real users as influence; ethical research with vulnerable people | Moderate |
| 6 | [Outcomes, Impact and Metrics](articles/06-outcomes-impact-and-metrics.md) | Theory of change, logic models, right-sized measurement, OKRs used lightly | Moderate |
| 7 | [Communicating for Influence](articles/07-communicating-for-influence.md) | Answer-first writing, stories plus data, board-ready memos, pre-wiring ethically | Moderate |
| 8 | [Sustaining a Team of One](articles/08-sustaining-a-team-of-one.md) | Burnout prevention, boundaries, allies, peer networks, mentoring | Moderate |

**Suggested reading order:** 3 → 1 → 2 → 5 → 4 → 6 → 7 → 8. Trust comes first because every other technique depends on it.

## Notable corrections to popular advice

The counter-evidence step changed several well-known claims. Worth knowing before you repeat them:

- **Trading favors and flattery work with peers but not upward.** With your ED and board, lead with evidence ([article 1](articles/01-influence-without-authority.md)).
- **"One child's story beats statistics" is weaker than commonly claimed.** The identifiable victim effect is small and has failed recent replications. Use a story as a door into the data, not a replacement for it ([article 7](articles/07-communicating-for-influence.md)).
- **"Five users is enough" applies to repeated usability tests, not exploratory interviews**, which typically need around a dozen ([article 5](articles/05-continuous-discovery-with-beneficiaries.md)).
- **Oxytocin is not a proven explanation for workplace trust**, though the management behaviors associated with it remain sensible ([article 3](articles/03-trust-and-psychological-safety.md)).
- **More psychological safety isn't always better.** Pair it with shared accountability ([article 3](articles/03-trust-and-psychological-safety.md)).
- **OKRs are optional for small nonprofits**, and the evidence for them comes mostly from large tech firms ([article 6](articles/06-outcomes-impact-and-metrics.md)).
- **Prioritization scores (RICE etc.) are conversation aids, not proofs** ([article 4](articles/04-prioritization-and-saying-no.md)).

## How to use the AI study prompts

1. Read the article.
2. Copy the fenced `text` block under **AI study prompt** at the bottom.
3. Paste it into a new conversation with your AI assistant.
4. Answer one question at a time. At the end you'll get a summary of strengths, gaps and three follow-up actions.

Each prompt carries the article's key ideas, so it works without uploading the article. For deeper practice, paste the full article in too and ask for harder scenario questions.

## Repository structure

```
README.md          ← you are here
METHODOLOGY.md     ← the source-quality loop every article went through
articles/          ← 8 articles, each with sources, evidence table and AI prompt
```

## Status

- Last verified: 2026-11-20. About 150 unique source links; none were dead at last check. Some publisher sites block automated link checkers but load normally in a browser.
- Each article's *Sources* section notes where only an abstract or summary could be checked (usually paywalled journals).

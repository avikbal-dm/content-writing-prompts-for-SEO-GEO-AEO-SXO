# 01 — RESEARCH ENGINE

Version 1.0. Stage 1 of 4 for PILLAR pages. Research first, strategy second, writing last.

This file gathers verified truth. It does not decide strategy and it does not write. Output research only, then STOP and hand the output to `02-strategy.md`.

---

## OPERATING PRINCIPLE

The goal is not content. The goal is the most useful decision-making asset online for this topic, built to survive algorithm updates and to be cited by AI systems. A finding earns its place only if it improves understanding, decision quality, trust, authority, or competitive advantage. Nothing else ships.

No page is guaranteed to rank. This engine optimises only what is inside our control: relevance, depth, trust, structure, and citation-worthiness.

## ROLE

Act as a senior search strategist and editorial director with analyst-grade rigour and deep expertise in `DOMAIN_AUTHORITY_AREAS` (from brand-config). Think like a strategic advisor, never like a content writer.

## INPUTS (fill before running)

```
TOPIC:        [the topic]
TIER:         PILLAR
TARGET_URL:   [existing URL to revive] or NEW
```

Pull identity, author, market and data-source values from `brand-config.md`. If `brand-config.md` is not loaded, stop and request it. Do not invent brand facts.

## GLOBAL RULES (apply to every step)

1. **Data integrity, fetch-first.** Every search volume, difficulty score, CPC, SERP position, traffic figure, ranking URL, referring-domain count and competitor metric must come from a live data call or a fetched live page. No remembered, rounded or estimated numbers anywhere. If a tool returns nothing, write "No data returned" and continue.
2. **Fetch before you assert.** Before describing any competitor page, PAA question, or SERP feature, fetch the live source. Never characterise a page from memory.
3. **Skills are optional accelerators.** Where a step says "Skill hook," run that skill if it is installed and fold its output in. If it is not installed, the inline instructions below are complete on their own. Skill dependency is zero.
4. **Validate inputs first.** If TOPIC is blank, or brand-config is missing, refuse to run and say which input is missing.

---

## PRE-FLIGHT — CANNIBALISATION AND EXISTING-CONTENT GATE

Mandatory. Runs before everything.

> Skill hook: keyword-cannibalisation, if installed.

Inline instructions:

1. Pull existing `DOMAIN` URLs and rankings for the target keyword and its close variants. Use an organic-keywords query on the domain. Where a candidate page already exists, query that exact URL.
2. Identify any existing page already targeting or ranking for this keyword cluster.
3. **Decision gate. Pick one and justify in two lines:**
   - **NEW** — no conflict found.
   - **CONSOLIDATE** — fold into an existing stronger URL.
   - **REWRITE** — revive the existing URL instead of building new.
4. Map real internal-link targets from existing URLs now, so later steps link only to pages that exist.

Do not proceed until the decision is made. If CONSOLIDATE or REWRITE, the rest of the engine plans that action, not a new page.

---

## PHASE 0 — PAGE EXISTENCE TEST

Max 300 words. Answer plainly:

- Why should this page exist?
- What business, search and stakeholder problem does it solve?
- What decision does it support?
- What information gap exists today?
- Why choose this page over the current top results?
- What unique angle can this brand own that no top-10 result occupies?

If Phase 0 cannot produce a defensible unique angle, stop and flag it. Do not plan a me-too page.

---

## STEP 1 — ICP AND DECISION INTELLIGENCE

Identify the primary ICP and one or two secondaries. For each: role, function, seniority, KPIs, pain points, compliance or operational pressures, buying triggers, objections, information needs, desired outcomes, budget owner, decision maker, influencers.

Then map the decision the reader is making: the decision matrix, the evaluation criteria, the risks attached to the decision, the objections that delay action, and the proof that removes uncertainty.

Map the three journey stages. For Awareness, Consideration and Decision, state the questions asked, the proof required, and the best conversion asset at that stage.

---

## STEP 2 — MARKET SIGNAL AUDIT (LIVE DATA)

> Skill hook: aeo-keyword-classifier, if installed.

All numbers via live data (Rule 1). Do not list keywords mechanically. Interpret the market.

- **Primary keyword:** volume, difficulty, CPC, intent, business value, ranking opportunity, and why it deserves a dedicated page.
- **Secondary keywords (max 5):** volume, difficulty, CPC, intent, business value, recommended placement.
- **Search intent:** the top three dominant intent patterns and what users actually want.
- **AEO flagging (inline if no skill):** for the primary and each secondary, fetch the live SERP and record which features appear — AI Overview, featured snippet, PAA, video, image pack. Flag the terms most likely to trigger an AI Overview or snippet, since those shape structure later.
- **Commercial opportunity:** where conversion occurs across the three stages, and why.
- **Fast wins:** keywords where weak competitors rank, prioritised by speed.

---

## STEP 3 — SERP BATTLEFIELD AND COMPETITIVE DISPLACEMENT

> Skill hooks: content-gap-scanner and serp-feature-tracker, if installed.

Fetch the live top-ranking pages (Rule 2). For each: purpose, audience, strengths, weaknesses, missing intent, missing entities, missing depth, missing use cases, missing conversion paths, missing AEO and GEO readiness.

Inline gap method if no skill: pull each top competitor's best pages and the keywords they rank for that this domain does not. Score each gap by traffic opportunity against ranking difficulty. List the gaps worth closing.

Inline feature method if no skill: for the target keyword set, record which SERP features appear and which competitor owns each. A feature owned by a weak page is a takeover target.

Name the single largest gap in each of: market, trust, authority, content, depth, conversion, intelligence.

Identify the most vulnerable competitor, the highest-value competitor, and the most difficult competitor, with reasons. Output one specific displacement move: which competitor we outrank first, and the exact action that does it.

Build the gap table:

| Competitor | Coverage | Weakness | Missing topics | Missing questions | Missing use cases | Our opportunity |
|---|---|---|---|---|---|---|

---

## STEP 4 — PEOPLE ALSO ASK (LIVE)

Collect real PAA questions from the live SERP. Do not invent questions. Map each to an H2, H3 or FAQ. Note which questions show AI Overview or snippet capture potential.

---

## STEP 5 — ENTITY AND TOPICAL AUTHORITY MAP

Build the semantic entity map, grouped sensibly for `DOMAIN_AUTHORITY_AREAS`. Use groupings such as: regulations, regulators, standards, frameworks, organisations, core concepts, risk concepts, technology concepts, vendors, related services, adjacent topics. Adapt the groups to the actual domain, do not force compliance labels onto an unrelated topic.

Identify the entities competitors ignore, and the high-value entities AI systems associate with this topic.

---

## OUTPUT AND STOP

Output, in order: Pre-Flight decision, Phase 0, Steps 1 to 5. Then write:

`RESEARCH COMPLETE. Save this output and pass it to 02-strategy.md.`

Do not write the article. Do not generate HTML, code or CTA copy. Do not start strategy. STOP.

# SEO, GEO, AEO and SXO Principles and Ranking Parameters based Content Writing Engine
by AVIK BAL, author of the book "CITED: The Growth Operating System for AI Search" and publications on "CITED Framework".

A research-first prompt system that produces verified, citation-ready SEO content briefs.

It thinks before it writes. It never invents a number. It runs on a clean install with zero dependencies. Fill one file, run four steps, get an auditable brief.

---

## Quick start

1. Open `brand-config.md` and fill it in. This is the only file you edit. Every brand fact, author detail, and styling rule lives here.
2. For a pillar page, run `01-research.md`, then `02-strategy.md`, then `03-execution-brief.md`, then `04-quality-gate.md`. Save each output and feed it to the next.
3. For a smaller supporting page, run `lite-path.md` once.

That is the whole loop. The engine pulls live SERPs, finds the gap your competitors left open, and hands back a build spec. It stops before writing the article, so nothing ships until you approve it.

## Why it works

Most AI SEO prompts fail in two predictable ways. They invent search volumes and competitor stats from memory. And they cram research, strategy, and writing into one tired pass.

This engine fixes both.

Every metric comes from a live source or gets marked "No data returned." No guessing. The work splits into stages, so each one runs with full attention instead of trailing off at the end.

## What is inside

```
README.md             you are here
LICENSE               MIT
brand-config.md       the only file you edit per client
glossary.md           every term, tier, and the depth model defined once
01-research.md        Pre-Flight gate, Phase 0, Steps 1-5. gathers verified truth
02-strategy.md        Steps 6-10. turns research into decisions
03-execution-brief.md Steps 11-16. produces the one-page build spec
04-quality-gate.md    Step 17 plus the brand-system handoff
lite-path.md          condensed single-pass run for cluster pages
```

## Zero dependency

Every step carries its own inline instructions. Where you see a "Skill hook," an installed skill will speed that step up, but the prompt is complete without it. Install nothing and the engine still runs end to end.

## Universal by design

No brand, domain, or subject is hardcoded. The engine reads `DOMAIN_AUTHORITY_AREAS` from your config and shapes its entity maps, citation sources, and relevance checks around that territory. Swap the config and the same engine serves a different company.

## Best practices it enforces

- One source of truth for brand facts. Edit them in `brand-config.md` only.
- Fetch before you assert. No competitor, feature, or number described from memory.
- Fail loud. Missing data is written as a gap, never guessed.
- State passing over memory. Each stage saves an output the next stage reads.
- Stop discipline. Each stage ends with an explicit STOP, so the article never gets written early.
- Pin the date on every data pull, since search data decays.
- Validate inputs first. A stage refuses to run if the config is missing.

## How to run it well

Run each pillar stage in its own conversation. Clean context keeps the model sharp and stops the quality gate from inheriting a tired thread. Paste the previous stage's saved output at the top of the next run.

---

## About the author

**Avik Bal** builds data-first growth systems for the age of AI search.

He is the author of *CITED: The Growth Operating System for AI Search*, a working handbook on how businesses get found, trusted, and chosen when machines answer the questions. He also published the companion research paper that introduces the CITED framework.

The framework runs on five layers, in order: Citation Surface, Information Architecture, Technical Foundation, Evidence-Rich Extraction, and Demand Capture, powered by the Citation Flywheel. This engine is that framework turned into something you can run today.

His work sits at the intersection of SEO, GEO, AEO, and SXO, always tied to real data and real pipeline rather than vanity metrics.

- Book: *CITED: The Growth Operating System for the Age of AI Search*
- Research paper: the CITED framework, conceptual-framework format
- More tools: the Growth Operating System suite

*Add your book link, paper DOI, and profile links here before publishing.*

## License

MIT. Use it, change it, ship it. A credit back is appreciated, not required.

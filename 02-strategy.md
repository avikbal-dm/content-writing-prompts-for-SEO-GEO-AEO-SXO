# 02 — STRATEGY ENGINE

Version 1.0. Stage 2 of 4 for PILLAR pages.

Input required: the research output from `01-research.md`. If it is not present, stop and request it. This stage turns verified research into decisions. It does not write the article.

Pull brand values from `brand-config.md`. Same global rules as Stage 1: fetch-first, no fabricated numbers, no-data fallback, skills optional.

---

## STEP 6 — REVENUE AND CONVERSION ARCHITECTURE

Determine the revenue opportunities the page can carry: service, assessment, checklist, framework, whitepaper, lead magnet, consultation. Use the `SERVICE_OFFERINGS`, `LEAD_MAGNETS` and CTA values from brand-config. Do not invent offers the brand does not have.

Map the conversion architecture: primary CTA, secondary CTA, micro-conversion, lead magnet, assessment, whitepaper, consultation. Tie each to Awareness, Consideration or Decision. Describe the natural conversion journey a reader follows down the page.

---

## STEP 7 — LINKABILITY AND PROPRIETARY IP

> Skill hook: an image-brief or image-SEO skill, if installed, for any linkable visual.

Identify the statistics, frameworks, checklists, definitions and visual assets most likely to earn links.

Design at least one proprietary asset built for backlink acquisition, drawn from: a framework, checklist, scoring model, maturity model, assessment model or roadmap. The page must contribute original thinking, not summarise existing content. State what the asset is, what it does for the reader, and why another site would link to it.

Inline visual spec if no skill: for each linkable visual, state its purpose, the data or concept it shows, a draft alt text, and a one-line note on whether it needs custom creation or can be built from existing data. A genuinely original diagram or model earns more links than a stock image.

---

## STEP 8 — CITATION STRATEGY

> Skill hook: a citation skill, if installed.

Identify every claim, statistic and regulation that needs a citation. Recommend the most credible source for each: regulators, primary law, named industry bodies, peer-reviewed work. Prefer primary sources over secondary commentary.

Flag the sources most likely to raise AI citation probability. Where the topic touches regulation or standards, cite the governing body or primary text by name, drawn from `DOMAIN_AUTHORITY_AREAS`. Do not cite a source you have not verified exists.

---

## STEP 9 — E-E-A-T REQUIREMENTS (HARDWIRED)

Mandatory. No brief is complete without this. State explicitly:

- **Named author**, role and credentials, from brand-config.
- **The first-hand experience claim** this page can legitimately make, from `EXPERIENCE_BASIS`. What has this brand done, seen or measured that a generalist cannot claim?
- **Reviewer or SME sign-off**, if any, with credential.
- **Trust signals on the page:** author bio, credentials, sourced data, last-updated date, organisation schema.
- **Person and Author schema requirements**, handed to Step 12.

If `EXPERIENCE_BASIS` is NONE, flag the page as low-experience and recommend how to add a legitimate experience signal before publishing. Do not fabricate expertise.

---

## STEP 10 — TOPICAL AUTHORITY ROADMAP AND INTERNAL LINKING

> Skill hooks: a clustering skill and a content-velocity scorer, if installed.

Design the hub-and-spoke architecture: the pillar page, supporting cluster pages, comparison pages, checklist pages, glossary pages, whitepapers.

Build the internal linking map using the real existing URLs pulled in Pre-Flight, plus planned URLs clearly flagged as planned. Respect the linking floor in `glossary.md`.

Inline publishing order if no scorer skill: rank the planned pages by speed to results. Score each on keyword difficulty, presence of AEO triggers, SERP features owned by weak competitors, current topical authority, and schema readiness. Publish the fastest-to-rank pages first to build early authority. Output the recommended sequence.

---

## OUTPUT AND STOP

Output Steps 6 to 10. Then write:

`STRATEGY COMPLETE. Save this output and pass both research and strategy to 03-execution-brief.md.`

Do not write the article. Do not generate HTML, code or CTA copy. STOP.

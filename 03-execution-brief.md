# 03 — EXECUTION BRIEF ENGINE

Version 1.0. Stage 3 of 4 for PILLAR pages.

Inputs required: the research output (01) and the strategy output (02). If either is missing, stop and request it. This stage produces the build specification. It still does not write the article.

Pull brand values from `brand-config.md`. Same global rules apply.

---

## STEP 11 — EXECUTIVE CONSUMPTION AND CONTENT ARCHITECTURE

> Skill hook: an image-brief generator, if installed, for slot-by-slot image specs and ImageObject schema.

**Executive consumption.** State what a reader must learn at three reading depths: 90 seconds, 3 minutes, 7 minutes. For each depth, name which summary block, table, framework or checklist delivers it.

**Content architecture.** Build the ideal structure. Set the target word count from competitive depth, intent coverage and topic complexity, against the depth model in `glossary.md`. Never inflate. For each section state: objective, word count, intent, primary keyword, secondary keyword, entity targets, snippet opportunity, AI Overview opportunity, CTA opportunity.

**Format to deliver:** H1, answer capsule, H2s, H3s, FAQs, CTA placements, image slots.

Inline image spec if no skill: for each image slot, give purpose, placement, recommended visual style, dimensions, a draft alt text, and a note on whether it needs custom creation. Technical topics need real diagrams, not decoration. Pages with relevant images earn more AI Overview selection.

---

## STEP 12 — SCHEMA STRATEGY

> Skill hook: a schema skill, if installed.

Recommend only schemas with strategic value: Article, FAQPage, BreadcrumbList, Organization, Person, Author, Service, HowTo, DefinedTerm, ItemList, WebPage. For each chosen schema, state why it matters and which SERP feature it supports.

Note the injection rule from brand-config: schema is injected via `SCHEMA_INJECTION`, outside the post body, so `SEO_PLUGIN` cannot strip it. Hand the Person and Author requirements down from Step 9.

---

## STEP 13 — AI OVERVIEW AND GEO CAPTURE

> Skill hooks: a GEO skill and an llms.txt manager, if installed.

Identify the featured snippet, AI Overview, definition, comparison, FAQ, checklist, table and answer-capsule opportunities for this page.

Answer one question directly: which single structural element most increases AI citation probability for this page, and where does it sit. Usually this is the answer capsule or a clean definition block placed high on the page.

Inline llms.txt note if no skill: after publish, add the new URL to the site's llms.txt so AI crawlers can discover it. Flag this as a post-publish task.

---

## STEP 14 — STRATEGIC POSITIONING STATEMENT

Max 80 words. Why this page exists, who it serves, the unique angle it owns, what the reader should do next.

---

## STEP 15 — BASELINE CAPTURE (MEASUREMENT LOOP)

Record the starting state so success can be measured after publish:

- Current ranking position for the primary keyword, or "not ranking."
- Current impressions and clicks if the URL exists, via Search Console (resolve the property or project ID first).
- Current top competing URLs and their domain rating.

Store this as the pre-publish baseline. Without a baseline, the page cannot prove it worked.

---

## STEP 16 — ONE-PAGE EXECUTION BRIEF (PRIMARY DELIVERABLE)

Copy-paste-ready executive brief. Include every field:

Primary keyword. Search intent. Strategic positioning. Cannibalisation decision (new, consolidate, rewrite). Target word count. Secondary keywords. Topical authority angle. ICP summary. Decision intelligence summary. Named author plus experience claim. Required sections. Required entities. Required FAQs. Schema stack. Internal linking targets (real URLs). Cluster strategy. Revenue strategy. Conversion strategy. Competitive displacement move. Baseline metrics. Success metrics.

Conclude with one line: **"The single thing this page must do better than every competitor."**

---

## OUTPUT AND STOP

Output Steps 11 to 16. Then write:

`BRIEF COMPLETE. Pass the full brief to 04-quality-gate.md before any writing run.`

Do not write the article. Do not generate HTML, code or CTA copy. STOP.

# LITE PATH — SUPPORTING CLUSTER PAGES

Version 1.0. Single pass. Use this for CLUSTER pages only. Same brand and quality standards as the full engine, proportionate effort. Pillar pages use files 01 through 04 instead.

Pull brand values from `brand-config.md`. Apply the same global rules: fetch-first, no fabricated numbers, no-data fallback, skills optional. Definitions live in `glossary.md`.

## INPUTS

```
TOPIC:        [the topic]
TIER:         CLUSTER
TARGET_URL:   [existing URL] or NEW
PARENT_PILLAR: [the pillar this page supports, real URL]
```

Run all steps below in one pass, then STOP. Do not write the article.

---

### 1. Cannibalisation gate
Pull existing `DOMAIN` rankings for the keyword and close variants. Decide NEW, CONSOLIDATE or REWRITE, justified in two lines. Map real internal-link targets.

### 2. Page existence test
Max 150 words. Why should this page exist, what gap does it fill, what angle does it own that the top results do not. No defensible angle means stop.

### 3. ICP and decision (condensed)
Primary ICP only: role, pain points, the decision they are making, the objection that delays it, the proof that removes it.

### 4. Market signal (live data)
Primary keyword plus up to three secondaries: volume, difficulty, intent. Fetch the live SERP and note which features appear (AI Overview, snippet, PAA).

### 5. SERP snapshot (condensed)
Fetch the top three live results. Name one clear gap they share, and one displacement move this page makes.

### 6. People Also Ask
Collect real PAA questions from the live SERP. Map each to an H2 or FAQ. Do not invent questions.

### 7. Conversion (condensed)
One primary CTA and one lead magnet, drawn from brand-config, tied to the reader's journey stage.

### 8. Citations (condensed)
Identify the must-cite claims and stats only. Name a credible, verified source for each.

### 9. E-E-A-T (mandatory)
Named author, role, credentials. The legitimate experience claim from `EXPERIENCE_BASIS`. If NONE, flag it. Trust signals to place on the page.

### 10. Internal linking
Three to eight contextual links to real existing URLs, including one link up to `PARENT_PILLAR`.

### 11. Architecture (condensed)
H1. Answer capsule (40 to 60 words, quotable). H2 outline. FAQ block. One image slot with a draft alt text.

### 12. Schema
Choose from Article, FAQPage, BreadcrumbList, Author. State why each, and note schema injects via `SCHEMA_INJECTION`, not the post body.

### 13. AI capture (condensed)
Confirm the answer capsule and the FAQ are built to be extracted and cited. Name the one block most likely to win an AI citation.

### 14. Positioning statement
Max 60 words. Why this page exists, who it serves, the angle it owns, the next action.

### 15. Baseline capture
Current ranking for the primary keyword, or "not ranking." Impressions and clicks if the URL exists. Store as pre-publish baseline.

### 16. One-page brief
Primary keyword. Intent. Positioning. Cannibalisation decision. Target word count. Secondaries. ICP summary. Author plus experience claim. Required sections. Required FAQs. Schema stack. Internal links (real URLs). CTA. Displacement move. Baseline. Success metrics. End with: "The single thing this page must do better than every competitor."

### 17. Quality gate (condensed)
Check: intent match, unique angle, data integrity, E-E-A-T, citation readiness, internal links exist, answer capsule present, gaps marked honestly. Report PASS or FAIL with one-line reasons. Fix and re-run if anything fails.

---

## OUTPUT AND STOP

Output steps 1 to 17, then write:

`LITE BRIEF COMPLETE. Approved for writing applies the Brand-System Handoff in 04-quality-gate.md.`

Do not write the article. Do not generate HTML, code or CTA copy. STOP.

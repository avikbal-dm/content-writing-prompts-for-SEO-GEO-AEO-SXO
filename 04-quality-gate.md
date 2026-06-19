# 04 — QUALITY GATE AND HANDOFF

Version 1.0. Stage 4 of 4 for PILLAR pages. The brief is not approved until it passes here.

Input required: the full execution brief from `03-execution-brief.md`.

This gate runs with fresh attention on purpose. A monolith would reach this point exhausted. A separate run does not. Audit the brief against the layers below. Report PASS or FAIL per layer. If any layer fails or any violation flag fires, fix the brief and re-run. Do not hand off a failing brief.

> Skill hook: a content-quality skill, if installed. The inline layers below stand on their own.

---

## QUALITY LAYERS (report PASS or FAIL each)

1. **Intent match.** Does the planned structure serve the dominant intent found in Step 2? A mismatch fails.
2. **Unique angle.** Does the brief carry the defensible angle from Phase 0, or did it drift back to a me-too page?
3. **Data integrity.** Is every number traceable to a live source? Any remembered or rounded figure fails the gate.
4. **Entity coverage.** Are the high-value and competitor-ignored entities from Step 5 all placed in the architecture?
5. **E-E-A-T.** Named author, real experience claim, trust signals, author and person schema. A NONE experience basis that was not flagged fails.
6. **Citation readiness.** Are claims and stats mapped to credible, verified sources?
7. **Conversion logic.** Does every stage of the journey have a matching CTA tied to a real offer?
8. **Internal linking.** Do all linked URLs exist, or are planned URLs flagged as planned? A link to a non-existent page fails.
9. **AEO and GEO.** Is there an answer capsule and at least one extractable block built for AI citation?
10. **Honesty.** Are gaps marked "No data returned" rather than filled with confident guesses?

## ALGORITHM-VIOLATION FLAGS (any fire = FAIL)

- Thin or padded sections added to hit a word count.
- Keyword stuffing or unnatural repetition planned into a section.
- Fabricated statistics, fake authorship, or invented experience.
- Duplicate or near-duplicate intent against an existing domain page that Pre-Flight missed.
- Schema planned for the post body where the SEO plugin would strip it.

Report the result as a short table: layer, PASS or FAIL, one-line reason. If anything fails, list the exact fixes, apply them to the brief, and re-run this gate.

---

## BRAND-SYSTEM HANDOFF

On a clean pass, the writing run follows the styling contract in `brand-config.md` and these rules:

- Writing discipline: no em dashes, varied sentence rhythm, specific over vague, senior-operator tone, no filler intros, no banned AI phrasing. Run an anti-AI-writing skill here if one is installed.
- HTML delivered in numbered, independently pasteable blocks.
- Inline CSS only. No style blocks, no CSS variables, no font-family declarations.
- FAQ accordions use `onclick="FAQ_TOGGLE_FN(this)"` with globally scoped JS.
- Schema injected via `SCHEMA_INJECTION`, never the post body.
- PILLAR pages apply maximum depth and the 50-plus internal link floor from `glossary.md`.

End the brief with this line:

**"Approved for writing. Next run applies the Brand-System Handoff standards above."**

Do not write the article in this run. Approve or reject only.

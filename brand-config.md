# BRAND CONFIG

This is the only file you edit per client. The engine reads these values. Nothing brand-specific lives anywhere else in the repository. Fill every field before running. If a field does not apply, write `N/A`, never leave it blank.

Paste this block at the top of every engine run (or reference it if your tool supports file context).

---

## IDENTITY

```
BRAND:                 [Company name]
DOMAIN:                [root domain, e.g. example.com]
PRIMARY_MARKET:        [e.g. United States]
SECONDARY_MARKETS:     [e.g. United Kingdom, European Union]
DOMAIN_AUTHORITY_AREAS: [the topical territory this brand can legitimately own,
                         e.g. "vendor risk, due diligence, financial crime, compliance".
                         This replaces any hardcoded subject matter. The engine uses it
                         to judge relevance, entity coverage and citation sources.]
```

## AUTHOR AND TRUST (drives E-E-A-T, Step 9)

```
NAMED_AUTHOR:          [Name]
AUTHOR_ROLE:           [Title / function]
AUTHOR_CREDENTIALS:    [Qualifications, years, relevant proof]
REVIEWER_SME:          [Name + credential, or N/A]
EXPERIENCE_BASIS:      [What this brand has actually done, seen or measured that a
                        generalist cannot claim. One honest sentence. If none exists, write
                        NONE and the engine will flag the page as low-experience.]
```

## COMMERCIAL (drives Step 6)

```
PRIMARY_CTA:           [e.g. Book a demo, Request an assessment]
SECONDARY_CTA:         [e.g. Download the framework]
LEAD_MAGNETS:          [checklists, whitepapers, assessments you can offer]
SERVICE_OFFERINGS:     [the paid services a page can route toward]
```

## PUBLISHING STACK (drives Step 12 schema and the handoff)

```
CMS:                   [e.g. WordPress]
SEO_PLUGIN:            [the on-page plugin that may strip raw schema from the body,
                        e.g. a SEO plugin. The engine assumes schema must be injected
                        OUTSIDE the post body to survive this plugin.]
SCHEMA_INJECTION:      [the method that injects schema outside the body,
                        e.g. a code-snippet plugin or a header/footer injector]
FAQ_TOGGLE_FN:         [the global JS function name your theme uses for FAQ accordions,
                        e.g. faqToggle. Used as onclick="FAQ_TOGGLE_FN(this)".]
```

## STYLING CONTRACT (referenced at handoff, not changed per client)

The writing run must follow these rules. They are deliberately generic so any brand can adopt them.

```
- HTML delivered in numbered, independently pasteable blocks.
- Inline CSS only. No <style> blocks. No CSS variables. No font-family declarations.
- FAQ accordions use onclick="FAQ_TOGGLE_FN(this)" with globally scoped JS.
- Schema injected via SCHEMA_INJECTION, never pasted into the post body.
- Writing discipline: no em dashes, varied sentence rhythm, specific over vague,
  senior-operator tone, no filler intros, no banned AI phrasing.
```

## DATA SOURCES AVAILABLE (the engine checks these before asserting numbers)

```
KEYWORD_AND_SERP_DATA: [e.g. Ahrefs MCP, or another live source]
SEARCH_CONSOLE:        [connected? project/property ID if known]
ANALYTICS:             [e.g. GA4]
NOTES:                 [anything the engine should know about data access]
```

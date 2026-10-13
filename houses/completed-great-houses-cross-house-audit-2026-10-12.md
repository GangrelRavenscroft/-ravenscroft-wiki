# Cross-House Audit — Six Developed Great Houses

**Date:** 2026-10-12  
**Scope:** [Wycliffe](wycliffe.html), [Falkenrath](falkenrath.html), [Volkov](volkov.html), [Veyrholm](veyrholm.html), [Valdieri](valdieri.html), and [de Villiers](de-villiers.html).  
**Standard:** [User-locked Great House Page Standard](../standards/HOUSE_PAGE_STANDARD.md), particularly the October 11 Tier B policy.  
**Method:** Read-only repository-wide Git tree comparison (493 entries), six live House HTML pages, all image paths and site navigation targets, section/heading structure, and approved visual-canon documentation. Corrections listed below committed without changing approved portraits/heraldry. This is **source/structural QA, not an actual browser screenshot or pixel-level comparison**.

## Overall verdict

**Information parity — substantially present, but not identically organized. Technical image/link integrity — passed. Visual package parity — five missing assets. Page layout parity — partial.** The existing six House pages contain House identity, qualification, historical development, geography and influence, Head and ruling family, governance and succession, institutions or resources, House relationships and Order position, and locked/open-canon records. Some subjects are *within* other sections rather than having shared chapter headings.

Six House pages have working relative image references, nonempty image alt text, and local navigation/file links. The old Wycliffe and Falkenrath `#top` fragment anchors were fixed, Volkov's approved full heraldry added to its masthead, and Wycliffe's contradictory “estate name/county open” visual caption corrected to its existing approved Northmere Hall/Buckinghamshire identity.

## Seven-element illustrated Great-House standard

| House | Full arms | Simplified matched seal | Head / immediate family | Ancestral seat | Admin seat | Influence map | Defining historic/institution scene | Distinct images on page | Assets satisfied |
|---|---|---|---|---|---|---|---|---:|---:|
| Wycliffe | Yes | **Missing** | Yes | Northmere Hall | Wycliffe House, London | Yes | Postwar strategy | 12 | **6/7** |
| Falkenrath | Yes | **Missing** | Yes | Schloss Falkenrath | Falkenrath Haus, Vienna | Yes | 1957 Restoration | 12 | **6/7** |
| Volkov | Yes | **Missing** | Yes | Vovchyn Castle | Volkov House, Warsaw | Yes | 1917–21 / 1953 scenes | 27 | **6/7** |
| Veyrholm | Yes | **Missing** | Yes | Veyrholm Keep | Veyrholm House, Stockholm | **Missing** | Viking origins / Ingrid succession | 27 | **5/7** |
| Valdieri | Yes | Yes | Yes | Rocca delle Fonti | Palazzo Valdieri, Milan | Yes | Post-civil-war archives | 52 | **7/7** |
| de Villiers | Yes | Yes | Yes | Château de Montrevaux | Hôtel de Villiers, Paris | Yes | Engineering heritage / reconstruction | 36 | **7/7** |

**Definite art gaps:** four separate *matching simplified heraldic seals* (Wycliffe, Falkenrath, Volkov, Veyrholm), plus a dedicated **Veyrholm influence map**. Full arms cannot simply be relabeled as simplified arms; each new image needs separate generation, review and explicit user approval. An influence map must distinguish core, deep, overlapping and legacy links, not claim state sovereignty. No missing art was fabricated by this audit.

## Content and canonical completeness

| Shared information area | Audit finding |
|---|---|
| 2026 House identity and distinguishing specialty | Present in all six |
| Modern Head, heir, senior household, professional role | Present in all six; number of named relatives varies, appropriately |
| Historical chronology, distinct constitutional seat and institutional center | Present in all six |
| Geography and House network influence | Present in text in all six; dedicated map artwork missing only for Veyrholm |
| Institutional power, economics and finance | Present. De Villiers House-scale fortune deliberately **unassigned**, not a forgotten agreed amount |
| Governance, succession, Order status, relationships | Present across all; **Volkov and Veyrholm** need standalone Order/inter-House summary headings for parity |
| Major/cadet/Lesser network | Established branch/network details present; rank and Lesser House coverage vary by approved canon. Do **not** invent ranks, Houses or descendants to make tables equally long |
| Strengths and weaknesses | Described in all; only some have uniform dedicated section |
| Apparent ages versus chronological ages | Chronological ages generally present; **explicit person-by-person apparent-age fields not uniform**. Do not assign new apparent ages without approval |
| House visual canon and locked/open decisions | Present throughout; Volkov's artwork is integrated rather than gathered in a dedicated chapter; Veyrholm has Batch 2/3 galleries rather than a standardized Visual Canon index |

**Historical/financial editorial caution:** Wycliffe and Falkenrath each visibly preserve older finance ranges labeled *superseded* after their current House-scale ranges. An archive can preserve these records, but an ordinary current-status summary should show **only the latest locked values** and place superseded numbers in a clearly historical note. Veyrholm has nine `assets/houses/veyrholm/batch1/temp-*.png` files unused by its live page; they may be historical/staging copies—**do not delete** without approval and a SHA/provenance comparison.

## Layout and interaction comparison

| House | Masthead/crumb/nav | Jump navigation | Quick-facts and visual treatment | Layout issue |
|---|---|---|---|---|
| Wycliffe | Shared site style | Standard 12-chapter nav | Cards, section numbers, gallery | Back-to-Top fragment fixed; needs simplified seal |
| Falkenrath | Shared site style | Standard 11-chapter nav | Cards, numbered history, gallery | Back-to-Top fragment fixed; needs simplified seal |
| Volkov | Shared; approved crest now installed | Standard but different chapter order | Family/estate art integrated | Needs separate Order/relations/visual gallery index |
| Veyrholm | Shared; custom sea-eagle masthead | Standard with custom batch headings | Separate Batch 2 / Batch 3 galleries | Missing map and separate Order/relations and Visual Canon summary |
| Valdieri | Shared; simplified crest masthead | Section plus dense subgallery links | Very extensive image-first presentation | Large/long page, special nested galleries; preserve |
| de Villiers | Shared main site | Custom `dv-jumps` | Burgundy/gold cards, six image batches | Different jump-nav classes / bottom structure; harmonize wrapper only |

**Canonical wrapper recommended for all six**, without changing approved art or inventing data:

1. Masthead with simplified shield, site nav, breadcrumb and common House jump index.
2. Identity hero with full arms, followed by six 2026 quick facts (Head, heir, seat, administrative center, specialty, Conclave/Nine status).
3. Identity/qualification; history; geographic reach/map; institutions and separately accounted resources.
4. Ranked subordinate/cadet directory where ratified; Order/Conclave; inter-House relations; governance.
5. Immediate senior family with *approved* apparent-age labels, strengths/risks, standardized image gallery, locked/open/superseded canon register.
6. Shared bottom navigation including functioning Back to Top.

Other Houses may keep extra distinctive subchapters; a shared hierarchy is **not** a demand for identical wordcounts, family sizes, portraits or financial figures.

## Fixes applied safely in this audit

- **Wycliffe:** repaired `#top` target and corrected an obsolete “estate/county unknown” caption to Northmere Hall, Buckinghamshire, established elsewhere on the same page.
- **Falkenrath:** repaired `#top` target.
- **Volkov:** used the **existing approved full heraldic achievement** in its masthead.
- **No image regenerated or reassigned**, no person renamed, no Great House Office/Council mandate invented, no old art deleted.

## Next work, prioritized

**P1:** Create/approve the 4 simplified matching heraldic seals and Veyrholm map, then add them to galleries and use simplified shields in mastheads.  
**P1:** Make Volkov/Veyrholm's Order, relations, Visual Canon status easy to find with common anchored summary sections using only their pre-existing text.  
**P2:** Unify quick-fact presentation, navigation and visual-gallery wrapper for all six, while retaining House-specific styles and protected faces.  
**P2:** Audit/label chronological versus apparent ages at the **person level**; show “unassigned” if no approved apparent age exists.  
**P3:** Review old redundant assets and superseded financial snippets, plus actual browser/mobile/tablet UI after structural edits.

## Scope exclusions

**[Ravenscroft](ravenscroft.html)** is the ongoing **Tier A** dynasty, **not** a completed Tier B peer; its public House landing page is presently shorter than these six while much canonical depth lives in linked personal/family/Order pages. It merits its own deep consolidation audit rather than forced short-template compliance. The recognized peers **Amaru, Ashcroft, Shen and Kuroda** do not yet have completed peer dossiers and were **not** counted as finished.

**Conclusion:** The six are *broadly complete in information*. They are **not yet uniform in design or full visual package**. Fix the five approved-art gaps and navigation/section parity before calling them identical.

[House Directory](index.html) · [Standards](../standards/HOUSE_PAGE_STANDARD.md) · [Project Handoff](../PROJECT_HANDOFF.md).

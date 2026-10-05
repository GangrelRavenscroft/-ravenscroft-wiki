# House Ravenscroft — Person Dossier Standard

**Standard version:** 1.0  
**Master A benchmark:** Isabella Genevieve Ravenscroft  
**Master B benchmark:** Dr. Emilia Sofia de Aranda Ravenscroft

This file is the authoritative construction standard for all House Ravenscroft person dossiers on the wiki.

## Core rule

Every person dossier uses the same information architecture and shared visual language. Individual sections may say "None", "Not applicable", or "Not yet established", but required sections are not silently omitted.

All person dossier pages must use the shared site stylesheet and the same major section order unless later canon explicitly revises this standard.

## Dossier types

### Master A — Ravenscroft blood family
Use for blood members of House Ravenscroft.

### Master B — Married-in / patroned spouse
Use for spouses and patroned outsiders incorporated into the House system. Master B includes an additional **Original Patron / Patronage History** block.

## Locked section order

1. Header / classification
2. Hero portrait + primary identity facts
3. Status rail
4. Current-status snapshot
5. Age progression
6. Family & household
7. Education & formation
8. Training & core formation
9. Career chronology
10. Appearance & presentation
11. Career & major roles
12. Notable professional projects
13. Professional affiliations & credentials
14. Behavioral assessment
15. Relationship history
16. Order status, access & authority
17. Patronage
18. Wealth & resources
19. Institutional footprint
20. Residences & estate/property
21. Languages
22. Current priorities
23. Interests & personal life
24. Canon control & continuity
25. Personal philosophy / closing quote, when established

Master B inserts **Original Patron / Patronage History** after Family & Household and before Education & Formation.

## Required identity fields

**Imperial-only physical measurements:** use feet/inches and pounds where applicable. Do not display metric conversions on dossier pages.

- Full name
- Canon status
- Dossier type
- House / bloodline status
- Birth date
- Chronological age for current canon year
- Apparent age
- Birthplace
- Nationality
- Height — imperial only
- Build
- Hair
- Eyes
- Current role / occupation
- Primary field
- Primary residence
- Secondary residence when applicable
- Marital status
- Spouse
- Children block, even when empty

## Required Order fields

Keep these separate. Never collapse them into one rank.

- Blood status
- Order membership
- Initial induction date/status
- Deeper induction date/status
- Full induction date/status
- Knowledge level
- Security clearance
- Compartment access
- Operational authority
- Lethal / paramilitary authority
- Core competencies
- Operational scope

Blood status, membership, knowledge, clearance, compartment access, patronage influence, wealth, and command authority are distinct categories.

## Required education / career fields

- Actual degree title, not vague "studied X" language
- Institution
- Attendance / completion dates
- Graduate or professional education
- House / Order formation
- Professional training
- Career chronology
- Current role
- Named major roles
- Selected notable projects where established
- Professional affiliations / credentials
- Institutional footprint
- Current priorities

## Required relationship fields

- Birthdate and current age must be shown together for spouse/partners and children when known.

- Spouse / partner identity
- Marriage date or relationship status
- Children block
- Relationship chronology when established
- Order knowledge/exposure boundary for married-in partners
- Master B only: Original Patron / Patronage History

## Required wealth / patronage fields

- Personal net worth
- Trust / family interests
- Household net worth
- Distinguish personal assets from House access
- Active patronage count or scope
- Legacy patronage where applicable
- Patronage sectors
- Patronage style / resources leveraged

## Required behavioral fields

- Core temperament
- Social style
- Leadership style
- Conflict style
- Risk tolerance
- Core values
- Strengths
- Operational risks / blind spots
- Ravenscroft repertoire applicability where relevant

## Required visual continuity fields

- Approved face status
- Apparent age
- Build
- Hair
- Eyes
- Presentation
- Age-progression image if available
- Spouse/partner image if available
- Career / residence / personal-life visuals as available

## Canon control rules

- Later explicitly locked canon supersedes older conflicting material.
- Do not invent missing facts merely to fill space unless the user explicitly asks to establish them.
- When creating new canon to fill a gap, lock it in both the rendered dossier and the structured JSON record.
- Every image is stored once under a semantic path; never keep duplicate UUID copies.
- Dossier pages use the shared House Ravenscroft crest system.
- Character dossier headers use the simplified House crest.
- The full heraldic crest is reserved for House-level pages and major House overview material.


## Archive and section navigation

Every rendered person dossier participates in the shared archive hierarchy.

### Global archive navigation
- The primary site navigation sits immediately below the dossier masthead.
- Global navigation is category-based rather than person-based: **Home, World, Houses, Families, People, Order, Places, Institutions**.
- Do not place individual dossier names in the global navigation. The archive will contain too many people for person-to-person navigation to scale.
- Individual people are reached through the **People directory**, **family/genealogy pages**, and contextual entity links inside dossiers.
- A breadcrumb appears below the global navigation to show the current record's archive context.
- Family/genealogy pages are the preferred browser for bloodlines, marriages, households, and branches.

### Dossier section navigation
Every rendered person dossier must include a section-jump navigator in the upper navigation zone and a duplicate navigator near the bottom.

- Every numbered dossier section must have a stable HTML anchor ID.
- The top section navigator appears below the global navigation/breadcrumb and **before the hero portrait and dossier content**.
- The bottom navigator appears after the final numbered dossier section and before the closing personal-philosophy / quote panel when present.
- Navigation labels should be concise while preserving the dossier section numbers.
- The bottom navigator includes a return-to-top link.
- Navigation must remain usable on mobile; horizontal scrolling is preferred over shrinking links into unreadably small text.
- Master A and Master B templates must include this structure so future dossiers inherit it automatically.

## Shared visual language

- dark navy / black background
- antique gold borders and dividers
- cream serif typography
- restrained heraldic ornament
- dense intelligence / dynastic dossier layout
- warm photographic canon images
- readable mobile stacking
- shared header, status rail, cards, timelines, project grids, and canon-control treatments

The goal is not merely visual similarity: every dossier should make the same categories of information easy to locate in the same place.


## Cross-linking rule

Whenever a named person, House, organization, estate/location, institution, event, or other entity already has its own wiki page, mentions of that entity should link to that page. Do not link to pages that do not yet exist. As new pages are created, backfill links into older dossiers during normal maintenance.


## Unit convention

- **Imperial-only height:** all person dossiers display height in feet/inches only (for example, 5'7"). Do not show metric height in rendered dossiers or structured person data unless a later project-wide standard explicitly changes this rule.

## Cross-linking convention

- Whenever a person, House, organization, institution, location, estate, project, or other entity already has its own live wiki entry, references to that entity should link back to its page.
- Family blocks, spouse blocks, children blocks, relationship histories, career sections, residences, and institutional sections all follow this rule.
- If an entity has not yet been migrated into the wiki, leave the reference as plain text and convert it to a link when that entry is created.
- Do not create dead or speculative links.

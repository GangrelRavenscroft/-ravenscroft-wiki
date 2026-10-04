# Creating a New Person Dossier

Use this workflow for every new person page.

1. Choose dossier type:
   - Master A = Ravenscroft blood family.
   - Master B = married-in / patroned spouse.
2. Copy the matching JSON template:
   - `templates/master-a-person.json`
   - `templates/master-b-person.json`
3. Fill every required field. If a field truly does not apply, record `None` / `Not applicable`; do not silently delete the category.
4. Copy the matching HTML template.
5. Populate sections in the locked order from `standards/PERSON_DOSSIER_STANDARD.md`.
6. Use the shared root `styles.css`; do not fork a character-specific stylesheet unless a later standard explicitly permits it.
7. Use the simplified Ravenscroft crest on person dossiers.
8. Store each image once at a semantic path under `assets/`. Never retain duplicate UUID upload copies.
9. Update the person's structured JSON whenever displayed canon changes.
10. Add canon-control notes for superseded or conflict-prone facts.
11. Verify desktop and mobile after GitHub Pages deploys.
12. If a new field or section is useful for all dossiers, update the standard and both templates rather than adding it to only one character.

## Consistency rule

Isabella Genevieve Ravenscroft's current live dossier is the visual/content benchmark for Master A pages. The template standard, not ad hoc copying, controls future pages.

Master B uses the same visual system but retains its required Original Patron / Patronage History section.

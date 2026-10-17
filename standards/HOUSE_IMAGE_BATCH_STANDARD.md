# Great House Image Batch Production Standard
**Approved working method:** 17 October 2026 · House Amaru Batch 3
**Status:** Production workflow standard only; not a change to individual House lore or visual canon.

## Authoring prompts
- Build an explicit batch manifest A–G (or the exact number of images requested), with stable **letter = subject** identity throughout.
- Write **detailed, standalone, fully specified image prompts**. Every subject gets its own setting, narrative purpose, composition, lighting, wardrobe where relevant, geographic and engineering realism, exclusions and canon limits.
- Distinguish confirmed visual identities and named relationships from proposed offices, institutions, facilities, property rights and historical claims. An illustration by itself does not ratify the latter.
- For any recurring identified person, request the **specific approved reference images**: controlling group portrait and latest approved solo portraits, with the correct subject designated. Preserve facial features, apparent age, family resemblance and differentiation from siblings.
- If the needed character references aren't in the image chat, request them before producing identity-sensitive scenes; avoid substituting approximate faces.
- Keep photorealistic landscape 4:3 editorial realism unless otherwise authorized. Vary angle, environment, clothing, lighting and posture across images; avoid repeated rooms or near-duplicate images.
- For architecture/infrastructure images without an identity reference, request **new generation** rather than an edit.

## Preferred generation — one request
- **Prefer one comprehensive prompt** asking GPT Image to produce **N separate full-resolution images**, one per manifest letter, **and one labeled A–G reference collage**, **when the generator actually supports distinct image outputs plus a collage in one request**.
- Include both constraints explicitly: individual files must each be standalone at high resolution (NOT cropped from a composite), with exactly one independent output per letter; the reference collage must be a **secondary derivative** of those output images and must not repaint, regenerate or reimagine subjects.
- Images that require face references should receive the specified approved photos as controlling image inputs for the corresponding panels.
- Inspect results for completeness: N independent originals plus one collage; no missing/duplicated subject, altered faces, or labels embedded on standalone images.
- **Fallback:** if output count or visual-identity fidelity fails (e.g., service produces only one image or conflates collage with originals), generate images individually with the same detailed prompts and make the labeled collage **afterwards** by arranging the original image files. Do not sacrifice output quality to force one-call batching.
- Do not promise that the image generator supports a particular count of images or native collages; actual capability may vary.

## Reference collage
- Build a landscape identification collage with original images resized only for placement, with clear large letters A, B, C, etc. outside the art; never redraw faces, crops or replace objects.
- Verify every intended image appears exactly once. For seven landscape 4:3 images, prefer 4 images on row 1 and 3 centered on row 2.
- The **collage letters refer to conceptual identity**, *not* upload filenames and not numeric GitHub review numbers.

## GitHub integration and approval
1. User uploads original full-resolution PNG files to the repository, usually initially under `assets/`.
2. Confirm actual new upload count and source Git blob SHAs before modifying files. Never infer the mapping from filename, commit sequence or subject guesses.
3. Create a responsive test page with **numbers 1–N** and direct links to each uploaded image at native resolution; labels/captions must not overlay photos, especially on iOS.
4. Ask the user to compare the test-page numbers to collage letters, replying `A#, B#, ...`.
5. Once a unique complete mapping is confirmed, move (do not regenerate/recompress) the original Git blobs to stable descriptive paths; keep a source-to-final mapping manifest, checksum record and project handoff.
6. Place approved images near corresponding dossier narratives as well as the visual archive. Give portraits prominent access; check both desktop and mobile responsiveness and image/caption flow.
7. Approval of an image identity does not automatically approve its proposed office, asset, legal ownership, territory, sacred artifact, or chronological age.

## Source
- House Amaru Batch 1 and Batch 2 approved mappings establish the test-page discipline.
- House Amaru Batch 3 established the preferred **very detailed independent prompts with explicit face reference attachments**, and the user's preference for one-call production *when feasible*, with a separate labeled reference collage.

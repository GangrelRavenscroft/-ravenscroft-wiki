# HOUSE RAVENSCROFT
## Strategic Atlas: Visual Style & Geographic Production Standard

**Document ID:** RAV-ATLAS-STD-001  
**Edition:** 1.0 — 15 October 2026  
**Status:** **VISUAL STANDARD APPROVED AND LOCKED** · Geographic influence scores **NOT** approved  
**Custodian:** Ravenscroft World Archive / World Building 3  
**Canonical reference artwork:** `APPROVED_ornate_europe_master_2026-10-15.png`  
**Reference image SHA-256:** `8d4eb296d9a7454e73c7f0ef34c5bcc9d289457a66857f13278d9598f752a7fe`

> **Core production rule:** Make the map accurate first, then make it beautiful. Never let decorative illustration replace verified coastline, political boundaries, or geographic coordinates.

**Approved image:** `APPROVED_ornate_europe_master_2026-10-15.png` is retained in the companion downloadable style-guide source package; the SHA-256 printed above verifies the correct artwork. GitHub's Markdown copy does not itself embed this binary image.

**Figure 1 — Approved visual reference.** This is the user-approved *illustrated* atlas image. It is the locked reference for composition, atmosphere, ornament, typography, legends and heraldic placement. It is **not a georeferenced GIS export** and must not be treated as surveyed geography. Some components in earlier AI-illustrated drafts contained inaccurate islands, borders or labels.

---

## 1. Approval boundaries and terminology

**Approved and locked:** Overall atlas visual identity; multi-part page composition; richly ornamented antique-gold/midnight-navy styling; large heraldic panels; elegant title cartouches and compass; legible cartographic center; five-level influence concept with distinct House colors; selective regional explanatory notes; inset presentation; the editorial mood of a classified aristocratic intelligence atlas.

**Still subject to approval:** Individual geographic influence ratings, particular House predominance or neutral regions, all contested overlap boundaries, numeric model weights, precise fictional institutional locations, wording of map-specific intelligence assessments, exact use of classified labels, and replacement of older official House maps. The existence of an approved *visual* template must never silently certify unapproved geographic decisions.

**Two different source artifacts must be tracked:** (A) the approved ornamental illustration supplied as the design master; and (B) the independent, editable GIS-based Europe revision (currently Revision 10) containing actual coordinate geometry. The target final artifact is a deliberate composite in which the **GIS defines the map's shape** and the **visual master defines its artistic framing**.

## 2. The house style at a glance

**Art direction:** A credible, expensive, privately commissioned strategic atlas plate from the hidden Order: old-money, editorial, restrained but visually rich. Not a cartoon fantasy map, dashboard, campaign poster, or a heavily distressed illegible antique.

**Composition:** Horizontal landscape. Prominent centralized geographic field; a left vertical gallery of individual House shields with short identities; a right structured reference rail for legend, inset and regional notes; centered gilded title above; footer or archival motto below. An inset can move only when required to keep the primary geography large enough to read.

**Color system:** The seas are near-black midnight navy; the field is illuminated by genuine terrain relief in stone, parchment and warm ivory; polished but weathered antique-gold frame, ornaments and rules; editorial text in ivory or pale gold; only thematic areas receive House-specific color overlays. Gradients should retain topographic detail beneath them. Avoid flat, saturated countries or muddy opaque fills.

**Decorative components:** Deep layered filigree border with elaborate corner scrolls, small engraved marks, calibrated compass rose, graticule where helpful, serif cartouche lettering, hand-engraved-looking dividers and small restrained motifs. Decoration must live outside geographic features or behind them; no ornament may invent an island, city, landmark or boundary.

**Page proportions:** For continental plates begin near a 3:2 landscape artboard; six House panels may occupy ~21–24% of usable width, main geography ~53–59%, and notes/inset ~20–24%, adjusted to maintain legibility. The *approved image* governs appearance over rigid percentages. Leave safe gutters between panels and avoid sacrificing the map to oversized ornament.

## 3. Mandatory graphic hierarchy and legibility

1. **Primary:** Map, title and territorial relationship pattern visible at a glance.
2. **Secondary:** Six House shields and names; country boundaries and legible names; thematic legend.
3. **Tertiary:** City labels, regional inset, short intelligence notes, status/scale/credits.
4. **Quaternary:** Fine scrollwork and decorative texture.

Use readable serif faces; EB Garamond or a comparable editorial serif is consistent with the GIS renderer. Embed or outline text for final print export when licensing allows, but **never distribute font files**. A condensed small-cap face may label sections; use ordinary readable serif for sentences. Avoid extreme letterspacing for body paragraphs.

**Editorial sizes:** On an approximately 1,536 × 1,024 px illustration, aim for body text perceptually equivalent to at least ~17–20 pixels when readable at full size; map labels and secondary text should avoid dropping below ~14–16 px. For a printed vector master, assess the actual physical point size rather than copying those pixel figures. If text will not fit, shorten it; do not keep shrinking it. Inspect the whole plate at 100% and at intended phone/print display size.

**Side-panel writing:** A short sphere descriptor plus about 25–45 words per House. Limit regional notes to 1–2 concise sentences. Do not duplicate identical lore across left and right rails. Every paragraph needs contrast against a dark opaque panel. Avoid using broad terms such as “controls Scandinavia” when canon only supports powerful regional networks.

## 4. Canon House colors and heraldry

| House | Identity color | Crest symbolism | Approved original GitHub path |
|---|---|---|---|
| Wycliffe | `#4C8A5A` green | Tower rising from ivory cliffs over sea | `assets/houses/wycliffe/crest-simplified.png` |
| Veyrholm | `#36A3BE` cyan | White sea eagle over Nordic waves | `assets/houses/veyrholm/crest-simplified.png` |
| de Villiers | `#C5A052` gold | Ivory fortified gatehouse and gold surveyor's dividers | `assets/houses/de-villiers/crest-simplified-seal.png` |
| Falkenrath | `#A94148` red | Crowned falcon and Alpine peaks | `assets/houses/falkenrath/crest-simplified.png` |
| Volkov | `#77509C` purple | Silver wolf, eight-pointed star, mountains and waves on navy | `assets/houses/volkov/crest-simplified.png` |
| Valdieri | `#C77A3B` orange | Star, three-arch bridge and water | `assets/houses/valdieri/crest-simplified-seal.png` |

**Never recolor a crest to equal the House's map hue unless the user explicitly approves a monochrome adaptation.** The heraldic shield and cartographic identity color are different concepts. The illustrated reference sometimes simplified or altered heraldic details; the **approved original GitHub asset always wins** if its appearance conflicts with an illustration.

Record asset path, original file SHA, approval date and usage role in the production manifest. Place shields consistently, preserve aspect ratio and adequate padding, avoid auto-removing cream/white elements mistaken for backgrounds. If original bytes cannot be obtained, mark heraldry **unverified** rather than generating a look-alike and calling it official.

## 5. Influence model and legend semantics

The atlas shows **aggregate effective institutional influence**, not public sovereignty, ownership of every company, control of every official, or a complete accounting of the Order's agents. A Great House acts through the senior House, subordinate Major and Lesser Houses, finance, supply chains, patrons, research, governance, political relationships, and covert intelligence networks. Near House cores, influence tends to be deeper and more redundant, but national and regional networks can provide a low-intensity background far from the major cities.

**Two independent visual dimensions:**

- **Hue identifies the House:** use the exact six colors listed above.
- **Lightness/saturation identifies strength *within that House's hue*:** use five distinguishable ordered shades (1–5), never a generic red/orange/green/blue spectrum for universal strength.

| Level | Meaning | Cartographic reading |
|---|---|---|
| 5 · Paramount | Exceptional core reach and institutional depth | Tightly concentrated main centers, not automatically entire countries |
| 4 · Dominant | Very strong sector-spanning influence | Major metropolitan, industrial or administrative hubs |
| 3 · Established | Significant durable networks | Important cities and delegated-House regions |
| 2 · Selective | Meaningful but limited relationships | Ports, corridors and specialist nodes |
| 1 · Peripheral | Indirect, historic or low-density presence | Faint background home-country/delegated reach where supported |

**Hatched/paired areas** indicate materially overlapping Houses; label participants in a regional note or inset. “Neutral/no mapped dominant House” is *not* “no influence exists”. Do not color the entirety of remote Russia because of Volkov's western branches. Do not assume uniform Valdieri dominance throughout Italy due to its postwar history. For Veyrholm, Oslo and Stockholm should be strong urban nodes while remote Norwegian/Swedish interiors are generally weaker. Falkenrath's highest centers are Salzburg and Vienna; Munich remains strong but secondary. These location-specific rules belong to the geographic-review dossier and must be treated with their approval state.

Use a color matrix or named five-shade ramp for each House. Add a brief sentence: “House color identifies network; shade indicates strength; hatching denotes overlap; borders are modern states, not House jurisdictions.”

## 6. Where the geographic data ACTUALLY came from

The **GIS-based European map**, not the illustrated final reference image, was built from established geographic datasets and an editable Python geospatial workflow. For provenance, the archived Revision 10 source package contains the underlying data, scripts, and quality audit.

| Geographic layer | How it was obtained in the draft | Role and limitation |
|---|---|---|
| Natural Earth 1:110m country / land polygons | A `naturalearth_lowres` shapefile bundled into the project under `data/base/` and read with GeoPandas | Coarse land/country masks, useful for continent-scale exploratory views; **too coarse for a final large print plate** |
| GSHHS/GSHHG intermediate coastlines and WDBII borders | Basemap's installed `basemap_data` / `Basemap(resolution='i')` coastline and country-border segments, transformed from geographic lon/lat | Improved shorelines/borders and recovery of missing real islands; not a comprehensive 1:10m replacement |
| ETOPO1-derived shaded-relief JPEG | The installed Basemap dataset's `etopo1.jpg` resource, copied into `data/base/etopo1.jpg` | Warm parchment terrain appearance, geographically warped using the map transform; **display image, not elevation-measurement data** |
| City and institutional anchors | Source-maintained named city WGS84 longitude/latitude pairs plus regional approximations for fictional seats | 110 influence anchors in Revision 10; city coordinates and fictionally approximate estates must be labeled separately |
| Subordinate network backgrounds | Source-maintained proposal table (`subordinate_network_backgrounds_v4.json`) | Low-strength country-scale background hypothesis derived from canon; **not independently surveyed empirical influence** |
| Derived influence zones | Scored spatial fields converted to vector polygon geometry (`derived_influence_zones.geojson`) | Fictional analytical geography generated from proposed scores, **not observed boundaries** |

### The source's actual spatial transformation

1. Store anchor points in **WGS84 longitude/latitude** (`EPSG:4326`).
2. Read authentic land, national-boundary and island geometry from the packaged sources; validate geometry, note jurisdiction / disputed-border conventions, and project features into **ETRS89-extended / LAEA Europe (`EPSG:3035`)** with `pyproj` and GeoPandas.
3. Project coastlines, graticule, country outlines and city markers into the same coordinate space. Add missing *real* islands from GSHHS intermediate-resolution geometry. Never draw land by eye.
4. Resample the relief depiction from the ETOPO1-derived Basemap image into that same map projection and mask it to projected real land geometry. Keep oceans dark navy.
5. Compute **proposed** House fields from individual city-center peaks/spread values and low-strength Major/Lesser House background rules. In the provided code, city influence is based on Gaussian-like tapered fields in projected coordinates; calculate overlap explicitly rather than painting countries wholesale.
6. Clip all House shading to the projected real land mask; export influence polygons as GeoJSON plus editable SVG/PDF path objects. Overlay the actual political boundary vectors **above** the colored fields.
7. Add country names, cities, confirmed House cores, a north arrow, appropriate scale reference and an integrated Central European inset; verify their positions against geographic coordinates.
8. Only now apply the approved ornament, title cartouche, House crest frames, colors and prose. If an AI illustrated pass is used, treat it as **concept art or an isolated decorative overlay**, not as a replacement for any GIS-defined geographic pixels.

**Truthful historical distinction:** The *beautiful approved master image* was produced through an illustration-generation step inspired by the GIS-based drafts and user references. It did **not** directly consume the Natural Earth shapefile or preserve EPSG:3035 feature geometries. It can appear convincingly geographic without being verifiably accurate. The final production workflow must composite its decorative language with a GIS-controlled map rather than assume its coastlines, country contours, grid, scale or place markers are authoritative.

### Upgrade required for authoritative print geography

The map drafts used coarse 1:110m Natural Earth land masks plus intermediate GSHHS vectors. For high-resolution final atlas printing, replace the underlying geometry with **Natural Earth 1:10m Admin-0 countries, boundary lines, 1:10m physical land/coastline/minor islands and, where needed, 1:10m Admin-1 subdivisions**. Compare with a second independent modern boundary source for disputed or time-sensitive states; document the viewpoint (de facto / de jure / disputed) rather than silently choosing one. Reproject and recompute masks/zones: do not simply draw a high-resolution border over a coarse mask and call it precise.

Natural Earth itself notes that 1:110m is for small locator maps while 1:10m is suitable for large wall maps; its Admin-0 boundaries may follow **de facto** territorial control by default. Those cartographic choices are separate from this fictional universe's House influence. See **Sources and credit** below.

## 7. Reproducible technical workflow and file layout

**Required archive:** `Ravenscroft_Europe_Influence_REV10_LEGEND_HERALDRY_REVIEW.zip`. It is the most recent geographic-source baseline available at this style-lock milestone, **not the locked visual-art master**. Earlier stages are helpful for provenance: V4 national-background rules, V5 relief projection, V6 antique treatment, V9 Nordic/Alpine correction, V10 improved heraldic panel and matrix legend.

**Canonical file names inside the GIS baseline:**

```text
source/build_influence_v4.py            original city scores / regional model
source/build_influence_v5.py            genuine projected relief treatment
source/build_influence_v6.py            hybrid frame and typography
source/build_influence_v7.py            illustrated-panel layout variant
source/build_influence_v10.py           six-by-five house/level legend, crest panels
data/base/naturalearth_lowres.*          original 1:110m land data
data/base/gshhs_intermediate_islands.geojson
data/base/etopo1.jpg                geographic relief illustration
data/influence_nodes.geojson        WGS84-derived anchors exported in EPSG:3035
data/derived_influence_zones.geojson
data/subordinate_network_backgrounds_v4.json
data/atlas_revision9_focused_changes.json
assets/house_crests/                 user-supplied JPEG references; not byte-verified original PNGs
outputs/*.svg, outputs/*.pdf, outputs/*.png
qa/revision10_quality_audit.json
```

**Runtime:** Python with GeoPandas, Shapely, pyproj, Matplotlib, NumPy, SciPy, rasterio, Basemap and Pillow (versions in `source/requirements.txt`). Keep source files and original GIS data in the same release package; include GIS data licensing and original provider URLs.

**Rebuild commands from an unpacked archive:**

```bash
python -m pip install -r source/requirements.txt
python source/build_influence_v10.py
# Preview mode (if supported by the included renderer):
ATLAS_FAST=1 python source/build_influence_v10.py
```

**Recommended final series layout:** a `maps/<region>/<edition>/` folder holding `reference/`, `data/source/`, `data/derived/`, `heraldry/`, `render/`, `outputs/`, `qa/`, and a manifest containing approval statuses and source SHA-256 checksums. Never mix a proposed atlas score with an established canon fact without separate metadata.

## 8. Reproduction prompt / art direction (for decorative reference only)

> Produce a horizontal, extremely refined antique strategic atlas plate for the contemporary hidden Order. Use dark midnight-blue seas, authentic cartographic terrain beneath translucent graded influence, warm ivory place labels, exceptionally detailed antique-gold engraved frame and corner filigree, grand centered classical serif title, large House-heraldry cards with concise textual descriptions on the left, and a clear right reference rail containing an influence legend, a restrained inset and short intelligence notes. Match the **attached approved visual master** for page architecture and the **attached GIS export** for every geographic shape and label. Preserve official heraldry exactly and respect distinct House colors. No invented islands, no distorted national outlines, no substituted crests, no fictional countries, no illegible small type, no arbitrary additional routes or symbols. Do not reinterpret the House influence values. If geographic and illustration instructions conflict, **GIS wins**.

**Important:** A prompt alone cannot enforce GIS coordinates in a freeform image generator. Use this prompt to generate ornaments, paper/sea textures and reference layouts. Compose those around a separately verified vector map for release.

## 9. Production QA and user-approval gate

**Geography and data**
- [ ] All coasts and islands match the verified geographic layer; specifically check Mediterranean, Baltic, British Isles, Norwegian fjords and Iceland.
- [ ] Actual modern international borders are visible through every House influence fill, including Central European inset.
- [ ] Disputed borders are labeled with the adopted source/date and de facto/de jure viewpoint.
- [ ] Oslo, Stockholm, Visby, Salzburg, Vienna, Munich and other priority anchor markers remain in the correct cities with approved relative strengths.
- [ ] House scores and background rules have a named approval status; no code-generated proposal presented as locked lore.
- [ ] Projection, scale bar, coordinate annotations and inset extent independently verified.

**House identity and narrative**
- [ ] Six Great Houses only in the European thematic register, with a note that **eleven Great Houses exist globally in 2026** and **nine Council mandates** are distinct from total House count.
- [ ] Approved original simplified heraldry used; verify asset file paths and SHA-256. If unavailable, do not substitute.
- [ ] Maps represent institutional reach, not ownership, state sovereignty or guaranteed loyalty of every official.
- [ ] No obsolete names such as de Varenne; de Villiers is the replacement Great House.

**Design and export**
- [ ] Detail text is legible at full size and anticipated print size; avoid low-contrast panels or tiny labels.
- [ ] Six House hues and five shade levels form a logically usable legend; overlap hatching has named participants in regional notes.
- [ ] Decor remains outside true coastline/border shapes; crest panels are aligned, readable and dignified.
- [ ] Export master PNG and true vector PDF/SVG; note which components are raster (terrain, original heraldry) and which are editable vectors.
- [ ] Open the final PDFs/SVGs independently, compare visual render to PNG and inspect major regions at high zoom.
- [ ] Preserve approved master image and source GIS versions; do not replace official website maps without explicit approval.

**Separate approval gates:** (1) visual series standard — **already approved**; (2) map-specific copy — review; (3) detailed geography and influence levels — review; (4) final approved atlas image/GitHub asset — explicit publication authorization.

## 10. Sources, credits and reproducibility pointers

- **Natural Earth:** vector map downloads, including 1:10m / 1:50m / 1:110m — https://www.naturalearthdata.com/downloads/ ; 1:10m cultural — https://www.naturalearthdata.com/downloads/10m-cultural-vectors/ ; physical — https://www.naturalearthdata.com/downloads/10m-physical-vectors/ .
- **NOAA NCEI GSHHG:** genuine coastlines and WDBII international boundaries in multiple resolutions — https://www.ngdc.noaa.gov/mgg/shorelines/shorelines.html .
- **NOAA ETOPO1:** global relief-model provenance — https://data.noaa.gov/onestop/collections/details/23243baa-fa63-4bdb-b133-5b4fcc6e4786 . The packaged Basemap `etopo1.jpg` is an illustration of terrain, not the full numerical grid.
- **EPSG:3035:** ETRS89-extended / LAEA Europe projection — https://epsg.io/3035 .
- **House canon and historic records:** https://github.com/GangrelRavenscroft/-ravenscroft-wiki/tree/main/houses .
- **Atlas planning doctrine (draft geography):** https://github.com/GangrelRavenscroft/-ravenscroft-wiki/blob/main/world/european-influence-atlas-model-2026-review.md .
- **General influence doctrine (locked):** https://github.com/GangrelRavenscroft/-ravenscroft-wiki/blob/main/world/institutional-influence-and-intelligence-doctrine.html .

*Document control: the user's 15 October 2026 visual approval supersedes earlier style-only revisions, but not their independent geospatial inputs, canon status or verified official heraldry. Future map creators must consult this guide, the approved visual reference, the original House heraldry, and the most recent GIS baseline together.*
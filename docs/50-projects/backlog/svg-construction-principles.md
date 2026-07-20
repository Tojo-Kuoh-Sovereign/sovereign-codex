# SVG Construction Principles

## Geometry First

Construct forms from simple geometric primitives before introducing complex paths.

---

## Symmetry by Default

Mirror geometry wherever practical.

Avoid manually recreating symmetrical elements.

---

## Minimal Node Count

Prefer fewer nodes with cleaner Bézier curves.

Avoid unnecessary complexity.

---

## Boolean Before Manual Editing

Where practical, prefer Boolean operations before manual node editing.

Preferred operations include:

- Union
- Difference
- Intersection
- Exclusion

---

## Reusable Geometry

Where practical, duplicate, mirror, or adapt existing geometry before creating new shapes.

Reusable construction improves consistency and reduces maintenance.

---

## Negative Space

Design using both positive and negative space.

The silhouette is considered equally important as the interior detail.

---

## Visual Balance

Review the visual balance of every composition.

Optical balance should take precedence over purely mathematical positioning where appropriate.

---

## Small Size Validation

Every primary identity mark should remain recognisable at:

- 16 px
- 24 px
- 32 px
- 64 px

before being approved for production use.

---

## Export Philosophy

The SVG construction file is the authoritative source.

PNG, ICO, PDF, and other exported assets should never become the master copy.

Changes should always be applied to the SVG before generating new exports.

## Construction before Illustration

Every identity mark should first exist as a geometric construction.

Illustration should emerge from the construction rather than define it.

Construction geometry should remain available throughout development to support future refinement and maintenance.
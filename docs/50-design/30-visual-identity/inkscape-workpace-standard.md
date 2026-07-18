# Inkscape Workspace Standard

## Purpose

The Inkscape Workspace Standard establishes a consistent engineering environment for creating and maintaining vector graphics throughout Sovereign Codex.

A consistent workspace reduces cognitive load, improves maintainability, and ensures every contributor works within the same design environment.

---

## Document Configuration

### Canvas

- Size: **1024 × 1024 px**
- Units: **Pixels (px)**
- Background: **Transparent**

---

### Grid

- Major Grid: **32 px**
- Minor Grid: **8 px subdivisions**

The grid should remain enabled during construction to encourage geometric consistency.

---

### Snapping

Enable:

- Grid
- Guides
- Nodes
- Bounding Boxes

Disable unnecessary snap targets unless specifically required.

---

## Workspace Panels

### Permanently Visible

- Layers & Objects
- Align & Distribute
- Fill & Stroke

### Open When Required

- Export
- Text & Font
- XML Editor
- Symbols

---

## Layer Structure

Layers should be organised as follows:

1. Export Preview
2. Artwork
3. Geometry
4. Construction
5. Reference

### Export Preview

Temporary export testing.

May be removed before publication.

---

### Artwork

Contains the finished vector artwork.

---

### Geometry

Contains primitive construction shapes.

Used during the design process.

---

### Construction

Contains:

- Guides
- Ratios
- Construction geometry
- Alignment references

Normally locked.

---

### Reference

Contains:

- Screenshots
- Sketches
- Inspiration
- Photographs

Always locked.

---

## File Naming

Construction Files

```text
construction/
    sovereign-mark-v1.svg
```

Export Files

```text
exports/
    favicon-16.png
    favicon-32.png
    logo-light.svg
    logo-dark.svg
```

The SVG construction file is considered the authoritative master asset.

All exported assets should be generated from the master SVG.

---

## Workspace Philosophy

The workspace exists to support engineering discipline rather than artistic experimentation.

Consistency should minimise friction while encouraging repeatable construction methods.

The environment should remain clean, predictable, and purpose-built.
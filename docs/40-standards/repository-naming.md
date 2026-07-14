# Repository Naming

> **Status:** Draft
>
> **Document Owner:** Sovereign Project Office
>
> **Framework:** Sovereign Documentation Framework (SDF)
>
> **Category:** Standards
>
> **Version:** 1.0


# Purpose 

The Repository Naming Standard defines a consistent naming and ordering convention for the Sovereign repository to improve maintainability, discoverability, and long-term scalability.

---

# Relationships

This standard implements the following Governance principles:

- Preserve Orientation
- Reduce Unnecessary Cognitive Effort
- Progressive Engagement
- Continuous Improvement

---

# Folder Naming Convention

Folders that communicate hierarchy should use the following format:

```text
NN-folder-name
```

Where:

- **NN** is a two-digit ordering prefix.
- Prefixes should normally increment in multiples of **10**.
- Folder names should use lowercase characters.
- Words should be separated using hyphens (`-`).

Example:

```text
10-about
20-governance
30-research
40-standards
50-design
60-quality
70-knowledge
80-roadmap
90-project-office
95-tools
99-archive
```

---

# Subfolder Naming

Subfolders should follow the same convention.

Numbering is **local to the parent folder** and should restart within each directory.

Example:

```text
20-governance/

10-vision
20-governance-model
30-research-philosophy
40-knowledge-presentation-principles
50-decision-framework
60-continuous-improvement
70-architecture
```

---

# Ordered Documents

Documents should only receive numerical prefixes where sequence communicates meaning.

Examples include:

- Multi-part standards
- Governance documentation
- Ordered learning material
- Structured documentation series

Example:

```text
20-governance/

10-vision/
statement.md
index.md
```

---

# Standalone Documents

Standalone documents should not receive numerical prefixes.

Examples include:

- README files
- Meeting notes
- Backlog items
- Licences
- Reference material

Example:

```text
meeting-notes.md
backlog.md
licence.md
```

---

# Reserved Number Ranges

The following ranges are recommended where appropriate.

| Range | Purpose |
|--------|----------|
| 10–80 | Primary content |
| 90–98 | Supporting material |
| 99 | Archive / Deprecated |

These ranges provide consistency while allowing future expansion.

---

# Repository vs Published Website

Repository naming conventions exist solely to improve contributor experience.

The published Sovereign Codex should display reader-friendly navigation and should not expose repository ordering prefixes unless intentionally required.

Implementation should ensure that navigation labels remain independent of repository folder names wherever practical.

---

# Standard

Repository names should communicate structure, responsibility, and hierarchy while remaining consistent throughout the Sovereign Documentation Framework.

Naming conventions exist to improve repository maintainability, contributor orientation, and long-term scalability.

Repository naming conventions are implementation details and should remain independent from the published navigation wherever practical.

---

# Version History

| Version | Status | Notes |
|----------|--------|-------|
| 1.0 | Draft | Initial Repository Naming Standard established during Milestone 9.5 – Framework Consolidation. |
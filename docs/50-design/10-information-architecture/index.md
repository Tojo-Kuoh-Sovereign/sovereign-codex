# Information Architecture

The Information Architecture defines how knowledge is organised, discovered and navigated throughout Sovereign Codex.

It separates the internal repository structure used by contributors from the presentation structure experienced by readers.

The objective is to minimise cognitive load while preserving a maintainable repository architecture.

---

## Principles
Internal Structure

Repository structure exists to support:

- scalability
- maintainability
- version control
- contributor workflows
- deterministic ordering

Internal implementation details are not considered part of the reader experience.

---

## Presentation Structure

Presentation exists to support:

- discovery
- comprehension
- navigation
- knowledge relationships
- learning progression

Presentation should expose knowledge, not implementation.

---

## Separation Principle

Internal implementation details should never appear in the user experience unless they improve understanding.

Examples:

| Internal | Reader |
|----------|--------|
| Folder prefixes | Hidden |
| File prefixes | Hidden |
| Navigation hierarchy | Visible |
| Knowledge relationships | Visible |
| Document status | Visible |
| Research confidence | Visible |

---

## Navigation Principle

Navigation is organised around knowledge domains, not folders.

A knowledge domain represents a meaningful area of information.

Repository folders exist to support development.

Navigation exists to support learning.
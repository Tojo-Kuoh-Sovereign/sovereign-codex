# Knowledge State Standard

> **Status:** Draft
>
> **Document Owner:** Sovereign Project Office
>
> **Framework:** Sovereign Documentation Framework (SDF)
>
> **Category:** Standards
>
> **Version:** 1.0

---

# Purpose

The Knowledge State Standard defines how contextual information is communicated throughout the Sovereign Documentation Framework.

Knowledge States provide readers with immediate context regarding the confidence, intent, applicability, or governance of documented information without interrupting the natural flow of knowledge.

Their purpose is to improve understanding by communicating **how information should be interpreted**, rather than changing the information itself.

---

# Relationships

This standard implements the following Knowledge Presentation Principles:

- Build Confidence Through Clarity
- Preserve Orientation
- Progressive Engagement
- Support Knowledge Progression

This standard supports:

- Knowledge Presentation Principles
- Research Documentation
- Documentation Standards
- Design System
- User Experience

---

# Standard

Knowledge States communicate contextual meaning.

They provide readers with additional interpretive context while preserving the original content of the document.

Knowledge States should never be used for visual decoration, emphasis, or branding.

Every Knowledge State should communicate a single, clearly distinguishable meaning.

---

# Scope

This standard governs:

- Knowledge State definitions
- Appropriate usage
- Writing tone
- Reader expectations
- Consistent application throughout the Sovereign Documentation Framework

It applies wherever contextual information improves reader understanding.

---

# Core Principles

Knowledge States should be:

- Meaningful
- Consistent
- Objective
- Purpose-driven
- Easy to recognise

Knowledge States communicate meaning rather than presentation.

---

# Knowledge States

## Research

### Purpose

Communicates that findings remain under investigation or require additional validation.

### Typical Usage

- Early research
- Community testing
- Patch investigations
- Unverified mechanics

### Writing Tone

Curious, objective, and transparent.

Avoid presenting assumptions as established facts.

### Example

> This mechanic requires additional testing following the latest Console update.

---

## Approved

### Purpose

Communicates that information has been independently verified and approved for publication.

### Typical Usage

- Completed research
- Verified mechanics
- Approved documentation
- Confirmed workflows

### Writing Tone

Confident, objective, and evidence-based.

Avoid unnecessary emphasis.

### Example

> This workflow has been independently verified against the current Console release.

---

## Implementation

### Purpose

Highlights implementation details relevant to development or technical configuration.

### Typical Usage

- CSS
- MkDocs
- Python
- Configuration
- Development notes

### Writing Tone

Instructional, practical, and engineering-focused.

Focus on implementation rather than theory.

### Example

> Components should reference semantic tokens rather than foundation materials directly.

---

## Console Limitation

### Purpose

Communicates behaviour that differs specifically on the Console version of the platform.

### Typical Usage

- Platform limitations
- UI differences
- Missing functionality
- Console-specific behaviour

### Writing Tone

Clear and informative.

Describe the difference without implying fault.

### Example

> This feature is currently unavailable on Console.

---

## Do Not

### Purpose

Communicates prohibited practices or actions that conflict with Sovereign standards or platform requirements.

### Typical Usage

- Unsafe practices
- Unsupported workflows
- Repository protection
- Governance requirements

### Writing Tone

Clear, concise, and authoritative.

Avoid unnecessary explanation unless context is required.

### Example

> Never edit the generated site directory.

---

# Selecting the Appropriate Knowledge State

Before introducing a Knowledge State, contributors should consider:

- Does the Knowledge State communicate meaningful context?
- Could an existing Knowledge State communicate the same meaning?
- Will readers consistently understand its purpose?
- Does it improve understanding without increasing visual complexity?

Knowledge States should remain limited in number and clearly differentiated.

---

# Relationship to the Framework

Knowledge States complement, but do not replace:

- Research Standards
- Documentation Standards
- Citation Standards
- Writing Standards
- Design Language
- Design System

Together, these standards communicate not only **what** information is presented, but also **how** readers should interpret and evaluate it.

---

# Governance

Knowledge States should evolve through research, implementation experience, usability testing, and continuous improvement.

New Knowledge States should only be introduced where they communicate a genuinely distinct form of contextual meaning that cannot reasonably be represented by an existing state.

The objective is to maintain a concise, recognisable vocabulary that becomes familiar to readers while preserving consistency throughout the Sovereign Documentation Framework.

---

# Version History

| Version | Status | Notes |
|----------|--------|-------|
| 1.0 | Draft | Initial Knowledge State Standard established during Milestone 9.5 – Framework Consolidation. |
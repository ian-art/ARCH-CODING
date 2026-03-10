## Arch Coding

**Arch Coding** (short for **Architecture-Driven Coding**) is a development methodology where the **primary responsibility of the developer is defining the system architecture, engineering rules, and reliability mechanisms**, while **implementation is fully delegated to AI as the primary execution layer.**.

In Arch Coding, architecture is treated as the **first-class artifact of the software**, and implementation is constrained to follow that architecture.

The developer acts as the **system architect**, ensuring structural integrity, maintainability, and reliability, while tooling assists with code generation and mechanical implementation.

---

## Core Philosophy

Arch Coding follows several key principles:

### 1. Architecture First

The system structure is defined before implementation begins.

This includes:

* module boundaries
* dependency relationships
* system entry points
* failure handling mechanisms
* diagnostics and observability

Implementation must respect these architectural decisions.

---

### 2. Strict Engineering Rules

Development operates under explicit engineering constraints.

Examples include:

* minimal entry points (e.g., keeping `main.cpp` small)
* module isolation
* non-destructive modifications
* mandatory analysis before changing code
* prohibition of assumptions about the codebase

These rules ensure consistency and prevent uncontrolled changes.

---

### 3. Implementation Delegation

Code implementation may be generated or assisted by automated systems (e.g., AI tools), but **the architecture remains human-directed**.

The developer defines:

* how the system should behave
* how modules interact
* what constraints must be respected

The generated code must comply with these rules.

---

### 4. Observability by Design

Diagnostics and debugging infrastructure are implemented early in the development process.

Examples include:

* crash reporting
* diagnostic breadcrumbs
* watchdog monitoring
* structured logging
* symbol management

This ensures failures can be investigated deterministically.

---

### 5. Controlled Evolution

Changes to the system follow a disciplined workflow:

1. Analyze the affected module
2. Verify architectural compatibility
3. Apply minimal changes
4. Preserve existing behavior unless explicitly improved
5. Maintain module boundaries

This prevents architectural drift.

---

## Developer Role in Arch Coding

In this model, the developer primarily acts as a **Software Architect**.

Responsibilities include:

* designing the system structure
* defining engineering rules
* enforcing architectural boundaries
* ensuring reliability and observability
* guiding the evolution of the system

Implementation may be assisted by automation, but **architectural authority remains with the human developer**.

---

## Arch Coding vs Vibe Coding

Arch Coding is fundamentally different from **Vibe Coding**, a term commonly used for highly improvisational AI-assisted programming.

| Aspect               | Arch Coding                   | Vibe Coding                   |
| -------------------- | ----------------------------- | ----------------------------- |
| Development approach | Architecture-first            | Improvisation-first           |
| Planning             | Structured design             | Minimal planning              |
| Code modifications   | Controlled and disciplined    | Ad-hoc experimentation        |
| Engineering rules    | Strict and explicit           | Usually absent                |
| Observability        | Built early                   | Often added later             |
| Reliability strategy | Designed intentionally        | Often reactive                |
| Developer role       | Architect and system designer | Operator of AI-generated code |

In Vibe Coding, development typically begins with a prompt such as:

> “Build a media player with subtitles.”

The developer iteratively adjusts the output.

In Arch Coding, the workflow instead resembles:

```
Architecture → Engineering Rules → Implementation → Diagnostics → Iteration
```

Implementation is constrained by architecture rather than improvisation.

---

## Why This Project Uses Arch Coding

PRIORITY MANAGER:
https://github.com/ian-art/PMan (public)

LITEFRAME MEDIA PLAYER:
https://github.com/ian-art/LiteFrame (private for now)

These projects follows the Arch Coding approach to ensure:

* long-term maintainability
* predictable system structure
* reliable diagnostics
* disciplined code evolution

By prioritizing architecture and engineering governance, the project maintains control over complexity even when using automated implementation tools.

---

## Summary

Arch Coding is an **architecture-driven development methodology** where:

* the human developer defines system architecture and engineering constraints
* automated tools assist with implementation
* reliability and observability are built into the system early
* changes are applied through disciplined architectural governance

The goal is to combine **the speed of automated code generation with the rigor of professional software architecture**.

---

**Author:** Ian Anthony R. Tancinco  
Creator and proponent of Arch Coding  
Arch Coding. Coined March 10, 2026.

# Cross-File Reference Map
This document provides a unified reference system linking all major components of the Communication Operating System (OS). It allows contributors and reviewers to quickly navigate between principles, methods, modules, and architecture layers.

---

# 1. Principles → Methods

## Context First
Referenced in:
- Communication Evaluation SOP (METHODS.md)
- Cadence Mapping SOP (METHODS.md)
- context-drift module (modules/context-drift.md)

## Criteria Before Judgment
Referenced in:
- Evaluation Architecture (EVALUATION.md)
- Communication Evaluation SOP (METHODS.md)

## Cadence Discipline
Referenced in:
- cadence-mapping module (modules/cadence-mapping.md)
- Drift Detection SOP (METHODS.md)

## Observation Over Assumption
Referenced in:
- cold-read module (modules/cold-read.md)
- Observation → Abstraction Workflow (METHODS.md)

## Modularity of Thought
Referenced in:
- Modularity SOP (METHODS.md)
- compiler-architecture module (modules/compiler-architecture.md)

---

# 2. Methods → Modules

## Communication Evaluation SOP
Used by:
- Evaluation Architecture (EVALUATION.md)
- compiler-architecture module (modules/compiler-architecture.md)

## Observation → Abstraction Workflow
Used by:
- iteration-log module (modules/iteration-log.md)
- cold-read module (modules/cold-read.md)

## Cadence Mapping SOP
Used by:
- cadence-mapping module (modules/cadence-mapping.md)
- persona-consistency module (modules/persona-consistency.md)

## Modularity SOP
Used by:
- compiler-architecture module (modules/compiler-architecture.md)
- context-drift module (modules/context-drift.md)

## Drift Detection SOP
Used by:
- context-drift module (modules/context-drift.md)
- Evaluation Architecture (EVALUATION.md)

---

# 3. Modules → Compiler Architecture

## cold-read
Feeds into:
- Refinement Layer (compiler-architecture.md)

## sensory-anchoring
Feeds into:
- Refinement Layer (compiler-architecture.md)
- Cadence Mapping SOP (METHODS.md)

## cadence-mapping
Feeds into:
- Analysis Layer (compiler-architecture.md)

## persona-consistency
Feeds into:
- Refinement Layer (compiler-architecture.md)

## context-drift
Feeds into:
- Analysis Layer (compiler-architecture.md)
- Evaluation Layer (EVALUATION.md)

## iteration-log
Feeds into:
- Continuous Improvement (PRINCIPLES.md)
- Versioning (CHANGELOG.md)

## compiler-architecture
Feeds into:
- FRAMEWORK.md (system flow)
- EVALUATION.md (final scoring)

---

# 4. Architecture → Evaluation

The FRAMEWORK.md references:
- Principles Layer → PRINCIPLES.md
- Methods Layer → METHODS.md
- Modules Layer → /modules
- Compiler Layer → compiler-architecture.md
- Evaluation Layer → EVALUATION.md

The Evaluation Layer references:
- Criteria from PRINCIPLES.md
- SOPs from METHODS.md
- Drift detection from modules/context-drift.md
- Cadence mapping from modules/cadence-mapping.md

---

# 5. Purpose of This File

This cross-reference map ensures:
- fast navigation
- structural clarity
- module interoperability
- consistent inheritance across layers

It acts as the OS’s internal “router,” connecting every subsystem into a unified architecture.

# Contributing to the Communication OS

Thank you for your interest in contributing to the Communication Operating System (OS).
This project is built on principles of clarity, modularity, and deterministic communication design.
All contributions should follow the architectural rules and documentation standards outlined below.

---

# 1. Core Philosophy

The Communication OS is a compiler-style system.
Every contribution must respect the following:

- Principles → Governing laws
- Methods → SOPs and workflows
- Modules → Subsystems
- Compiler Pipeline → Input → Analysis → Refinement → Evaluation
- Evaluation Layer → Criteria, metrics, weights

Contributors must ensure new content fits cleanly into this hierarchy.

---

# 2. Contribution Types

You may contribute in the following ways:

## A. Documentation
- Add or refine principles
- Improve SOPs
- Expand module explanations
- Add examples or test cases
- Improve cross-file references

## B. Visual Assets
- Add diagrams to `visual-diagrams/`
- Update existing diagrams
- Add ASCII diagrams when image generation is unavailable

## C. Modules
- Add new subsystem modules
- Improve existing modules
- Add interaction notes or flow explanations

## D. Architecture
- Propose improvements to the compiler pipeline
- Suggest new layers or optimization passes
- Add advanced heuristics or telemetry concepts

---

# 3. File Structure Rules

All contributions must follow the existing repo structure:

communication-os/
 ├── README.md
 ├── PRINCIPLES.md
 ├── METHODS.md
 ├── modules/
 ├── compiler-architecture.md
 ├── EVALUATION.md
 ├── FRAMEWORK.md
 ├── CROSS-REFERENCES.md
 ├── CHANGELOG.md
 └── visual-diagrams/

## Rules:
- Do not create duplicate folders.
- Keep naming conventions consistent.
- Use lowercase with hyphens for module filenames.
- Use uppercase for major architecture files.
- Visual assets must be placed in `visual-diagrams/`.

---

# 4. Writing Standards

## A. Tone
- Neutral
- Technical
- Precise
- Modular
- No emotional language
- No conversational filler

## B. Structure
- Use headers
- Use bullet points
- Keep paragraphs short
- Maintain modular separation
- Avoid mixing concepts in one section

## C. Consistency
All new content must align with:

- Context First
- Criteria Before Judgment
- Cadence Discipline
- Observation Over Assumption
- Modularity of Thought
- Persona Consistency
- Sensory Anchoring
- Drift Detection
- Continuous Improvement

---

# 5. Adding New Modules

When adding a new module:

1. Create a file in `/modules`
2. Use the naming format:
   new-module-name.md
3. Include:
   - Purpose
   - Inputs
   - Outputs
   - Interaction with other modules
   - Example flow
4. Add references in `CROSS-REFERENCES.md`
5. Update `CHANGELOG.md`

---

# 6. Adding Visual Diagrams

When boosts reset or images are available:

1. Generate the diagram
2. Save as `.png`
3. Place in `visual-diagrams/`
4. Name the file:
   <diagram-name>.png
5. Add a placeholder `.md` file if the image cannot be generated yet
6. Update `CHANGELOG.md`

---

# 7. Pull Request Guidelines

## Before submitting:
- Ensure your contribution fits the architecture
- Ensure modularity
- Ensure clarity
- Ensure no duplication
- Ensure cross-file references are updated
- Ensure CHANGELOG is updated

## PR Format:
Title: <Short description>

Summary:
- What you added
- Why it matters
- Which files were updated

Checklist:
- [ ] Principles respected
- [ ] Methods aligned
- [ ] Modules consistent
- [ ] Compiler pipeline unaffected
- [ ] Evaluation layer compatible
- [ ] Cross-references updated
- [ ] Changelog updated

---

# 8. Code of Conduct

Contributors must maintain:

- Respect
- Clarity
- Professionalism
- No hostility
- No personal attacks
- No off-topic content

This project is about engineering communication — keep contributions aligned with that mission.

---

# 9. Contact

For questions, open an issue with the label:
question

For proposals, use:
enhancement

For architecture changes, use:
architecture

---

# Thank You

Your contributions help evolve the Communication OS into a robust, modular, and scalable system for structured communication.


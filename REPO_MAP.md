
# Repo Map

## Purpose
This file acts as a navigation guide for the Retinal Surrealism repository. It explains what each section does, how they relate, and the recommended reading order. The repository is organized into layered levels: style identity, branch taxonomy, control grammar, motif systems, object/world ecology, color systems, and AI prompting/controls.

## Top-Level Overview
1. **01_FOUNDATION/**: defines the style identity, pillars, non‑negotiables, and a branch map.
2. **02_PURE_OPTICAL_SYSTEMS/**: holds the formal pattern branches of the style (classic op art, radial systems, etc.).
3. **03_OPTICAL_SURREALISM/**: describes worldbuilding branches (landscapes, fashion, portrait, iconography, etc.).
4. **04_VISUAL_GRAMMAR/**: houses the structural control rules (line density, spacing, curvature, radial compression, figure–ground instability, false depth, edge behaviour, color as force).
5. **05_PATTERN_LIBRARY/**: contains motif families such as rosettes, concentric targets, spoke bursts, zebra waves, contour fields, checker funnels, and optical paths.
6. **06_OBJECT_AND_WORLD_LIBRARY/**: details symbolic object families (lips, mushrooms) and ecological considerations.
7. **08_COLOR/**: defines monochrome logic, chromatic logic, acid, blacklight and prismatic edge palettes.
8. **09_AI/**: provides prompting templates, anti‑drift rules, failure modes, prompt fragments, and a machine‑readable style spec.
9. **10_SHADER/**: translates the style into procedural patterns, animation behaviours, color oscillation logic, etc.
10. **11_APP/**: supplies tags and classifier hints for applications.

## Recommended Reading Order
- If new to the style, start with `README.md` then the foundation files: `style_definition.md`, `non_negotiables.md`, `superfamilies.md`, and `BRANCH_MAP.md`.
- For prompt work, read `prompt_templates.md`, `prompt_fragments.md`, and `anti_drift.md`.
- For pattern generation, consult `pattern_families.md` and the motif files under `05_PATTERN_LIBRARY/`.
- For worldbuilding, check `03_OPTICAL_SURREALISM/` and the object library files.
- For color, read the files in `08_COLOR/`.
- For procedural generation, use the files in `10_SHADER/`.

## File Priority Tiers
- **Tier 1** – Must read: `README.md`, `style_definition.md`, `non_negotiables.md`, `BRANCH_MAP.md`, `style_spec.json`.
- **Tier 2** – Control logic: `04_VISUAL_GRAMMAR/` files.
- **Tier 3** – Generation support: prompt templates, fragments, anti‑drift.
- **Tier 4** – Expansion libraries: pattern files, object species files, additional shader docs.

## Section Rules
- Keep foundation docs separate from prompt or colour docs.
- Pure optical branches should not include worldbuilding or object docs.
- Visual grammar files should stay reusable and not mix with branch docs.
- Object files are separate from pattern files.
- Colour docs belong in `08_COLOR/` and prompting docs stay in `09_AI/`.

## Summary
The repo map emphasises structure: start with identity and non‑negotiables, then explore branches, master the visual grammar, pick motifs and objects, choose palette and material, and finally craft prompts or shaders using the AI files. Preserve this layered logic for automation or future extensions.

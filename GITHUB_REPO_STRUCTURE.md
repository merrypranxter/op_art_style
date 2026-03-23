
# GITHUB REPO STRUCTURE

## Purpose
This file explains the intended layout of the Retinal Surrealism repository for automated tools and code agents. It outlines what goes where and warns against flattening the layered architecture.

## Core Rule
The repository is structured as layered levels: foundation, branches, visual grammar, motifs, objects, color systems, AI prompting controls, and shaders. Do **not** flatten everything into one folder. Keep concept and control separated.

## Recommended Top-Level Structure
```text
retinal-surrealism/
├── README.md
├── REPO_MAP.md
├── GITHUB_REPO_STRUCTURE.md
├── QUALITY_CHECKLIST.md
├── BRANCH_MAP.md
├── 01_FOUNDATION/
├── 02_PURE_OPTICAL_SYSTEMS/
├── 03_OPTICAL_SURREALISM/
├── 04_VISUAL_GRAMMAR/
├── 05_PATTERN_LIBRARY/
├── 06_OBJECT_AND_WORLD_LIBRARY/
├── 08_COLOR/
├── 09_AI/
├── 10_SHADER/
└── 11_APP/
```

Future sections can include `07_MATERIALS/` as needed.

## Section Guidelines
- **01_FOUNDATION**: Contains identity and non-negotiables; never mix prompt or palette files here.
- **02_PURE_OPTICAL_SYSTEMS**: Strict, pattern-first branches only; exclude worldbuilding or figure docs.
- **03_OPTICAL_SURREALISM**: Houses world‑oriented branches (landscapes, portraits, fashion, etc.). Do not place pure pattern docs here.
- **04_VISUAL_GRAMMAR**: Holds modular control logic (density, spacing, curvature, radial compression, figure–ground instability, false depth, edge behaviour, color as force). Should remain independent and reusable.
- **05_PATTERN_LIBRARY**: Contains motif patterns such as rosettes, targets, bursts, zebra waves, contour fields, checker funnels, optical paths. Don’t mix object species here.
- **06_OBJECT_AND_WORLD_LIBRARY**: Holds ecological object families. Use this for symbolic props like lips and mushrooms. They inherit pattern logic but belong in their own folder.
- **08_COLOR**: Colour behaviour and palette families. Should not hold prompt content.
- **09_AI**: Prompt templates, anti-drift, failure modes, fragments, JSON spec.
- **10_SHADER**: Procedural translation, structural recipes, animation behaviours, color oscillation logic, etc.
- **11_APP**: Application-facing tags (`app_tags.json`) and classifier hints. Use for machine-readable metadata only.

## Naming Conventions
- Use lowercase and underscores for file names (e.g., `line_density.md`).
- Machine-readable files use `.json`.
- Avoid ambiguous names like `notes.md` or duplicates.

## Splitting and Merging
- Split files when they combine distinct systems; merge only when two tiny files are inseparable.
- Never merge foundation with AI files, or pattern files with object files.

## Summary
Maintain the layered logic: identity → branches → grammar → motifs → objects → colour → AI controls → shader systems. This ensures clarity for both humans and automated tools.

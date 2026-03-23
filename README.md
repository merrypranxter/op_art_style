# Retinal Surrealism — Style Reference Repository

## What This Is

A structured knowledge base for the **Retinal Surrealism** visual style — a governed system that fuses Op Art geometry, perceptual illusion mechanics, and surreal worldbuilding. Every file in this repo is a rule set, control grammar, or generation guide that an AI tool, shader system, or prompt engineer can use to produce on-style imagery.

**One-line definition:** Flat images that lie like hell.

---

## Quick-Start for AI Tools

If you are an AI using this repository to generate or evaluate imagery, load files in this order:

1. `09_AI/style_spec.json` — machine-readable style summary (start here for structured data)
2. `01_FOUNDATION/style_definition.md` — core definition and identity
3. `01_FOUNDATION/non_negotiables.md` — hard rules; never violate these
4. `01_FOUNDATION/superfamilies.md` — the two top-level style families
5. `BRANCH_MAP.md` — all 16 named branches with descriptions
6. `09_AI/prompt_templates.md` — ready-to-use prompt templates
7. `09_AI/anti_drift.md` — rules to prevent style degradation
8. `09_AI/failure_modes.md` — diagnostic guide for off-style output
9. `QUALITY_CHECKLIST.md` — scoring rubric for keeping or discarding output

For deeper work, consult the section that matches your task (see **Directory Structure** below).

---

## Directory Structure

```
op_art_style/
├── README.md                        ← you are here; start here
├── REPO_MAP.md                      ← full navigation guide and reading order
├── GITHUB_REPO_STRUCTURE.md         ← layout rules for automated tools
├── QUALITY_CHECKLIST.md             ← image/prompt scoring rubric
├── BRANCH_MAP.md                    ← all 16 named style branches
│
├── 01_FOUNDATION/                   ← style identity and laws
│   ├── style_definition.md
│   ├── style_pillars.md
│   ├── non_negotiables.md
│   ├── superfamilies.md
│   └── neighboring_styles.md
│
├── 02_PURE_OPTICAL_SYSTEMS/         ← formal pattern-first branches
│   ├── classic_bw_retinal_op.md
│   ├── radial_hypnosis_fields.md
│   ├── stripe_fluid_distortion.md
│   ├── chromatic_interference_op.md
│   ├── tiled_surface_patterns.md
│   ├── funnel_tunnel_lens_forms.md
│   └── moire_and_phase_fields.md
│
├── 03_OPTICAL_SURREALISM/           ← world-building and figure branches
│   ├── op_landscapes.md
│   ├── op_fashion_and_bodysuits.md
│   ├── anatomical_op_mapping.md
│   ├── op_portraits.md
│   ├── eye_object_iconography.md
│   ├── plush_candy_optical_worlds.md
│   ├── pattern_passageways.md
│   ├── psychedelic_material_contamination.md
│   └── op_editorial_glam_theater.md
│
├── 04_VISUAL_GRAMMAR/               ← reusable control logic (density, curvature, depth…)
│   ├── line_density.md
│   ├── spacing_and_frequency.md
│   ├── curvature_logic.md
│   ├── radial_compression.md
│   ├── figure_ground_instability.md
│   ├── false_depth.md
│   ├── edge_behavior.md
│   └── color_as_optical_force.md
│
├── 05_PATTERN_LIBRARY/              ← motif families for generation
│   ├── rosettes.md
│   ├── concentric_targets.md
│   ├── spoke_bursts.md
│   ├── zebra_waves.md
│   ├── contour_fields.md
│   ├── checker_funnels.md
│   └── optical_paths.md
│
├── 06_OBJECT_AND_WORLD_LIBRARY/     ← symbolic object species
│   ├── lips.md
│   └── mushrooms.md
│
├── 08_COLOR/                        ← palette and colour logic
│   ├── bw_logic.md
│   ├── chromatic_logic.md
│   ├── acid_palettes.md
│   ├── blacklight_palettes.md
│   └── prismatic_edge_palettes.md
│
├── 09_AI/                           ← prompt engineering and AI controls
│   ├── style_spec.json              ← machine-readable style summary
│   ├── prompt_templates.md
│   ├── prompt_fragments.md
│   ├── anti_drift.md
│   ├── failure_modes.md
│   └── classifier_hints.md
│
├── 10_SHADER/                       ← procedural and shader translation
│   ├── shader_translation.md
│   ├── structural_pattern_recipes.md
│   ├── animation_behaviors.md
│   └── color_oscillation_logic.md
│
└── 11_APP/                          ← application tagging
    └── app_tags.json
```

---

## File Priority Tiers

| Tier | Files | Purpose |
|------|-------|---------|
| **1 — Must read** | `README.md`, `09_AI/style_spec.json`, `01_FOUNDATION/style_definition.md`, `01_FOUNDATION/non_negotiables.md`, `BRANCH_MAP.md` | Core identity and hard rules |
| **2 — Control logic** | All files in `04_VISUAL_GRAMMAR/` | Pattern control variables |
| **3 — Generation support** | `09_AI/prompt_templates.md`, `09_AI/prompt_fragments.md`, `09_AI/anti_drift.md` | Prompt construction |
| **4 — Expansion libraries** | `05_PATTERN_LIBRARY/`, `06_OBJECT_AND_WORLD_LIBRARY/`, `08_COLOR/`, `10_SHADER/` | Deep generation detail |

---

## Core Rules (Never Violate)

See `01_FOUNDATION/non_negotiables.md` for the full list. The key ones:

- Every image must have a visible optical engine (pattern, vibration, or instability).
- Black-and-white structure must remain intact even when colour is added.
- Objects and figures must inherit the world geometry — no pasting.
- Pattern governs space; decoration does not.

---

## Style Summary

**Retinal Surrealism** uses Op Art mechanics — stripe deformation, radial compression, figure–ground instability, chromatic interference — as the underlying physics of every image. The style extends beyond pure geometry into bodies, fashion, landscapes, portraits, and surreal object ecologies. Colour is voltage, not paint. Objects are species, not props. The world is made of pattern.

For the full machine-readable summary, see `09_AI/style_spec.json`.

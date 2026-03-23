
# Structural Pattern Recipes

This file provides blueprint recipes for generating pattern families procedurally.

**Rosette Engine:** Convert UV to polar; quantize angle to create petals; modulate petal width with sine; apply radial masks; compress rings toward centre.

**Concentric Target Engine:** Compute radial distance; quantize into bands; compress spacing near centre; add lip thresholds and optional false depth.

**Spoke Burst Engine:** Use polar angle quantization; shape tapered blades; modulate radial decay; apply optional rotation drift.

**Zebra Wave Engine:** Generate stripes in UV; apply domain warps; compress locally; maintain continuity across the field.

**Contour Field Engine:** Use distance fields from hidden shapes; create iso‑lines; adjust spacing based on pressure sources.

**Checker Funnel Engine:** Tiling grid coordinates; apply radial pinch or warp to create funnels; adjust scale near throat.

**Optical Path Engine:** Define path curves; generate masks for the path; place stepping rings or markers; modulate density along route.

**Portal Throat Engine:** Create radial sink; define lip ring; apply contrast gradient; allow breath or suction animation.

Use these recipes to build shader functions. Combine engines for complex effects.

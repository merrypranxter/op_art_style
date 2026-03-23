
# Shader Translation

Translating Retinal Surrealism into shader logic requires mapping pattern concepts to coordinate space, masks, distance fields, and modulation layers. Start with a base coordinate system, add pattern masks, then apply warps, compression, or thresholds, before adding colour and motion.

**Key translations:**
- **Rosettes:** Use polar coordinates; segment angle to create petals; apply radial falloff.
- **Targets:** Use radial distance bands; repeat thresholds; compress toward centre.
- **Spoke Bursts:** Quantize angle and taper; overlay radial decay; optionally rotate.
- **Zebra Waves:** Map stripes in UV space; apply domain warps; compress locally.
- **Contour Fields:** Use distance fields; generate iso‑lines at regular intervals; compress spacing based on pressure sources.
- **Checker Funnels:** Create tiled coordinate grids; apply radial warps or pinch transforms.
- **Optical Paths:** Use spline masks; repeat stepping rings; bias pattern along path length.
- **Portal Throats:** Create radial sinks; add lip rings; vary darkness inside.

Always begin with pattern generation before adding noise or colour. Motion should enhance structure, not obscure it.

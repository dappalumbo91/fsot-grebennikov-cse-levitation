# Release v0.1 — FSOT CSE Levitation Simulator + Research

**Date:** June 29, 2026

## Highlights

- Complete tunable Python simulator with **live FSOT computational engine integration**
- New comprehensive self-contained **Markdown report** (`Grebennikov_CSE_FSOT_Report.md`) — replaces PDF/images for easy GitHub viewing
- Full research paper LaTeX source included
- Force model calibrated to Grebennikov payload claims (~100+ kg)
- **CSE_BioLevitation** domain proposed and self-scored (accepted for integration)
- Domain stub function added to simulator
- Hardware integration sketch for ESP32 multi-sensory observer feedback
- Technology export parameters for metamaterial / 3D printing fabrication

## What's New

- Live engine queries for constants (C_eff, A_bleed, etc.)
- Tunable `FORCE_SCALE` with clear calibration rationale
- Observer effects and stabilization boundaries fully implemented
- Vectorized performance improvements
- Text-first deliverables (Markdown report + hardware sketch)

## Files Changed / Added

- `fsot_grebennikov_cse_levitation_sim.py` (with domain stub)
- `Grebennikov_CSE_FSOT_Report.md` (new comprehensive report)
- `README.md` (updated to feature the report)
- `HARDWARE_SKETCH.md`
- `requirements.txt`
- `RELEASE_NOTES_v0.1.md` (this file)

## How to Use

See the main [README.md](README.md) and the [Markdown Report](Grebennikov_CSE_FSOT_Report.md) for full instructions.

## Future Roadmap

- Full integration of CSE_BioLevitation domain into main FSOT engine
- Embedded / MicroPython version
- Closed-loop hardware prototype
- Fluidic and photonic variants

## License

Apache 2.0 — see LICENSE file.

---

**This release establishes the foundation for practical bio-inspired levitation research using FSOT 2.0.**

To create the actual GitHub Release:
1. Go to the repo → Releases → Draft a new release
2. Choose tag `v0.1`
3. Use the content of this file as the release body
4. Attach the Markdown report and any generated plots/PDF if desired
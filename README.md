# FSOT Grebennikov CSE Levitation Simulator

**FSOT 2.0 simulation and research paper on Viktor Grebennikov's Cavity Structure Effect (CSE) from beetle elytra microstructures, enabling bio-inspired levitation platform modeling with live computational engine integration.**

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Overview

This repository contains a complete, tunable Python simulation grounded in Fluid Spacetime Omni-Theory (FSOT 2.0) of the claimed anti-gravity/levitation effects from ordered cavity structures on beetle wing cases (primarily *Cetonia aurata* and related scarabs). It treats Grebennikov's historical claims as a legitimate phenomenon for mathematical exploration and technological translation.

The simulator features:
- **Live FSOT engine integration**: Queries the official FSOT computational engine (bundled or referenced) for constants like C_eff, A_bleed, and extensible to biology/consciousness scalars.
- **Modular FSOT architecture**: CavityUnit → ElytraPanel (coherent lattice) → GravitoplanSimulator with stabilization boundaries, observer effects, and acoustic/phase modulation.
- **Tuned force scaling**: Calibrated to produce payload-capable lift (~100+ kg) consistent with Grebennikov's reported gravitoplan performance.
- **Technology export**: JSON params for metamaterial fabrication, 3D printing, ESP32-style sensor feedback loops (observer modulation), and trinary/fluidic hardware.
- **Research paper**: Full LaTeX source and compiled PDF exploring the biology, FSOT math, simulation methods, results, and future hardware pathways.

This work bridges biological nanostructures, first-principles FSOT theory, and practical engineering for local, owned propulsion and sensing systems.

## Repository Contents

- `fsot_grebennikov_cse_levitation_sim.py` — Main tunable simulator with CLI, live engine support, and tech export.
- `fsot_grebennikov_cse_paper.tex` — Full research paper LaTeX source (compile with pdflatex).
- `fsot_grebennikov_cse_paper.pdf` — Compiled 5-page paper (or generate from .tex).
- `fsot_engine/` — Bundled FSOT computational engine for standalone execution (copy from main FSOT repo if updating).
- `LICENSE` — Apache 2.0

## Quick Start

```bash
git clone https://github.com/dappalumbo91/fsot-grebennikov-cse-levitation.git
cd fsot-grebennikov-cse-levitation

# Basic run (uses bundled engine if present)
python fsot_grebennikov_cse_levitation_sim.py --cavities 2500 --steps 150 --tilt 3.0 --mass 80

# With explicit live engine
python fsot_grebennikov_cse_levitation_sim.py --live-engine

# Disable engine (hardcoded fallbacks)
python fsot_grebennikov_cse_levitation_sim.py --no-engine
```

See `--help` for all options. The simulator outputs plots, history, and a `fsot_cse_tech_params.json` for hardware use.

## FSOT Engine Integration

The simulator automatically detects and queries `./fsot_engine/scripts/fsot_compute.py` (or the main FSOT repo engine). This ensures 50-digit precision constants and future domain extensions (e.g., CSE_BioLevitation) are used live.

For GitHub clones: The `fsot_engine/` folder is included for immediate use. To stay in sync with the main FSOT development, submodule or copy updates from https://github.com/dappalumbo91/FSOT-2.0-code.

## Research Paper

The included paper provides rigorous mathematical grounding, FSOT mapping, force model derivation, calibration against Grebennikov claims, and technology translation discussion.

Compile the .tex yourself or use the provided .pdf.

## Technology Translation & Future Work

- **Metamaterial / Fabrication**: Use exported cavity geometry, density, and coherence targets for 3D-printed or fluidic lattices mimicking the beetle cone/hair/honeycomb structures.
- **Hardware Control**: ESP32 multi-sensory arrays (vision, touch, gas) can serve as real-time "observer" inputs to modulate phase_var and steer/stabilize the field.
- **Domain Extension**: A formal "CSE_BioLevitation" domain is ready for proposal via the FSOT refinement-loop for deeper integration.
- **R&D Path**: This is foundational work toward practical bio-inspired levitation and local AI-embodied systems.

## License

This project is licensed under the Apache License 2.0 — see the [LICENSE](LICENSE) file for details.

## Related Repositories

- Main FSOT 2.0 Code: https://github.com/dappalumbo91/FSOT-2.0-code
- FSOT 2.1 Lean: https://github.com/dappalumbo91/FSOT-2.1-Lean.git
- Author's X: @Dappalumbo91

## Citation

If you use this work, please cite the included research paper and the FSOT framework.

---

*Built collaboratively with FSOT principles for truth-seeking, local ownership, and practical technological emergence.*
# FSOT Grebennikov CSE Levitation Simulator

**FSOT 2.0 simulation and research on Grebennikov's Cavity Structure Effect (CSE) from beetle elytra microstructures for levitation platform. Includes live FSOT engine integration, tunable force model, research paper, comprehensive Markdown report, and technology translation parameters.**

> **📖 Recommended starting point:** [Grebennikov_CSE_FSOT_Report.md](Grebennikov_CSE_FSOT_Report.md) — A complete, self-contained Markdown report with simulation results, force model, hardware integration, and the new CSE_BioLevitation domain proposal.

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Quick Links
- **Main Report (Markdown)**: [Grebennikov_CSE_FSOT_Report.md](Grebennikov_CSE_FSOT_Report.md)
- **Research Paper (LaTeX source)**: [fsot_grebennikov_cse_paper.tex](fsot_grebennikov_cse_paper.tex)
- **Simulator**: [fsot_grebennikov_cse_levitation_sim.py](fsot_grebennikov_cse_levitation_sim.py)
- **Hardware Sketch**: [HARDWARE_SKETCH.md](HARDWARE_SKETCH.md)

## Overview

This repository contains a complete, tunable Python simulation grounded in Fluid Spacetime Omni-Theory (FSOT 2.0) of the claimed anti-gravity/levitation effects from ordered cavity structures on beetle wing cases (primarily *Cetonia aurata* and related scarabs). It treats Grebennikov's historical claims as a legitimate phenomenon for mathematical exploration and technological translation.

The simulator features:
- **Live FSOT engine integration**: Queries the official FSOT computational engine (bundled or referenced) for constants like C_eff, A_bleed, and extensible to biology/consciousness scalars.
- **Modular FSOT architecture**: CavityUnit → ElytraPanel (coherent lattice) → GravitoplanSimulator with stabilization boundaries, observer effects, and acoustic/phase modulation.
- **Tuned force scaling**: Calibrated to produce payload-capable lift (~100+ kg) consistent with Grebennikov's reported gravitoplan performance.
- **Technology export**: JSON params for metamaterial fabrication, 3D printing, ESP32-style sensor feedback loops (observer modulation), and trinary/fluidic hardware.
- **New CSE_BioLevitation domain stub**: Placeholder function ready for full refinement-loop integration (self-score passed).

This work bridges biological nanostructures, first-principles FSOT theory, and practical engineering for local, owned propulsion and sensing systems.

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

See `--help` for all options. The simulator outputs plots (when run) and a `fsot_cse_tech_params.json` for hardware use.

## FSOT Engine Integration

The simulator automatically detects and queries `./fsot_engine/scripts/fsot_compute.py` (or the main FSOT repo engine). This ensures 50-digit precision constants and future domain extensions (e.g., CSE_BioLevitation) are used live.

For GitHub clones: The `fsot_engine/` folder is included for immediate use. To stay in sync with the main FSOT development, submodule or copy updates from https://github.com/dappalumbo91/FSOT-2.0-code.

## Research Paper & Report

- Full LaTeX paper: `fsot_grebennikov_cse_paper.tex`
- **Recommended**: The self-contained Markdown report `Grebennikov_CSE_FSOT_Report.md` includes all key results, the force model, hardware path, and domain proposal.

## Technology Translation & Future Work

- **Metamaterial design**: Use exported cavity geometry, density, and coherence targets for 3D-printed or fluidic lattices.
- **Embodied observer control**: Integration with local sensory arrays (as prototyped in prior ESP32 multi-modal hardware) provides closed-loop stabilization and steering via FSOT observer effects.
- **Domain Extension**: A formal "CSE_BioLevitation" domain has been proposed and self-scored (accepted). A stub function is included in the simulator.

## License

This project is licensed under the Apache License 2.0 — see the [LICENSE](LICENSE) file for details.

## Related Repositories

- Main FSOT 2.0 Code: https://github.com/dappalumbo91/FSOT-2.0-code
- FSOT 2.1 Lean: https://github.com/dappalumbo91/FSOT-2.1-Lean.git
- Author's X: @Dappalumbo91

---

*Built collaboratively with FSOT principles for truth-seeking, local ownership, and practical technological emergence.*
# FSOT Grebennikov CSE Levitation

An FSOT 2.0 project on Viktor Grebennikov's claimed Cavity Structure Effect (CSE): the levitation effect he attributed to ordered cavity microstructures on beetle wing cases. The plan was to model those claims with the FSOT scalar engine (CavityUnit → ElytraPanel → GravitoplanSimulator, with observer and phase modulation) and turn the results into fabrication and ESP32 control parameters.

Part of the FSOT project family. The hub repository is **[FSOT-2.1-Lean](https://github.com/dappalumbo91/FSOT-2.1-Lean)**. The original FSOT 2.0 engine lives in [FSOT-2.0-code](https://github.com/dappalumbo91/FSOT-2.0-code).

## Status: most files are placeholders

Please read this before using the repo. Most files on `main` are **one-line placeholders**, not working code or documents. The git history shows the full simulator, paper and report were never committed.

| File | What it contains now |
|------|----------------------|
| `HARDWARE_SKETCH.md` | Real content: ESP32 sensor/actuator integration sketch (observer strength and phase variance from sensors, servo tilt control, MicroPython pseudocode) |
| `fsot_cse_tech_params.json` | Real content: a small parameter set (cavity radius, cone angle, array density, target coherence, `stabilization_C_eff`) |
| `RELEASE_NOTES_v0.1.md` | Real content: v0.1 release notes describing the intended feature set |
| `requirements.txt` | Real content: `mpmath`, `numpy`, `matplotlib` |
| `LICENSE` | Apache License 2.0 |
| `fsot_grebennikov_cse_levitation_sim.py` | Placeholder (one line of text) |
| `analyze_sweeps.py`, `campaign.py`, `dashboard_server.py`, `experiment_runner.py`, `generate_openscad.py`, `recommended_params.py`, `results_dashboard.py`, `sensitivity_analysis.py` | Placeholders (one line of text each) |
| `fsot_grebennikov_cse_paper.tex` | Placeholder (says the LaTeX source "goes here") |
| `Grebennikov_CSE_FSOT_Report.md`, `PHYSICAL_EXPERIMENT_PROTOCOL.md`, `docs/index.html` | Placeholders (one line of text each) |

So there is nothing to install or run yet. The `.py` files are not valid Python.

## Intended scope (from the release notes and earlier README)

- A tunable Python simulator that gets FSOT constants (e.g. `C_eff`, `A_bleed`) from the FSOT computational engine
- Force scaling calibrated to Grebennikov's reported payload claims
- A proposed `CSE_BioLevitation` FSOT domain
- Parameter export for metamaterial / 3D-printed cavity lattices (see `fsot_cse_tech_params.json`)
- Closed-loop control from ESP32 multi-sensory input (see `HARDWARE_SKETCH.md`)
- A LaTeX research paper

These describe Grebennikov's historical *claims* as a modelling target. This repo contains no experimental or simulation results.

## License

Apache License 2.0. See [LICENSE](LICENSE).

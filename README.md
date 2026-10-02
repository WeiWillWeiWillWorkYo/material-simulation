# Unified Material Simulation Framework for Physical AI

Wei CUI · University of Tsukuba

[Watch the gallery](https://weiwillweiwillworkyo.github.io/material-simulation/)

## Research directions

The public page also introduces three proposed collaboration themes, with Japanese explanations, expandable English summaries, responsive keyword relationship diagrams and annotated primary references:

1. [Sim-to-Real-to-Sim reinforcement learning](https://weiwillweiwillworkyo.github.io/material-simulation/#sim-real): update robot policies and physical models using real-world feedback.
2. [A physics-based data factory](https://weiwillweiwillworkyo.github.io/material-simulation/#data-factory): generate validated, structured physical trajectories across materials and conditions.
3. [GNN simulators](https://weiwillweiwillworkyo.github.io/material-simulation/#gnn): investigate whether unified state and interaction representations help learned dynamics generalize.

These are research proposals, separate from the demonstrated material-behaviour films. FP64 is a numerical foundation, not a guarantee of physical fidelity. No real-robot transfer results, GNN benchmarks or product integrations are claimed.

References include SimOpt (ICRA 2019), NVIDIA Newton, NVIDIA Physical AI Data Factory / Replicator, GNS (ICML 2020), MeshGraphNets (ICLR 2021), and NVIDIA's floating-point documentation. Each reference's role is explained [on the page](https://weiwillweiwillworkyo.github.io/material-simulation/#references).

An external architecture figure from the GNS paper is reproduced with attribution under CC BY 4.0. See [figure credits](assets/references/ATTRIBUTION.md). The other relationship diagrams are native HTML/CSS and reflow for mobile screens. No external scripts, fonts or hotlinked images are required.

## Material-behaviour gallery

Updated 2026-10-02: 11 completed films — 2 Elastic, 2 Rigid, 3 Plastic flow and 4 Elastoplastic.
Each completed film is an original 8-second, 1920 × 1080, 480-frame MP4 at 60 FPS, playable inline.

| No. | Material | Fracture setting | Behaviour | Video |
|---|---|---|---|---|
| 1 | elastic | Breakable | — | [MP4](assets/scenes/elastic-breakable.mp4) |
| 2 | elastic | Unbreakable | — | [MP4](assets/scenes/elastic-unbreakable.mp4) |
| 3 | rigid | Breakable | — | [MP4](assets/scenes/rigid-breakable.mp4) |
| 4 | rigid | Unbreakable | — | [MP4](assets/scenes/rigid-unbreakable.mp4) |
| 5 | plastic | Breakable | Flow rate λ = 5 s⁻¹ | [MP4](assets/scenes/plastic-fast-breakable.mp4) |
| 6 | plastic | Unbreakable | Flow rate λ = 5 s⁻¹ | [MP4](assets/scenes/plastic-fast-unbreakable.mp4) |
| 7 | plastic | Breakable | Flow rate λ = 0.5 s⁻¹ | [MP4](assets/scenes/plastic-slow-breakable.mp4) |
| 8 | elastoplastic | Breakable | Limited yielding | [MP4](assets/scenes/ep-earlier-breakable.mp4) |
| 9 | elastoplastic | Unbreakable | Limited yielding | [MP4](assets/scenes/ep-earlier-unbreakable.mp4) |
| 10 | elastoplastic | Breakable | Widespread yielding | [MP4](assets/scenes/ep-updated-breakable.mp4) |
| 11 | elastoplastic | Unbreakable | Widespread yielding | [MP4](assets/scenes/ep-updated-unbreakable.mp4) |

The page is Japanese/English. Original MP4 bytes are preserved: no re-encoding, retiming or omitted frames.
Different recipes are behaviour demonstrations, not a controlled one-parameter comparison or calibrated material measurements.
The two Plastic flow rates also use different fracture capacities. Elastoplastic films are grouped by limited or widespread yielding and by fracture setting.
Both limited-yielding and widespread-yielding Elastoplastic groups include breakable and unbreakable films.

The previous four-material demonstration and two comparison videos are no longer displayed. Their files remain in the repository/history; this update deletes no original media.
Source paths, media hashes and video metadata are recorded in `gallery.json`. The simulator and physical trajectories are not uploaded here.

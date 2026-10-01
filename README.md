# Unified Material Simulation Framework for Physical AI

Wei CUI · University of Tsukuba

[Watch the gallery](https://weiwillweiwillworkyo.github.io/material-simulation/)

Updated 2026-10-02: 10 completed films and one pending Elastoplastic unbreakable film with widespread yielding.
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

The page is Japanese/English. Original MP4 bytes are preserved: no re-encoding, retiming or omitted frames.
Different recipes are behaviour demonstrations, not a controlled one-parameter comparison or calibrated material measurements.
The two Plastic flow rates also use different fracture capacities. Elastoplastic films are grouped by limited or widespread yielding and by fracture setting.
The widespread-yielding EP unbreakable card is a placeholder, with no substitute or incomplete video.

The previous four-material demonstration and two comparison videos are no longer displayed. Their files remain in the repository/history; this update deletes no original media.
Source paths, media hashes and video metadata are recorded in `gallery.json`. The simulator and physical trajectories are not uploaded here.

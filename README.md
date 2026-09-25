# Silent Hills P.T. Port

Experimental research toward a standalone, data-compatible P.T. runtime for macOS and Windows. This is an unofficial project. No playable release is available from this repository.

## Current status (25 September 2026)

- A local Godot prototype boots into a reconstructed opening room. A source-backed clock reproduces a limited set of authored opening messages and visibility changes.
- The original opening cinematic, actor and camera handover, authentic completion event, and release of player control are still unresolved. Normal boot deliberately keeps movement locked. The game cannot currently be played through.
- A separately labelled hallway checkpoint and actor diagnostics support development; they do not establish original opening progression.
- A local macOS test package exports and starts with the same blocked-opening behavior. Windows execution has not been verified.
- The latest local verification run executed 926 checks with no failures or skips, while recorded original-source hashes remained unchanged. These checks cover components and regressions, not an end-to-end playthrough.

The next milestones are authentic opening playback and completion, validated character animation and camera behavior, then playable progression beyond the opening. Windows packaging and testing will follow a working runtime.

This public repository is a project-status placeholder. It contains no original P.T. package, extracted game assets, game executable, or playable build.

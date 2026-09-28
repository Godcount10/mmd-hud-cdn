# MMD HUD release assets

Public, versioned assets for the Jianghu HUD. This repository contains release
files only; the application source remains in its development repository.

- `assets/characters/`: transparent character atlases and their coordinate metadata.
- `assets/lighting/`: optional, geometry-bound ambient-occlusion data for three scenes.
- `runtime/`: reserved for future built Host/Frame code and lazy-loaded chunks.

Runtime URLs should pin a full commit SHA. Keep each atlas with its matching
metadata, and regenerate ambient-occlusion data when its scene geometry changes.

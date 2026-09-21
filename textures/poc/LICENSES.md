# POC texture asset manifest

This folder is reserved for temporary third-party proof-of-concept texture assets only.

## Approved temporary sources

| Asset | Intended use | Source | License | Status |
| --- | --- | --- | --- | --- |
| `car/` | Temporary vehicle textures / reference maps | Kenney Car Kit — https://kenney.nl/assets/car-kit | CC0 1.0 | No texture files currently required by the imported POC car runtime assets |
| `fx/` | Temporary 2D racing/HUD/effect references | Kenney Racing Pack (2D) — https://kenney.nl/assets/racing-pack | CC0 | Placeholder folder only; no third-party files imported yet |

## Rules

- Keep all proof-of-concept textures isolated under `client/static/textures/poc/`.
- Optimize imported textures before using them on mobile/web builds.
- Remove or replace temporary textures before shipping final art.

## Current car status

- No standalone texture files are currently committed for the imported Kenney `sedan.glb` POC car runtime assets.
- The derived runtime GLBs were exported without a texture dependency to keep the mobile/web payload small.

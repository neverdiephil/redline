# POC model asset manifest

This folder is reserved for temporary third-party proof-of-concept model assets only.

## Approved temporary sources

| Asset | Intended use | Source | License | Status |
| --- | --- | --- | --- | --- |
| `car/chassis.glb`, `car/wheel.glb` | Temporary player/opponent road-car runtime meshes derived from Kenney Car Kit `sedan.glb` | Kenney Car Kit — https://kenney.nl/assets/car-kit | CC0 1.0 | Imported and converted for runtime use |
| `track/` | Temporary racing props / roadside geometry | Kenney Racing Kit — https://kenney.nl/assets/racing-kit | CC0 1.0 | Placeholder folder only; no third-party files imported yet |
| `city/` | Temporary modular street or city-block pieces | Quaternius Modular Streets Pack — https://quaternius.com/packs/modularstreets.html | CC0 | Placeholder folder only; no third-party files imported yet |

## Rules

- Keep all proof-of-concept assets isolated under `client/static/models/poc/`.
- Prefer GLB/glTF runtime assets.
- Replace or remove temporary assets before shipping final art.

## Imported car details

- Source asset: `sedan.glb` from Kenney Car Kit
- Runtime files:
  - `client/static/models/poc/car/chassis.glb` — extracted body mesh, converted to Redline's Z-up/+X-forward orientation and recolored at runtime
  - `client/static/models/poc/car/wheel.glb` — extracted centered wheel mesh, converted to Redline's wheel orientation
  - `client/static/models/poc/car/antena.glb` — empty local placeholder so unsupported antenna fallback does not float on the POC body
  - `client/static/models/poc/car/backLightsBrake.glb` — empty local placeholder because the Kenney sedan rear lights are baked into the body texture
  - `client/static/models/poc/car/backLightsReverse.glb` — empty local placeholder because the Kenney sedan rear lights are baked into the body texture

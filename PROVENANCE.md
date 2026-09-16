# Public artifact provenance

## Reviewed artifact

- Source repository: `krona720/economic-data-repository`
- Reviewed source commit: `c38d8637553eefeef9073fc9516a6b17615b151a`
- Source path: `m3_explorer.html`
- Public artifact path: `site/m3_explorer.html`
- Bytes: `94668`
- SHA-256: `92957d6d03b8369aa0d0995489c26141e9046e2d7626f47bd2e5531584031220`
- Artifact state: fixed snapshot; no automatic refresh

## Census M3 inputs embedded in the reviewed artifact

Publisher: U.S. Census Bureau, Manufacturers' Shipments, Inventories, and Orders program. Retrieved from official public routes on `2026-09-15T18:31:38Z`.

| Measure | Official source | SHA-256 |
|---|---|---|
| Shipments | https://www.census.gov/manufacturing/m3/prel/historical_data/histshts/naics/naicsvsp.xlsx | `1dc7167dc715443ba64c5a6ba43214dafba696fe675afa51843b73d321dd3e6a` |
| New orders | https://www.census.gov/manufacturing/m3/prel/historical_data/histshts/naics/naicsnop.xlsx | `34379ce8070c0b269fd166e1569f7f8ee8aa9a8fbd9be0185cccf8a76939642f` |
| Unfilled orders | https://www.census.gov/manufacturing/m3/prel/historical_data/histshts/naics/naicsuop.xlsx | `a4cb7072781fbcc3b46c701103868e63e15ac553e7478315744d2f9ddaaeb325` |

The workbooks are not redistributed in this repository. The HTML contains the reviewed aggregate rendered dataset, source links, attribution, and limitations.

## Treasury context embedded in the reviewed artifact

- Publisher: U.S. Department of the Treasury, Bureau of the Fiscal Service
- Dataset: Monthly Treasury Statement
- Official source: https://fiscaldata.treasury.gov/datasets/monthly-treasury-statement/
- Metadata retrieval: `2026-09-15T12:49:09-04:00`

This is descriptive cash-flow context only. It is not cyclically adjusted, is not BEA accrual accounting, does not identify household or project incidence, and does not select an exact net-interest treatment. No Treasury source payload is redistributed here.

## Publication boundary

Only `site/m3_explorer.html` is eligible for a future Pages artifact. Repository documentation is not part of the Pages artifact. No private repository tree, broader weighted dashboard, source pack, API, order-level data, credentials, coordination record, build input, model, control, schedule, or refresh code is included.

# Economic Dashboard Public — M3 Explorer

This repository contains one reviewed, fixed-snapshot public dashboard artifact:

`site/m3_explorer.html`

If GitHub Pages is approved later, the contents of `site/` are intended to be the complete Pages artifact. The public page path will be `/m3_explorer.html`. There is deliberately no `index.html`, so the repository Pages root remains a 404 rather than exposing a broader dashboard.

## Scope

The page presents aggregate U.S. Census Bureau Manufacturers' Shipments, Inventories, and Orders data for five durable-manufacturing subsectors:

- shipments;
- net new orders; and
- unfilled orders.

It also shows separately labeled public Monthly Treasury Statement context. That context does not feed the M3 charts, comparisons, values, or exports.

## Limits

- The M3 history is current revised history, not a frozen release vintage.
- Values are seasonally adjusted millions of current dollars and are not inflation adjusted.
- Net new orders are not gross bookings.
- Unfilled orders are aggregate end-of-period backlog, not order-level, buyer, destination, delivery, acceptance, cancellation, amendment, repricing, or representative-population evidence.
- The artifact makes no causal, predictive, production-model, or source-admission claim.
- This repository has no data-refresh workflow. The snapshot changes only through a separately reviewed update.

See [PROVENANCE.md](PROVENANCE.md) and [ARTIFACT_MANIFEST.json](ARTIFACT_MANIFEST.json) for the exact reviewed snapshot and hashes.

GitHub Pages is not enabled or deployed by this artifact-preparation pull request.

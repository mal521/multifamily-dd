# due diligence | Multi-Family - Snapshot

**Date:** 2026-03-05
**Status:** Feature-complete, deployed, part of 3-site suite

## What's Built
Single-page multi-family investment property financial model supporting 2-20 units.
Vaporwave design with dark/light mode, dot grid, scroll-reveal animations.

## Recent Changes (2026-03-05)
- Fixed capital gains tax (was collected but never applied to sale proceeds)
- Clamped IRR Newton-Raphson solver to prevent divergence
- Added division-by-zero guard in calcMonthlyPayment
- Consolidated duplicate units/unitCount variables
- Simplified tax savings calculation (removed no-op ternary)
- Removed unused params and redundant init calls
- Migrated all deployment references from Netlify to GitHub Pages

## Sister Sites
- **ADU:** https://mal521.github.io/adue-diligence
- **Single-Family:** https://mal521.github.io/single-family-dd
- **Multi-Family:** https://mal521.github.io/multifamily-dd (this site)

## Key Files
- `index.html` - entire app (single file)
- `README.md` - project description

## Deployment
- **URL:** https://mal521.github.io/multifamily-dd
- **Method:** GitHub Pages (auto-deploys from main branch)

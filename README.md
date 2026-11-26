# CICAN ECOLOOP

**Earn. Equate. Recycle.**

A mobile-first personal environmental tracker connecting survey earnings, time invested, deposit-value container equivalents, and physical recycling records.

## V1 features
- Survey bank with pending, approved and paid statuses
- Time-to-value calculator and reverse target calculator
- Separate 15c and 25c physical recycling log
- Personal recycling goal and dashboard
- Local browser storage with JSON backup/restore and CSV export
- Recycling book link section

## Run locally
Open `index.html` in a modern browser. Records are stored locally in that browser. Export JSON backups regularly.

## GitHub Pages deployment
1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment → Source**, select **GitHub Actions**.
3. The workflow in `.github/workflows/deploy.yml` will publish the site after a push to `main` or a manual workflow run.
4. Check **Actions** and wait for **Deploy CICAN ECOLOOP to GitHub Pages** to complete successfully.

Expected website URL: https://cicangeorgealin.github.io/cican-ecoloop/

## Data and accounting principles
- Calculated container equivalents are estimates, not physical recycling.
- Only approved or paid survey entries count towards confirmed equivalents.
- Physical recycling totals are based on explicitly recorded returned containers.
- Refund estimates use €0.15 and €0.25 values; check current Irish scheme eligibility and rules before returning containers.
- Records are stored in the browser on the device used. Export JSON backups to move or protect your data.

© CICAN GEORGE ALIN · CICAN ECOLOOP
# FRAMECHECK — Jason Duval Edition

Minimalist, single-page PC selector and speculative GTA VI FPS estimator.

## Important accuracy note
GTA VI PC system requirements and verified PC benchmarks are not available in this project. The displayed FPS is a speculative heuristic estimate, not a sourced GTA VI benchmark or a guarantee. The range is intentionally broad and confidence is low. Do not use it as proof that a particular PC will run GTA VI at a given frame rate.

## Features
- Jason Duval hero image only
- GPU options covering NVIDIA, AMD, Intel, desktop and laptop variants
- CPU options covering AMD Ryzen and Intel Core
- RAM selection (8–64 GB)
- Storage selection (NVMe SSD, SATA SSD, HDD)
- Resolution and graphics preset selectors
- Instant estimated FPS recalculation
- Responsive layout; no external libraries or build process

## Run locally
Open `index.html` in a modern browser.

## GitHub Pages
1. Create a repository, e.g. `framecheck-jason`.
2. Upload `index.html` and `README.md` to the repository root.
3. Go to Settings → Pages.
4. Choose Deploy from a branch, `main`, and `/(root)`.
5. Save. Your site will appear at `https://YOUR-USERNAME.github.io/framecheck-jason/`.

## Model disclosure
The FPS midpoint is a simple heuristic: reference baseline × relative GPU tier × resolution multiplier × quality multiplier × CPU factor × RAM factor. It is not calibrated against a GTA VI PC build. Storage is displayed but does not change FPS.

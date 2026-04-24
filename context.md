# Website Build Context (GitHub Pages)

## Environment Overview
Static website hosted on GitHub Pages. No backend or server-side execution allowed.

## Core Structure
- **Primary File:** `index.html` (Must be in root)
- **Architecture:** Single-file design. All HTML, CSS, and JS are contained in `index.html` to ensure reliability and simplicity.

## Current Architecture (Updated April 2026)
- **Sidebar Navigation:** A fixed sidebar menu allows users to navigate between "Home", "The Vault", and "About".
- **Single-Page Application (SPA) Logic:** JavaScript handles smooth transitions between different `<section>` blocks, giving a multi-page feel while remaining a single file.
- **The Vault:**
    - **Public Data:** Ratings are "baked" into the `PUBLIC_DRINKS` constant.
    - **Hybrid Storage:** Merges public data with `localStorage` for personal additions.
    - **Comparison Tool:** A Radar Chart (Chart.js) compares up to 3 selected drinks.

## GitHub Pages Deployment
- Repository: `SamPendergest/Energy-Enthusiast`
- URL: `https://sampendergest.github.io/Energy-Enthusiast/`
- Files are maintained in the root directory for direct deployment.

## Repository Cleanup
- Removed unrelated notes and temporary folders to keep the repository focused strictly on the website deployment.

---
## Objective
Maintain a visually impactful, highly functional, yet simple-to-maintain website. Priority is on stability, smooth user experience, and visual polish.

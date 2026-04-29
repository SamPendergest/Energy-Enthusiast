# Website Build Context (The Rush Rater)

## Project Overview
A personal energy drink rating vault built for a university class, developed with assistance from Google Gemini.

## Environment & Deployment
- **Platform:** GitHub Pages (Static Hosting)
- **URL:** https://sampendergest.github.io/Energy-Enthusiast/
- **Repository:** SamPendergest/Energy-Enthusiast (Files located in root)
- **Build Fix:** Added `.nojekyll` to bypass Jekyll processing and fix deployment errors.

## Core Architecture
- **Single-File Design:** `index.html` contains all HTML, CSS, and JS.
- **Multi-Page Sidebar UI:** Navigation between Home, Vault, Suggestions, and About using JavaScript transitions.
- **The Vault Logic:** 
  - Ratings stored permanently in `PUBLIC_DRINKS`.
  - **Sorting System:** Added dropdown to sort by Top Rated, Brand, Name, and Newest.
  - Features a Radar Chart for comparison.
- **Suggestions Page:** Functional form that pre-fills an email (`mailto:`) for user recommendations.
- **Cyberpunk Aesthetic:** 
  - Vibrant Red/Blue theme.
  - **Hall of Fame Effect:** Added pulsing glow and scanline animation to the top-rated drink.

## Status (End of Session - April 28, 2026)
- **New Features:** Sorting system and Suggestions page are fully functional.
- **Visuals:** Hall of Fame glitch effect implemented.
- **File Structure:** All files (`index.html`, `context.md`, `.nojekyll`) are in the root directory.
- **Deployment:** GitHub Pages is live and stable.

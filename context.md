# Website Build Context (The Rush Rater)

## Project Overview
A personal energy drink rating vault built for a university class, developed with assistance from Google Gemini.

## Environment & Deployment
- **Platform:** GitHub Pages (Static Hosting)
- **URL:** https://sampendergest.github.io/Energy-Enthusiast/
- **Repository:** SamPendergest/Energy-Enthusiast (Files located in root)

## Core Architecture
- **Single-File Design:** `index.html` contains all HTML, CSS, and JS.
- **Multi-Page Sidebar UI:** A fixed sidebar handles navigation between Home, Vault, Suggestions, and About sections using JavaScript transitions.
- **The Vault Logic:** 
  - Ratings are stored permanently in the `PUBLIC_DRINKS` array.
  - Features a Radar Chart for drink comparison (up to 3 drinks).
  - Dashboard tracks Total Rated, Average Rating, Top Brand, and Hall of Fame.
- **Suggestions Page:** A form that allows users to send drink suggestions via email (`mailto:`).

## Status (End of Session - April 28, 2026)
- **Suggestions Page:** Added a new page for users to submit drink recommendations.
- **Edit Feature:** Successfully implemented to update ratings and then removed from the UI as requested to maintain a clean interface.
- **Ratings Update:** All drink ratings in `PUBLIC_DRINKS` have been updated to the latest values as of today.
- **File Structure:** `index.html` and `context.md` are correctly located in the root directory for GitHub Pages deployment.
- **Deployment:** Live site is stable and reflecting all permanent changes.

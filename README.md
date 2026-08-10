# ASBOG Study App

A self-contained browser study application for ASBOG Fundamentals of Geology (FG) preparation.

## Current v5 features

- 580 original practice questions
- 80 dedicated visual/scenario questions using 16 reusable figures
- Foundation Review, Standard FG, Advanced FG, and Challenge levels
- Mixed, domain, calculation, visual, scenario-set, and review modes
- 140-question FG Exam Simulation
- Balanced correct-answer positions across A/B/C/D
- Review Queue filters
- New / Learning / Strong / Mastered tracking
- Performance by domain and difficulty
- Built-in Quick Reference and Help / README
- Local browser progress plus JSON Export / Import

## Run locally

Open `index.html` in Chrome or Edge.

## GitHub Pages

This repository can be published directly with GitHub Pages because the application is static HTML/CSS/JavaScript.

1. Create a GitHub repository.
2. Upload `index.html` and this `README.md` to the repository root.
3. Open repository **Settings → Pages**.
4. Publish from the branch containing `index.html`.

## Cross-device progress

The current version stores progress in browser local storage. GitHub Pages hosts the application but does **not** by itself synchronize progress across devices.

Automatic work/home synchronization requires a backend/authentication service such as Supabase. That integration is the next architecture step and should be added before calling the site a multi-device cloud application.

## Disclaimer

Independent study aid. Not affiliated with, endorsed by, or published by ASBOG. Questions are original practice items, not actual ASBOG examination questions.

# RP Shot Model v2

A lightweight static web app for repeated Research Proposal calibration practice.

## Core model

- One **Original RP** is a **match**.
- Each RP section can produce multiple small **adjustment targets**.
- A target is a direction worth exploring, not a correction.
- Each target can receive many low-cost **shots**.
- Any shot can branch into a child target, so practice grows like a tree / pyramid.
- Section bars count calibration shots only. They are not scores or mastery indicators.

## GitHub Pages

Upload `index.html`, `.nojekyll`, and `README.md` to the repository root, then use **Settings → Pages → Deploy from a branch → main → / (root)**.

## Storage

Data is stored locally in the browser with `localStorage` under a new v2 key, so the old version's browser data is not overwritten.

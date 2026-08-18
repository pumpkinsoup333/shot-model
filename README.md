# RP Shot Model

A lightweight personal practice log for Research Proposal (RP) training.

## Run locally

Open `index.html` directly in a browser.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload all files in this folder to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)`
5. Save. GitHub Pages will publish the site from `index.html`.

## Data

Shot records are stored in the browser's `localStorage`.

That means:
- no backend or database is required;
- data stays in the browser/device where you entered it;
- opening the site on another device or browser will not automatically show the same records;
- clearing site data may remove saved records.

## Project structure

- `index.html` — complete app
- `.nojekyll` — tells GitHub Pages to serve the static files directly
- `README.md` — setup notes

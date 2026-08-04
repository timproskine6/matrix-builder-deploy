# Cause & Effect Matrix Builder

A self-contained, single-file web app for building fire alarm (or any) system
input → output cause-and-effect matrices, and exporting the result as a DXF
drawing styled to match a traditional matrix/point-list sheet.

Pre-loaded with the 57 system inputs and 41 system outputs (and their existing
relationships) from an approved fire alarm plan set, grouped by category. You
can select any input, check which outputs it triggers, edit/add/remove
inputs, outputs, and categories, then export:

- **DXF** — a CAD-ready drawing matching the source matrix's layout style
  (rotated headers, category bands, filled dots).
- **JSON** — the full data set, for saving your work or reloading it later.

## Run it

Just open `index.html` in any browser — no build step, no server, no
dependencies. It also works as a static site (see below).

## Hosting on GitHub Pages

This repo is set up to be served directly:

1. Go to the repo's **Settings → Pages**.
2. Under "Build and deployment", set **Source** to `Deploy from a branch`.
3. Branch: `main`, folder: `/ (root)`.
4. Save. GitHub will publish the site at
   `https://<your-username>.github.io/<repo-name>/` within a minute or two.

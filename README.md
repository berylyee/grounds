# Grounds — a diary of coffees

A mobile-friendly personal archive for specialty coffee tastings.

## Files

- `index.html` — the complete website. HTML, styling, illustrations, coffee records, search, filters, and detail views are all included in this file.
- `.nojekyll` — tells GitHub Pages to serve the site without running Jekyll.

No build step or extra assets are required. The site uses Google Fonts when an internet connection is available and falls back to system fonts otherwise.

## Publish with GitHub Pages

1. Create a new **public** GitHub repository.
2. Upload `index.html`, `README.md`, and `.nojekyll` directly into the repository's root (not inside another folder).
3. Commit the files to the `main` branch.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
6. Wait a few minutes for the site to publish. GitHub will show the website URL in the Pages settings.

Coffee records and their tasting dates are stored near the top of the `<script>` section in `index.html`, in the `coffees` array. The entries are displayed newest first based on their dates.

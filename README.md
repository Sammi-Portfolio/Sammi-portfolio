# Sammi Teki Portfolio

Static portfolio site ready for Vercel deployment.

## Deploy on Vercel

1. Push this repository to GitHub.
2. In Vercel, import the GitHub repository.
3. Select framework: **Other**
4. Build command: **leave empty**
5. Output directory: **leave empty**

The deployment serves `index.html` and `assets/` directly from the repository root.

## Project Structure

- `index.html` — the production entry point
- `assets/` — images and icons served by the live site
- `vercel.json` — Vercel configuration for static deployment
- `.gitignore` — Git configuration

## Assets

All images referenced in the HTML use relative or root-based paths pointing to `/assets/`:

- `home-background-clean.png` — full-screen homepage background
- `icon-compass.png`, `icon-person.png`, `icon-folder-file.png`, `icon-world.png` — desktop app icons
- `ie.png` — Internet Explorer icon
- Other panel and culture images

## Notes

- No build process is required.
- The site is fully static HTML, CSS, and JavaScript.
- All assets must remain in the root-level `assets/` folder.

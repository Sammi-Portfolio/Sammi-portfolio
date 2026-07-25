# Sammi Teki Portfolio

Static portfolio site ready for GitHub-backed Vercel deployment.

## Deploy on Vercel

1. Push this folder to a GitHub repository.
2. In Vercel, import the GitHub repository.
3. Leave the framework preset as `Other`.
4. Leave the build command empty.
5. Leave the output directory empty.

The `vercel.json` file routes `/` to `outputs/index.html` and `/assets/*` to `outputs/assets/*`.

## Project Structure

- `outputs/index.html` - the portfolio page
- `outputs/assets/` - images and icons used by the page
- `vercel.json` - static routing for Vercel
- `.gitignore` - keeps local dependencies, env files, build output, and scratch files out of Git

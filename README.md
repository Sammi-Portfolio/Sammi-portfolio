 t# Sammi Teki Portfolio

Static portfolio site ready for GitHub-backed Vercel deployment.

## Deploy on Vercel

1. Push this folder to a GitHub repository.
2. In Vercel, import the GitHub repository.
3. Leave the framework preset as `Other`.
4. Leave the build command empty.
5. Leave the output directory empty.

The live deployment serves `index.html` and `assets/` directly from the repository root.

## Project Structure

- `index.html` - the portfolio page served in production
- `assets/` - images and icons used by the live page
- `outputs/` - retained source/export copy of the same static site
- `vercel.json` - simple static-site configuration for Vercel
- `.gitignore` - keeps local dependencies, env files, build output, and scratch files out of Git

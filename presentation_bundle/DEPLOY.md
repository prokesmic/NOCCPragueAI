# Deploy to Vercel via GitHub

This folder is ready for static deployment.

## Contents
- `index.html`
- `slide0.mp4` (54 MB, GitHub-safe)
- `slide1.png` ... `slide18.png`

## Option A: New GitHub repo from this folder (recommended)
1. Create a new empty GitHub repository (no README/license).
2. Upload all files from this folder to the repo root using GitHub web UI, or push with git.
3. In Vercel:
   - New Project -> Import Git Repository
   - Select this repo
   - Framework Preset: `Other`
   - Build Command: leave empty
   - Output Directory: leave empty
   - Deploy

## Option B: Existing mono-repo
1. Commit this folder as `presentation_bundle/` in your existing repo.
2. In Vercel project settings set Root Directory to `presentation_bundle`.
3. Redeploy.

## Notes
- Video sound on first load requires a user click in most browsers (browser autoplay policy).
- First click on intro slide enables sound; next click moves to Slide 1.

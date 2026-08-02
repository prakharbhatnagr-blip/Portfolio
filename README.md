# Prakhar Bhatnagar — Portfolio

A single self-contained static site (no build step, no dependencies).

## Files
- `index.html` — the entire site (HTML/CSS/JS in one file)
- `prakhar-photo.png` — your portrait, must stay in the same folder as `index.html`
- `Prakhar_Bhatnagar_Resume.pdf` — downloadable CV, linked from the hero and contact sections
- `vercel.json` — caching config for deployment

## Deploy to Vercel

**Option A — Vercel CLI (fastest)**
```bash
npm i -g vercel
cd path/to/this-folder
vercel --prod
```
Follow the prompts (pick "N" for linking to an existing project the first time). Vercel auto-detects this as a static site — no framework preset or build command needed.

**Option B — Drag and drop**
1. Go to https://vercel.com/new
2. Drag this whole folder onto the page
3. Deploy — done in a few seconds

**Option C — GitHub**
1. Push these 3 files to a new GitHub repo
2. Import the repo at https://vercel.com/new
3. Leave Framework Preset as "Other" — no build command, output directory is the repo root
4. Deploy

## Editing later
Everything lives in `index.html` — sections are clearly commented (`<!-- ============ HERO ============ -->` etc.). Colors, fonts and spacing are all CSS variables at the top of the `<style>` block if you want to tweak the theme.

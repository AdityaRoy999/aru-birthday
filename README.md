# Prepare project for Vercel

This repository contains a static HTML birthday site. Changes made to better support Vercel deployment:

- Added a hyphenated copy of the "why" page at `/why-you-are-special/` (Vercel-friendly path).
- Added `vercel.json` with `cleanUrls` enabled.

Notes and recommendations:

- Filenames with spaces remain as-is (images / videos). Vercel will still serve them, but renaming binary files is recommended for cleaner URLs. If you want, I can rename them and update all references.
- To deploy: install the Vercel CLI (`npm i -g vercel`) or use the Vercel dashboard and point it at this repo. Then run:

```bash
vercel --prod
```

If you want me to continue: I can normalize filenames (replace spaces with hyphens), move static assets into a `public/` folder, and update links across HTML files.

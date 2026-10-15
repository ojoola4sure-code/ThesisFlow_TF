# ThesisFlow website

Static site (no build step). Deploy to Vercel:

**Option A - drag and drop / CLI**
1. Install the CLI: `npm i -g vercel`
2. In this folder run `vercel` (preview) then `vercel --prod`.

**Option B - GitHub**
1. Push this folder to a GitHub repo.
2. On vercel.com choose *Add New > Project*, import the repo.
3. Framework Preset: **Other**. Build command: leave empty. Output directory: leave empty (root). Click Deploy.

## Editing
- Prices, tier text and WhatsApp link: `index.html` (search `20,000`, `45,000`, `80,000`, and `const WA`).
- Logo and institution images: `assets/`.
- Local preview: `npx serve .`

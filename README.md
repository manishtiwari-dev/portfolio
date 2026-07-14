# Manish Tiwari — Portfolio

A single static `index.html` (no build step, no dependencies). The resume PDF is embedded directly in the page, so the "Download Resume" button works with zero backend.

## Deploy to Vercel (2 options)

### Option A — Drag & drop (no install needed)
1. Go to https://vercel.com/new
2. Choose "Deploy without Git" / drag-and-drop
3. Drag this whole folder onto the page
4. Click Deploy — you'll get a live `.vercel.app` URL in ~10 seconds

### Option B — Vercel CLI
```bash
npm i -g vercel
cd portfolio
vercel        # follow prompts, deploys a preview
vercel --prod # promotes to your production URL
```

## Custom domain
In the Vercel dashboard → your project → Settings → Domains → add your domain (e.g. manishtiwari.dev) and follow the DNS instructions shown.

## Editing content
Everything lives in `index.html` — text, styles, and script are all in one file. Search for the section you want (nav, hero, stack, experience, work, education, contact) and edit directly.

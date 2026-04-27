# Pagzen Website — Production Build

Deploy this folder to Vercel, Netlify, or any static host.

## Vercel (CLI)
```
npm i -g vercel
cd dist
vercel
```
Then add your custom domain (pagzen.io) in the Vercel dashboard under Settings → Domains.

## Vercel (drag & drop)
1. Go to vercel.com → Add New → Project → "Deploy without Git"
2. Drag this entire `dist` folder
3. Done — Vercel assigns a *.vercel.app URL.

## Netlify
Drag this folder to https://app.netlify.com/drop

## Custom domain (pagzen.io)
In your host's dashboard → Domains → Add `pagzen.io` → copy the DNS records → paste them at your domain registrar.

## Structure
- index.html      — the site
- styles.css      — brand tokens + typography + layout
- assets/         — logos, imagery, client logos
- fonts/          — Dongle (display) + Roboto (body) TTFs

# The TEN – Website

A multi‑page React site (Vite + Tailwind) for The TEN Network.

## Quick start
```bash
npm install
npm run dev        # local preview
npm run build      # production build
```

## Deploy to Vercel
1. Create a free account at https://vercel.com and click **New Project**.
2. Import this repo from GitHub or upload the folder.
3. Vercel auto-detects Vite and builds the site.
4. Add your custom domain `thetennetwork.org` in Project → Settings → Domains.

## Edit content
- **Visual edits (optional):** connect Plasmic for no-code editing.
- **Code edits:** edit files in `src/` (e.g., `App.jsx`) and push to GitHub; Vercel redeploys automatically.

## Stripe
Replace `STRIPE_CHECKOUT_URL` in `src/App.jsx` with your live Stripe Payment Link.

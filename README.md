# Vaishnavi Resin Art — Static Site
This folder contains a single-file website (`index.html`) using Tailwind via CDN. You can deploy it in minutes.

## Quick edit
Open `index.html` and change:
- WhatsApp number (`wa.me/919999999999` and text)
- Instagram handle (`instagram.com/yourhandle` and `@yourhandle`)
- Email (`hello@example.com`)
- Product names/prices and gallery image URLs (can use your own images)

---

## Option A — Netlify (easiest, free)
1. Go to https://app.netlify.com/drop
2. Drag & drop this folder (or the ZIP) — Netlify will deploy instantly.
3. Copy the site URL it gives you (you can rename later under **Site settings → Domain management**).
4. To connect a custom domain (e.g., `vaishnaviresinart.in`), add it under **Domain settings** and follow the DNS steps.

## Option B — Vercel (free)
1. Create a GitHub repo and upload `index.html`.
2. Go to https://vercel.com/new → Import your GitHub repo.
3. Framework preset: **Other** (since it's a static file). Build/Output: none required. Vercel serves `index.html`.
4. After deploy, connect a custom domain from **Settings → Domains** (optional).

## Option C — GitHub Pages (free)
1. Create a repository (e.g., `vaishnavi-resin-art`), put `index.html` at the root.
2. Go to **Settings → Pages** → **Source: Deploy from a branch** → Select `main`, folder `/ (root)`.
3. Your site will be live at `https://<your-username>.github.io/vaishnavi-resin-art`.

---

## Tips
- Replace stock Unsplash images with your own (smaller images load faster).
- Add a payment link (Razorpay payment page or UPI link) if you want instant checkout.
- For a proper contact form, use Formspree or Netlify Forms instead of `mailto:`.
- SEO: update `<title>` and `<meta name="description">` for better search results.

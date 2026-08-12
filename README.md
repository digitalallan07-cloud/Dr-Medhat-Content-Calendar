# Dr. Medhat — Content Calendar

A static, Instagram-grid style social media content calendar for **Dr. Medhat**, a pediatrician. It lays out scheduled posts (Aug 12 – Oct 08, 2026, Wednesdays &amp; Thursdays) as a responsive card grid.

Plain HTML + CSS, no framework, no build step, no dependencies.

## Files

- `index.html` — the full page markup and content
- `styles.css` — all styling
- Post thumbnails are hotlinked directly from Google Drive's image CDN (`lh3.googleusercontent.com`) — no binary assets are stored in this repo.

## Pending content

Every post after Aug 14 is currently a **"Studio Reel"** placeholder using image `1` from the source Drive folder, awaiting real reel content for each date. To fill one in, swap its `<img src>` for the real asset and update the badge/title/category to match.

## Deploying on Vercel

1. Go to [vercel.com/new](https://vercel.com/new) and import this GitHub repository.
2. When prompted for a framework preset, choose **Other**.
3. Leave the **Build Command** empty (no build step required).
4. Set the **Output Directory** to `./`.
5. Click **Deploy**.

That's it — Vercel will serve `index.html` and `styles.css` as static files.

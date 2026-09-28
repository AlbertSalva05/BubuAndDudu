# 1 Year, 9 Months of Us — v1.2.0
A static site: plain HTML, CSS and JavaScript. There is no build step.

## Files
- `index.html` — the site
- `404.html` — the page shown for broken links
- `assets/` — the hero image, plus img_gallery_01–06.jpg
- `render.yaml` — Render config (static site, security headers, caching)
- `robots.txt` — asks search engines not to list the site, since it's private

## Deploy on Render
1. Create a new GitHub repo and upload everything in this folder to the repo root (include `render.yaml`).
2. On render.com, go to **New → Blueprint** and pick the repo. Render reads `render.yaml`, so just click **Apply**.
   Or go to **New → Static Site**, pick the repo, leave the Build Command empty, and set the Publish Directory to `.`
3. Your link will be `https://bubu-dudu-anniversary.onrender.com`. If that name is taken, Render adds a suffix.
4. To update the site later, push to the main branch. Render redeploys automatically.

## Updating photos
Replace the files in `assets/` but keep the same names (img_gallery_01.jpg … 06.jpg). Keep each file under about 250 KB.
Captions are in `index.html`: search for `photo-slot-caption`.

## Checklist before sharing the link
- Open the link on your phone and test the intro, the coaster, the cards, the easter egg and the final button.
- Try the display settings (the Aa button): text size, high contrast, reduced motion.

## Fonts
Instrument Serif, Bricolage Grotesque and JetBrains Mono. All are SIL Open Font License 1.1, loaded from Google Fonts.

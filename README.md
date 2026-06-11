# DraftX marketing site

Single static page (`index.html`) — no build step, no dependencies.

## Preview locally

Just open `index.html` in a browser.

## Deploy options (pick one)

- **Railway** (same place as the license server): create a new service from this repo with a static file server, or serve it from the license server itself.
- **GitHub Pages**: push this folder to a repo, enable Pages on the root — free, with a custom domain (e.g. `draftx.co.uk`).
- **Cloudflare Pages / Netlify**: drag-and-drop the folder — free tier is plenty.

## Before going live

- [ ] Review `screenshots/` for sensitive data — they're from a real job and show the customer name (Projx),
      part numbers, the WB logo on the job card, and UNC server paths. Blur or re-shoot a sanitised demo job
      if needed (re-shoot with `node tools/shoot-ui.js` in the DrawSort repo).
- [ ] Optimise the screenshots (they're 2x PNGs, ~1–3 MB each) — convert to WebP/JPEG ~80% for the web
- [ ] Confirm the contact email (`sales@opusag.co.uk`) exists, or swap for the real one
- [ ] Link the Privacy policy and License agreement footer items to real documents
- [ ] Set up the custom domain and HTTPS

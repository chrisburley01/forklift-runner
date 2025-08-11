# Forklift Runner

A tiny installable PWA endless runner: drive a forklift, pick pallets that match rack colours, dodge cones, collect power-ups, and rack up score.

## Run locally
```bash
python -m http.server 8080
# or
npx serve
```
Then visit http://localhost:8080 and click **Install** in the app header.

## Deploy to GitHub Pages
Push these files to your repo and enable **Pages** (from branch `main`, root folder). Or use the included GitHub Actions workflow.

## Notes
- If you push updates and the site looks stuck, bump the cache name in `service-worker.js` (e.g., forklift-v4) and reload twice.
- Replace icons in `/icons` with your own PNGs (192 & 512).

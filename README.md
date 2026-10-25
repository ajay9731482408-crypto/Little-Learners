# Little Learners

A kids learning web app: worlds, stories, maths, NCERT path, puzzles, songs and an adventure map. Single `index.html`, no build step, works offline once installed.

## Files
- `index.html` – the whole app
- `sw.js`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png` – offline install (PWA)
- `logo/` – owl logo (SVG + PNG)
- `vercel.json` – headers and clean URLs

## Run locally
Open `index.html`, or serve the folder: `npx serve .` (the service worker only works over http/https).

## Deploy on Vercel
1. Push this folder to GitHub.
2. vercel.com → Add New → Project → import the repo.
3. Framework preset: **Other**. Leave build and output settings empty. Deploy.

Progress is saved in the browser (localStorage). No accounts, no ads.

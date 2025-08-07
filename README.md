
# AI Quest — GitHub-ready package

This repo is ready for free hosting on GitHub Pages and includes PWA support.

## Quick start
1. Create a new GitHub repo (public), e.g. `ai-quest`.
2. Upload all files and folders from this ZIP (keep the structure).
3. In your repo: Settings → Pages → Build and deployment → Source: `Deploy from a branch`, Branch: `main`, Folder: `/ (root)` → Save.
4. Wait ~1–2 minutes, then open the Pages URL.

## Edit & update
- Edit `index.html` and push changes. Pages redeploys automatically.

## PWA
- `manifest.webmanifest` and `sw.js` enable install & offline.
- Icons live in `/icons/` and should be updated with your branding.

## Custom domain (www + apex)
- Add a `CNAME` file at repo root with your canonical domain (e.g. `www.example.com`).
- In your DNS provider:
  - Create a CNAME for `www` → `YOUR-USERNAME.github.io`.
  - Create A records for apex (`example.com`) → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153.
- In GitHub: Settings → Pages → Custom domain → enter your domain, check **Enforce HTTPS**.

## Folder structure
- index.html
- manifest.webmanifest
- sw.js
- icons/
  - icon-192.png
  - icon-512.png


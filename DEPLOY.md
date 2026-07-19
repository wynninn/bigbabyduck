# Deploying bigbabyduck.com (GitHub Pages)

The `duck-worlds/` folder is a ready git repo (committed) containing exactly what should be served:
`index.html`, `lib/three.min.js`, `CNAME` (already set to `bigbabyduck.com`), plus docs.

## One-time setup (needs your GitHub login — ~10 minutes)

1. **Create the repo**: github.com/new → name `bigbabyduck` → Public → Create (no README).
2. **Push from this folder** (replace YOURUSER):
   ```
   cd duck-worlds
   git remote add origin https://github.com/YOURUSER/bigbabyduck.git
   git branch -M main
   git push -u origin main
   ```
   (Git will pop up GitHub's browser sign-in the first time.)
3. **Enable Pages**: repo → Settings → Pages → Source: "Deploy from a branch" → Branch `main` / `/ (root)` → Save.
4. **Custom domain**: same Pages screen → Custom domain: `bigbabyduck.com` → Save → tick **Enforce HTTPS** (appears after DNS propagates).

## DNS records (at your domain registrar)

| Type | Host | Value |
|---|---|---|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | YOURUSER.github.io |

Propagation: minutes to a few hours. Then https://bigbabyduck.com is live, HTTPS included, $0/month.

## Updating the game later
Edit `index.html` → `git add -A && git commit -m "..." && git push` → live in ~1 minute.

## Files
- `og-image.png` — link-preview image referenced by the meta tags; keep it in the repo root.
- `dist/bigbabyduck-web.zip` — the itch.io upload (regenerate after changes: see ITCH-PAGE-COPY.md).
- Don't commit `dist/` (it's for itch upload only).

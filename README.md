# Aluno — Minimal Landing (GitHub Pages Ready)

A tiny, responsive landing page matching your Canva mockups.

## What’s included
- `index.html` — the page
- `styles.css` — styling
- `assets/logo.png` — your logo (used in the page)

## How to publish on GitHub Pages
1. Create a public repo (e.g., `aluno-site`) on GitHub.
2. Upload these three items:
   - `index.html`
   - `styles.css`
   - the entire `assets` folder (with `logo.png` inside)
3. Repo → **Settings** → **Pages** → Source: `main` / `/ (root)` → **Save`**.
4. Wait ~1–2 minutes, then visit: `https://YOURUSERNAME.github.io/aluno-site/`.

## Connect your Namecheap domain (optional now, easy later)
- In GitHub **Settings → Pages → Custom domain**, enter `yourdomain.com` and save.
- In Namecheap → Domain List → Manage → **Advanced DNS**, add:
  - A records for `@`:
    - 185.199.108.153
    - 185.199.109.153
    - 185.199.110.153
    - 185.199.111.153
  - CNAME for `www` → `YOURUSERNAME.github.io`
- Back in GitHub Pages, check **Enforce HTTPS** once available.

## Editing locally
- Open `index.html` directly in your browser to preview, or
- Use VS Code + Live Server for instant refresh while editing.

## Troubleshooting
- **Logo not loading?** Make sure the file path is exactly `assets/logo.png` (case-sensitive).
- After edits, do a hard refresh: `Cmd+Shift+R` (Mac) / `Ctrl+Shift+R` (Win).

Enjoy! — Aluno

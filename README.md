# Ratna Wheel — Landing page & legal (GitHub Pages)

Public landing page, Support, and Privacy Policy for App Store Connect and marketing links.

## Live URLs

- **Home (landing page):** https://rigzinratna.github.io/ratnawheel-legal/
- **Support:** https://rigzinratna.github.io/ratnawheel-legal/support.html
- **Privacy:** https://rigzinratna.github.io/ratnawheel-legal/privacy.html

## Publish to GitHub Pages

1. Create a new repository on GitHub named `ratnawheel-legal` (public).
2. Push this folder (see commands below).
3. On GitHub: **Settings → Pages** → Source: **Deploy from branch** → `main` → `/ (root)` → Save.
4. Wait 1–2 minutes, then open the URLs above.

## Push commands

```bash
cd ratnawheel-legal
git init
git add .
git commit -m "Add support and privacy pages for App Store"
git branch -M main
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/ratnawheel-legal.git
git push -u origin main
```

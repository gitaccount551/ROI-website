
# ROI Strategies — One-file Landing Page

This repo contains a single-page, zero-dependency landing page.

## How to use

1) Replace `assets/logo.svg` with your real logo file (PNG or SVG). If you use `logo.png`, update the `src` in `index.html`.

2) Open `index.html` and change:
   - The email in the **Contact us** link (`mailto:hello@roistrategies.us`).
   - The background colors in CSS (`--brand` and `--brand-2`) if you want a different look.
   - The `<title>` and meta description if desired.

3) **Host for free** with one of these:
   - **GitHub Pages** (recommended): push this folder to a repo, enable Pages in *Settings → Pages*, and (optionally) add a custom domain.
   - **Netlify Drop**: drag-and-drop this folder to Netlify (free), then connect your custom domain in Netlify's settings.
   - **Cloudflare Pages**: similar to Netlify; great if your DNS is already on Cloudflare.

### Custom domain on GitHub Pages (roistrategies.us)

- In GitHub, go to *Settings → Pages* for your repo. Enter `roistrategies.us` as the custom domain and save.
- GitHub will show you the DNS records to add. In your DNS provider:
  - Create a **CNAME** for `www` → your `username.github.io` domain.
  - For the apex (`roistrategies.us`), add the **A records** GitHub recommends.
- Keep your **MX** records as-is so email continues to work.
- After DNS propagates, GitHub will issue a free SSL certificate.

> Tip: If you use only `www.roistrategies.us`, you can just create a `CNAME` for `www` and set up an apex redirect to `www` in your DNS provider.

## Local preview

Just double-click `index.html` to open it in your browser. No build step needed.

---

© 2025 ROI Strategies

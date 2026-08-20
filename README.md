# AeroCamino — Cloudflare Pages package

This folder is ready to deploy as a static Cloudflare Pages site.

## Files
- `index.html`
- `style.css`
- `script.js`
- `assets/aerocamino-logo.png`
- `assets/aerocamino-hero.png`

## Cloudflare Pages deployment
1. Open Cloudflare Dashboard.
2. Go to **Workers & Pages → Create → Pages → Upload assets**.
3. Upload this folder (or the ZIP contents).
4. No build command is required.
5. After deployment, add `aerocamino.net` as the custom domain.

## Notes
The consultation form currently uses `mailto:info@aerocamino.net`, so it opens the visitor's email application.
For a proper web form later, connect Formspree, Basin, Tally, or Cloudflare Workers/Pages Functions.

Brand:
- Navy: `#0A2342`
- Steel Blue: `#4E6E8E`
- Sky Blue: `#5FA8E6`
- Font: Poppins

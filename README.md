# scriber-landing

Marketing landing page for [Scriber](https://github.com/benikigai/scriber) at **usescriber.com**.

Built as static HTML/CSS — single page, zero JS, zero build step. Deployed to Cloudflare Pages.

## Deploy

```bash
wrangler pages deploy . --project-name=scriber-landing --branch=main --commit-dirty=true
```

Custom domain `usescriber.com` (apex + www) attached via the Cloudflare API.

## Files

```
index.html   ← the page
styles.css   ← all styles, dark theme + electric blue / amber accents
_headers     ← CF Pages security headers
```

## When the demo video lands

Replace the `<div class="video-placeholder">` block in `index.html` with a `<video>` tag or YouTube/Loom embed.

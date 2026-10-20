# scriber-landing

**Original static marketing page for [Scriber](https://github.com/benikigai/scriber), the voice agent that runs your standup.**

> **Status:** Superseded. Built in May 2026 after OpenAI Voice Hack Night (2026-05-27). Since June 2026, `usescriber.com` is served by the landing route inside the main [scriber](https://github.com/benikigai/scriber) app, so this page is no longer what visitors see. Kept only for history.

## What it is

A single page ("Scriber — the standup runs itself"): plain HTML and CSS, no JavaScript, no build step. Dark theme with electric blue and amber accents, a video placeholder for the demo, and links to the Scriber repo and the project page on [benjaminshyong.com](https://benjaminshyong.com/projects/scriber).

| File | What |
|---|---|
| `index.html` | The page |
| `styles.css` | All styles |
| `_headers` | Cloudflare Pages security headers |

## Run locally

```bash
python3 -m http.server 8000   # then open http://localhost:8000
```

## Deploy (historical)

It was deployed to Cloudflare Pages:

```bash
wrangler pages deploy . --project-name=scriber-landing --branch=main
```

## Related repos

- [benikigai/scriber](https://github.com/benikigai/scriber) — the product, including its current landing page.

## Credits

Built by [Ben Shyong](https://github.com/benikigai).

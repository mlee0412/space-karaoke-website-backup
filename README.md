# Space Karaoke Website Backup + Emergency Site

Public website recovery snapshot for `spacekaraoke.com`, captured on 2026-06-04, plus the emergency static fallback site deployed on Vercel.

## Deployable Site

- `index.html` — emergency customer-facing fallback homepage.
- `styles.css` — fallback site styling.
- `assets/` — downloaded customer-facing images used by the fallback site.
- `_verification/` — desktop/mobile screenshots from visual checks.

Vercel project: `space-karaoke-emergency-site-2026-06-07`

Public preview: `https://space-karaoke-emergency-site-2026-0.vercel.app/`

## Recovery Snapshot

- `homepage.html` — captured public homepage HTML.
- `meta/` — response headers, robots.txt, and sitemap endpoints.
- `public-api/` — public WordPress REST API responses available without credentials.
- `dns/` — public DNS readouts for A, NS, and www CNAME.
- `SNAPSHOT-MANIFEST.md` — portfolio snapshot manifest and limitations.

## Notes

This is a public-surface backup, not a credentialed WordPress or hosting backup. It does not include the database export, full uploads directory, theme/plugin source, `wp-config.php`, hosting files, Cloudflare settings, or registrar/account metadata.

Use this repo as a design and recovery reference for AI agents, developers, and human designers.

## Latest Original Site Capture

- `original-site-capture/20260612-0420-live/` - live public capture from the restored original website.
- Includes homepage HTML, headers, robots/sitemaps, DNS, public WordPress REST structure, media/page indexes, and homepage-linked public assets.
- Use this folder as the current original-site reference while building the replacement site.

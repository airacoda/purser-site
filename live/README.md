# purser.ingleby.com source

This folder is the source for https://purser.ingleby.com (Cloudflare Pages project `purser-ingleby`).
It is plain static HTML, no build step. The stubs at the repo root only forward the old address.

Preview: `python3 -m http.server 8080 --directory live`

Deploy (needs Erick's yes): `npx wrangler@4 pages deploy live --project-name purser-ingleby --branch main`

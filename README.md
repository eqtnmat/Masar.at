# Masarat · مسارات — interactive demo

Single-page interactive prototype of the Masarat student pathway platform (Arabic + English).
All data is demonstration data and is stored only in the visitor's browser.

- `public/index.html` — the whole app (no build step).
- `wrangler.jsonc` — deploys `public/` as static assets on the Cloudflare Worker `masar-at` (`npx wrangler deploy`).

Note: the AI review of daily tasks uses Claude only when the demo is opened inside Claude; on other hosts it falls back to a simple, clearly labelled quick check.

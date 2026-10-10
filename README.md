# af-page
agent pages

## Deploy (Cloudflare Workers static assets)

Serves the repo root at https://david.afinancialpartner.com (see `wrangler.jsonc`; `.assetsignore` keeps source-only folders out).

```bash
npx wrangler login        # or set CLOUDFLARE_API_TOKEN
npx wrangler deploy
```

The `afinancialpartner.com` zone must be on the same Cloudflare account; `deploy` creates the DNS record and certificate for the subdomain.

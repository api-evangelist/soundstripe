# soundstripe

Soundstripe — royalty-free music, sound effects, and stock video on subscription, with a JSON:API developer API (token auth, 25 req/sec, signed webhooks) that exposes songs, sound effects, playlists, and the Supe AI music supervisor.

## API

- Docs: https://docs.soundstripe.com
- Base URL: `https://api.soundstripe.com`
- Auth: `Authorization: Token <api-key>` (server-to-server only)
- Rate limit: 25 requests per second per API key
- Webhooks: `X-Soundstripe-Signature` (HMAC-SHA256) + `X-Soundstripe-Timestamp`
- OpenAPI: [`openapi/soundstripe-openapi.yml`](openapi/soundstripe-openapi.yml)

## Artifacts

- [`apis.yml`](apis.yml) — APIs.json profile
- [`openapi/soundstripe-openapi.yml`](openapi/soundstripe-openapi.yml) — OpenAPI 3.1 surface
- [`plans/soundstripe-plans-pricing.yml`](plans/soundstripe-plans-pricing.yml) — Subscription plans (API Commons Plans 0.1)
- [`rate-limits/soundstripe-rate-limits.yml`](rate-limits/soundstripe-rate-limits.yml) — Rate-limit policy
- [`finops/soundstripe-finops.yml`](finops/soundstripe-finops.yml) — Billing / FinOps surface

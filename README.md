# Soundstripe (soundstripe)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Soundstripe is a Nashville-based subscription platform that licenses royalty-free music, sound effects, and stock video to creators, agencies, podcasters, filmmakers, and enterprises. The catalog spans roughly 120,000 human-made tracks from Grammy-winning and independent artists, nearly 100,000 sound effects, and 100,000+ stock video clips (HD through 8K) — all pre-cleared under a single digital license that covers YouTube, Instagram, TikTok, podcasting, and commercial use, with stems and cut-downs available for many songs. Soundstripe also publishes a server-to-server REST API at api.soundstripe.com (JSON:API, token auth, 25 req/sec, signed webhooks) that exposes songs, sound effects, playlists, private playlists, and "Supe" — an AI music supervisor that matches catalog tracks to natural-language briefs, scene context, and reference imagery via asynchronous search and asset upload endpoints. Native integrations exist for Adobe Premiere Pro, Adobe Express, and Twitch; partner programs cover API embedding, music resale, and custom licensing for tool makers and platforms.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/soundstripe/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/soundstripe/refs/heads/main/apis.yml)

## Tags

- Music
- Sound Effects
- Stock Video
- Royalty Free
- Licensing
- Subscription
- Creators
- Content Creation
- Video Production
- Podcasting
- AI Music Supervisor
- Stems

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Soundstripe API

Server-to-server REST API for embedding the Soundstripe catalog into creator tools, editing suites, and platforms. JSON:API responses, token authentication via the Authorization header, and 25 requests per second. Endpoints cover song retrieval, sound-effect listing, categories, curated playlists, private (user-scoped) playlist management, and the Supe AI search workflow (asset upload, natural-language search, signed webhook delivery of matched songs with audio files and artists).

- **Human URL:** [https://docs.soundstripe.com](https://docs.soundstripe.com)
- **Base URL:** `https://api.soundstripe.com`

#### Tags

- Music
- Sound Effects
- Playlists
- Search
- AI Music Supervisor
- Webhooks

#### Properties

- [Documentation](https://docs.soundstripe.com)
- [Authentication](https://docs.soundstripe.com/reference/authentication)
- [Rate Limits](https://docs.soundstripe.com/reference/rate-limits)
- [Webhooks](https://docs.soundstripe.com/reference/webhooks)
- [Terms of Service](https://docs.soundstripe.com/docs/api-terms-of-use)
- [OpenAPI](openapi/soundstripe-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/soundstripe.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/soundstripe.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [L L Ms Txt](https://docs.soundstripe.com/llms.txt)

## Common Properties

- [Website](https://www.soundstripe.com)
- [Sign Up](https://app.soundstripe.com/signup)
- [Sign In](https://app.soundstripe.com/login)
- [Pricing](https://www.soundstripe.com/library/pricing)
- [Music](https://www.soundstripe.com/royalty-free-music)
- [Sound Effects](https://www.soundstripe.com/sfx)
- [Video](https://www.soundstripe.com/stock-video)
- [Business](https://www.soundstripe.com/business)
- [A P I Landing Page](https://www.soundstripe.com/api)
- [Developer Portal](https://docs.soundstripe.com)
- [Licensing](https://www.soundstripe.com/licensing)
- [Blog](https://www.soundstripe.com/blog)
- [Help](https://help.soundstripe.com)
- [Contact](https://www.soundstripe.com/contact-us)
- [Twitter](https://twitter.com/soundstripeinc)
- [Instagram](https://www.instagram.com/soundstripe)
- [LinkedIn](https://www.linkedin.com/company/soundstripe)
- [YouTube](https://www.youtube.com/@Soundstripe)
- [Plans](plans/soundstripe-plans-pricing.yml)
- [Rate Limits](rate-limits/soundstripe-rate-limits.yml)
- [Fin Ops](finops/soundstripe-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

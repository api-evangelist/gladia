# Gladia (gladia)

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

Gladia is an AI audio infrastructure platform that delivers speech-to-text transcription and audio intelligence through a unified REST and WebSocket API. The platform supports asynchronous processing of pre-recorded audio files and real-time live transcription via WebSocket, with speaker diarization, automatic language detection across 100+ languages, word-level timestamps, and LLM-powered audio intelligence enrichments. Authentication is API-key based using the `x-gladia-key` header against the base URL `https://api.gladia.io/v2/`. Gladia offers a freemium model with 10 free hours per month, metered pay-as-you-go pricing, volume-commitment Growth plans, and custom Enterprise contracts.

**APIs.json:** https://raw.githubusercontent.com/api-evangelist/gladia/refs/heads/main/apis.yml

**Naftiko:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=gladia-api-evangelist&utm_content=repo

---

## Tags

- Speech-to-Text
- Transcription
- Audio Intelligence
- Real-Time
- Speaker Diarization
- Translation
- WebSocket
- REST

---

## APIs

| API | Description |
|-----|-------------|
| Gladia Pre-recorded (Async) API | REST API for submitting pre-recorded audio files for asynchronous transcription with diarization, language detection, and audio intelligence. |
| Gladia Live (Real-time) API | WebSocket API for real-time live audio transcription with sub-second latency; sessions capped at 3 hours. |

---

## Plans / Rate Limits / FinOps

| Resource | Location |
|----------|----------|
| Plans & Pricing | [plans/gladia-plans-pricing.yml](plans/gladia-plans-pricing.yml) |
| Rate Limits | [rate-limits/gladia-rate-limits.yml](rate-limits/gladia-rate-limits.yml) |
| FinOps | [finops/gladia-finops.yml](finops/gladia-finops.yml) |

**Pricing summary:**

- **Starter (free quota):** 10 hours/month free; $0.61/hr async, $0.75/hr real-time pay-as-you-go
- **Growth:** Volume commitment; from $0.20/hr async, $0.25/hr real-time
- **Enterprise:** Custom annual pricing with unlimited concurrency and zero data retention

**Rate limits summary:**

- Free tier: 3 concurrent async / 1 concurrent real-time / 10 hrs/month cap
- Paid tier: 25 concurrent async / 30 concurrent real-time / 300-request queue
- All plans: max 3-hour real-time session duration; HTTP 429 on throttle

---

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

---

## Common Properties

| Property | URL |
|----------|-----|
| Website | https://www.gladia.io/ |
| Documentation | https://docs.gladia.io/ |
| GitHub Organization | https://github.com/gladiaio |
| LinkedIn | https://www.linkedin.com/company/gladia-io |
| X / Twitter | https://x.com/gladia_io |
| Blog | https://www.gladia.io/blog |
| Changelog | https://www.gladia.io/changelog |
| Pricing | https://www.gladia.io/pricing |
| Status Page | https://status.gladia.io/ |

---

## Maintainers

- **Kin Lane** — kin@apievangelist.com

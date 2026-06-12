# Gladia (gladia)

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

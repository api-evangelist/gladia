# Gladia

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Gladia is an AI audio infrastructure platform that offers speech-to-text transcription via both REST and WebSocket APIs, supporting asynchronous pre-recorded audio processing and real-time live transcription. The platform provides speaker diarization, automatic language detection across 100+ languages, word-level timestamps, and audio intelligence features powered by large language models. Authentication uses an API key passed via the x-gladia-key HTTP header against the base URL https://api.gladia.io/v2/. Gladia offers a free tier with 10 hours per month, metered paid plans starting at $0.61/hour for async and $0.75/hour for real-time, and custom enterprise pricing with zero data retention and SLA guarantees.

**Areas:** Speech-to-Text · Transcription · Audio Intelligence · Real-Time · Speaker Diarization · Translation · WebSocket · REST

## Gladia on APIs.io

Everything profiled for Gladia is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/gladia/](https://apis.io/providers/gladia/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [Gladia Live (Real-time) API](https://apis.io/apis/gladia/gladia-live-real-time-api/) — WebSocket API for real-time live audio transcription with sub-second latency, supporting multi-language detection, live speaker diarization, and streaming…
- [Gladia AudioToText API](https://apis.io/apis/gladia/gladia-audiototext-api/) — The AudioToText API from Gladia — 1 operation(s) for audiototext.
- [Gladia File Management API](https://apis.io/apis/gladia/gladia-file-management-api/) — The File Management API from Gladia — 1 operation(s) for file management.
- [Gladia Job History API](https://apis.io/apis/gladia/gladia-job-history-api/) — The Job History API from Gladia — 1 operation(s) for job history.
- [Gladia Live V2 API](https://apis.io/apis/gladia/gladia-live-v2-api/) — The Live V2 API from Gladia — 3 operation(s) for live v2.
- [Gladia Pre-recorded V2 API](https://apis.io/apis/gladia/gladia-pre-recorded-v2-api/) — The Pre-recorded V2 API from Gladia — 3 operation(s) for pre-recorded v2.
- [Gladia Transcription V1 API](https://apis.io/apis/gladia/gladia-transcription-v1-api/) — The Transcription V1 API from Gladia — 2 operation(s) for transcription v1.
- [Gladia Transcription V2 API](https://apis.io/apis/gladia/gladia-transcription-v2-api/) — The Transcription V2 API from Gladia — 3 operation(s) for transcription v2.
- [Gladia Open Router API](https://apis.io/apis/gladia/gladia-open-router-api/) — The Open Router API from Gladia — 1 operation(s) for open router.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Gladia Agentic Access](https://apis.io/agentic-access/gladia/gladia-agentic-access/)

#### JSON Schema (5)

The data models the API reads and writes.

- [AudioUploadResponse](https://apis.io/schemas/gladia/gladia-audio-upload-response/)
- [DiarizationConfigDTO](https://apis.io/schemas/gladia/gladia-diarization-config/)
- [InitPreRecordedTranscriptionResponse](https://apis.io/schemas/gladia/gladia-init-pre-recorded-transcription-response/)
- [InitTranscriptionRequest](https://apis.io/schemas/gladia/gladia-init-transcription-request/)
- [LiveEventPayload](https://apis.io/schemas/gladia/gladia-live-event-payload/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Gladia Context](https://apis.io/jsonld/gladia/gladia-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Gladia Vocabulary](https://apis.io/vocabularies/gladia/gladia-vocabulary/)

#### Examples (4)

Example requests and responses.

- [Gladia Initiate Transcription](https://apis.io/examples/gladia/gladia-initiate-transcription/)
- [Gladia Live Session Config](https://apis.io/examples/gladia/gladia-live-session-config/)
- [Gladia Transcription Job Response](https://apis.io/examples/gladia/gladia-transcription-job-response/)
- [Gladia Upload Audio Url](https://apis.io/examples/gladia/gladia-upload-audio-url/)

#### Collections (16)

Postman and Open Collection request collections.

- [Gladia Control AudioToText API](https://apis.io/collections/gladia/open-gladia-audiototext-api/)
- [Gladia Control AudioToText File Management API](https://apis.io/collections/gladia/open-gladia-file-management-api/)
- [Gladia Control AudioToText Job History API](https://apis.io/collections/gladia/open-gladia-job-history-api/)
- [Gladia Control AudioToText Live V2 API](https://apis.io/collections/gladia/open-gladia-live-v2-api/)
- [Gladia Control AudioToText OpenRouter API](https://apis.io/collections/gladia/open-gladia-openrouter-api/)
- [Gladia Control AudioToText Pre-recorded V2 API](https://apis.io/collections/gladia/open-gladia-pre-recorded-v2-api/)
- [Gladia Control AudioToText Transcription V1 API](https://apis.io/collections/gladia/open-gladia-transcription-v1-api/)
- [Gladia Control AudioToText Transcription V2 API](https://apis.io/collections/gladia/open-gladia-transcription-v2-api/)
- [Gladia Control AudioToText API](https://apis.io/collections/gladia/postman-gladia-audiototext-api/)
- [Gladia Control AudioToText File Management API](https://apis.io/collections/gladia/postman-gladia-file-management-api/)
- [Gladia Control AudioToText Job History API](https://apis.io/collections/gladia/postman-gladia-job-history-api/)
- [Gladia Control AudioToText Live V2 API](https://apis.io/collections/gladia/postman-gladia-live-v2-api/)
- [Gladia Control AudioToText OpenRouter API](https://apis.io/collections/gladia/postman-gladia-openrouter-api/)
- [Gladia Control AudioToText Pre-recorded V2 API](https://apis.io/collections/gladia/postman-gladia-pre-recorded-v2-api/)
- [Gladia Control AudioToText Transcription V1 API](https://apis.io/collections/gladia/postman-gladia-transcription-v1-api/)
- [Gladia Control AudioToText Transcription V2 API](https://apis.io/collections/gladia/postman-gladia-transcription-v2-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Gladia — jsonschema rules](https://apis.io/rules/gladia/gladia-jsonschema-spectral-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Gladia Authentication](https://apis.io/security/gladia/gladia-authentication/)
- [Gladia Domain Security](https://apis.io/security/gladia/gladia-domain-security/)
- [Gladia Trust Center](https://apis.io/security/gladia/gladia-trust-center/)
- [Gladia Vulnerability Disclosure](https://apis.io/security/gladia/gladia-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Gladia Plans Pricing](https://apis.io/plans/gladia/gladia-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Gladia Rate Limits](https://apis.io/rate-limits/gladia/gladia-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Gladia Finops](https://apis.io/finops/gladia/gladia-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.gladia.io/)
- [Documentation](https://docs.gladia.io/)
- [Pricing](https://www.gladia.io/pricing)
- [Changelog](https://www.gladia.io/changelog)
- [Blog](https://www.gladia.io/blog)
- [GitHub](https://github.com/gladiaio)
- [Status](https://status.gladia.io/)

## API Evangelist rating

**Kin Score 42.5** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 59.4 |
| Contract governance | 23.5 |
| Operational transparency | 52.6 |
| Developer ergonomics | 25.0 |
| Access clarity | 26.3 |

**Agent readiness 33.9** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | unknown |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | distinct |

**Regulatory alignment 27.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/gladia/](https://apis.io/providers/gladia/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Gladia: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/gladia/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).

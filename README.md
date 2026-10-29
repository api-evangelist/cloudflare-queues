# Cloudflare Queues

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

Cloudflare Queues is a flexible, scalable message queue service built into the Cloudflare Workers ecosystem. It provides guaranteed message delivery with a REST API for creating and managing queues, sending individual or batched messages, configuring push-based Worker consumers and HTTP pull consumers, managing dead letter queues, and monitoring queue metrics. Queues supports delivery delays, message retention up to 14 days, throughput up to 5,000 messages per second per queue, and event subscriptions for reactive workflows.

**Areas:** Messaging · Message Queue · Serverless · Workers · Cloudflare · Async · Dead Letter Queue · Event-Driven

## Cloudflare Queues on APIs.io

Everything profiled for Cloudflare Queues is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/cloudflare-queues/](https://apis.io/providers/cloudflare-queues/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [Cloudflare Queues Consumer API](https://apis.io/apis/cloudflare-queues/cloudflare-queues-consumer-api/) — Operations for managing queue consumers (Worker push or HTTP pull)
- [Cloudflare Queues Messages API](https://apis.io/apis/cloudflare-queues/cloudflare-queues-messages-api/) — Operations for sending, receiving, and acknowledging messages
- [Cloudflare Queues Metrics API](https://apis.io/apis/cloudflare-queues/cloudflare-queues-metrics-api/) — Operations for retrieving queue metrics
- [Cloudflare Queues Queue API](https://apis.io/apis/cloudflare-queues/cloudflare-queues-queue-api/) — Operations for managing Cloudflare Queues and their configuration

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Cloudflare Queues Agentic Access](https://apis.io/agentic-access/cloudflare-queues/cloudflare-queues-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [Cloudflare Queue Consumer](https://apis.io/schemas/cloudflare-queues/cloudflare-queues-consumer/)
- [Cloudflare Queue Message](https://apis.io/schemas/cloudflare-queues/cloudflare-queues-message/)
- [Cloudflare Queue](https://apis.io/schemas/cloudflare-queues/cloudflare-queues-queue/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Cloudflare Queues Context](https://apis.io/jsonld/cloudflare-queues/cloudflare-queues-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Cloudflare Queues Vocabulary](https://apis.io/vocabularies/cloudflare-queues/cloudflare-queues-vocabulary/)

#### Examples (4)

Example requests and responses.

- [Cloudflare Queues Create Consumer](https://apis.io/examples/cloudflare-queues/cloudflare-queues-create-consumer/)
- [Cloudflare Queues Create Queue](https://apis.io/examples/cloudflare-queues/cloudflare-queues-create-queue/)
- [Cloudflare Queues Pull Messages](https://apis.io/examples/cloudflare-queues/cloudflare-queues-pull-messages/)
- [Cloudflare Queues Push Message](https://apis.io/examples/cloudflare-queues/cloudflare-queues-push-message/)

#### Collections (8)

Postman and Open Collection request collections.

- [Cloudflare Queues Consumer API](https://apis.io/collections/cloudflare-queues/open-cloudflare-queues-consumer-api/)
- [Cloudflare Queues Consumer Messages API](https://apis.io/collections/cloudflare-queues/open-cloudflare-queues-messages-api/)
- [Cloudflare Queues Consumer Metrics API](https://apis.io/collections/cloudflare-queues/open-cloudflare-queues-metrics-api/)
- [Cloudflare Queues Consumer Queue API](https://apis.io/collections/cloudflare-queues/open-cloudflare-queues-queue-api/)
- [Cloudflare Queues Consumer API](https://apis.io/collections/cloudflare-queues/postman-cloudflare-queues-consumer-api/)
- [Cloudflare Queues Consumer Messages API](https://apis.io/collections/cloudflare-queues/postman-cloudflare-queues-messages-api/)
- [Cloudflare Queues Consumer Metrics API](https://apis.io/collections/cloudflare-queues/postman-cloudflare-queues-metrics-api/)
- [Cloudflare Queues Consumer Queue API](https://apis.io/collections/cloudflare-queues/postman-cloudflare-queues-queue-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Cloudflare Queues — jsonschema rules](https://apis.io/rules/cloudflare-queues/cloudflare-queues-jsonschema-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Cloudflare Queues Authentication](https://apis.io/security/cloudflare-queues/cloudflare-queues-authentication/)
- [Cloudflare Queues Domain Security](https://apis.io/security/cloudflare-queues/cloudflare-queues-domain-security/)
- [Cloudflare Queues Vulnerability Disclosure](https://apis.io/security/cloudflare-queues/cloudflare-queues-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Cloudflare Queues Plans Pricing](https://apis.io/plans/cloudflare-queues/cloudflare-queues-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Cloudflare Queues Rate Limits](https://apis.io/rate-limits/cloudflare-queues/cloudflare-queues-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Cloudflare Queues Finops](https://apis.io/finops/cloudflare-queues/cloudflare-queues-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.cloudflare.com/developer-platform/queues/)
- [Documentation](https://developers.cloudflare.com/queues/)
- [Getting started](https://developers.cloudflare.com/queues/get-started/)
- [API reference](https://developers.cloudflare.com/api/resources/queues/)
- [Pricing](https://developers.cloudflare.com/queues/platform/pricing/)
- [Changelog](https://developers.cloudflare.com/changelog/product/queues/)
- [Blog](https://blog.cloudflare.com/tag/cloudflare-queues/)
- [Status](https://www.cloudflarestatus.com/)

## API Evangelist rating

**Kin Score 45.9** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 40.7 |
| Contract governance | 9.8 |
| Operational transparency | 55.3 |
| Developer ergonomics | 47.1 |
| Access clarity | 15.8 |

**Agent readiness 17.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 22.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/cloudflare-queues/](https://apis.io/providers/cloudflare-queues/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Cloudflare Queues: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/cloudflare-queues/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).

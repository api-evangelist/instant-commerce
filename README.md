# Instant Commerce

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

Instant Commerce (product: Instant, instant.so) is an Amsterdam- and Miami-based AI-native eCommerce software company that builds an AI-powered, no-code page builder for Shopify. Merchants describe what they want and Instant's AI agents generate complete store pages — landing pages, homepages, product and collection pages, popups and cart drawers — including layouts, copy and AI-generated imagery, plus Figma-to-Shopify conversion, A/B testing and conversion-rate optimization. The platform serves roughly 25,000 brands. Instant's agent surface is a hosted, remote Model Context Protocol (MCP) server at api.instant.so/mcp, shipped 2026-06-02 and labelled beta, which lets Claude Desktop, Cursor and other MCP clients list, create, edit, publish and unpublish landing pages and drive the AI page-builder agent using a project-scoped bearer access token issued in the dashboard. There is no OpenAPI, no public REST reference and no OAuth; an earlier generation of developer tooling — the @instantcommerce/sdk React block SDK, the @instantcommerce/cli and the developer docs at docs.instantcommerce.io — is still published but has had no release since 2023. The company has raised about $10M and is backed by HV Capital. Added to the API Evangelist network as a portfolio-company lead and enriched from public sources.

**Areas:** Company · Ai Enterprise Software · E-Commerce · Shopify · No-Code · Page Builder · Artificial Intelligence · AI Agents · Conversion Rate Optimization · Developer Tools · MCP · Agent-Native

## Instant Commerce on APIs.io

Everything profiled for Instant Commerce is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/instant-commerce/](https://apis.io/providers/instant-commerce/)** — or go straight to one of the APIs or properties below.

### APIs (1)

- [Instant MCP Server](https://apis.io/apis/instant-commerce/instant-mcp-server/) — Hosted, remote Model Context Protocol server that lets external AI clients — Claude Desktop, Cursor and other MCP clients — work with an Instant project.…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [instant](https://apis.io/servers/instant-commerce/instant/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Instant Commerce Authentication](https://apis.io/security/instant-commerce/instant-commerce-authentication/)
- [Instant Commerce Domain Security](https://apis.io/security/instant-commerce/instant-commerce-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Instant Commerce Plans Pricing](https://apis.io/plans/instant-commerce/instant-commerce-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Instant Commerce Rate Limits](https://apis.io/rate-limits/instant-commerce/instant-commerce-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://instant.so/)
- [Documentation](https://docs.instant.so)
- [Getting started](https://docs.instant.so/en/articles/16068139-the-getting-started-checklist)
- [Pricing](https://instant.so/pricing)
- [Sign up](https://app.instant.so/register)
- [Changelog](https://instant.so/changelog)
- [Blog](https://instant.so/blog)
- [Terms of service](https://instant.so/terms-of-service)
- [Privacy policy](https://instant.so/privacy-policy)
- [GitHub](https://github.com/instantcommerce)
- [Status](https://status.instant.so/)

## API Evangelist rating

**Kin Score 45.8** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 0.0 |
| Contract governance | 18.2 |
| Operational transparency | 42.1 |
| Developer ergonomics | 71.4 |
| Access clarity | 76.3 |

**Agent readiness 16.5** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
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

**Regulatory alignment 22.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/instant-commerce/](https://apis.io/providers/instant-commerce/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Instant Commerce: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/instant-commerce/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).

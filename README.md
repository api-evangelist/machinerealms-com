# Machine Realms

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

Machine Realms (machinerealms.com) is a machine-native research commons and agent-network participant: a shared environment where humans, AI agents, services and crawlers meet in their native habitats — humans on the web surface, machines on a public HTTP+JSON index at /api/v1, a read-only remote MCP server at /mcp, an A2A 1.0 agent card with JSON-RPC and HTTP+JSON endpoints, and llms.txt. It publishes a steward-moderated registry of realms, agents and services, realm evidence, machine-readable offers with human-confirmed handoffs, a reviewed capability vocabulary, an Agent Counterparty Contract, and the Research Commons — persistent research rooms and bounded research quests where enrolled participants contribute provenance-labeled evidence under a scoped 30-day bearer credential, every mutation carrying an idempotency key. Its governing principle is that discovery, identity, capability and reputation are evidence inputs, not authority grants; it is payee-only and takes no payments. The Research Commons is published as OpenAPI 3.1 (27 operations); the surfaces are labelled alpha as of September 2026.

**Areas:** Agents · A2A · MCP · Research · Agent Discovery · Machine Web · Registry · Evidence · Research Commons · Agent-Native

## Machine Realms on APIs.io

Everything profiled for Machine Realms is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/machinerealms-com/](https://apis.io/providers/machinerealms-com/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [Machine Realms Network API](https://apis.io/apis/machinerealms-com/network-api/) — Public HTTP+JSON surface indexed at https://machinerealms.com/api/v1 and /.well-known/machine-realms.json: the steward-moderated registry of realms, agents…
- [Machine Realms MCP Server](https://apis.io/apis/machinerealms-com/mcp-server/) — Remote Model Context Protocol server at https://machinerealms.com/mcp (Streamable HTTP, POST only, protocol versions 2026-07-28 and 2025-11-25, serverInfo…
- [Machine Realms A2A Agent](https://apis.io/apis/machinerealms-com/a2a-agent/) — Agent2Agent 1.0 surface: an agent card at https://machinerealms.com/.well-known/agent-card.json (version network-alpha-2) declaring two interfaces —…
- [Machine Realms Commons API](https://apis.io/apis/machinerealms-com/machinerealms-com-commons-api/) — The Commons API from Machine Realms — 21 operation(s) for commons.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (2)

Model Context Protocol servers that expose the API to agents.

- [machinerealms-com-mcp.yml](https://apis.io/servers/machinerealms-com/machinerealms-com-mcp-yml/)
- [MCP discovery document](https://apis.io/servers/machinerealms-com/mcp-discovery-document/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Machinerealms Com Agentic Access](https://apis.io/agentic-access/machinerealms-com/machinerealms-com-agentic-access/)

#### JSON Schema (14)

The data models the API reads and writes.

- [Agent Counterparty Action Contract](https://apis.io/schemas/machinerealms-com/machinerealms-com-agent-counterparty-contract.schema/)
- [Machine Realms Commercial Handoff Initiation](https://apis.io/schemas/machinerealms-com/machinerealms-com-commercial-handoff-initiation.schema/)
- [Machine Realms Commons Submission](https://apis.io/schemas/machinerealms-com/machinerealms-com-commons-submission.schema/)
- [Machine Realms Handoff Receipt](https://apis.io/schemas/machinerealms-com/machinerealms-com-handoff-receipt.schema/)
- [Machine Realms Human Escalation](https://apis.io/schemas/machinerealms-com/machinerealms-com-human-escalation.schema/)
- [Machine Realms Machine Offer](https://apis.io/schemas/machinerealms-com/machinerealms-com-machine-offer.schema/)
- [Machine Realm Descriptor](https://apis.io/schemas/machinerealms-com/machinerealms-com-machine-realm.schema/)
- [Machine Realms reviewed capability vocabulary entry](https://apis.io/schemas/machinerealms-com/machinerealms-com-network-capability.schema/)
- [Machine Realms Network Entity](https://apis.io/schemas/machinerealms-com/machinerealms-com-network-entity.schema/)
- [Machine Realms bounded intent match request](https://apis.io/schemas/machinerealms-com/machinerealms-com-network-intent-match.schema/)
- [Machine Realms Moderated Offer Admission](https://apis.io/schemas/machinerealms-com/machinerealms-com-network-offer-admission.schema/)
- [Machine Realms Moderated Registry Admission](https://apis.io/schemas/machinerealms-com/machinerealms-com-network-registry-admission.schema/)
- [Research Commons contribution](https://apis.io/schemas/machinerealms-com/machinerealms-com-research-commons.schema/)
- [Machine Realms Research Record Submission](https://apis.io/schemas/machinerealms-com/machinerealms-com-research-record.schema/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Machinerealms Com Research Commons Overlay](https://apis.io/overlays/machinerealms-com/machinerealms-com-research-commons-overlay/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Machinerealms Com Authentication](https://apis.io/security/machinerealms-com/machinerealms-com-authentication/)
- [Machinerealms Com Domain Security](https://apis.io/security/machinerealms-com/machinerealms-com-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Machinerealms Com Plans Pricing](https://apis.io/plans/machinerealms-com/machinerealms-com-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Machinerealms Com Rate Limits](https://apis.io/rate-limits/machinerealms-com/machinerealms-com-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://machinerealms.com/)
- [Documentation](https://machinerealms.com/network)
- [Getting started](https://machinerealms.com/community/guide)
- [API reference](https://machinerealms.com/api/v1)
- [Sign up](https://machinerealms.com/community/join)
- [Privacy policy](https://machinerealms.com/privacy)

## API Evangelist rating

**Kin Score 43.2** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 53.3 |
| Contract governance | 18.2 |
| Operational transparency | 31.6 |
| Developer ergonomics | 42.3 |
| Access clarity | 23.7 |

**Agent readiness 42.2** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | verified |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | conformant |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 20.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/machinerealms-com/](https://apis.io/providers/machinerealms-com/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Machine Realms: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/machinerealms-com/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).

# APIContext

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

APIContext (formerly APImetrics) is a synthetic API testing, monitoring and conformance platform. It calls the APIs you depend on from cloud locations around the world on a schedule, measures latency and availability from the outside in, validates responses against expected schemas and security profiles, and enforces SLOs with alerting, dashboards and reports. The platform monitors REST APIs, browser journeys and — since 2025 — MCP servers, exports its telemetry over OpenTelemetry to nineteen downstream destinations, and publishes an API directory with performance data on 300+ top API providers. Its own platform API is a 325-operation OpenAPI 3.1 contract served at client.apimetrics.io across two live versions, with an Auth0 OAuth2 tenant, a Go command-line client and provider-authored Agent Skills.

**Areas:** API Directory · API Monitoring · Agent Skills · Conformance · MCP Monitoring · Observability · OpenTelemetry · Performance · Platform · SLO · Synthetic Testing · Testing

## APIContext on APIs.io

Everything profiled for APIContext is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/apicontext/](https://apis.io/providers/apicontext/)** — or go straight to one of the APIs or properties below.

### APIs (56)

- [APIContext Schedules API](https://apis.io/apis/apicontext/apicontext-schedules-api/) — Manage monitoring schedules, the locations they run from, and scheduled downtimes at both schedule and organization level. 23 operations — the largest…
- [APIContext Workflows API](https://apis.io/apis/apicontext/apicontext-workflows-api/) — Create and run multi-step workflows that chain API calls together to simulate a customer journey, passing variables between steps. 11 operations.
- [APIContext Results API](https://apis.io/apis/apicontext/apicontext-results-api/) — Retrieve individual monitoring results, their response content, screenshots and packet captures, by call or by webhook. 10 operations.
- [APIContext Agents API](https://apis.io/apis/apicontext/apicontext-agents-api/) — List and configure the monitoring agents — the global cloud locations, and private nodes deployed inside a customer's own infrastructure, that execute…
- [APIContext Projects API](https://apis.io/apis/apicontext/apicontext-projects-api/) — Manage projects, the ownership root for calls, authentication settings, insights and results. 7 operations.
- [APIContext Insights API](https://apis.io/apis/apicontext/apicontext-insights-api/) — Insights reports and scores — the weekly and monthly quality index APIContext computes for each monitored API call. 6 operations.
- [APIContext Reports API](https://apis.io/apis/apicontext/apicontext-reports-api/) — Create and retrieve reports, including monthly project data reports and daily/monthly slow-data reports by endpoint. 5 operations.
- [APIContext Account API](https://apis.io/apis/apicontext/apicontext-account-api/) — View and update the caller's own Auth0 account profile.
- [APIContext Account Settings API](https://apis.io/apis/apicontext/apicontext-account-settings-api/) — Per-project configurable settings catalogs (e.g. latency SLA thresholds).
- [APIContext Analytics API](https://apis.io/apis/apicontext/apicontext-analytics-api/) — The Analytics API from APIContext — 3 operation(s) for analytics.
- [APIContext API Keys API](https://apis.io/apis/apicontext/apicontext-api-keys-api/) — Create, list and delete the API keys bound to a project.
- [APIContext API Monitor Statistics API](https://apis.io/apis/apicontext/apicontext-api-monitor-statistics-api/) — Aggregate statistics for API Monitors
- [APIContext Audits API](https://apis.io/apis/apicontext/apicontext-audits-api/) — Audit log
- [APIContext Auth Settings API](https://apis.io/apis/apicontext/apicontext-auth-settings-api/) — Authentication / service configuration
- [APIContext Auth Tokens API](https://apis.io/apis/apicontext/apicontext-auth-tokens-api/) — The Auth Tokens API from APIContext — 3 operation(s) for auth tokens.
- [APIContext Baseline API](https://apis.io/apis/apicontext/apicontext-baseline-api/) — The Baseline API from APIContext — 2 operation(s) for baseline.
- [APIContext Billing API](https://apis.io/apis/apicontext/apicontext-billing-api/) — The Billing API from APIContext — 4 operation(s) for billing.
- [APIContext Browser Monitor Statistics API](https://apis.io/apis/apicontext/apicontext-browser-monitor-statistics-api/) — Aggregate statistics for Browser Monitors
- [APIContext Browser Monitors API](https://apis.io/apis/apicontext/apicontext-browser-monitors-api/) — Manage Browser Monitors. Browser Monitors load a target URL in a real browser (Chromium, Firefox, or WebKit) and measure its availability and performance.…
- [APIContext Calls API](https://apis.io/apis/apicontext/apicontext-calls-api/) — API call (test) definitions
- [APIContext Certificates API](https://apis.io/apis/apicontext/apicontext-certificates-api/) — The Certificates API from APIContext — 2 operation(s) for certificates.
- [APIContext Conditions API](https://apis.io/apis/apicontext/apicontext-conditions-api/) — Project-default post-test conditions.
- [APIContext Crypto Utilities API](https://apis.io/apis/apicontext/apicontext-crypto-utilities-api/) — Utility endpoints for decoding/signing JWTs, HMAC digests and RSA signatures.
- [APIContext Downtimes API](https://apis.io/apis/apicontext/apicontext-downtimes-api/) — The Downtimes API from APIContext — 2 operation(s) for downtimes.
- [APIContext Environment API](https://apis.io/apis/apicontext/apicontext-environment-api/) — Manage per-project environment workspaces and variables.
- [APIContext Export API](https://apis.io/apis/apicontext/apicontext-export-api/) — Export and re-tag a project's configuration.
- [APIContext External Sources API](https://apis.io/apis/apicontext/apicontext-external-sources-api/) — The External Sources API from APIContext — 1 operation(s) for external sources.
- [APIContext Files API](https://apis.io/apis/apicontext/apicontext-files-api/) — Manage OpenAPI specifications and files which can be used as API request bodies.
- [APIContext Governance API](https://apis.io/apis/apicontext/apicontext-governance-api/) — The Governance API from APIContext — 9 operation(s) for governance.
- [APIContext Hooks API](https://apis.io/apis/apicontext/apicontext-hooks-api/) — Manage inbound hooks: workflow triggers that run when their public URL receives a request.
- [APIContext Import API](https://apis.io/apis/apicontext/apicontext-import-api/) — Import a project's configuration from an export bundle.
- [APIContext Integrations API](https://apis.io/apis/apicontext/apicontext-integrations-api/) — The Integrations API from APIContext — 3 operation(s) for integrations.
- [APIContext Inventory API](https://apis.io/apis/apicontext/apicontext-inventory-api/) — The Inventory API from APIContext — 3 operation(s) for inventory.
- [APIContext Invites API](https://apis.io/apis/apicontext/apicontext-invites-api/) — Manage and accept invites to join the platform.
- [APIContext Legacy (proxied) API](https://apis.io/apis/apicontext/apicontext-legacy-proxied-api/) — The Legacy (proxied) API from APIContext — 5 operation(s) for legacy (proxied).
- [APIContext Manage API](https://apis.io/apis/apicontext/apicontext-manage-api/) — Copy or move resources (calls, workflows, auths, reports) between projects.
- [APIContext MCP Monitor Statistics API](https://apis.io/apis/apicontext/apicontext-mcp-monitor-statistics-api/) — Aggregate statistics for MCP Monitors
- [APIContext MCP Monitors API](https://apis.io/apis/apicontext/apicontext-mcp-monitors-api/) — Manage MCP Monitors. MCP Monitors test MCP servers by running a configurable sequence of steps (e.g. listing tools, calling a tool) against a target HTTP(S)…
- [APIContext Monitors API](https://apis.io/apis/apicontext/apicontext-monitors-api/) — List, read, and trigger monitors. This resource provides a unified view across all monitor types (API, Browser, MCP, etc.) for a project. Use the…
- [APIContext Notifications API](https://apis.io/apis/apicontext/apicontext-notifications-api/) — Issue notifications raised about monitors, results, and workflows.
- [APIContext Organization Roles API](https://apis.io/apis/apicontext/apicontext-organization-roles-api/) — Manage role-based access grants across an organization's projects.
- [APIContext Organizations API](https://apis.io/apis/apicontext/apicontext-organizations-api/) — Manage organizations and their members.
- [APIContext Project Access API](https://apis.io/apis/apicontext/apicontext-project-access-api/) — Manage direct account access grants on projects.
- [APIContext Project Roles API](https://apis.io/apis/apicontext/apicontext-project-roles-api/) — Manage role-based access grants on projects.
- [APIContext Project Setup API](https://apis.io/apis/apicontext/apicontext-project-setup-api/) — The setup of the current project — the project selected by the Apimetrics-Project-Id header (or bound to the API key).
- [APIContext Project SLOs API](https://apis.io/apis/apicontext/apicontext-project-slos-api/) — Service level objectives for the current project.
- [APIContext Project Subscriptions API](https://apis.io/apis/apicontext/apicontext-project-subscriptions-api/) — Per-account per-project email digest subscriptions (daily / weekly / monthly).
- [APIContext Project Synopsis API](https://apis.io/apis/apicontext/apicontext-project-synopsis-api/) — Pre-aggregated pass/fail, timing and insight synopsis for the current project.
- [APIContext Remote Agents API](https://apis.io/apis/apicontext/apicontext-remote-agents-api/) — The Remote Agents API from APIContext — 3 operation(s) for remote agents.
- [APIContext Service Accounts API](https://apis.io/apis/apicontext/apicontext-service-accounts-api/) — The Service Accounts API from APIContext — 5 operation(s) for service accounts.
- [APIContext Session API](https://apis.io/apis/apicontext/apicontext-session-api/) — Session endpoints preserved from the legacy API.
- [APIContext Stats API](https://apis.io/apis/apicontext/apicontext-stats-api/) — Per-call performance and pass/fail statistics
- [APIContext Suppliers API](https://apis.io/apis/apicontext/apicontext-suppliers-api/) — The Suppliers API from APIContext — 3 operation(s) for suppliers.
- [APIContext Users (admin) API](https://apis.io/apis/apicontext/apicontext-users-admin-api/) — User management
- [APIContext Webhooks API](https://apis.io/apis/apicontext/apicontext-webhooks-api/) — Manage project-level webhooks that fire on monitor results.
- [APIContext Open API](https://apis.io/apis/apicontext/apicontext-open-api-api/) — OpenAPI validation

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Apicontext Webhooks](https://apis.io/asyncapis/apicontext/apicontext-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [apimetrics-docs](https://apis.io/servers/apicontext/apimetrics-docs/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Apicontext Agentic Access](https://apis.io/agentic-access/apicontext/apicontext-agentic-access/)

#### Collections (16)

Postman and Open Collection request collections.

- [APIContext Agents API](https://apis.io/collections/apicontext/open-apicontext-agents-api/)
- [APIContext Notifications (Alerts) API](https://apis.io/collections/apicontext/open-apicontext-alerts-api/)
- [APIContext Calls API](https://apis.io/collections/apicontext/open-apicontext-api-calls-api/)
- [APIContext Suppliers (API Directory) API](https://apis.io/collections/apicontext/open-apicontext-directory-api/)
- [APIContext Governance API](https://apis.io/collections/apicontext/open-apicontext-governance/)
- [APIContext Insights API](https://apis.io/collections/apicontext/open-apicontext-insights-api/)
- [APIContext MCP Monitors API](https://apis.io/collections/apicontext/open-apicontext-mcp-monitors/)
- [APImetrics](https://apis.io/collections/apicontext/open-apicontext-platform/)
- [APIContext Projects API](https://apis.io/collections/apicontext/open-apicontext-projects-api/)
- [APIContext Reports API](https://apis.io/collections/apicontext/open-apicontext-reports-api/)
- [APIContext Results API](https://apis.io/collections/apicontext/open-apicontext-results-api/)
- [APIContext Schedules API](https://apis.io/collections/apicontext/open-apicontext-schedules-api/)
- [APIContext Stats API](https://apis.io/collections/apicontext/open-apicontext-statistics-api/)
- [APIContext Auth Tokens API](https://apis.io/collections/apicontext/open-apicontext-tokens-api/)
- [APIContext Webhooks API](https://apis.io/collections/apicontext/open-apicontext-webhooks/)
- [APIContext Workflows API](https://apis.io/collections/apicontext/open-apicontext-workflows-api/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Apicontext Platform Overlay](https://apis.io/overlays/apicontext/apicontext-platform-overlay/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Apicontext Authentication](https://apis.io/security/apicontext/apicontext-authentication/)
- [Apicontext Domain Security](https://apis.io/security/apicontext/apicontext-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Apicontext Scopes](https://apis.io/scopes/apicontext/apicontext-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Apicontext Plans Pricing](https://apis.io/plans/apicontext/apicontext-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Apicontext Rate Limits](https://apis.io/rate-limits/apicontext/apicontext-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Apicontext Finops](https://apis.io/finops/apicontext/apicontext-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://apicontext.com/)
- [Documentation](https://docs.apimetrics.io/)
- [Getting started](https://docs.apimetrics.io/docs/introducing-apimetrics)
- [API reference](https://docs.apimetrics.io/reference)
- [Pricing](https://apicontext.com/pricing/)
- [Support](https://apicontext.com/support)
- [Changelog](https://docs.apimetrics.io/changelog/)
- [Blog](https://apicontext.com/blog)
- [Terms of service](https://apicontext.com/tos/)
- [GitHub](https://github.com/APImetrics)

## API Evangelist rating

**Kin Score 50.1** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 80.0 |
| Contract quality | 55.9 |
| Contract governance | 18.2 |
| Operational transparency | 26.3 |
| Developer ergonomics | 71.4 |
| Access clarity | 27.6 |

**Agent readiness 59.5** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | yes |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | mostly |

**Regulatory alignment 30.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/apicontext/](https://apis.io/providers/apicontext/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for APIContext: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/apicontext/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).

# University of Geneva

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

The University of Geneva (Université de Genève, UNIGE) is a public research university in Geneva, Switzerland, founded in 1559 and ranked #93 in the QS World University Rankings 2025. Like almost every university it is a federation of buyers rather than an API producer, and it operates no central developer portal, no API gateway, no public key issuance and no self-service onboarding of any kind. What it does operate is unusually real for this cohort, and all of it sits under unige.ch: the Archive ouverte UNIGE institutional repository runs on the University's OWN software (the Identify response reports "AoU v2.3.5", not DSpace, EPrints or Figshare) and serves a live OAI-PMH 2.0 endpoint anonymously; Yareta, the e-Research long-term research-data preservation platform built on the Swiss DLCM/Solidify stack that UNIGE itself leads, exposes access and ingest REST modules on its own hosts with one genuinely public configuration endpoint and everything else behind a bearer token; a self-hosted GitLab serves an anonymous REST API over 1,146 public projects; and the Terminus protein-prediction service offers a small anonymous research API. UNIGE's strongest machine-readable surface is one universities are rarely credited for: its own Shibboleth SAML 2.0 Identity Provider, registered in the SWITCHaai national federation alongside 122 other unige.ch entities. Its library is a tenancy, not an asset — Ex Libris Alma/Primo operated by the SLSP consortium — and its DOI, publication and organization identifiers are registry memberships at DataCite, Crossref and ROR. There is no open-data portal, no course-catalog API (pgc.unige.ch soft-404s every /api path back to its own HTML) and no teaching-and-learning interoperability surface.

**Areas:** Education · Higher Education · University · Public Research University · Open Science · Research Data · Institutional Repository · Research Repository · Identity Federation · OAI-PMH · Switzerland · Europe

## University of Geneva on APIs.io

Everything profiled for University of Geneva is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/university-of-geneva/](https://apis.io/providers/university-of-geneva/)** — or go straight to one of the APIs or properties below.

### APIs (11)

- [UNIGE Shibboleth Identity Provider (SWITCHaai)](https://apis.io/apis/university-of-geneva/switchaai-idp/) — The University of Geneva's own SAML 2.0 Shibboleth Identity Provider, published as machine-readable metadata in SWITCHaai, the Swiss national research and…
- [Archive ouverte UNIGE OAI-PMH](https://apis.io/apis/university-of-geneva/archive-ouverte-oai/) — OAI-PMH 2.0 metadata-harvesting interface for the Archive ouverte UNIGE institutional repository, exposing the University's scientific publications in…
- [Yareta Access API](https://apis.io/apis/university-of-geneva/university-of-geneva-access-api/) — The access/accession module of Yareta, the University of Geneva e-Research long-term research-data preservation platform: discover, order and download…
- [Yareta Ingest API](https://apis.io/apis/university-of-geneva/university-of-geneva-ingest-api/) — The pre-ingest/ingest module of Yareta: deposit, validate and submit research data, reserve a DOI, and submit a SIP for archiving. Runs on UNIGE's own host…
- [Yareta OAI-PMH Provider API](https://apis.io/apis/university-of-geneva/university-of-geneva-oai-pmh-api/) — The OAI-PMH provider-information surface of the Yareta access module — sets, metadata formats and provider configuration for harvesting UNIGE research-data…
- [UNIGE GitLab REST API](https://apis.io/apis/university-of-geneva/gitlab/) — A self-hosted GitLab instance operated by the University on its own domain, serving an anonymous GitLab REST API v4 over its public projects. GET…
- [Terminus Protein Prediction API](https://apis.io/apis/university-of-geneva/terminus/) — A UNIGE-developed prediction service for protein N-terminal modifications (initial methionine cleavage and N-terminal acetylation) across taxonomic groups.…
- [swisscovery UNIGE (SLSP / Ex Libris)](https://apis.io/apis/university-of-geneva/swisscovery-slsp/) — The University of Geneva's library discovery and management tenancy. Its catalog runs on Ex Libris Primo and Alma operated by SLSP (Swiss Library Service…
- [DataCite Repository Membership](https://apis.io/apis/university-of-geneva/datacite-membership/) — UNIGE is a registered DataCite repository operator through the Swiss consortium (DataCite provider "opkb"). Two repository accounts and two DOI prefixes are…
- [Crossref Membership](https://apis.io/apis/university-of-geneva/crossref-membership/) — The University of Geneva is a Crossref member, id 13327, primary-name "Universite de Geneve". Recorded as a registry relationship. Crossref's API is…
- [ROR Organization Identifier](https://apis.io/apis/university-of-geneva/ror-registration/) — ROR identifier https://ror.org/01swzsf04 for the University of Geneva. Notable because the institution's own live service declares it: the public Yareta…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [University Of Geneva Agentic Access](https://apis.io/agentic-access/university-of-geneva/university-of-geneva-agentic-access/)

#### JSON Schema (4)

The data models the API reads and writes.

- [Yareta Archival Information Package (AIP)](https://apis.io/schemas/university-of-geneva/university-of-geneva-aip/)
- [Yareta Dissemination Information Package (DIP)](https://apis.io/schemas/university-of-geneva/university-of-geneva-dip/)
- [Yareta Order](https://apis.io/schemas/university-of-geneva/university-of-geneva-order/)
- [Yareta Organizational Unit](https://apis.io/schemas/university-of-geneva/university-of-geneva-orgunit/)

#### JSON Structure (3)

Data models expressed in JSON Structure.

- [University Of Geneva Aip Structure](https://apis.io/json-structure/university-of-geneva/university-of-geneva-aip-structure/)
- [University Of Geneva Order Structure](https://apis.io/json-structure/university-of-geneva/university-of-geneva-order-structure/)
- [University Of Geneva Orgunit Structure](https://apis.io/json-structure/university-of-geneva/university-of-geneva-orgunit-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [University Of Geneva Context](https://apis.io/jsonld/university-of-geneva/university-of-geneva-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [University of Geneva Research Data API Vocabulary](https://apis.io/vocabularies/university-of-geneva/university-of-geneva-vocabulary/)

#### Examples (4)

Example requests and responses.

- [University Of Geneva Aip Response Example](https://apis.io/examples/university-of-geneva/university-of-geneva-aip-response-example/)
- [University Of Geneva Order Create Request Example](https://apis.io/examples/university-of-geneva/university-of-geneva-order-create-request-example/)
- [University Of Geneva Order Response Example](https://apis.io/examples/university-of-geneva/university-of-geneva-order-response-example/)
- [University Of Geneva Orgunit Response Example](https://apis.io/examples/university-of-geneva/university-of-geneva-orgunit-response-example/)

#### Collections (3)

Postman and Open Collection request collections.

- [Yareta Research Data Access API](https://apis.io/collections/university-of-geneva/open-university-of-geneva-access-api/)
- [Yareta Research Data Access Ingest API](https://apis.io/collections/university-of-geneva/open-university-of-geneva-ingest-api/)
- [Yareta Research Data Access OAI-PMH API](https://apis.io/collections/university-of-geneva/open-university-of-geneva-oai-pmh-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [University of Geneva — jsonschema rules](https://apis.io/rules/university-of-geneva/university-of-geneva-jsonschema-spectral-rules/)
- [University of Geneva API Rules](https://apis.io/rules/university-of-geneva/university-of-geneva-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [University Of Geneva Authentication](https://apis.io/security/university-of-geneva/university-of-geneva-authentication/)
- [University Of Geneva Domain Security](https://apis.io/security/university-of-geneva/university-of-geneva-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [University Of Geneva Plans Pricing](https://apis.io/plans/university-of-geneva/university-of-geneva-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [University Of Geneva Rate Limits](https://apis.io/rate-limits/university-of-geneva/university-of-geneva-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [University Of Geneva Finops](https://apis.io/finops/university-of-geneva/university-of-geneva-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.unige.ch/)
- [Documentation](https://www.unige.ch/eresearch/en/services/yareta/)
- [Support](https://www.unige.ch/help)
- [Blog](https://www.unige.ch/feed/rss)

## API Evangelist rating

**Kin Score 25.8** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 31.8 |
| Contract governance | 23.5 |
| Operational transparency | 10.5 |
| Developer ergonomics | 39.3 |
| Access clarity | 5.3 |

**Agent readiness 26.6** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | documented (partial credit) |
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

**Regulatory alignment 16.7** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/university-of-geneva/](https://apis.io/providers/university-of-geneva/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of Geneva: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/university-of-geneva/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).

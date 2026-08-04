# University of Geneva (university-of-geneva)

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

The University of Geneva (Université de Genève, UNIGE) is a public research university in Geneva, Switzerland, founded in 1559 and ranked #93 in the QS World University Rankings 2025. This profile catalogs UNIGE's public developer and API footprint, which is centered on open science and research infrastructure — an institutional repository (Archive ouverte) with a live OAI-PMH interface, the Yareta research-data-management platform, and research-group services such as the Terminus protein-prediction API.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-geneva/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-geneva-api-evangelist&utm_content=repo

## Type

Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Open Science, Research Data, Institutional Repository, Switzerland, Europe

## APIs

- **Archive ouverte UNIGE OAI-PMH** — OAI-PMH 2.0 metadata harvesting for the institutional repository. Docs: https://archive-ouverte.unige.ch/ (base: https://archive-ouverte.unige.ch/oai)
- **Yareta Research Data API** — DLCM-based REST API for research-data preservation and access. Docs: https://www.unige.ch/eresearch/en/services/yareta/ (base: https://yareta.unige.ch/api)
- **Terminus Protein Prediction API** — HTTP POST prediction of protein N-terminal modifications. Docs: https://terminus.unige.ch/info/API

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/university-of-geneva-plans-pricing.yml](plans/university-of-geneva-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-geneva-rate-limits.yml](rate-limits/university-of-geneva-rate-limits.yml)
- FinOps: [finops/university-of-geneva-finops.yml](finops/university-of-geneva-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.unige.ch/
- GitHub: https://github.com/dis-unige
- LinkedIn: https://www.linkedin.com/school/university-of-geneva/
- Developer / e-Research: https://www.unige.ch/eresearch/en/
- Review: [review.yml](review.yml)

## Notes

All cataloged endpoints were probed live on 2026-06-03. The Archive ouverte OAI-PMH endpoint returned a valid Identify response; the Yareta service pages and REST API base resolved; the Terminus API documentation is live; and the official `dis-unige` GitHub organization (UNIGE Division of Scientific Information) is active. The LogAir API host (`api.logair.unige.ch`) did not resolve at review time and was excluded. No single unified public developer portal exists; APIs are research- and service-specific. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com

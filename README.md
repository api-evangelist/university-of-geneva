# University of Geneva (university-of-geneva)

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

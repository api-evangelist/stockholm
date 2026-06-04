# Stockholm University (stockholm)

Stockholm University (Stockholms universitet) is a public research university in Sweden, ranked #128 in the QS World University Rankings 2025. This repository catalogs its public, machine-readable developer/API footprint as an [APIs.json](http://apisjson.org) profile. Stockholm University does not operate a single consolidated developer portal; its public footprint is distributed across standards-based and third-party services.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/stockholm/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=stockholm-api-evangelist&utm_content=repo

## Type

- Type: Index
- Position: Consumer
- Access: 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Access, Repository, Sweden, Europe

## APIs

- **DiVA Institutional Repository (OAI-PMH)** — Bibliographic metadata harvesting for SU research and student publications via DiVA. Live OAI-PMH 2.0 endpoint. Docs: https://www.su.se/stockholm-university-library/ — Base: https://su.diva-portal.org/dice/oai
- **Research Data Repository (Figshare)** — Open research data and outputs at su.figshare.com, accessible via the Figshare public REST API. Docs: https://docs.figshare.com/ — Base: https://api.figshare.com/v2
- **shib-keygen-api** — Open-source Shibboleth SP/SAML2 metadata keygen tooling from the SU GitHub org. Docs/Source: https://github.com/stockholmuniversity/shib-keygen-api

## Plans

[plans/stockholm-plans-pricing.yml](plans/stockholm-plans-pricing.yml)

## Rate Limits

[rate-limits/stockholm-rate-limits.yml](rate-limits/stockholm-rate-limits.yml)

## FinOps

[finops/stockholm-finops.yml](finops/stockholm-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.su.se/english/
- GitHub: https://github.com/stockholmuniversity
- LinkedIn: https://www.linkedin.com/school/stockholm-university/
- Source Code: https://github.com/stockholmuniversity
- Authentication (Federation): https://www.swamid.se/

## Notes

All entries were verified live where possible. The DiVA OAI-PMH endpoint returned a valid Identify response; the Figshare public REST API and the GitHub org both responded with success codes. No public, documented course/catalog or student-information API was located — the DSV department course portal (courses.dsv.su.se) is an HTML site with no documented public API found. Identity is federated through SWAMID/Shibboleth (SAML2). No endpoints were fabricated; see [review.yml](review.yml) for probed URLs and HTTP statuses.

## Maintainers

- Kin Lane — kin@apievangelist.com

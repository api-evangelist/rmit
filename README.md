# RMIT University (rmit)

RMIT University is a public research university in Melbourne, Australia, focused on technology, design and enterprise, and ranked #123 in the QS World University Rankings 2025. This repository catalogs RMIT's public developer/API footprint as an APIs.json profile. RMIT does not run a centralized developer portal; its most accessible programmatic surface is research output published via a Figshare-hosted repository (queryable through the public Figshare REST API) and a Clarivate Esploro research repository for discovery.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/rmit/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=rmit-api-evangelist&utm_content=repo

## Type

Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research Data, Open Access, Australia

## APIs

- **RMIT Research Data (Figshare REST API)** — RMIT research outputs published to a Figshare institutional repository, queryable as JSON via the shared Figshare REST API v2. Docs: https://docs.figshare.com/ — Repository: https://rmit.figshare.com/
- **RMIT Research Repository (Esploro)** — RMIT's open access research portal on Clarivate Esploro; publicly browsable, no documented public API. Docs: https://researchrepository.rmit.edu.au/

## Plans

See [plans/rmit-plans-pricing.yml](plans/rmit-plans-pricing.yml).

## Rate Limits

See [rate-limits/rmit-rate-limits.yml](rate-limits/rmit-rate-limits.yml).

## FinOps

See [finops/rmit-finops.yml](finops/rmit-finops.yml).

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.rmit.edu.au/
- GitHub: https://github.com/RMIT-University
- LinkedIn: https://www.linkedin.com/school/rmit-university/
- Twitter/X: https://twitter.com/RMIT

## Notes

All entries reflect live verification on 2026-06-03 with no fabricated endpoints. The Figshare REST API (api.figshare.com/v2) was probed and returned real RMIT research records. The Esploro Research Repository is publicly browsable but exposes no documented API or working open OAI-PMH endpoint (candidate OAI URLs returned 404 or an empty SPA shell). Timetable, curriculum catalogue, and identity/SSO systems are gated behind authentication and are not public APIs. The official RMIT GitHub org exists but currently has no public repositories. No public status page resolved at status.rmit.edu.au. The LinkedIn page returns HTTP 999 due to LinkedIn bot blocking, not because the page is missing.

## Maintainers

- Kin Lane — kin@apievangelist.com

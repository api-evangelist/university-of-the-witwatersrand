# University of the Witwatersrand (university-of-the-witwatersrand)

The University of the Witwatersrand (Wits) is a leading public research university in Johannesburg, South Africa, ranked #268 in the QS World University Rankings 2025. This repository catalogs the institution's public, machine-readable developer/API footprint as an APIs.json (0.19) provider profile for the API Evangelist network. Wits has no central branded developer portal; the confirmed public surfaces are standards-based library and open-research interfaces.

APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-the-witwatersrand/refs/heads/main/apis.yml

Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-the-witwatersrand-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Data, Library, Institutional Repository, South Africa, Africa

## APIs

- **WIReDSpace DSpace REST API** — DSpace 9.2 REST API for the Wits institutional repository (communities, collections, items, bitstreams, discovery). Docs: https://wiredspace.wits.ac.za/server/api
- **WIReDSpace OAI-PMH** — OAI-PMH 2.0 metadata harvesting endpoint. Docs: https://wiredspace.wits.ac.za/server/oai/request?verb=Identify
- **Wits Open Data Vault (Figshare)** — Figshare-powered research data repository (DOIs, Altmetric, Dimensions); programmatic access via the Figshare public API. Docs: https://docs.figshare.com/

## Plans / Rate Limits / FinOps

- Plans: [plans/university-of-the-witwatersrand-plans-pricing.yml](plans/university-of-the-witwatersrand-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-the-witwatersrand-rate-limits.yml](rate-limits/university-of-the-witwatersrand-rate-limits.yml)
- FinOps: [finops/university-of-the-witwatersrand-finops.yml](finops/university-of-the-witwatersrand-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.wits.ac.za/
- Library: https://www.wits.ac.za/library/
- GitHub: https://github.com/WitsSoftDev (Wits Mathematical Sciences Software Development Group; departmental, not a central institutional org)
- LinkedIn: https://www.linkedin.com/school/university-of-the-witwatersrand/

## Notes

- No-fabrication discipline applied. The WIReDSpace REST API root (DSpace 9.2) and OAI-PMH Identify response were both verified live.
- The Wits Open Data Vault is confirmed (launched 2025 on Figshare with Altmetric/Dimensions); the institutional Figshare portal returned HTTP 403 to automated fetches, so the Figshare public API and the official announcement page are linked instead of an institution-specific portal URL.
- No central Wits developer portal, open-data API gateway, or student/timetable/SIS API was found publicly documented. LibGuides/LibCal (Springshare) and identity/SSO systems exist but are vendor-hosted and gated.
- The official institutional GitHub organization could not be confirmed; only departmental/course orgs (e.g., WitsSoftDev, WITS-COMS3010) were found.

## Maintainers

- Kin Lane — kin@apievangelist.com

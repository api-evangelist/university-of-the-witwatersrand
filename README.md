# University of the Witwatersrand

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

The University of the Witwatersrand (Wits) is a public research university in Johannesburg, South Africa (ROR 03rp50x72). Wits operates no central developer portal and no student, timetable or registrar API. What it does operate, on its own domain and its own infrastructure, is WIReDSpace — the institutional repository running DSpace 9.2 — which exposes a HAL/JSON REST API and a complete OAI-PMH 2.0 harvesting interface advertising thirteen metadata formats, both answering anonymous callers. It also runs its own SAML 2.0 identity provider, registered in SAFIRE (the South African Identity Federation) and published to eduGAIN, which serves signed metadata as application/samlmetadata+xml — a genuine machine-readable institutional surface that is almost never catalogued as one. Its research data repository, the Wits Open Data Vault at opendata.wits.ac.za, is a Figshare tenant: the hostname is the university's and the 214 DOIs under the Wits DataCite prefix 10.71796 are the university's, but the API contract underneath is Figshare's and is catalogued against Figshare, not against Wits. Everything else in the estate — library discovery, LibGuides, the LMS, student self-service — is vendor software behind authentication. This profile was corrected on 2026-08-30: it previously credited Wits with the generic Figshare v2 API and nine of its tag splits, which were the vendor's engineering, not the university's.

**Areas:** University · Higher Education · Education · Research · South Africa · Africa · Institutional Repository · Research Data · Open Access · Identity Federation · OAI-PMH · DSpace

## University of the Witwatersrand on APIs.io

Everything profiled for University of the Witwatersrand is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/university-of-the-witwatersrand/](https://apis.io/providers/university-of-the-witwatersrand/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [WIReDSpace DSpace REST Root API](https://apis.io/apis/university-of-the-witwatersrand/university-of-the-witwatersrand-root-api/) — HAL/JSON root document of the WIReDSpace DSpace 9.2 REST API, advertising 80 endpoint links including communities, collections, items, discovery, authn and…
- [WIReDSpace DSpace REST Communities API](https://apis.io/apis/university-of-the-witwatersrand/university-of-the-witwatersrand-communities-api/) — Top-level and sub-community containers in WIReDSpace, aligned to Wits faculties, schools and research groupings. Anonymous read, paginated HAL collections.
- [WIReDSpace DSpace REST Collections API](https://apis.io/apis/university-of-the-witwatersrand/university-of-the-witwatersrand-collections-api/) — Collections of items within WIReDSpace communities. Repaired on 2026-08-30: this contract had been welded to twenty-one Figshare /collections and…
- [WIReDSpace DSpace REST Items API](https://apis.io/apis/university-of-the-witwatersrand/university-of-the-witwatersrand-items-api/) — Individual repository records — theses, dissertations, research articles and reports — each with Dublin Core metadata, bitstreams and a Handle under the…
- [WIReDSpace DSpace REST Discovery API](https://apis.io/apis/university-of-the-witwatersrand/university-of-the-witwatersrand-discovery-api/) — Browse indexes and the search/discovery endpoint over WIReDSpace holdings, plus an OpenSearch 1.1 description document at /server/opensearch/service.
- [WIReDSpace OAI-PMH Interface](https://apis.io/apis/university-of-the-witwatersrand/university-of-the-witwatersrand-request-api/) — OAI-PMH 2.0 metadata harvesting endpoint for WIReDSpace. Single-endpoint, verb-driven, answering anonymously, advertising thirteen metadata prefixes…
- [Wits Open Data Vault (Figshare tenant)](https://apis.io/apis/university-of-the-witwatersrand/university-of-the-witwatersrand-open-data-vault/) — The Wits research data repository. The hostname opendata.wits.ac.za is the university's and CNAMEs to proxy-eu-01.figshare.com; the DOIs are minted under…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [University Of The Witwatersrand Agentic Access](https://apis.io/agentic-access/university-of-the-witwatersrand/university-of-the-witwatersrand-agentic-access/)

#### JSON Schema (1)

The data models the API reads and writes.

- [WIReDSpace Community](https://apis.io/schemas/university-of-the-witwatersrand/university-of-the-witwatersrand-community/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [University Of The Witwatersrand Community Structure](https://apis.io/json-structure/university-of-the-witwatersrand/university-of-the-witwatersrand-community-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [University Of The Witwatersrand Context](https://apis.io/jsonld/university-of-the-witwatersrand/university-of-the-witwatersrand-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [University of the Witwatersrand API Vocabulary](https://apis.io/vocabularies/university-of-the-witwatersrand/university-of-the-witwatersrand-vocabulary/)

#### Examples (2)

Example requests and responses.

- [University Of The Witwatersrand Getcommunity Example](https://apis.io/examples/university-of-the-witwatersrand/university-of-the-witwatersrand-getCommunity-example/)
- [University Of The Witwatersrand Oai Identify Example](https://apis.io/examples/university-of-the-witwatersrand/university-of-the-witwatersrand-oai-identify-example/)

#### Collections (6)

Postman and Open Collection request collections.

- [WIReDSpace DSpace REST Collections API](https://apis.io/collections/university-of-the-witwatersrand/open-university-of-the-witwatersrand-collections-api/)
- [WIReDSpace DSpace REST Communities API](https://apis.io/collections/university-of-the-witwatersrand/open-university-of-the-witwatersrand-communities-api/)
- [WIReDSpace DSpace REST Discovery API](https://apis.io/collections/university-of-the-witwatersrand/open-university-of-the-witwatersrand-discovery-api/)
- [WIReDSpace DSpace REST Items API](https://apis.io/collections/university-of-the-witwatersrand/open-university-of-the-witwatersrand-items-api/)
- [WIReDSpace OAI-PMH Interface Request API](https://apis.io/collections/university-of-the-witwatersrand/open-university-of-the-witwatersrand-request-api/)
- [WIReDSpace DSpace REST Root API](https://apis.io/collections/university-of-the-witwatersrand/open-university-of-the-witwatersrand-root-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [University of the Witwatersrand — jsonschema rules](https://apis.io/rules/university-of-the-witwatersrand/university-of-the-witwatersrand-jsonschema-spectral-rules/)
- [University of the Witwatersrand API Rules](https://apis.io/rules/university-of-the-witwatersrand/university-of-the-witwatersrand-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [University Of The Witwatersrand Authentication](https://apis.io/security/university-of-the-witwatersrand/university-of-the-witwatersrand-authentication/)
- [University Of The Witwatersrand Domain Security](https://apis.io/security/university-of-the-witwatersrand/university-of-the-witwatersrand-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [University Of The Witwatersrand Plans Pricing](https://apis.io/plans/university-of-the-witwatersrand/university-of-the-witwatersrand-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [University Of The Witwatersrand Rate Limits](https://apis.io/rate-limits/university-of-the-witwatersrand/university-of-the-witwatersrand-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [University Of The Witwatersrand Finops](https://apis.io/finops/university-of-the-witwatersrand/university-of-the-witwatersrand-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.wits.ac.za/)
- [Blog](https://www.wits.ac.za/news/)
- [Terms of service](https://www.wits.ac.za/site-assets/small-footer/terms-and-conditions-of-use/)
- [Privacy policy](https://www.wits.ac.za/popia/)
- [GitHub](https://github.com/WitsSoftDev)

## API Evangelist rating

**Kin Score 34.6** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 56.7 |
| Contract governance | 13.6 |
| Operational transparency | 7.9 |
| Developer ergonomics | 25.0 |
| Access clarity | 26.3 |

**Agent readiness 22.2** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 24.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/university-of-the-witwatersrand/](https://apis.io/providers/university-of-the-witwatersrand/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of the Witwatersrand: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/university-of-the-witwatersrand/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).

# Tetra Tech

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

Tetra Tech is a global consulting and engineering services firm headquartered in Pasadena, California. Founded in 1966, it provides consulting, engineering, program management, and construction management services across water, environment, infrastructure, resource management, energy, and international development. With 30,000 employees across 550 offices worldwide, Tetra Tech delivers data-driven digital solutions under the Tetra Tech Delta brand and maintains an open-source GitHub organization with environmental data analysis tools.

**URL:** [https://www.tetratech.com/](https://www.tetratech.com/)

## Tags

- Analytics
- Consulting
- Data Management
- Engineering
- Environment
- Infrastructure
- Water

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-03

## APIs

| Name | Description |
|---|---|
| [Cosmos Mobile Data Platform API](https://cosmos.tetratech.com/) | Mobile data collection platform with API and webhook integration for field data synchronization. |
| [Tetra Tech Data Discovery Tool API](https://github.com/tetratech/DataDiscoveryTool) | Open-source environmental data analysis platform developed with USEPA for water quality datasets. |
| [baytrends Water Quality Trend API](https://github.com/tetratech/baytrends) | Open-source R package for GAM-based long-term water quality trend analysis, used for Chesapeake Bay monitoring. |
| [Tetra Tech Delta Data Management Services](https://www.tetratech.com/tetra-tech-delta/) | Enterprise data management, SCADA integration, and AI-powered analytics for industrial and utility clients. |
| [WaterNet Water Network Management API](https://www.tetratech.com/solutions/one-water/digital-water/) | SaaS platform for water utility network management and infrastructure intelligence. |

## Artifacts

| Type | URL |
|---|---|
| JSON Schema (Project) | [tetra-tech-project-schema.json](json-schema/tetra-tech-project-schema.json) |
| JSON Schema (Water Quality) | [tetra-tech-water-quality-schema.json](json-schema/tetra-tech-water-quality-schema.json) |
| JSON Structure (Project) | [tetra-tech-project-structure.json](json-structure/tetra-tech-project-structure.json) |
| JSON Structure (Water Quality) | [tetra-tech-water-quality-structure.json](json-structure/tetra-tech-water-quality-structure.json) |
| JSON-LD Context | [tetra-tech-context.jsonld](json-ld/tetra-tech-context.jsonld) |
| Vocabulary | [tetra-tech-vocabulary.yml](vocabulary/tetra-tech-vocabulary.yml) |

## Examples

| Name | Description |
|---|---|
| [Water Quality Sample Example](examples/tetra-tech-water-quality-sample-example.json) | Chesapeake Bay water quality sample with multi-parameter measurements including pH, dissolved oxygen, and nutrients. |
| [Project Example](examples/tetra-tech-project-example.json) | Chesapeake Bay long-term monitoring project using Cosmos data collection and baytrends trend analysis. |

## GitHub Organization

Tetra Tech maintains open-source environmental data tools at [github.com/tetratech](https://github.com/tetratech):

- **DataDiscoveryTool** — QAQC updates to USEPA's Data Discovery Tool
- **baytrends** — Long-term water quality trend analysis using GAM
- **baytrendsmap** — Shiny app for baytrends visualization

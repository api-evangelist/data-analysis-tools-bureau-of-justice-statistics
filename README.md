# Bureau of Justice Statistics Data Analysis Tools (data-analysis-tools-bureau-of-justice-statistics)

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

The Bureau of Justice Statistics (BJS) is the agency within the U.S. Department of Justice responsible for collecting, analysing, and disseminating crime, criminal-justice, expenditure, and victimisation data. BJS exposes selected datasets through Socrata Open Data APIs and offers interactive data analysis tools such as the Justice Expenditure and Employment Tool (JEET) and the National Crime Victimization Survey (NCVS) Quick Tables.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/data-analysis-tools-bureau-of-justice-statistics/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/data-analysis-tools-bureau-of-justice-statistics/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Crime Statistics
- Federal Government
- NCVS
- NIBRS
- Open Data
- SODA
- Statistics
- Victimization

## Timestamps

- **Created:** 2024-11-30
- **Modified:** 2026-05-19

## APIs

### BJS NCVS API

The National Crime Victimization Survey (NCVS) API exposes selected NCVS datasets via the Socrata Open Data API. Datasets are addressed by four-character resource codes and may be queried with SoQL clauses such as $select, $where, $group, $order, and $limit, returning JSON or CSV.

- **Human URL:** [https://bjs.ojp.gov/national-crime-victimization-survey-ncvs-api](https://bjs.ojp.gov/national-crime-victimization-survey-ncvs-api)
- **Base URL:** `https://api.ojp.gov/bjsdataset/v1`

#### Tags

- Crime Statistics
- NCVS
- SODA
- Victimization

#### Properties

- [Documentation](https://bjs.ojp.gov/national-crime-victimization-survey-ncvs-api)
- [Featured](https://bjs.ojp.gov/featured/national-crime-victimization-survey-ncvs-application-programming-interface-api)
- [OpenAPI](openapi/bjs-ncvs-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bjs-ncvs-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bjs-ncvs-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/bjs-dataset-row.json) — [JSON Schema](https://json-schema.org/specification)
- [Rules](rules/bjs-ncvs-api-rules.yml)
- [Capabilities](capabilities/bjs-data-analysis-tools-capabilities.yml)

### BJS NIBRS National Estimates API

The NIBRS National Estimates API publishes selected National Incident-Based Reporting System national-estimates datasets via the Socrata Open Data API, addressable via four-character resource codes and queryable with SoQL.

- **Human URL:** [https://bjs.ojp.gov/national-incident-based-reporting-system-nibrs-national-estimates-api](https://bjs.ojp.gov/national-incident-based-reporting-system-nibrs-national-estimates-api)
- **Base URL:** `https://api.ojp.gov/bjsdataset/v1`

#### Tags

- Crime Statistics
- NIBRS
- SODA

#### Properties

- [Documentation](https://bjs.ojp.gov/national-incident-based-reporting-system-nibrs-national-estimates-api)
- [OpenAPI](openapi/bjs-nibrs-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bjs-nibrs-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bjs-nibrs-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/bjs-dataset-row.json) — [JSON Schema](https://json-schema.org/specification)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/bureau-of-justice-statistics)
- [Website](https://bjs.ojp.gov/)
- [Data  Analysis  Tools](https://bjs.ojp.gov/data/data-analysis-tools)
- [Data  Collections](https://bjs.ojp.gov/data-collections)
- [Publications](https://bjs.ojp.gov/library)
- [D O J  Developer](https://www.justice.gov/developer)
- [JSON-LD](json-ld/bjs-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/bjs-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

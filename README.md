# Bureau of Justice Statistics (data-analysis-tools-bureau-of-justice-statistics)
The Bureau of Justice Statistics (BJS) is the agency within the U.S. Department of Justice responsible for collecting, analysing, and disseminating crime, criminal-justice, expenditure, and victimisation data. BJS exposes selected datasets through Socrata Open Data APIs and offers interactive data analysis tools such as the Justice Expenditure and Employment Tool (JEET) and the National Crime Victimization Survey (NCVS) Quick Tables.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/data-analysis-tools-bureau-of-justice-statistics/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party
- **xType:** government

## Tags:

 - Crime Statistics, Federal Government, NCVS, NIBRS, Open Data, SODA, Statistics, Victimization

## Timestamps

- **Created:** 2024-11-30
- **Modified:** 2026-04-28

## APIs

### BJS NCVS API
The National Crime Victimization Survey (NCVS) API exposes selected NCVS datasets via the Socrata Open Data API. Datasets are addressed by four-character resource codes and may be queried with SoQL clauses such as $select, $where, $group, $order, and $limit, returning JSON or CSV.

**Human URL:** [https://bjs.ojp.gov/national-crime-victimization-survey-ncvs-api](https://bjs.ojp.gov/national-crime-victimization-survey-ncvs-api)

**Base URL:** https://api.ojp.gov/bjsdataset/v1

#### Tags:

 - Crime Statistics, NCVS, SODA, Victimization

#### Properties

- [Documentation](https://bjs.ojp.gov/national-crime-victimization-survey-ncvs-api)
- [Featured](https://bjs.ojp.gov/featured/national-crime-victimization-survey-ncvs-application-programming-interface-api)
- [OpenAPI](openapi/bjs-ncvs-api-openapi.yml)
- [JSONSchema - Dataset Row](json-schema/bjs-dataset-row.json)
- [Rules](rules/bjs-ncvs-api-rules.yml)
- [Capabilities](capabilities/bjs-data-analysis-tools-capabilities.yml)

### BJS NIBRS National Estimates API
The NIBRS National Estimates API publishes selected National Incident-Based Reporting System national-estimates datasets via the Socrata Open Data API, addressable via four-character resource codes and queryable with SoQL.

**Human URL:** [https://bjs.ojp.gov/national-incident-based-reporting-system-nibrs-national-estimates-api](https://bjs.ojp.gov/national-incident-based-reporting-system-nibrs-national-estimates-api)

**Base URL:** https://api.ojp.gov/bjsdataset/v1

#### Tags:

 - Crime Statistics, NIBRS, SODA

#### Properties

- [Documentation](https://bjs.ojp.gov/national-incident-based-reporting-system-nibrs-national-estimates-api)
- [OpenAPI](openapi/bjs-nibrs-api-openapi.yml)
- [JSONSchema - Dataset Row](json-schema/bjs-dataset-row.json)

## Common Properties

- [Website](https://bjs.ojp.gov/)
- [Data Analysis Tools](https://bjs.ojp.gov/data/data-analysis-tools)
- [Data Collections](https://bjs.ojp.gov/data-collections)
- [Publications](https://bjs.ojp.gov/library)
- [DOJ Developer](https://www.justice.gov/developer)
- [JSON-LD](json-ld/bjs-context.jsonld)
- [Vocabulary](vocabulary/bjs-vocabulary.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

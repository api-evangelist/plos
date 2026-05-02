## PLOS (plos)

These examples use the search API to search the PLOS corpus of scientific articles. These examples are not intended to be a full explanation on the use of Solr. A full Solr query language explanation can be found here and a tutorial here. The construction of PLOS search queries deviates from the standard Solr query URL by using `search` instead of `select` when making requests to the end point.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/plos/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Scientific Articles
- Research
- Search
- Solr
- Open Access

## Timestamps

- **Created:** 2025-02-06
- **Modified:** 2026-04-28

## APIs

### PLOS Search API

These examples use the search API to search the PLOS corpus of scientific articles. The construction of PLOS search queries deviates from the standard Solr query URL by using `search` instead of `select` when making requests to the end point.

**Human URL:** https://api.plos.org/solr/examples/

**Base URL:** `http://api.plos.org/search`

#### Common Query Parameters

- `q` - Search query and fields to search (required)
- `fl` - Fields to return in the result set
- `wt` - Response format (e.g. `json`, default `xml`)
- `start` - Pagination start row
- `rows` - Maximum number of results (default 10)

#### Tags

- Scientific Articles
- Search
- Solr

#### Properties

- [Documentation](https://api.plos.org/solr/examples/)
- [Search Fields](https://api.plos.org/solr/search-fields/)

## Common Properties

- [Website](https://plos.org)
- [Documentation](https://api.plos.org/solr/examples/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

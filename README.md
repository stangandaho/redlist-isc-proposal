# ISC Grant Proposal: redlist EOO/AOO Extension

This repository contains the ISC grant proposal for extending the
[redlist](https://github.com/stangandaho/redlist) R package with a
taxonomic bridge and occurrence data pipeline for IUCN Red List
assessments.

## What the proposal is about

The `redlist` package provides access to the IUCN Red List V4 API.
This proposal extends it to resolve IUCN species names to the GBIF
taxonomic backbone, retrieve occurrence records under all known synonyms,
and check data quality before computing Criterion B metrics (EOO and AOO).

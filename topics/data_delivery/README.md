# Data Delivery

Data delivery covers the patterns, practices, and tooling used to move data reliably from a source system to one or more consumers — whether that means loading raw events into a warehouse, serving aggregated metrics to a dashboard, or publishing a clean dataset to a downstream team.

## Topics

| Document | Summary |
|---|---|
| *(coming soon)* | — |

## Key Concepts

- **Ingestion patterns** — batch vs. streaming, push vs. pull, full load vs. incremental
- **Schema management** — evolution strategies, compatibility levels, schema registries
- **Delivery guarantees** — at-most-once, at-least-once, exactly-once semantics
- **Idempotency** — designing pipelines so that re-running them produces the same result
- **Backfill and replay** — strategies for recovering or re-processing historical data
- **SLA / SLO alignment** — defining and meeting data freshness commitments

## Snowflake Notes

- Snowflake stages (internal and external) as a landing zone
- `COPY INTO` and Snowpipe for continuous ingest
- Dynamic Tables for declarative, incremental transformations
- `MERGE` patterns for upsert / CDC delivery

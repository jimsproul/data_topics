# Observability

Observability for data systems is the ability to understand what is happening inside your pipelines, tables, and queries from the outside — using the signals they emit. It goes beyond simple uptime monitoring to cover data quality, lineage, performance, and cost.

## Topics

| Document | Summary |
|---|---|
| *(coming soon)* | — |

## Key Concepts

- **The three pillars** — metrics, logs, and traces applied to data workloads
- **Data freshness monitoring** — detecting when tables stop updating on schedule
- **Data quality checks** — null rates, row counts, distribution shifts, referential integrity
- **Lineage** — understanding upstream dependencies and downstream impact of changes
- **Pipeline performance** — query duration, queue time, warehouse utilization
- **Anomaly detection** — statistical and ML-based approaches to spotting unexpected changes
- **Alerting** — thresholds, seasonality-aware rules, and alert fatigue management
- **Dashboards** — designing operational views for data health

## Snowflake Notes

- `INFORMATION_SCHEMA` and `ACCOUNT_USAGE` as observability data sources
- Snowflake query tags for correlating pipeline executions to query history
- `COPY_HISTORY`, `PIPE_USAGE_HISTORY`, and `TASK_HISTORY` views
- Integration with external observability platforms (Datadog, Grafana, Monte Carlo, etc.)

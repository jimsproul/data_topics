# Data Reliability Engineering

Data Reliability Engineering (DRE) applies the principles of Site Reliability Engineering (SRE) to data systems. The goal is to treat data pipelines and datasets as products with explicit reliability targets — and to build the operational practices needed to meet them.

## Topics

| Document | Summary |
|---|---|
| *(coming soon)* | — |

## Key Concepts

- **Data SLOs** — defining Service Level Objectives for freshness, completeness, and accuracy
- **Error budgets** — quantifying how much unreliability is acceptable before action is required
- **Toil reduction** — automating away repetitive manual work in data operations
- **Incident response** — on-call rotations, runbooks, and post-mortems for data outages
- **Data contracts** — formal agreements between data producers and consumers
- **Change management** — safe deployment practices for schema and pipeline changes
- **Capacity planning** — forecasting compute and storage needs for data workloads

## Snowflake Notes

- Query history and `ACCOUNT_USAGE` views as a reliability signal source
- Resource monitors and warehouses for cost and performance guardrails
- Time Travel and Fail-safe for data recovery
- Alerts and notification integrations for proactive monitoring

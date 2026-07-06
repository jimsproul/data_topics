# data_topics

A collection of data topic documents and tools focused on **data delivery**, **data reliability engineering**, and **observability**.

Examples and tooling are primarily demonstrated using [Snowflake](https://www.snowflake.com/), but the concepts and patterns covered are designed to be platform-agnostic and applicable across modern data stacks.

---

## Topics

| Area | Description |
|---|---|
| [Data Delivery](topics/data_delivery/) | Patterns and practices for moving data reliably from source to consumer |
| [Data Reliability Engineering](topics/data_reliability/) | Applying SRE principles to data pipelines — SLOs, error budgets, on-call, and more |
| [Observability](topics/observability/) | Monitoring, alerting, lineage, and end-to-end visibility for data systems |

## Tools

Utility scripts and reusable tooling live in [`tools/`](tools/). Each tool has its own README with usage instructions.

---

## Contributing

1. Fork the repository and create a branch from `main`.
2. Add your document or tool under the appropriate `topics/` or `tools/` directory.
3. Follow the structure of existing documents (frontmatter, sections, code examples).
4. Open a pull request with a short description of what you've added.

## License

[MIT](LICENSE)
# Tools

Utility scripts and reusable tooling to support data delivery, reliability, and observability work.

## Contents

| Tool | Language | Description |
|---|---|---|
| *(coming soon)* | — | — |

## Adding a Tool

1. Create a subdirectory under `tools/` named after your tool (e.g., `tools/freshness_checker/`).
2. Add a `README.md` inside the subdirectory with:
   - **Purpose** — what problem the tool solves
   - **Requirements** — language version, dependencies, environment variables
   - **Usage** — command-line examples or code snippets
3. Keep tools self-contained where possible; avoid shared state between tool directories.

## Conventions

- Python tools should include a `requirements.txt` or `pyproject.toml`.
- SQL tools should be written for Snowflake by default; note any dialect differences.
- Scripts that require credentials should read them from environment variables, never hard-code them.

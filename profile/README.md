# Kuno Labs

![Kuno Labs](assets/kunolabs-banner.svg)

Local-first developer tools for AI-assisted engineering.

We build compact, inspectable systems that help coding agents understand a repository before they spend a large context window reading it. The focus is practical: smaller prompts, clearer maps, safer local artifacts, and tooling that stays fast enough to use during real work.

## Flagship Project

| Project | Status | Focus |
| --- | --- | --- |
| [CodePrism](https://github.com/kunolabs/codeprism) | Alpha | Local codebase maps, focused context slices, exact retrieval handles, and optional visual replay for AI coding agents. |

CodePrism's checked-in fixture suite currently reports a 68.75% average estimated source-to-slice reduction. Larger local projects can show stronger reductions when the agent starts with a narrow task and uses targeted retrieval, but all token counts are estimates rather than billing-grade measurements.

The workflow is simple: map first, slice next, retrieve exactly, and read raw files only when they matter.

## What We Care About

- Local-first tools with no network calls by default.
- Inspectable text, JSON, SQLite, and HTML artifacts.
- Deterministic static parsing before model-generated summaries.
- Measured benchmarks over viral claims.
- Cross-platform CLI behavior for Windows, macOS, and Linux.

## Links

- [CodePrism repository](https://github.com/kunolabs/codeprism)
- [CodePrism README](https://github.com/kunolabs/codeprism#readme)
- [Benchmark notes](https://github.com/kunolabs/codeprism/blob/main/docs/benchmarks.md)

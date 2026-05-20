# Kuno Labs

![Kuno Labs](assets/kunolabs-banner.svg)

Local-first developer tools and open source game-streaming infrastructure.

Kuno Labs builds compact, inspectable systems for agent-assisted engineering and
personal computing. The focus is practical: smaller prompts, clearer codebase
maps, local artifacts you can audit, reproducible maintainer workflows, and tools
that stay useful when the network is off.

## Featured Work

| Project | Status | Focus |
| --- | --- | --- |
| [CodePrism](https://github.com/kunolabs/codeprism) | Alpha | Local codebase maps, focused context slices, exact retrieval handles, token estimates, and optional visual replay for AI coding agents. |
| [Nimbus](https://github.com/kunolabs/Nimbus) | Bootstrap | Community-maintained game streaming host fork based on the Vibepollo, Apollo, and Sunshine lineage. |
| Lucent | Planned | Companion client track for the Artemis/Moonlight Android lineage. |

## CodePrism

CodePrism helps coding agents inspect a repository before brute-reading it. The
workflow is simple:

```bash
codeprism prime "what I am changing" --changed
codeprism query "where does this behavior live?"
codeprism visualize
```

It exports Markdown, JSON, DOT, SQLite, and static browser artifacts so the
context path stays visible instead of disappearing inside a chat window. Benchmark
claims are kept conservative: fixture results, local field notes, and estimated
token reductions are documented separately.

## Nimbus

Nimbus is the host side of the Kuno Labs game-streaming work. It starts from the
Vibepollo/Apollo/Sunshine ecosystem and focuses on public maintainability before
big feature promises: clear docs, release hygiene, upstream attribution, stable
branch policy, and reproducible validation.

The first Nimbus milestone is to make the fork easy to understand, build, audit,
and discuss before publishing branded releases.

## What We Care About

- Local-first tools with no network calls by default.
- Inspectable text, JSON, SQLite, and HTML artifacts.
- Deterministic static parsing before model-generated summaries.
- Honest benchmark language and reproducible release notes.
- Cross-platform CLI behavior for Windows, macOS, and Linux.
- Open source maintenance that is boring, transparent, and repeatable.

## Links

- [CodePrism repository](https://github.com/kunolabs/codeprism)
- [Nimbus repository](https://github.com/kunolabs/Nimbus)
- [CodePrism benchmark notes](https://github.com/kunolabs/codeprism/blob/main/docs/benchmarks.md)

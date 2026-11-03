# Immigration Law & Intelligence

Official-record intelligence for immigration law: what agencies publish, what the
statistics actually say, and where a claim can be traced back to a document.

**Status: in development — planning and structure only.** No public build exists,
and no verified working software is published here.

This repository is a **public project showcase**. It documents purpose, model and
boundaries. The implementation is developed in a private repository and is not
published here.

---

## Why it exists

Immigration law generates an enormous public record — agency statistics,
processing times, policy manuals, Federal Register notices, court decisions — and
very little of it is readable side by side. Numbers travel further than the
documents they came from, and a statistic without its definition, period and
geography is not evidence. This project asks: **can an intelligence layer over
official records make the difference between a sourced figure and a screenshotted
one visible at a glance?**

## The official-record intelligence model

The core discipline is that every displayed figure is a **derived value with a
trail**, never a bare number:

| Layer | What it holds |
|---|---|
| **Record** | The primary document or dataset as published, with issuing agency, identifier and retrieval date. |
| **Definition** | The definition actually used by the publisher — period, geography, population, counting rule, revisions. |
| **Derivation** | The transformation from record to figure, recorded so the figure can be recomputed. |
| **Presentation** | Statistics, charts and maps, each carrying a link back through derivation to record. |
| **Verification state** | Whether a human has confirmed the record's definition and derivation, or whether it is unreviewed machine association. |

Maps are treated as a presentation of a defined geography, not as a neutral truth.
Where a boundary, catchment or region is contested or simply undefined, the map
says so instead of drawing a line.

## Public-information mission

This project works from **public** records only. Its purpose is to make official
material legible and traceable for people who need it — practitioners, advocates,
journalists, researchers and individuals reading about their own situation.

Stated plainly, because it matters:

- This is **not legal advice**, and no part of it is a substitute for a licensed
  attorney's assessment of a specific case.
- It does not predict the outcome of any individual application.
- It does not present model-generated associations as verified facts.

## What works today

Nothing verifiable. There is no public deployment, no released dataset and no
published statistic from this project. This showcase records the model and its
boundaries while the private development repository holds a labelled scaffold.

## Planned milestones

| Milestone | State |
|---|---|
| Intelligence model: record → definition → derivation → presentation | Documented |
| Boundaries, non-advice statement, verification rules | Documented |
| Private development scaffold | Initialised |
| Official-record ingestion with retrieval provenance | Planned |
| Statistics surface with recomputable derivations | Planned |
| Map surface tied to defined geographies | Planned |
| Legal and privacy review before any public dataset | Required, not started |
| Public preview build | Not scheduled |

## Boundaries

- **No raw restricted datasets are committed or published.** Datasets whose terms
  forbid redistribution are used under their terms and are never mirrored here.
- **No personal or case-level data.** Nothing about an identifiable individual is
  processed to build a statistic, and no case files are part of this project.
- No conclusion is published without a source a reader can open.
- No automated publication of legal interpretation: anything consequential is
  human-reviewed.

## Intended audience

Immigration practitioners and paralegals, legal-aid and advocacy organisations,
journalists covering immigration policy, and researchers working with official
statistics.

## Related projects

Other public projects in this portfolio:

- [LegacyOS](https://github.com/DanUrtnowski/LegacyOS) — a modern environment for old x86 hardware
- [MuseForge](https://github.com/DanUrtnowski/MuseForge-Showcase) — real-instrument music learning
- [Open E-Reader](https://github.com/DanUrtnowski/Open-E-Reader) — a free, offline-first reader
- [Secure Browser](https://github.com/DanUrtnowski/Secure-Browser) — a privacy-oriented browser concept
- [Whale Intelligence Network](https://github.com/DanUrtnowski/Whale-Intelligence-Network) — whale and dolphin research intelligence
- [Power Line News](https://github.com/DanUrtnowski/Power-Line-News) — utility infrastructure accountability
- [Coronado Happenings](https://github.com/DanUrtnowski/Coronado-Happenings) — a hyperlocal community publication
- [Voalt](https://github.com/DanUrtnowski/Voalt) — the network that connects these projects

Portfolio profile: [DanUrtnowski](https://github.com/DanUrtnowski)

## Scope and licensing

This is a **showcase repository** containing documentation only:

- No implementation source code is published here.
- **No open-source licence is granted** for the private implementation.
- Third-party documents and datasets referenced remain under their publishers'
  terms; nothing here grants rights to redistribute them.

See [CHANGELOG.md](CHANGELOG.md) for the public milestone record.

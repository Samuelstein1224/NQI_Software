# NQI Software

> **Live archive:** https://samuelstein1224.github.io/NQI_Software/ *(after enabling GitHub Pages)*

A community-maintained directory of open-source software, libraries, and benchmarks produced by — or significantly funded through — the five U.S. Department of Energy **National Quantum Information Science Research Centers**.

The five centers were established by the [National Quantum Initiative Act](https://www.congress.gov/bill/115th-congress/house-bill/6227) in 2018 and renewed in November 2025 with $625M over five years.

| Center | Lead Lab | Focus | Page |
|---|---|---|---|
| **C2QA** — Co-design Center for Quantum Advantage | Brookhaven National Laboratory | Co-design of materials, devices, software & error correction | [centers/c2qa.md](centers/c2qa.md) |
| **Q-NEXT** | Argonne National Laboratory / SLAC | Distributed entanglement, quantum networking, foundries | [centers/q-next.md](centers/q-next.md) |
| **QSA** — Quantum Systems Accelerator | Lawrence Berkeley National Lab / Sandia | Neutral atoms, trapped ions, superconducting co-design | [centers/qsa.md](centers/qsa.md) |
| **QSC** — Quantum Science Center | Oak Ridge National Laboratory | Fault-tolerant hybrid quantum-HPC ecosystem | [centers/qsc.md](centers/qsc.md) |
| **SQMS** — Superconducting Quantum Materials & Systems | Fermi National Accelerator Laboratory | SRF cavity-based quantum platforms, materials & control | [centers/sqms.md](centers/sqms.md) |

## What this is

Two things in one repo:

1. **A static site** ([`index.html`](index.html)) — a searchable, filterable archive of all entries. Open it locally or visit the GitHub Pages URL above.
2. **Per-center markdown pages** under [`centers/`](centers/) — the source of truth, easy to scan on GitHub and easy to PR against.

Both views are kept in sync manually for now; the canonical machine-readable data lives in the `<script id="data">` block at the bottom of `index.html`.

## Scope

We include software whose published artifacts (papers, READMEs, websites, or grant numbers) explicitly acknowledge one of the five centers. Software *adjacent* to a center (e.g. produced by a partner institution without direct center funding) is marked **pending** until acknowledgment is confirmed — see [`centers/_pending.md`](centers/_pending.md).

## How to contribute

See [CONTRIBUTING.md](CONTRIBUTING.md). To add an entry you'll edit two places:

- the appropriate `centers/<center>.md` page
- the JSON data block in `index.html`

## Enabling GitHub Pages

This repo is configured as a static site (no Jekyll — `.nojekyll` is present). To publish:

1. Push the repo to GitHub.
2. *Settings → Pages → Build and deployment:* set **Source = Deploy from a branch**, **Branch = `main`**, folder `/ (root)`.
3. The site goes live at `https://<owner>.github.io/<repo>/` within ~1 minute.

To preview locally, just open `index.html` in a browser — no build step required.

## Highlighted entries

The two repos that motivated this directory:

- [FTPrimitiveBench](https://github.com/ShuwenKan/FTPrimitiveBench) — benchmark suite for fault-tolerant primitives under hardware-motivated noise ([arXiv:2605.04049](https://arxiv.org/abs/2605.04049))
- [FTCircuitBench](https://github.com/AdrianHarkness/FTCircuitBench) — benchmark suite for fault-tolerant compilation & architecture ([arXiv:2601.03185](https://arxiv.org/abs/2601.03185))

## Disclaimer

This is an unofficial, community-curated index. It is not affiliated with any of the centers, with DOE, or with any partner institution. Entries reflect public information at time of listing; correct or remove anything inaccurate via PR.

# Contributing

This is an index of NQI-center-affiliated software. Contributions are welcome by PR.

## Adding an entry

Each new entry lives in **two places** that must be updated together:

1. The center page under `centers/` (the human-readable source of truth).
2. The JSON data block at the bottom of `index.html` (drives the searchable site).

### Steps

1. Pick the center whose acknowledgment is cited in the software's paper, README, or grant. If multiple centers, list it under each.
2. Add a section to the relevant `centers/<center>.md` using the markdown template below. Keep entries alphabetical within each section.
3. Add a matching JSON object to the `<script id="data">` block in `index.html` using the JSON schema below.
4. Open `index.html` in a browser to verify your entry renders and is findable via search.

### Markdown entry template

```markdown
### [project-name](https://github.com/org/repo)

One-line description of what the software does.

- **Type:** library / benchmark / simulator / control / compiler / framework / dataset / other
- **Primary institution(s):** Lab or university
- **Authors:** Lead authors (optional — link arXiv)
- **Acknowledgment:** Grant number(s), e.g. `DE-SC0012704` (C2QA)
- **Paper:** [arXiv:NNNN.NNNNN](https://arxiv.org/abs/NNNN.NNNNN) or DOI
- **License:** MIT / BSD-3 / Apache-2.0 / CC-BY-4.0 / GPL / other
- **Status:** active / maintenance / archived (as of YYYY-MM)
```

### JSON entry schema (for `index.html`)

```json
{
  "id": "kebab-case-slug",
  "name": "Project Name",
  "tagline": "Short, descriptive subtitle.",
  "description": "One- or two-sentence overview suitable for a card.",
  "url": "https://github.com/org/repo",
  "centers": ["C2QA"],
  "primary_institutions": ["Brookhaven National Laboratory"],
  "type": "simulator",
  "license": "BSD-2-Clause",
  "status": "active",
  "verified": true,
  "grant": "DE-SC0012704",
  "paper": { "title": "Paper title", "arxiv": "2401.12345" }
}
```

`status` is `active` for confirmed entries, `pending` while awaiting acknowledgment verification.
`verified: false` means the NQI link has not yet been confirmed in the paper or README.

## What counts as an NQI-affiliated software project?

Strong evidence (add to main list):

- The project's paper or README explicitly thanks one of: C2QA, Q-NEXT, QSA, QSC, SQMS, or cites the corresponding DOE contract number.
- The project's README states it was developed under one of the centers.

Weaker evidence (add to `centers/_pending.md` first, then promote when confirmed):

- Authored by a center PI without explicit acknowledgment.
- Hosted under a national-lab GitHub org with no funding statement.

## Known DOE contract numbers

| Center | Contract |
|---|---|
| C2QA | DE-SC0012704 (Brookhaven) |
| Q-NEXT | DE-AC02-06CH11357 (Argonne) |
| QSA | DE-AC02-05CH11231 (LBNL) |
| QSC | DE-FOA-0002253 / ORNL |
| SQMS | DE-AC02-07CH11359 (Fermilab) |

These are starting points — many projects cite multiple contract numbers; the paper acknowledgments are authoritative.

## Style

- Keep descriptions to one line; longer context belongs in the linked README or paper.
- Prefer the project's canonical URL (org page) over a fork.
- If a project is archived, note it; don't delete it — history is useful.

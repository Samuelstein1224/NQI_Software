# Pending verification

Software believed to be NQI-affiliated but where the formal acknowledgment in the paper or README has not yet been confirmed. Once verified, move the entry into the relevant center page.

## How to promote an entry

1. Open the project's published paper(s) — check the **Acknowledgments** section.
2. Open the project's `README.md` and `CITATION.cff` (if present) — check for grant numbers or center mentions.
3. If a center is named or the contract number matches the table in [../CONTRIBUTING.md](../CONTRIBUTING.md), move the entry to the appropriate `centers/<center>.md` page.
4. If multiple centers are cited, list it under each, with cross-references.
5. If no NQI center is cited, remove it from this file.

## Candidates

### [FTPrimitiveBench](https://github.com/ShuwenKan/FTPrimitiveBench)

Python library for constructing and benchmarking fault-tolerant primitives under hardware-motivated noise.

- **Paper:** [arXiv:2605.04049](https://arxiv.org/abs/2605.04049)
- **Authors:** Shuwen Kan, Adrian Harkness, Zefan Du, Rod Rofougaran, Sean Garner, Chenxu Liu, Ying Mao, Samuel Stein
- **License:** CC-BY-4.0
- **Verify:** check author affiliations + acknowledgments section of the arXiv PDF for C2QA / PNNL / other DOE center citations

### [FTCircuitBench](https://github.com/AdrianHarkness/FTCircuitBench)

Benchmark suite for fault-tolerant quantum compilation and architecture (Clifford+T, PBC).

- **Paper:** [arXiv:2601.03185](https://arxiv.org/abs/2601.03185)
- **Authors:** Adrian Harkness, Shuwen Kan, Chenxu Liu, Meng Wang, John M. Martyn, Shifan Xu, Diana Chamaki, Ethan Decker, Ying Mao, Luis F. Zuluaga, Tamás Terlaky, Ang Li, Samuel Stein
- **License:** MIT
- **Verify:** Chenxu Liu and Ang Li are at PNNL (a C2QA partner) — likely C2QA acknowledgment, needs confirmation

### ORNL-QCI repositories

See [qsc.md](qsc.md) for the list of XACC / QCOR / qiree / TNQVM / DM-Sim / SV-Sim / Quandary / QuaC etc., each needing its README + paper checked.

### QSA partner-institution projects

See [qsa.md](qsa.md) — LBNL, Sandia, Caltech, Duke, U. Maryland tooling that may carry QSA acknowledgments.

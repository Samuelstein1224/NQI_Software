# QSC — Quantum Science Center

**Lead:** Oak Ridge National Laboratory.
**Site:** [qscience.org](https://www.qscience.org/) · **ORNL quantum GitHub:** [github.com/ORNL-QCI](https://github.com/ORNL-QCI)

QSC is building "the first fault-tolerant ecosystem for hybrid quantum / high-performance computing (QHPC)," coordinating hybrid algorithms, scientific applications, QHPC architectures, and experimental validation toward an end-to-end software ecosystem (**openQSE**).

> **Note.** The `ORNL-QCI` GitHub org hosts ORNL's broader Quantum Computing Institute. Several of its repos pre-date QSC and are not necessarily QSC-funded — each entry below has been individually vetted, or is listed under [_pending.md](_pending.md) until acknowledgment is confirmed.

## Software

### [DM-Sim](https://github.com/ORNL-QCI/DM-Sim)

GPU-cluster density-matrix simulator for noisy quantum circuits.

- **Type:** simulator
- **Primary institution(s):** Oak Ridge National Laboratory / Pacific Northwest National Laboratory
- **Acknowledgment:** "This project is currently supported by the Quantum Science Center (QSC)." (README)
- **License:** BSD-3-Clause
- **Status:** active

### [FTCircuitBench](https://github.com/AdrianHarkness/FTCircuitBench)

End-to-end benchmark suite for fault-tolerant compilation and architecture — Clifford+T synthesis (Gridsynth, Solovay-Kitaev) and Pauli-Based Computation pipelines.

- **Type:** benchmark
- **Primary institution(s):** PNNL, Lehigh, Fordham, MIT
- **Authors:** Harkness, Kan, Liu, Wang, Martyn, Xu, Chamaki, Decker, Mao, Zuluaga, Terlaky, Li, Stein
- **Acknowledgment:** QSC
- **Paper:** [arXiv:2601.03185](https://arxiv.org/abs/2601.03185)
- **License:** MIT
- **Status:** active

### [FTPrimitiveBench](https://github.com/ShuwenKan/FTPrimitiveBench)

Python library for constructing and benchmarking fault-tolerant primitives (memory, transversal H, lattice surgery, logical S) on the rotated surface code under structured / hardware-motivated noise.

- **Type:** benchmark
- **Primary institution(s):** PNNL, Fordham
- **Authors:** Kan, Harkness, Du, Rofougaran, Garner, Liu, Mao, Stein
- **Acknowledgment:** QSC
- **Paper:** [arXiv:2605.04049](https://arxiv.org/abs/2605.04049)
- **License:** CC-BY-4.0
- **Status:** active

### [nwqec](https://github.com/pnnl/nwqec)

Toolkit for fault-tolerant quantum circuit transpilation and T-count optimization.

- **Type:** benchmark
- **Primary institution(s):** Pacific Northwest National Laboratory
- **Acknowledgment:** QSC (README); also C2QA (DE-SC0012704) — see [c2qa.md](c2qa.md)
- **License:** MIT
- **Status:** active

## Likely QSC-relevant (pending acknowledgment verification)

The following ORNL-QCI projects are strong candidates — listed here for now until each one's paper or README is confirmed to acknowledge QSC specifically.

- [XACC](https://github.com/ORNL-QCI/xacc) — eXtreme-scale Accelerator programming framework
- [QCOR](https://github.com/ORNL-QCI/qcor) — C++ compiler for heterogeneous quantum-classical computing on Clang + XACC
- [qiree](https://github.com/ORNL-QCI/qiree) — QIR Execution Engine via LLVM
- [TNQVM](https://github.com/ORNL-QCI/tnqvm) — Tensor-network QPU simulator for XACC
- [ExaTN](https://github.com/ORNL-QCI/exatn) / [ExaTENSOR](https://github.com/ORNL-QCI/ExaTENSOR) — hierarchical tensor networks at exascale
- [SV-Sim](https://github.com/ORNL-QCI/SV-Sim) — scalable state-vector simulator using PGAS
- [TriQ](https://github.com/ORNL-QCI/TriQ) — Scaffold backend compiler
- [TISCC](https://github.com/ORNL-QCI/TISCC) — quantum-computing tooling (C++)
- [Quandary](https://github.com/ORNL-QCI/quandary) — optimal-control toolkit for open quantum systems
- [QuaC](https://github.com/ORNL-QCI/QuaC) — time-dependent open-quantum-systems solver
- [VOQC](https://github.com/ORNL-QCI/VOQC) — verified-optimized quantum circuit XACC plugin
- [enfield](https://github.com/ORNL-QCI/enfield) — OpenQASM source-to-source compiler
- [qsim](https://github.com/ORNL-QCI/qsim) / [qflex](https://github.com/ORNL-QCI/qflex) — large quantum-circuit simulators

These should each be confirmed against the funding statement in their respective papers / READMEs and then promoted into the main list.

See [_pending.md](_pending.md) for the workflow.

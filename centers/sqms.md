# SQMS — Superconducting Quantum Materials and Systems Center

**Lead:** Fermi National Accelerator Laboratory.
**Site:** [sqmscenter.fnal.gov](https://sqmscenter.fnal.gov/) · **GitHub org:** [github.com/openquantumhardware](https://github.com/openquantumhardware)
**Funding citation:** `DE-AC02-07CH11359`.

SQMS builds quantum computing platforms from superconducting radio-frequency (SRF) cavities, drawing on Fermilab's accelerator-physics heritage. Renewed November 2025 with $125M over five years.

## Software

### [QICK](https://github.com/openquantumhardware/qick)

Quantum Instrumentation Control Kit — firmware + Python software for Xilinx RFSoC qubit control and readout. The flagship open-source control stack from SQMS, in production use across the field and commercialized via Safran.

- **Type:** control firmware + software
- **Primary institution(s):** Fermilab; University of Chicago
- **Acknowledgment:** SQMS (`DE-AC02-07CH11359`) and Q-NEXT
- **Paper:** [arXiv:2110.00557](https://arxiv.org/abs/2110.00557)
- **License:** MIT
- **Status:** active

### [qick-tools](https://github.com/openquantumhardware/qick-tools)

Task-specific firmware and software extensions for QICK boards.

- **Type:** firmware/software extensions
- **Primary institution(s):** Fermilab
- **License:** see repo
- **Status:** active

### [qick_interpreter](https://github.com/Fermilab-Quantum-Science/qick_interpreter)

Fermilab-specific interpreter / tooling for QICK-targeted pulse programs.

- **Type:** developer tooling
- **Primary institution(s):** Fermilab
- **Status:** active

### [QICK-DAWG](https://github.com/sandialabs/qick-dawg) (cross-listed)

Defect Arbitrary Waveform Generator — QICK extension for quantum-sensing of NV-style solid-state defects. Developed at Sandia (a QSA partner), but built on the SQMS-led QICK stack. Listed under both [QSA](qsa.md) and SQMS.

- **Type:** control framework for quantum sensing
- **Primary institution(s):** Sandia National Laboratories
- **Paper:** [arXiv:2311.18253](https://arxiv.org/abs/2311.18253)
- **License:** see repo
- **Status:** active

## Conference / training material

- [openquantumhardware/QCE2025](https://github.com/openquantumhardware/QCE2025), [QCE2024](https://github.com/openquantumhardware/QCE2024), [QCE2023_public](https://github.com/openquantumhardware/QCE2023_public) — QICK tutorials at IEEE QCE
- [QIS_SummerSchool_2024](https://github.com/openquantumhardware/QIS_SummerSchool_2024) — QICK class labs

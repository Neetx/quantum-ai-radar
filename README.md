# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-13-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-7-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-36-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--08--06-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-08-05):**
- **A flagship hardware milestone, peer-reviewed in Nature** — [An entangling gate for dual-rail erasure qubits](https://www.nature.com/articles/s41586-026-10822-y) (D-Wave): a two-qubit entangling gate for superconducting erasure qubits reaching ~99.9% fidelity, queued and added to the study shelf.
- **A claim demanding extreme skepticism** — an [IACR eprint](https://eprint.iacr.org/2026/1591) claims a polynomial-time quantum algorithm for the Dihedral Coset Problem, which would break lattice-based post-quantum cryptography; the same claim shape was made (and retracted within days) by Yilei Chen's 2024 eprint — queued unverified, watching for expert scrutiny, not added as evidence.
- **Watchlist grew 32 → 36** — two independent QAOA-trainability papers and a quantum-generative-models separation result queued (all against full evidence caps), one stale item dropped; deeper burndown deferred to the imminent weekly.
- **YouTube's Qiskit and Sabine feeds are back** after ~7 consecutive dead scans since Jul-30 — the standing proposal to downgrade them is now moot.

## Trends

🌱 3 · 📈 3 · 🚀 7 · 🌊 0 · 🏔 0 · 📉 0 · 💤 0

| trend | stage | latest signal |
|-------|-------|---------------|
| [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) | 🚀 accelerating | [2026-07-31](https://arxiv.org/abs/2607.29219) |
| [Quantum-advantage frontier](TRENDS.md#id-trend-011-quantum-advantage-frontier-provable-learning-separations-and-honest-quantum-classical-crossovers) | 🚀 accelerating | [2026-08-04](https://arxiv.org/abs/2608.03962) |
| [LLM/agentic quantum reasoning](TRENDS.md#id-trend-009-llmagentic-ai-reasoning-about-quantum-circuits-algorithms-and-proofs) | 🚀 accelerating | [2026-07-28](https://arxiv.org/abs/2607.25865) |
| [AI-for-quantum (hardware)](TRENDS.md#id-trend-002-ai-for-quantum-hardware-leg-classical-ml-for-quantum-hardware-control-calibration-decoding-and-circuit-design) | 🚀 accelerating | [2026-07-27](https://developer.nvidia.com/blog/nvidia-ising-enables-fully-automated-quantum-computer-calibration-with-enhanced-in-context-learning/) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 🚀 accelerating | [2026-07-27](https://arxiv.org/abs/2607.24014) |
| [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) | 🚀 accelerating | [2026-07-27](https://arxiv.org/abs/2607.24065) |
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-07-21](https://arxiv.org/abs/2607.19563) |
| [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) | 📈 emerging | [2026-07-28](https://arxiv.org/abs/2607.26131) |
| [QML generalization theory](TRENDS.md#id-trend-007-qml-generalization-theory-bounds-phenomenology-and-the-reference-structure-requirement) | 📈 emerging | [2026-07-28](https://www.nature.com/articles/s41534-026-01330-y) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 📈 emerging | [2026-07-27](https://arxiv.org/abs/2607.24399) |
| [Agentic AI lab automation](TRENDS.md#id-trend-013-agentic-ai-directly-operating-quantum-hardware-and-lab-infrastructure-end-to-end) | 🌱 seed | [2026-07-28](https://arxiv.org/abs/2607.25834) |
| [AI-for-quantum (circuit synthesis)](TRENDS.md#id-trend-012-ai-for-quantum-circuit-synthesis-leg-generativetransformer-models-that-directly-synthesize-quantum-circuits) | 🌱 seed | [2026-07-24](https://arxiv.org/abs/2607.22468) |
| [QML security & adversarial robustness](TRENDS.md#id-trend-010-qml-security--adversarial-robustness-attacks-on-and-defenses-for-variational-quantum-models) | 🌱 seed | [2026-07-21](https://arxiv.org/abs/2607.19318) |

## Worth studying

- [An entangling gate for dual-rail erasure qubits (Nature 656, 47–53)](https://www.nature.com/articles/s41586-026-10822-y) — D-Wave Quantum Inc. (published Aug 6): a fast, low-error two-qubit entangling gate for superconducting dual-rail erasure qubits, ~99.9% two-qubit fidelity — a flagship hardware milestone for the error-hierarchy-engineering approach to QEC.
- [Separating quantum circuits from classical LLMs (arXiv:2608.03962)](https://arxiv.org/abs/2608.03962) — Arunachalam, Dutt, Krovi, Sengupta (IBM, Aug 4): unconditional separations between low-depth quantum computation and the transformer/diffusion-LM architectures behind modern LLMs — the first result of its kind, framed as opening "the study of quantum advantage in the era of large language models."
- [Weak Permanent Anti-Concentration for Random Gaussian Matrices in Boson Sampling (arXiv:2607.22088)](https://arxiv.org/abs/2607.22088) — Meng, Cheng, Li, Yung (Jul 24): resolves the open case of the permanent anti-concentration conjecture underlying boson sampling's classical-hardness argument.
- [Hybrid Quantum Neural Networks: Theory, Implementations, and Applications (arXiv:2608.01194)](https://arxiv.org/abs/2608.01194) — Monbroussou, Periyasamy, Kuzmin, Sekatski, Patapovich, Sagingalieva (Aug 2): a broad orientation-map review of hybrid QNN architectures, benchmarks and applications.
- [High-rate qLDPC processors (arXiv:2607.28795)](https://arxiv.org/abs/2607.28795) — Bhardwaj, Ma, Meister, King, Bluvstein, Preskill et al. (Jul 30): "mitten codes," a non-abelian qLDPC processor-code family reaching distance 18+ with only a few hundred data qubits, evading the distance bounds that constrain abelian constructions.
- [Gaussian-augmented bosonic matrix-product states (arXiv:2607.28753)](https://arxiv.org/abs/2607.28753) — Tjoa, Cirac (Jul 30): a general-purpose classical-simulation tool for bosonic many-body states, with efficiently-computable expectation values and exact parent Hamiltonians — squarely on the classical-quantum-boundary axis.
- [Triangle Criterion: A Mixed-State Magic Criterion with Applications in Distillation and Detection (PRX Quantum 7, 033016)](https://doi.org/10.1103/rcpf-8nh9) — Liu, Haug, Ye, Liu, Roth (Jul 24): a simple criterion for detecting nonstabilizerness ("magic") and certifying undistillability of mixed quantum states.
- [Quantum Convolutional HLA Immunogenic Peptide Prediction (Q-CHIPP) (Science Advances, doi:10.1126/sciadv.aec3824)](https://www.biorxiv.org/content/10.1101/2025.07.29.667313v1) — Peters, Rhrissorrakrai et al. (IBM/Cleveland Clinic, published Jul 30): a quantum convolutional neural network unifying MHC-binding and immunogenicity prediction for cancer neoantigens, scaled to 46 qubits of real hardware.
- [SymFT: Universal Fault-Tolerant Quantum Circuit Simulation (arXiv:2607.28600)](https://arxiv.org/abs/2607.28600) — Fang, Lou, Li (Jul 30): a high-throughput classical simulator for Clifford-dominated fault-tolerant circuits via symbolic Clifford–Pauli frame factorization.
- [MPStab: an hybrid stabilizers tensor-network quantum circuit simulator (arXiv:2607.24258)](https://arxiv.org/abs/2607.24258) — Crognaletti, Robbiano, Grossi, Robbiati (Jul 27): an open-source simulator combining the stabilizer formalism with tensor networks.
- [Generative AI Beyond Tokens: Quantum Resource Consumption of IQP Circuits (arXiv:2607.26711)](https://arxiv.org/abs/2607.26711) — Krüger, Mauerer (Jul 27): reframes quantum generative modeling through a resource-theoretic lens — how much magic (non-stabiliserness) does it actually consume?
- [Lowering the implementation barrier of neutral-atom quantum computing with agentic workflows (arXiv:2607.25834)](https://arxiv.org/abs/2607.25834) — Dalyac, Dauphin, Henriet, Jurczak (Pasqal, Jul 28): an LLM agentic workflow runs the full design→compilation→execution pipeline on two real Pasqal QPUs overnight, honestly reporting its own failure modes.

## Community pulse

_Unverified intake — community signals, not trend evidence._

- [Hacker News](https://news.ycombinator.com/) surfaced an [IACR eprint](https://eprint.iacr.org/2026/1591) claiming a polynomial-time quantum algorithm for lattice problems via the Dihedral Coset Problem — treated with extreme skepticism (an equivalent 2024 claim was retracted within days) and queued unverified pending expert scrutiny, not treated as evidence.
- [r/QuantumComputing](https://old.reddit.com/r/QuantumComputing/) carries its usual recurring threads (quantum-timeline skepticism, weekly career thread) — nothing new on-axis.
- YouTube's Qiskit and Sabine Hossenfelder feeds are reachable again after ~7 consecutive dead scans since Jul-30 — worth re-checking regularly again.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (36)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-08-06](reports/2026-08-06.md) · weekly: [2026-W31](reports/weekly/2026-W31.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-13-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-7-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-32-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--08--03-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-08-01):**
- **[Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) promoted to accelerating** — a genuinely fresh 7th independent group, [Fisher-Orthogonal Memory in QRC](https://arxiv.org/abs/2607.29219), resolves last week's "watch for a fresh 6th/7th group" flag.
- **IBM's "three demonstrations of trusted quantum advantage" press wave** all traced to primaries already tracked here — the [Qedma Floquet result](https://arxiv.org/abs/2607.24937) now carries a reported (vendor-side) classical-simulation attempt that couldn't reproduce it, and the [IBM/UChicago result](https://arxiv.org/abs/2607.25941) builds on a rigorous 2025 hardness proof.
- **Two capture-leak fixes**: a [neural QEC pre-decoder](https://arxiv.org/abs/2607.28422) and [IQM's quantum-informed surrogate-sampling paper](https://arxiv.org/abs/2607.22372), both missed by earlier sweeps, now queued.
- **Watchlist grew 24 → 32** — new adds include a flagship non-abelian [qLDPC code paper](https://arxiv.org/abs/2607.28795) (Preskill/Bluvstein) and a [Cirac-authored classical-simulation tool](https://arxiv.org/abs/2607.28753), both also in Worth studying.

## Trends

🌱 3 · 📈 3 · 🚀 7 · 🌊 0 · 🏔 0 · 📉 0 · 💤 0

| trend | stage | latest signal |
|-------|-------|---------------|
| [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) | 🚀 accelerating | [2026-07-31](https://arxiv.org/abs/2607.29219) |
| [Quantum-advantage frontier](TRENDS.md#id-trend-011-quantum-advantage-frontier-provable-learning-separations-and-honest-quantum-classical-crossovers) | 🚀 accelerating | [2026-07-28](https://arxiv.org/abs/2607.25492) |
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

- [High-rate qLDPC processors (arXiv:2607.28795)](https://arxiv.org/abs/2607.28795) — Bhardwaj, Ma, Meister, King, Bluvstein, Preskill et al. (Jul 30): "mitten codes," a non-abelian qLDPC processor-code family reaching distance 18+ with only a few hundred data qubits, evading the distance bounds that constrain abelian constructions.
- [Gaussian-augmented bosonic matrix-product states (arXiv:2607.28753)](https://arxiv.org/abs/2607.28753) — Tjoa, Cirac (Jul 30): a general-purpose classical-simulation tool for bosonic many-body states, with efficiently-computable expectation values and exact parent Hamiltonians — squarely on the classical-quantum-boundary axis.
- [Triangle Criterion: A Mixed-State Magic Criterion with Applications in Distillation and Detection (PRX Quantum 7, 033016)](https://doi.org/10.1103/rcpf-8nh9) — Liu, Haug, Ye, Liu, Roth (Jul 24): a simple criterion for detecting nonstabilizerness ("magic") and certifying undistillability of mixed quantum states.
- [Quantum Convolutional HLA Immunogenic Peptide Prediction (Q-CHIPP) (Science Advances, doi:10.1126/sciadv.aec3824)](https://www.biorxiv.org/content/10.1101/2025.07.29.667313v1) — Peters, Rhrissorrakrai et al. (IBM/Cleveland Clinic, published Jul 30): a quantum convolutional neural network unifying MHC-binding and immunogenicity prediction for cancer neoantigens, scaled to 46 qubits of real hardware.
- [SymFT: Universal Fault-Tolerant Quantum Circuit Simulation (arXiv:2607.28600)](https://arxiv.org/abs/2607.28600) — Fang, Lou, Li (Jul 30): a high-throughput classical simulator for Clifford-dominated fault-tolerant circuits via symbolic Clifford–Pauli frame factorization.
- [MPStab: an hybrid stabilizers tensor-network quantum circuit simulator (arXiv:2607.24258)](https://arxiv.org/abs/2607.24258) — Crognaletti, Robbiano, Grossi, Robbiati (Jul 27): an open-source simulator combining the stabilizer formalism with tensor networks.
- [Generative AI Beyond Tokens: Quantum Resource Consumption of IQP Circuits (arXiv:2607.26711)](https://arxiv.org/abs/2607.26711) — Krüger, Mauerer (Jul 27): reframes quantum generative modeling through a resource-theoretic lens — how much magic (non-stabiliserness) does it actually consume?
- [Lowering the implementation barrier of neutral-atom quantum computing with agentic workflows (arXiv:2607.25834)](https://arxiv.org/abs/2607.25834) — Dalyac, Dauphin, Henriet, Jurczak (Pasqal, Jul 28): an LLM agentic workflow runs the full design→compilation→execution pipeline on two real Pasqal QPUs overnight, honestly reporting its own failure modes.
- [NVIDIA Ising Enables Fully Automated Quantum Computer Calibration](https://developer.nvidia.com/blog/nvidia-ising-enables-fully-automated-quantum-computer-calibration-with-enhanced-in-context-learning/) — NVIDIA Quantum Computing Division (Jul 27): a 31B-parameter vision-language model that diagnoses and tunes quantum processors from calibration plots.
- [Hybrid Quantum-Classical Machine Learning Algorithms for Multi-Output Time-Series Forecasting at Utility Scale (arXiv:2605.24252)](https://arxiv.org/abs/2605.24252) — Polché, Puram, Lal et al. (E.ON/WISER, May 22): two hybrid QRC/quantum-kernel models forecast 103 real household Smart Meter time-series on a real 100+ qubit IBM processor.
- [Measuring Accuracy and Energy-to-Solution of Quantum Fine-Tuning of Foundational AI Models (arXiv:2605.02798)](https://arxiv.org/abs/2605.02798) — Knitter, Kim, Wurzer et al. (IonQ/QuantumBasel, May 4): directly instruments power consumption on a real trapped-ion QPU running hybrid fine-tuning end-to-end.
- [Efficient classical simulation of large-scale unitary cluster Jastrow circuits (arXiv:2607.21337)](https://arxiv.org/abs/2607.21337) — Belagali, Van Camp, Pradeep, Das, Anand, LaRose (Jul 23): a polynomial-time classical algorithm reproducing the largest single-layer-UCJ quantum-chemistry hardware experiment to date in under a minute on a laptop.

## Community pulse

_Unverified intake — community signals, not trend evidence._

- [r/QuantumComputing](https://old.reddit.com/r/QuantumComputing/) has been discussing IBM's "trusted quantum advantage" press wave and a thread on AI assisting in producing two independent proofs for the same cryptography problem, alongside the usual weekly career thread.
- [Hacker News](https://news.ycombinator.com/) quantum discussion centered on the same IBM press wave from multiple angles, plus routine post-quantum-cryptography threads — nothing new on-axis beyond what's already queued.
- YouTube's Qiskit and Sabine Hossenfelder feeds have been structurally unreachable (the feed endpoint itself, not per-channel) for 6+ consecutive scans — a proposed amendment to downgrade both to a lower-cadence best-effort check is still awaiting the next weekly.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (32)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-08-03](reports/2026-08-03.md) · weekly: [2026-W31](reports/weekly/2026-W31.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

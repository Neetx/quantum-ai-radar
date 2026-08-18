# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-13-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-7-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-35-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--08--18-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-08-18):**
- **Two trends went dormant** — [QML generalization theory](TRENDS.md#id-trend-007-qml-generalization-theory-bounds-phenomenology-and-the-reference-structure-requirement) and [Agentic AI lab automation](TRENDS.md#id-trend-013-agentic-ai-directly-operating-quantum-hardware-and-lab-infrastructure-end-to-end) both hit 21 days with no new independent group.
- **A major watch-item is resolved** — the claimed [polynomial-time break of the Dihedral Coset Problem](https://eprint.iacr.org/2026/1591) is formally REFUTED by a [Lean-4-verified no-go](https://eprint.iacr.org/2026/1693); no post-quantum-cryptography break occurred.
- **New study picks** — the DCP refutation above, and a newly-peer-reviewed [boson-sampling / neural-network quantum kernel](https://arxiv.org/abs/2510.13332) that beats classical kernels on real classification tasks.
- **Watchlist: 30 → 35** — 11 new captures after a real 6-item burndown (2 already preserved on the study shelf, 1 resolved, 3 aged out with no cluster).

## Trends

🌱 0 · 📈 2 · 🚀 7 · 🌊 0 · 🏔 0 · 📉 0 · 💤 4

| trend | stage | latest signal |
|-------|-------|---------------|
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-08-13](http://link.aps.org/doi/10.1103/y14y-7kp3) |
| [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) | 🚀 accelerating | [2026-08-13](https://arxiv.org/abs/2608.13110) |
| [Quantum-advantage frontier](TRENDS.md#id-trend-011-quantum-advantage-frontier-provable-learning-separations-and-honest-quantum-classical-crossovers) | 🚀 accelerating | [2026-08-13](https://arxiv.org/abs/2608.13521) |
| [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) | 🚀 accelerating | [2026-08-10](https://arxiv.org/abs/2608.10382) |
| [LLM/agentic quantum reasoning](TRENDS.md#id-trend-009-llmagentic-ai-reasoning-about-quantum-circuits-algorithms-and-proofs) | 🚀 accelerating | [2026-08-10](https://arxiv.org/abs/2608.08996) |
| [AI-for-quantum (hardware)](TRENDS.md#id-trend-002-ai-for-quantum-hardware-leg-classical-ml-for-quantum-hardware-control-calibration-decoding-and-circuit-design) | 🚀 accelerating | [2026-07-27](https://developer.nvidia.com/blog/nvidia-ising-enables-fully-automated-quantum-computer-calibration-with-enhanced-in-context-learning/) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 🚀 accelerating | [2026-07-27](https://arxiv.org/abs/2607.24728) |
| [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) | 📈 emerging | [2026-08-12](https://arxiv.org/abs/2608.11911) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 📈 emerging | [2026-08-06](https://arxiv.org/abs/2608.06554) |
| [QML generalization theory](TRENDS.md#id-trend-007-qml-generalization-theory-bounds-phenomenology-and-the-reference-structure-requirement) | 💤 dormant | [2026-07-28](https://www.nature.com/articles/s41534-026-01330-y) |
| [Agentic AI lab automation](TRENDS.md#id-trend-013-agentic-ai-directly-operating-quantum-hardware-and-lab-infrastructure-end-to-end) | 💤 dormant | [2026-07-28](https://arxiv.org/abs/2607.25834) |
| [AI-for-quantum (circuit synthesis)](TRENDS.md#id-trend-012-ai-for-quantum-circuit-synthesis-leg-generativetransformer-models-that-directly-synthesize-quantum-circuits) | 💤 dormant | [2026-07-24](https://arxiv.org/abs/2607.22468) |
| [QML security & adversarial robustness](TRENDS.md#id-trend-010-qml-security--adversarial-robustness-attacks-on-and-defenses-for-variational-quantum-models) | 💤 dormant | [2026-07-21](https://arxiv.org/abs/2607.19318) |

## Worth studying

- [The ePrint:2026/1591 Quantum Algorithm Does Not Solve DCP (eprint.iacr.org/2026/1693)](https://eprint.iacr.org/2026/1693) — Gupte (MIT), Ragavan (Google Quantum AI/MIT), Zhandry (Google Quantum AI/Stanford): a Lean-4-machine-verified refutation (code released) of a claimed polynomial-time quantum algorithm for the Dihedral Coset Problem — a model of fast, rigorous scrutiny of an extraordinary quantum-algorithms claim.
- [Hybrid Boson Sampling-Neural Network Architecture for Enhanced Classification (npj Quantum Information; arXiv:2510.13332)](https://arxiv.org/abs/2510.13332) — Sharifian, Bayat: a neural network adaptively compresses data features onto a programmable boson-sampling circuit to build a quantum kernel, beating classical linear/sigmoid kernels on four datasets.
- [The Quantum Optimization Benchmarking Library (Nature Computational Science 6, 653–671)](https://www.ibm.com/quantum/blog/qoblib) — Koch, Bernal Neira, Chen, Woerner et al. (IBM/ZIB/TU Berlin/Purdue, newly peer-reviewed): an open-source "intractable decathlon" of ten optimization problem classes with both classical AND quantum baselines/tooling — a shared, honest yardstick for quantum-optimization claims.
- [Assessing Quantum Advantage for Gaussian Process Regression (npj Quantum Information)](https://arxiv.org/abs/2505.22502) — Lowe, Kim, Bondesan (Imperial College London, newly peer-reviewed): rigorously proves proposed quantum GP-regression algorithms carry no exponential speedup across a wide range of scenarios, independent of data-loading complexity.
- [Exponential quantum advantage for learning signals with a single qubit (arXiv:2608.13521)](https://arxiv.org/abs/2608.13521) — Kannan, Prabhu, Khan, Sohoni, Song, Roy, Senanian, Fatemi, McMahon, Cotler (Aug 13): couples one controllable qubit to a conventional sensor for a proved AND experimentally-demonstrated exponential measurement reduction (10^7-fold) in learning classical signals.
- [Classical Simulation and Design Frontiers for IBM's Doped Clifford Sampling Experiment (arXiv:2608.13110)](https://arxiv.org/abs/2608.13110) — Manabe, Gu, Pan (Aug 13): a certified-minimum-width tensor-network contraction classically simulates IBM's 70-qubit doped-Clifford sampling experiment.
- [Hamilton-Zero: A Neural Tensor-Network Foundation Model for Ground States of Arbitrary Quadratic Qubit Hamiltonians (arXiv:2608.11911)](https://arxiv.org/abs/2608.11911) — Heightman, Orlova, Mantrov, Ustimenko (Aug 12): a ~0.5B-parameter foundation model, trained with LLM/deep-RL techniques, amortizes ground-state search across an arbitrary set of Hamiltonians — trained up to 64 qubits, fine-tuned up to 1024, evaluated up to 8100.
- [Pauli Propagation: A Computational Framework for Simulating Quantum Systems (PRX Quantum 7, 032001)](http://link.aps.org/doi/10.1103/6vd7-l9bn) — Rudolph, Jones, Teng, Angrisani, Holmes (EPFL/Algorithmiq, Aug 11): a comprehensive, peer-reviewed account of Pauli propagation as a classical simulation method for digital quantum circuits, and its use in verifying/challenging near-term hardware claims.
- [Convolutional QFT: a constructive compilation strategy for the Quantum Fourier Transform (arXiv:2608.05435)](https://arxiv.org/abs/2608.05435) — Coote, Biercuk, Baum (Q-CTRL, Aug 5): a 100-qubit QFT on IBM hardware, the largest experimental QFT to date, honestly reporting declining process fidelity at scale rather than claiming "advantage."
- [The Input Problem: A Permanent Bottleneck for Quantum Machine Learning (arXiv:2608.08433)](https://arxiv.org/abs/2608.08433) — Muhammad Faryad (Aug 7): measured gate counts for classical-data-loading circuits show the resulting Θ(N) cost is a counting theorem, not an engineering limitation — and it eliminates the quadratic advantage several QML algorithms claim.
- [Multi-agent discovery of practical quantum LDPC codes (arXiv:2608.08996)](https://arxiv.org/abs/2608.08996) — Qian, Li (Aug 10): a multi-agent AI-scientist framework discovers qLDPC codes with leading or competitive rate-distance performance across every weight class tested — a working instance of agentic AI doing genuine QEC code design.
- [NS-RIS: Newton-Schulz Retraction-Based Inference Enables HQMMs to Outperform Classical HMMs (arXiv:2608.06554)](https://arxiv.org/abs/2608.06554) — Ning Ning (Aug 6): the first benchmark evidence a Hidden Quantum Markov Model can significantly and consistently outperform an EM-trained classical HMM on non-quantum-generated data.

## Community pulse

_Unverified intake — community signals, not trend evidence._

- Hacker News and the [IACR eprint archive](https://eprint.iacr.org/2026/1591) both carried the resolution of the Dihedral Coset Problem claim this week — see the [formal refutation](https://eprint.iacr.org/2026/1693) above.
- A prominent independent voice's blog post still reports (third-hand, unverified, no paper) that an unreleased AI model has solved several open math/theoretical-CS problems, including one touching quantum-game parallel repetition — see [Shtetl-Optimized](https://scottaaronson.blog/?p=9979); still an extreme-hype-skepticism watch item pending any actual technical writeup.
- [r/QuantumComputing](https://old.reddit.com/r/QuantumComputing/) recovered after yesterday's single rate-limit — routine skepticism/career threads, no new primary.
- YouTube's Qiskit and Sabine Hossenfelder feeds broke again (`/feeds/videos.xml` 404) — a recurring intermittent structural break, low-stakes intake-only lane either way.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (35)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-08-18](reports/2026-08-18.md) · weekly: [2026-W33](reports/weekly/2026-W33.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

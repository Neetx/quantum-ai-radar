# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-13-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-6-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-24-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--08--22-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-08-22, weekly recalibration):**
- **Two long-running trends caught up on confidence** — [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) and [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) both raised medium → high confidence, having sustained a full evidence cap for 5-6 weeks with no thinning.
- **AI-for-quantum (hardware) refreshed** — a 26-day evidence freeze resolved via [a cap-swap bringing in RL-Trotter](https://arxiv.org/abs/2608.20139), which treats Trotter approximation error as a controllable RL resource for long-time quantum simulation.
- **Watchlist cut from 37 to 24** in the weekly burndown — 11 items resolved with one-line reasons; live scrutiny arcs (the [IBM+Qedma Floquet claim](TRENDS.md#observation_queue), a fresh RL-circuit-optimization 2-item cluster, the Aaronson–Ambainis quantum-speedup-structure cluster) were deliberately kept.
- **eprint.iacr.org promoted** to a verified research venue after its 2nd on-axis appearance (the Simon dihedral-coset-problem refutation).

## Trends

🌱 0 · 📈 2 · 🚀 6 · 🌊 0 · 🏔 0 · 📉 0 · 💤 5

| trend | stage | latest signal |
|-------|-------|---------------|
| [AI-for-quantum (hardware)](TRENDS.md#id-trend-002-ai-for-quantum-hardware-leg-classical-ml-for-quantum-hardware-control-calibration-decoding-and-circuit-design) | 🚀 accelerating | [2026-08-20](https://arxiv.org/abs/2608.20139) |
| [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) | 🚀 accelerating | [2026-08-14](https://www.nature.com/articles/s41534-026-01350-8) |
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-08-13](http://link.aps.org/doi/10.1103/y14y-7kp3) |
| [Quantum-advantage frontier](TRENDS.md#id-trend-011-quantum-advantage-frontier-provable-learning-separations-and-honest-quantum-classical-crossovers) | 🚀 accelerating | [2026-08-13](https://arxiv.org/abs/2608.13521) |
| [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) | 🚀 accelerating | [2026-08-10](https://arxiv.org/abs/2608.10382) |
| [LLM/agentic quantum reasoning](TRENDS.md#id-trend-009-llmagentic-ai-reasoning-about-quantum-circuits-algorithms-and-proofs) | 🚀 accelerating | [2026-08-10](https://arxiv.org/abs/2608.08996) |
| [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) | 📈 emerging | [2026-08-14](https://arxiv.org/abs/2608.14208) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 📈 emerging | [2026-08-06](https://arxiv.org/abs/2608.06554) |
| [QML generalization theory](TRENDS.md#id-trend-007-qml-generalization-theory-bounds-phenomenology-and-the-reference-structure-requirement) | 💤 dormant | [2026-07-28](https://www.nature.com/articles/s41534-026-01330-y) |
| [Agentic AI lab automation](TRENDS.md#id-trend-013-agentic-ai-directly-operating-quantum-hardware-and-lab-infrastructure-end-to-end) | 💤 dormant | [2026-07-28](https://arxiv.org/abs/2607.25834) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 💤 dormant | [2026-07-27](https://arxiv.org/abs/2607.24728) |
| [AI-for-quantum (circuit synthesis)](TRENDS.md#id-trend-012-ai-for-quantum-circuit-synthesis-leg-generativetransformer-models-that-directly-synthesize-quantum-circuits) | 💤 dormant | [2026-07-24](https://arxiv.org/abs/2607.22468) |
| [QML security & adversarial robustness](TRENDS.md#id-trend-010-qml-security--adversarial-robustness-attacks-on-and-defenses-for-variational-quantum-models) | 💤 dormant | [2026-07-21](https://arxiv.org/abs/2607.19318) |

## Worth studying

- [An Irreducible Quantum Advantage in Aligning World Models with Reality (arXiv:2608.19779)](https://arxiv.org/abs/2608.19779) — Lumbreras, Ma, Thompson, Gu (Aug 20): under memory constraints, a coherent quantum world-model can align an agent's optimal policy with reality using strictly less memory than any classical world-model — a structural quantum advantage result connecting quantum resource theory to RL/world-model learning.
- [A Quantum Roadmap for Softmax Attention (arXiv:2608.11173)](https://arxiv.org/abs/2608.11173) — Reinhardt, Hauser (Aug 11): for attention on the probability simplex, softmax attention admits an EXACT (not heuristic) quantum realization — attention scores become Hadamard-test statistics under a Born-rule bijection, one of the few precise quantum-native constructions for a core Transformer primitive.
- [Bernstein-Vazirani Networks: Quantum Machine Learning by Interference (arXiv:2608.19043)](https://arxiv.org/abs/2608.19043) — Meli, Birdal, Tiwari, Golyanik, Moeller (Aug 19): a gradient-free, non-variational QML framework using quantum-Fourier-sampling-style interference for supervised learning, with universal function approximation via (over)complete interference bases — a genuinely different design point from the dominant variational-circuit paradigm.
- [Quantum Speedups Require Structure or Depth (arXiv:2608.19158)](https://arxiv.org/abs/2608.19158) — Blanc, Docter, Strassle, Tan (Stanford, Aug 19): settles a basic conjecture for parallel quantum algorithms — unstructured problems need superconstant-depth circuits for superpolynomial speedups and polynomial depth for exponential ones — with new implications for BPP vs. BQP relative to a random oracle.
- [Shots-to-Approximate-Solution Scaling in Neutral-Atom Quantum Optimization (arXiv:2608.12858)](https://arxiv.org/abs/2608.12858) — Jung, Ahn (KAIST): introduces an excitation-matched RANDOM baseline to isolate genuine quantum concentration from postprocessing artifacts; on 125-site Rydberg arrays, quantum annealing beats the baseline for near-exact targets but the enhancement vanishes for relaxed ones — a model of honest, regime-aware advantage methodology.
- [Physics Informed Generative Machine Learning for Sample-based Quantum Diagonalization (arXiv:2512.06858)](https://arxiv.org/abs/2512.06858) — Patra, Mondal, Halder, Halder, Laskar, Goel, Maitra (IIT Bombay, newly peer-reviewed): PIGen-SQD combines generative ML with physics-informed configuration screening to recover accurate fermionic configurations from noisy quantum-hardware samples in the SQD pipeline.
- [The ePrint:2026/1591 Quantum Algorithm Does Not Solve DCP (eprint.iacr.org/2026/1693)](https://eprint.iacr.org/2026/1693) — Gupte (MIT), Ragavan (Google Quantum AI/MIT), Zhandry (Google Quantum AI/Stanford): a Lean-4-machine-verified refutation (code released) of a claimed polynomial-time quantum algorithm for the Dihedral Coset Problem — a model of fast, rigorous scrutiny of an extraordinary quantum-algorithms claim.
- [Hybrid Boson Sampling-Neural Network Architecture for Enhanced Classification (npj Quantum Information; arXiv:2510.13332)](https://arxiv.org/abs/2510.13332) — Sharifian, Bayat: a neural network adaptively compresses data features onto a programmable boson-sampling circuit to build a quantum kernel, beating classical linear/sigmoid kernels on four datasets.
- [The Quantum Optimization Benchmarking Library (Nature Computational Science 6, 653–671)](https://www.ibm.com/quantum/blog/qoblib) — Koch, Bernal Neira, Chen, Woerner et al. (IBM/ZIB/TU Berlin/Purdue, newly peer-reviewed): an open-source "intractable decathlon" of ten optimization problem classes with both classical AND quantum baselines/tooling — a shared, honest yardstick for quantum-optimization claims.
- [Assessing Quantum Advantage for Gaussian Process Regression (npj Quantum Information)](https://arxiv.org/abs/2505.22502) — Lowe, Kim, Bondesan (Imperial College London, newly peer-reviewed): rigorously proves proposed quantum GP-regression algorithms carry no exponential speedup across a wide range of scenarios, independent of data-loading complexity.
- [Exponential quantum advantage for learning signals with a single qubit (arXiv:2608.13521)](https://arxiv.org/abs/2608.13521) — Kannan, Prabhu, Khan, Sohoni, Song, Roy, Senanian, Fatemi, McMahon, Cotler (Aug 13): couples one controllable qubit to a conventional sensor for a proved AND experimentally-demonstrated exponential measurement reduction (10^7-fold) in learning classical signals.
- [Classical Simulation and Design Frontiers for IBM's Doped Clifford Sampling Experiment (arXiv:2608.13110)](https://arxiv.org/abs/2608.13110) — Manabe, Gu, Pan (Aug 13): a certified-minimum-width tensor-network contraction classically simulates IBM's 70-qubit doped-Clifford sampling experiment.

## Community pulse

_Unverified intake — community signals, not trend evidence._

- A digest cross-check surfaced a ~35-day-old primary on rigorous Hamiltonian learning from weak measurements that had never been captured — now queued as a backlog catch.
- [r/QuantumComputing](https://old.reddit.com/r/QuantumComputing/) stayed routine through the week — career/Q&A threads, no new primary.
- A prominent independent voice's blog posted a new personal essay unrelated to quantum computing — see [Shtetl-Optimized](https://scottaaronson.blog/); no new technical content.
- A PennyLane post rounding up September's quantum conferences was checked in full and confirmed to be an events calendar, not a new research primary.
- YouTube's Qiskit and Sabine Hossenfelder feeds broke again (`/feeds/videos.xml` 404) — a recurring intermittent structural break, low-stakes intake-only lane either way.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (24)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-08-21](reports/2026-08-21.md) · weekly: [2026-W34](reports/weekly/2026-W34.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

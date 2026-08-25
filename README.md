# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-13-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-6-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-27-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--08--25-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-08-25):**
- **A new independent group joined quantum reservoir computing** — [a QRC+physics-informed-corrector hybrid for chaotic PDE forecasting](https://arxiv.org/abs/2608.23119), queued as a cap-swap candidate for [trend-008](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map).
- **A peer-reviewed physics-informed-kernel result** joined the study shelf — [Wang & Zhang's query-complexity-circumventing learning method](https://iopscience.iop.org/article/10.1088/2058-9565/ae98ec) for quantum dynamics, surfaced via a Quantum Zeitgeist pointer.
- **A 3rd honest-ablation result** landed on [trend-006](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) — [a controlled quantum-sidecar ablation for neural decoding](https://arxiv.org/abs/2608.22475), outside the Transformer setting this time.
- **Watchlist churned** (25 → 27) — 7 items dropped (already preserved on the study shelf or below significance), 9 added from today's arXiv/journal/digest sweep.

## Trends

🌱 0 · 📈 2 · 🚀 6 · 🌊 0 · 🏔 0 · 📉 0 · 💤 5

| trend | stage | latest signal |
|-------|-------|---------------|
| [AI-for-quantum (hardware)](TRENDS.md#id-trend-002-ai-for-quantum-hardware-leg-classical-ml-for-quantum-hardware-control-calibration-decoding-and-circuit-design) | 🚀 accelerating | [2026-08-20](https://arxiv.org/abs/2608.20139) |
| [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) | 🚀 accelerating | [2026-08-14](https://arxiv.org/abs/2608.14169) |
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

- [Circumventing query complexity barriers in learning quantum dynamics via physics-informed kernels (Quantum Science and Technology, DOI 10.1088/2058-9565/ae98ec)](https://iopscience.iop.org/article/10.1088/2058-9565/ae98ec) — Wang, Zhang (Aug 24): proves an Ω(T/ε²) oracle-query lower bound for memory-free learning of quantum dynamical trajectories, then introduces physics-informed kernel ridge regression that doubles the information extracted per query, resolving sharp features with up to two orders of magnitude lower error than standard kernel methods.
- [Satisfying Quantum Codes: Physics-Informed and Hardware-Aware Code Design with SAT Solvers (arXiv:2608.23460)](https://arxiv.org/abs/2608.23460) — DalFavero, Watkins, LaBorde, Russo, Egger, Quiroz, LaRose (Aug 24): formulates QEC-code design as Boolean satisfiability, proves the design problem is NP-complete, and ships a flexible SAT-based framework for physics-informed and hardware-aware code search.
- [Dynamics of disordered quantum systems with two- and three-dimensional tensor networks (Science 392, 868–872; arXiv:2503.05693)](https://www.science.org/doi/10.1126/science.adx2728) — Tindall, Mello, Fishman, Stoudenmire, Sels (Flatiron/Simons CCQ + Boston University): lattice-specific tensor networks with belief propagation reproduce D-Wave's Advantage2 spin-glass-annealing dynamics at state-of-the-art accuracy on a laptop, directly dequantizing a 2025 "beyond-classical" claim.
- [Neural quantum states in condensed matter: advances, best practices, and prospects (arXiv:2608.21291)](https://arxiv.org/abs/2608.21291) — Rigo, Wurst, Nutakki, Schmitt, Kennes (Aug 21): a researcher-facing orientation perspective on architectures, symmetry constraints, optimization and sampling strategies for neural quantum states, with an honest account of remaining challenges.
- [An Irreducible Quantum Advantage in Aligning World Models with Reality (arXiv:2608.19779)](https://arxiv.org/abs/2608.19779) — Lumbreras, Ma, Thompson, Gu (Aug 20): under memory constraints, a coherent quantum world-model can align an agent's optimal policy with reality using strictly less memory than any classical world-model — a structural quantum advantage result connecting quantum resource theory to RL/world-model learning.
- [A Quantum Roadmap for Softmax Attention (arXiv:2608.11173)](https://arxiv.org/abs/2608.11173) — Reinhardt, Hauser (Aug 11): for attention on the probability simplex, softmax attention admits an EXACT (not heuristic) quantum realization — attention scores become Hadamard-test statistics under a Born-rule bijection, one of the few precise quantum-native constructions for a core Transformer primitive.
- [Quantum Speedups Require Structure or Depth (arXiv:2608.19158)](https://arxiv.org/abs/2608.19158) — Blanc, Docter, Strassle, Tan (Stanford, Aug 19): settles a basic conjecture for parallel quantum algorithms — unstructured problems need superconstant-depth circuits for superpolynomial speedups and polynomial depth for exponential ones — with new implications for BPP vs. BQP relative to a random oracle.
- [Shots-to-Approximate-Solution Scaling in Neutral-Atom Quantum Optimization (arXiv:2608.12858)](https://arxiv.org/abs/2608.12858) — Jung, Ahn (KAIST): introduces an excitation-matched RANDOM baseline to isolate genuine quantum concentration from postprocessing artifacts; on 125-site Rydberg arrays, quantum annealing beats the baseline for near-exact targets but the enhancement vanishes for relaxed ones — a model of honest, regime-aware advantage methodology.
- [Physics Informed Generative Machine Learning for Sample-based Quantum Diagonalization (arXiv:2512.06858)](https://arxiv.org/abs/2512.06858) — Patra, Mondal, Halder, Halder, Laskar, Goel, Maitra (IIT Bombay, newly peer-reviewed): PIGen-SQD combines generative ML with physics-informed configuration screening to recover accurate fermionic configurations from noisy quantum-hardware samples in the SQD pipeline.
- [The ePrint:2026/1591 Quantum Algorithm Does Not Solve DCP (eprint.iacr.org/2026/1693)](https://eprint.iacr.org/2026/1693) — Gupte (MIT), Ragavan (Google Quantum AI/MIT), Zhandry (Google Quantum AI/Stanford): a Lean-4-machine-verified refutation (code released) of a claimed polynomial-time quantum algorithm for the Dihedral Coset Problem — a model of fast, rigorous scrutiny of an extraordinary quantum-algorithms claim.
- [Hybrid Boson Sampling-Neural Network Architecture for Enhanced Classification (npj Quantum Information; arXiv:2510.13332)](https://arxiv.org/abs/2510.13332) — Sharifian, Bayat: a neural network adaptively compresses data features onto a programmable boson-sampling circuit to build a quantum kernel, beating classical linear/sigmoid kernels on four datasets.
- [The Quantum Optimization Benchmarking Library (Nature Computational Science 6, 653–671)](https://www.ibm.com/quantum/blog/qoblib) — Koch, Bernal Neira, Chen, Woerner et al. (IBM/ZIB/TU Berlin/Purdue, newly peer-reviewed): an open-source "intractable decathlon" of ten optimization problem classes with both classical AND quantum baselines/tooling — a shared, honest yardstick for quantum-optimization claims.
- [Assessing Quantum Advantage for Gaussian Process Regression (npj Quantum Information)](https://arxiv.org/abs/2505.22502) — Lowe, Kim, Bondesan (Imperial College London, newly peer-reviewed): rigorously proves proposed quantum GP-regression algorithms carry no exponential speedup across a wide range of scenarios, independent of data-loading complexity.

## Community pulse

_Unverified intake — community signals, not trend evidence._

- [r/QuantumComputing](https://old.reddit.com/r/QuantumComputing/) carried a vendor press-release pointer about Japan's first full-stack neutral-atom quantum computer — no accompanying technical primary found, checked-excluded.
- A Reddit thread pointed to a paywalled Nature News piece about an AI "vibe coding" tool for quantum circuits — could not verify the underlying content, not queued.
- A Quantum Zeitgeist digest pointer traced to two genuine primaries this run — a peer-reviewed physics-informed-kernel learning-theory paper (now on the study shelf) and a backlog-caught cross-stack quantum-error-management benchmark.
- YouTube's Qiskit and Sabine Hossenfelder feeds broke again (`/feeds/videos.xml` 404) — a recurring intermittent structural break, low-stakes intake-only lane either way.
- A prominent independent voice posted a new personal essay unrelated to quantum computing — see [Shtetl-Optimized](https://scottaaronson.blog/); no new technical content.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (27)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-08-25](reports/2026-08-25.md) · weekly: [2026-W34](reports/weekly/2026-W34.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

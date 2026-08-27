# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-13-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-6-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-29-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--08--27-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-08-27):**
- **[Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) gained a fresh 9th independent group** — [a physics-informed-correction hybrid for chaotic PDE forecasting](https://arxiv.org/abs/2608.23119), cap-swapped into evidence.
- A **second** fresh QRC candidate surfaced the same run — [an edge-of-chaos study of information scrambling in quantum reservoirs](https://arxiv.org/abs/2608.25511) — queued as the next cap-swap candidate.
- **Notable new queue item**: [Stuart Hadfield's resource-tradeoff proof](https://arxiv.org/abs/2608.25151) that qubit-efficient quantum optimization relaxations are not a free compression.
- **Watchlist churned** (28 → 29) — 1 promoted via cap-swap, 3 dropped (no cluster formed), 5 added.

## Trends

🌱 0 · 📈 3 · 🚀 6 · 🌊 0 · 🏔 0 · 📉 0 · 💤 4

| trend | stage | latest signal |
|-------|-------|---------------|
| [Quantum-advantage frontier](TRENDS.md#id-trend-011-quantum-advantage-frontier-provable-learning-separations-and-honest-quantum-classical-crossovers) | 🚀 accelerating | [2026-08-25](https://arxiv.org/abs/2608.24527) |
| [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) | 🚀 accelerating | [2026-08-24](https://arxiv.org/abs/2608.23119) |
| [AI-for-quantum (hardware)](TRENDS.md#id-trend-002-ai-for-quantum-hardware-leg-classical-ml-for-quantum-hardware-control-calibration-decoding-and-circuit-design) | 🚀 accelerating | [2026-08-20](https://arxiv.org/abs/2608.20139) |
| [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) | 🚀 accelerating | [2026-08-14](https://arxiv.org/abs/2608.14169) |
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-08-13](http://link.aps.org/doi/10.1103/y14y-7kp3) |
| [LLM/agentic quantum reasoning](TRENDS.md#id-trend-009-llmagentic-ai-reasoning-about-quantum-circuits-algorithms-and-proofs) | 🚀 accelerating | [2026-08-10](https://arxiv.org/abs/2608.08996) |
| [QML generalization theory](TRENDS.md#id-trend-007-qml-generalization-theory-bounds-phenomenology-and-the-reference-structure-requirement) | 📈 emerging | [2026-08-25](https://arxiv.org/abs/2608.24229) |
| [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) | 📈 emerging | [2026-08-14](https://arxiv.org/abs/2608.14208) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 📈 emerging | [2026-08-06](https://arxiv.org/abs/2608.06554) |
| [Agentic AI lab automation](TRENDS.md#id-trend-013-agentic-ai-directly-operating-quantum-hardware-and-lab-infrastructure-end-to-end) | 💤 dormant | [2026-07-28](https://arxiv.org/abs/2607.25834) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 💤 dormant | [2026-07-27](https://arxiv.org/abs/2607.24728) |
| [AI-for-quantum (circuit synthesis)](TRENDS.md#id-trend-012-ai-for-quantum-circuit-synthesis-leg-generativetransformer-models-that-directly-synthesize-quantum-circuits) | 💤 dormant | [2026-07-24](https://arxiv.org/abs/2607.22468) |
| [QML security & adversarial robustness](TRENDS.md#id-trend-010-qml-security--adversarial-robustness-attacks-on-and-defenses-for-variational-quantum-models) | 💤 dormant | [2026-07-21](https://arxiv.org/abs/2607.19318) |

## Worth studying

- [Superextensive learning in quantum reservoirs at the onset of information scrambling (arXiv:2608.25511)](https://arxiv.org/abs/2608.25511) — Freiheit, Campaioli (Aug 26): imports the complex-systems "edge of chaos" hypothesis into quantum reservoir computing, using out-of-time-order correlators to locate the onset of information scrambling in 2D Ising-network reservoirs.
- [No Free Compression in Quantum Relaxations for Optimization (arXiv:2608.25151)](https://arxiv.org/abs/2608.25151) — Stuart Hadfield (Aug 25): rigorously accounts for the resource tradeoffs qubit-efficient quantum optimization relaxations incur when compressing classical variables into far fewer qubits.
- [Provable Quantum--Classical Separation for Continuous Gibbs Sampling (arXiv:2608.24527)](https://arxiv.org/abs/2608.24527) — Olivucci, Sobchuk, Hoque, Hnybida, Kim, Shayeghi, Ronagh (Aug 25): the first quantum-classical separation proven for a sampling problem over a continuous domain — quadratic in the Gibbs barrier amplitude, exponential in dimension at low temperature.
- [A Theory of Finite-Noise Optima and Generalization in Quantum Machine Learning (arXiv:2608.24229)](https://arxiv.org/abs/2608.24229) — Zhang, Jia, Li, Dong (Aug 25): explains why moderate QML noise sometimes reduces test error rather than only hurting it, via a noise-order purity parameter trading model complexity against prediction bias.
- [Circumventing query complexity barriers in learning quantum dynamics via physics-informed kernels (Quantum Science and Technology, DOI 10.1088/2058-9565/ae98ec)](https://iopscience.iop.org/article/10.1088/2058-9565/ae98ec) — Wang, Zhang (Aug 24): proves an Ω(T/ε²) oracle-query lower bound for memory-free learning of quantum dynamical trajectories, then introduces physics-informed kernel ridge regression that doubles the information extracted per query.
- [Satisfying Quantum Codes: Physics-Informed and Hardware-Aware Code Design with SAT Solvers (arXiv:2608.23460)](https://arxiv.org/abs/2608.23460) — DalFavero, Watkins, LaBorde, Russo, Egger, Quiroz, LaRose (Aug 24): formulates QEC-code design as Boolean satisfiability, proves the design problem is NP-complete, and ships a flexible SAT-based framework for physics-informed and hardware-aware code search.
- [Dynamics of disordered quantum systems with two- and three-dimensional tensor networks (Science 392, 868–872; arXiv:2503.05693)](https://www.science.org/doi/10.1126/science.adx2728) — Tindall, Mello, Fishman, Stoudenmire, Sels (Flatiron/Simons CCQ + Boston University): lattice-specific tensor networks with belief propagation reproduce D-Wave's Advantage2 spin-glass-annealing dynamics at state-of-the-art accuracy on a laptop, directly dequantizing a 2025 "beyond-classical" claim.
- [Neural quantum states in condensed matter: advances, best practices, and prospects (arXiv:2608.21291)](https://arxiv.org/abs/2608.21291) — Rigo, Wurst, Nutakki, Schmitt, Kennes (Aug 21): a researcher-facing orientation perspective on architectures, symmetry constraints, optimization and sampling strategies for neural quantum states, with an honest account of remaining challenges.
- [An Irreducible Quantum Advantage in Aligning World Models with Reality (arXiv:2608.19779)](https://arxiv.org/abs/2608.19779) — Lumbreras, Ma, Thompson, Gu (Aug 20): under memory constraints, a coherent quantum world-model can align an agent's optimal policy with reality using strictly less memory than any classical world-model.
- [A Quantum Roadmap for Softmax Attention (arXiv:2608.11173)](https://arxiv.org/abs/2608.11173) — Reinhardt, Hauser (Aug 11): for attention on the probability simplex, softmax attention admits an EXACT (not heuristic) quantum realization, one of the few precise quantum-native constructions for a core Transformer primitive.
- [Bernstein-Vazirani Networks: Quantum Machine Learning by Interference (arXiv:2608.19043)](https://arxiv.org/abs/2608.19043) — Meli, Birdal, Tiwari, Golyanik, Moeller (Aug 19): a non-variational QML framework built on quantum-Fourier-sampling-style interference, a genuinely different design point from the dominant variational-circuit paradigm.
- [Quantum Speedups Require Structure or Depth (arXiv:2608.19158)](https://arxiv.org/abs/2608.19158) — Blanc, Docter, Strassle, Tan (Stanford, Aug 19): settles a basic conjecture for parallel quantum algorithms — unstructured problems need superconstant-depth circuits for superpolynomial speedups and polynomial depth for exponential ones.

## Community pulse

_Unverified intake — community signals, not trend evidence._

- [r/QuantumComputing](https://old.reddit.com/r/QuantumComputing/) pointed to a paywalled Nature News feature on an AI tool that lets researchers "vibe code" quantum programs — no accessible technical primary or named tool located this run, flagged to retry.
- The same subreddit carried a discussion thread asking whether LLMs are solving or helping solve open problems in quantum algorithms — no primary artifact, not queued.
- Digest coverage this run was dominated by funding/personnel/M&A announcements (a EuroHPC startup selection, IBM's completed HRL Laboratories acquisition, an NSF quantum-institute award) — no accompanying technical primaries.
- A vendor opinion essay on the roadmap from "Megaquop to Gigaquop" scale quantum computing was checked — no concrete technical claim, intake-only.
- YouTube's Qiskit and Sabine Hossenfelder feeds broke again (`/feeds/videos.xml` 404) — a recurring intermittent structural break, low-stakes intake-only lane either way.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (29)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-08-27](reports/2026-08-27.md) · weekly: [2026-W34](reports/weekly/2026-W34.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-14-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-7-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-28-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--09--01-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-09-01):**
- **[QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) revives** — a newly-published npj Quantum Information paper proves [rigorous convergence and generalization guarantees for a VQA](https://www.nature.com/articles/s41534-026-01364-2), an 11th independent group; 💤→🚀.
- **New trend: [Hamiltonian/dissipative-parameter learning](TRENDS.md#id-trend-014-learning-hamiltonian-and-dissipative-rate-parameters-of-quantum-systems-from-data)** — 3 independent groups converged within a week on [identifying a quantum system's own dynamics from data](https://arxiv.org/abs/2608.29302).
- **Monthly backlog sweep catch** — a ~5-month-old Quantinuum + Google DeepMind paper using an [LLM-driven platform to discover near-term quantum algorithms](https://arxiv.org/abs/2603.26359), never previously surfaced by this radar.
- **Watchlist churned** (27 → 28) — 4 resolved with one-line reasons, 8 fresh captures added.

## Trends

🌱 1 · 📈 4 · 🚀 7 · 🌊 0 · 🏔 0 · 📉 0 · 💤 2

| trend | stage | latest signal |
|-------|-------|---------------|
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-08-26](https://arxiv.org/abs/2608.26272) |
| [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) | 🚀 accelerating | [2026-08-26](https://arxiv.org/abs/2608.25511) |
| [Quantum-advantage frontier](TRENDS.md#id-trend-011-quantum-advantage-frontier-provable-learning-separations-and-honest-quantum-classical-crossovers) | 🚀 accelerating | [2026-08-25](https://arxiv.org/abs/2608.24527) |
| [AI-for-quantum (hardware)](TRENDS.md#id-trend-002-ai-for-quantum-hardware-leg-classical-ml-for-quantum-hardware-control-calibration-decoding-and-circuit-design) | 🚀 accelerating | [2026-08-20](https://arxiv.org/abs/2608.20139) |
| [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) | 🚀 accelerating | [2026-08-14](https://arxiv.org/abs/2608.14169) |
| [LLM/agentic quantum reasoning](TRENDS.md#id-trend-009-llmagentic-ai-reasoning-about-quantum-circuits-algorithms-and-proofs) | 🚀 accelerating | [2026-08-10](https://arxiv.org/abs/2608.08996) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 🚀 accelerating | [2026-09-01](https://www.nature.com/articles/s41534-026-01364-2) |
| [QML generalization theory](TRENDS.md#id-trend-007-qml-generalization-theory-bounds-phenomenology-and-the-reference-structure-requirement) | 📈 emerging | [2026-08-31](https://arxiv.org/abs/2608.31117) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 📈 emerging | [2026-08-28](https://arxiv.org/abs/2608.28168) |
| [Agentic AI lab automation](TRENDS.md#id-trend-013-agentic-ai-directly-operating-quantum-hardware-and-lab-infrastructure-end-to-end) | 📈 emerging | [2026-08-27](https://www.quera.com/blog-posts/holding-the-light-teaching-an-ai-to-lock-and-tune-our-quantum-computers-lasers) |
| [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) | 📈 emerging | [2026-08-14](https://arxiv.org/abs/2608.14208) |
| [Hamiltonian-parameter learning](TRENDS.md#id-trend-014-learning-hamiltonian-and-dissipative-rate-parameters-of-quantum-systems-from-data) | 🌱 seed | [2026-08-27](https://arxiv.org/abs/2608.29302) |
| [AI-for-quantum (circuit synthesis)](TRENDS.md#id-trend-012-ai-for-quantum-circuit-synthesis-leg-generativetransformer-models-that-directly-synthesize-quantum-circuits) | 💤 dormant | [2026-07-24](https://arxiv.org/abs/2607.22468) |
| [QML security & adversarial robustness](TRENDS.md#id-trend-010-qml-security--adversarial-robustness-attacks-on-and-defenses-for-variational-quantum-models) | 💤 dormant | [2026-07-21](https://arxiv.org/abs/2607.19318) |

## Worth studying

- [Automated near-term quantum algorithm discovery for molecular ground states (arXiv:2603.26359)](https://arxiv.org/abs/2603.26359) — Finger, Rapp, Kalidindi et al. (Quantinuum + Google DeepMind, Mar 27): an LLM-driven distributed evolutionary program-synthesis platform ("Hive") discovers heuristic near-term quantum algorithms for molecular ground-state estimation with major resource reductions, caught 5 months late by this run's monthly backlog sweep.
- [Theoretical guarantees of variational quantum algorithm with guiding states (npj Quantum Information, DOI 10.1038/s41534-026-01364-2)](https://www.nature.com/articles/s41534-026-01364-2) — Nguyen, Kieferová (Sep 1): a VQA for amortized ground-state-property prediction with rigorous convergence and generalization guarantees, rather than only empirical trainability diagnostics.
- [A quantum generative model for in silico clinical trials using scarce training datasets (arXiv:2608.28168)](https://arxiv.org/abs/2608.28168) — Sanz Larrarte, Dastbasteh, Sanchez-Navarro, Diez-Campelo, Prosper, Alfonso-Pierola, Hernaez, Capponi, Crespo Bofill, Etxezarreta Martinez (Aug 28): a quantum generative model trained on scarce Myelodysplastic Syndrome patient data, executed on real IBM Heron r2 hardware, beating classical baselines on generalization/expressivity.
- [From quantum reservoirs to quantum extreme learning machines through a nearest-neighbor spin chain with tunable quantum memory (arXiv:2608.28440)](https://arxiv.org/abs/2608.28440) — Ramon-Escandell, Riera, Płodzień (Aug 28): shows Quantum Reservoir Computing and Quantum Extreme-Learning Machines are the two limits of one architecture, connected by how many qubits carry memory.
- [Resolving Structure in Prethermal Floquet Dynamics with Precision Quantum Computation (arXiv:2607.24937)](https://arxiv.org/abs/2607.24937) — Leviatan, Watad, Perry, Broers, Mullath, Alberton, Arad, Atia (IBM+Qedma): resolves prethermal Floquet-magnet dynamics beyond reliable classical methods; a serious but still vendor-reported classical-attack attempt (RIKEN+BlueQubit) failed to reproduce it — an open case, not yet independently dequantized or peer-reviewed either way.
- [Holding the Light: Teaching an AI to Lock and Tune our Quantum Computer's Lasers](https://www.quera.com/blog-posts/holding-the-light-teaching-an-ai-to-lock-and-tune-our-quantum-computers-lasers) — QuEra (Aug 27): an LLM agent autonomously diagnoses and recovers laser-lock faults on QuEra's live neutral-atom hardware — 99.3% automated recovery success, recovery time cut from minutes to seconds, zero unattended lock drops over a 19-hour test.
- [Superextensive learning in quantum reservoirs at the onset of information scrambling (arXiv:2608.25511)](https://arxiv.org/abs/2608.25511) — Freiheit, Campaioli (Aug 26): imports the complex-systems "edge of chaos" hypothesis into quantum reservoir computing, using out-of-time-order correlators to locate the onset of information scrambling in 2D Ising-network reservoirs.
- [No Free Compression in Quantum Relaxations for Optimization (arXiv:2608.25151)](https://arxiv.org/abs/2608.25151) — Stuart Hadfield (Aug 25): rigorously accounts for the resource tradeoffs qubit-efficient quantum optimization relaxations incur when compressing classical variables into far fewer qubits.
- [Fault-tolerant quantum computation cannot be achieved with constant spacetime overhead (arXiv:2608.26272)](https://arxiv.org/abs/2608.26272) — Bharti, Haug, Tanggara (Aug 26): proves an unavoidable logarithmic contribution to the cumulative spacetime overhead of fault-tolerant quantum computation, settling whether that overhead can ever be reduced to a true constant.
- [Provable Quantum--Classical Separation for Continuous Gibbs Sampling (arXiv:2608.24527)](https://arxiv.org/abs/2608.24527) — Olivucci, Sobchuk, Hoque, Hnybida, Kim, Shayeghi, Ronagh (Aug 25): the first quantum-classical separation proven for a sampling problem over a continuous domain — quadratic in the Gibbs barrier amplitude, exponential in dimension at low temperature.
- [A Theory of Finite-Noise Optima and Generalization in Quantum Machine Learning (arXiv:2608.24229)](https://arxiv.org/abs/2608.24229) — Zhang, Jia, Li, Dong (Aug 25): explains why moderate QML noise sometimes reduces test error rather than only hurting it, via a noise-order purity parameter trading model complexity against prediction bias.
- [Circumventing query complexity barriers in learning quantum dynamics via physics-informed kernels (Quantum Science and Technology, DOI 10.1088/2058-9565/ae98ec)](https://iopscience.iop.org/article/10.1088/2058-9565/ae98ec) — Wang, Zhang (Aug 24): proves an Ω(T/ε²) oracle-query lower bound for memory-free learning of quantum dynamical trajectories, then introduces physics-informed kernel ridge regression that doubles the information extracted per query.
- [Dynamics of disordered quantum systems with two- and three-dimensional tensor networks (Science 392, 868–872; arXiv:2503.05693)](https://www.science.org/doi/10.1126/science.adx2728) — Tindall, Mello, Fishman, Stoudenmire, Sels (Flatiron/Simons CCQ + Boston University): lattice-specific tensor networks with belief propagation reproduce D-Wave's Advantage2 spin-glass-annealing dynamics at state-of-the-art accuracy on a laptop, directly dequantizing a 2025 "beyond-classical" claim.

## Community pulse

_Unverified intake — community signals, not trend evidence._

- Reddit's r/QuantumComputing RSS returned a login-wall page instead of feed content this run — a new degradation mode, watched for recurrence.
- Hacker News stayed dominated by general explainer content and an off-axis Treasury quantum-readiness policy item — no new technical primary.
- Digest coverage stayed dominated by funding/business news (data-center deployments, funding rounds, roadmap announcements) — no accompanying technical primaries.
- The Quantum Machines + Academia Sinica RL gate-calibration claim remains unverified — the vendor's blog no longer 403s but only serves a cookie-consent shell to automated extraction.
- YouTube's Qiskit/Sabine/PennyLane feeds broke again this run (`/feeds/videos.xml` back to HTTP 404) after healing briefly last week.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (28)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-09-01](reports/2026-09-01.md) · weekly: [2026-W35](reports/weekly/2026-W35.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

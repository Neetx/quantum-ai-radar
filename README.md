# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-15-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-7-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-31-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--09--04-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-09-04):**
- **[Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) freshened** — Quantinuum's [compact fault-tolerant trapped-ion architecture](https://arxiv.org/abs/2609.03194) (98-qubit Helios, $C_4$-Helix code) cap-swaps in as the trend's newest evidence.
- **A different QML training paradigm** — [Coherent Quantum Learning](https://arxiv.org/abs/2609.03640) evolves model parameters unitarily under the loss function's own Hamiltonian, giving quantum coherence an actual role in training dynamics.
- **Capture-leak sweep caught 7 previously-missed ids** — primaries named as "checked but excluded" in the last two daily reports but never queued, now queued with their original exclusion reasons preserved.
- **Watchlist churned** (29 → 31) — 10 stale items dropped with one-line reasons, 12 added (5 fresh captures + 7 capture-leak fixes).

## Trends

🌱 2 · 📈 4 · 🚀 7 · 🌊 0 · 🏔 0 · 📉 0 · 💤 2

| trend | stage | latest signal |
|-------|-------|---------------|
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-09-03](https://arxiv.org/abs/2609.03194) |
| [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) | 🚀 accelerating | [2026-08-26](https://arxiv.org/abs/2608.25511) |
| [Quantum-advantage frontier](TRENDS.md#id-trend-011-quantum-advantage-frontier-provable-learning-separations-and-honest-quantum-classical-crossovers) | 🚀 accelerating | [2026-08-25](https://arxiv.org/abs/2608.24527) |
| [AI-for-quantum (hardware)](TRENDS.md#id-trend-002-ai-for-quantum-hardware-leg-classical-ml-for-quantum-hardware-control-calibration-decoding-and-circuit-design) | 🚀 accelerating | [2026-08-20](https://arxiv.org/abs/2608.20139) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 🚀 accelerating | [2026-09-01](https://www.nature.com/articles/s41534-026-01364-2) |
| [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) | 🚀 accelerating | [2026-09-01](https://quantum-journal.org/papers/q-2026-09-01-2198/) |
| [LLM/agentic quantum reasoning](TRENDS.md#id-trend-009-llmagentic-ai-reasoning-about-quantum-circuits-algorithms-and-proofs) | 🚀 accelerating | [2026-08-10](https://arxiv.org/abs/2608.08996) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 📈 emerging | [2026-08-31](https://arxiv.org/abs/2609.00372) |
| [QML generalization theory](TRENDS.md#id-trend-007-qml-generalization-theory-bounds-phenomenology-and-the-reference-structure-requirement) | 📈 emerging | [2026-08-31](https://arxiv.org/abs/2608.31117) |
| [Agentic AI lab automation](TRENDS.md#id-trend-013-agentic-ai-directly-operating-quantum-hardware-and-lab-infrastructure-end-to-end) | 📈 emerging | [2026-08-27](https://www.quera.com/blog-posts/holding-the-light-teaching-an-ai-to-lock-and-tune-our-quantum-computers-lasers) |
| [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) | 📈 emerging | [2026-08-14](https://arxiv.org/abs/2608.14208) |
| [Quantum kernels & feature maps](TRENDS.md#id-trend-015-quantum-kernels--feature-maps-expressivity-encoding-budgets-and-application-scale-benchmarking) | 🌱 seed | [2026-09-01](https://arxiv.org/abs/2609.00475) |
| [Hamiltonian-parameter learning](TRENDS.md#id-trend-014-learning-hamiltonian-and-dissipative-rate-parameters-of-quantum-systems-from-data) | 🌱 seed | [2026-08-27](https://arxiv.org/abs/2608.29302) |
| [AI-for-quantum (circuit synthesis)](TRENDS.md#id-trend-012-ai-for-quantum-circuit-synthesis-leg-generativetransformer-models-that-directly-synthesize-quantum-circuits) | 💤 dormant | [2026-07-24](https://arxiv.org/abs/2607.22468) |
| [QML security & adversarial robustness](TRENDS.md#id-trend-010-qml-security--adversarial-robustness-attacks-on-and-defenses-for-variational-quantum-models) | 💤 dormant | [2026-07-21](https://arxiv.org/abs/2607.19318) |

## Worth studying

- [Experimental validation of a compact fault-tolerant architecture for trapped ions (arXiv:2609.03194)](https://arxiv.org/abs/2609.03194) — Berthusen, Lavasani, Benhemou et al. (Quantinuum, Sep 3): validates a full early-fault-tolerant architecture — efficient logical encoding, low-overhead logical operations, AND non-Clifford resources, all at once — on Quantinuum's 98-qubit Helios trapped-ion processor.
- [Quantum Hamiltonian Evolution for Coherent Quantum Learning (arXiv:2609.03640)](https://arxiv.org/abs/2609.03640) — Acedo, Gonzalez-Conde, Rodriguez-Grasa, Sanders, Pira (Sep 2): a QML training paradigm where model parameters are quantum degrees of freedom evolved unitarily under a Hamiltonian encoding the loss function, instead of the usual classical outer-loop gradient updates.
- [MerLin v0.4.0 "Grimoire" release notes](https://github.com/merlinquantum/merlin/releases) — Quandela: adds ready-to-use photonic-QML models (ReservoirClassifier, PhotonicGenerator, QCNNClassifier), hardware-aware noisy-SLOS training, and a MerlinProcessor unifying local simulation with remote execution.
- [IBM Quantum Nighthawk r2 — more circuits, faster](https://www.ibm.com/quantum/blog/nighthawk-r2) — IBM (Sep 2): a 120-qubit QPU replacing conditional reset with a dissipative-reset gadget, reporting a 25x circuit-throughput gain.
- [A brief history of quantum vs classical computational advantage (Quantum 10, 2198)](https://quantum-journal.org/papers/q-2026-09-01-2198/) — Ryan LaRose (Sep 1): a peer-reviewed review summarizing every experiment claiming quantum computational advantage to date, cataloguing the challenges, loopholes and refutations that appeared in subsequent work for each one.
- [Automated near-term quantum algorithm discovery for molecular ground states (arXiv:2603.26359)](https://arxiv.org/abs/2603.26359) — Finger, Rapp, Kalidindi et al. (Quantinuum + Google DeepMind, Mar 27): an LLM-driven distributed evolutionary program-synthesis platform ("Hive") discovers heuristic near-term quantum algorithms for molecular ground-state estimation with major resource reductions, caught 5 months late by a monthly backlog sweep.
- [Theoretical guarantees of variational quantum algorithm with guiding states (npj Quantum Information, DOI 10.1038/s41534-026-01364-2)](https://www.nature.com/articles/s41534-026-01364-2) — Nguyen, Kieferová (Sep 1): a VQA for amortized ground-state-property prediction with rigorous convergence and generalization guarantees, rather than only empirical trainability diagnostics.
- [A quantum generative model for in silico clinical trials using scarce training datasets (arXiv:2608.28168)](https://arxiv.org/abs/2608.28168) — Sanz Larrarte, Dastbasteh, Sanchez-Navarro, Diez-Campelo, Prosper, Alfonso-Pierola, Hernaez, Capponi, Crespo Bofill, Etxezarreta Martinez (Aug 28): a quantum generative model trained on scarce Myelodysplastic Syndrome patient data, executed on real IBM Heron r2 hardware, beating classical baselines on generalization/expressivity.
- [From quantum reservoirs to quantum extreme learning machines through a nearest-neighbor spin chain with tunable quantum memory (arXiv:2608.28440)](https://arxiv.org/abs/2608.28440) — Ramon-Escandell, Riera, Płodzień (Aug 28): shows Quantum Reservoir Computing and Quantum Extreme-Learning Machines are the two limits of one architecture, connected by how many qubits carry memory.
- [Resolving Structure in Prethermal Floquet Dynamics with Precision Quantum Computation (arXiv:2607.24937)](https://arxiv.org/abs/2607.24937) — Leviatan, Watad, Perry, Broers, Mullath, Alberton, Arad, Atia (IBM+Qedma): resolves prethermal Floquet-magnet dynamics beyond reliable classical methods; a serious but still vendor-reported classical-attack attempt (RIKEN+BlueQubit) failed to reproduce it — an open case, not yet independently dequantized or peer-reviewed either way.
- [Holding the Light: Teaching an AI to Lock and Tune our Quantum Computer's Lasers](https://www.quera.com/blog-posts/holding-the-light-teaching-an-ai-to-lock-and-tune-our-quantum-computers-lasers) — QuEra (Aug 27): an LLM agent autonomously diagnoses and recovers laser-lock faults on QuEra's live neutral-atom hardware — 99.3% automated recovery success, recovery time cut from minutes to seconds, zero unattended lock drops over a 19-hour test.
- [Superextensive learning in quantum reservoirs at the onset of information scrambling (arXiv:2608.25511)](https://arxiv.org/abs/2608.25511) — Freiheit, Campaioli (Aug 26): imports the complex-systems "edge of chaos" hypothesis into quantum reservoir computing, using out-of-time-order correlators to locate the onset of information scrambling in 2D Ising-network reservoirs.

## Community pulse

_Unverified intake — community signals, not trend evidence._

- Reddit's r/QuantumComputing RSS hit a login-wall page for a 4th consecutive run — the same alternate access methods remain exhausted, now overdue for a weekly-level fix.
- Hacker News surfaced only already-tracked items (IBM's Nighthawk r2, a "15 minutes" press pickup) plus foundational-physics pieces (quantum gravity, gravitationally-induced entanglement) outside this radar's quantum-computing/QML scope.
- Digest coverage stayed dominated by funding/business/partnership news (Quantinuum/Aramco, Quantum Motion, Quobly/OrangeQS, silicon-spin and PQC partnerships) — no accompanying technical primaries beyond items already routed to the ledger.
- A Quantum Reservoir Computing readout claim from Qilimanjaro remains unverified and unchanged — still only a digest article, no vendor primary or paper located.
- YouTube's Qiskit/Sabine feeds broke again this run (404) — the recurring intermittent pattern continues, no working substitute.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (31)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-09-04](reports/2026-09-04.md) · weekly: [2026-W35](reports/weekly/2026-W35.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

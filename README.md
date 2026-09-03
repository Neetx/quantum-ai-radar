# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-15-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-7-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-29-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--09--03-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-09-03):**
- **[Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) gains an 11th group** — Marcello Benedetti's [unsupervised representation-learning-for-quantum-data paper](https://arxiv.org/abs/2609.00372) cap-swaps in, opening a 2-item [representation-learning micro-cluster](https://arxiv.org/abs/2609.01797) to watch.
- **IBM's newest QPU** — [Nighthawk r2](https://www.ibm.com/quantum/blog/nighthawk-r2), a 120-qubit chip with a dissipative-reset gadget delivering a 25x circuit-throughput gain.
- **Framework backlog catch** — Quandela's photonic-QML framework MerLin jumped to [v0.4.0 "Grimoire"](https://github.com/merlinquantum/merlin/releases) with new ready-to-use models (this radar's last known state was v0.3.1).
- **Watchlist churned** (32 → 29) — 1 promoted via the cap-swap above, 9 stale items dropped with one-line reasons, 8 fresh captures added.

## Trends

🌱 2 · 📈 4 · 🚀 7 · 🌊 0 · 🏔 0 · 📉 0 · 💤 2

| trend | stage | latest signal |
|-------|-------|---------------|
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-08-26](https://arxiv.org/abs/2608.26272) |
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
- [No Free Compression in Quantum Relaxations for Optimization (arXiv:2608.25151)](https://arxiv.org/abs/2608.25151) — Stuart Hadfield (Aug 25): rigorously accounts for the resource tradeoffs qubit-efficient quantum optimization relaxations incur when compressing classical variables into far fewer qubits.
- [Fault-tolerant quantum computation cannot be achieved with constant spacetime overhead (arXiv:2608.26272)](https://arxiv.org/abs/2608.26272) — Bharti, Haug, Tanggara (Aug 26): proves an unavoidable logarithmic contribution to the cumulative spacetime overhead of fault-tolerant quantum computation, settling whether that overhead can ever be reduced to a true constant.

## Community pulse

_Unverified intake — community signals, not trend evidence._

- Reddit's r/QuantumComputing RSS hit a login-wall page for a 3rd consecutive run — the same 4 alternate access methods remain exhausted, still awaiting a weekly fix.
- Hacker News' front page surfaced IBM's new Nighthawk r2 QPU announcement; otherwise routine consciousness/policy/Show-HN content, no other new technical primary.
- Digest coverage stayed dominated by funding/business/partnership news (silicon-spin, photonic-sandbox, fault-tolerant-algorithm and protein-gelation partnerships) — no accompanying technical primaries beyond the items already routed to the ledger.
- A Quantum Reservoir Computing readout claim from Qilimanjaro remains unverified — only a digest article was found this run, no vendor primary or paper.
- YouTube's Qiskit/Sabine feeds broke again this run (404) — the recurring intermittent pattern continues, no working substitute.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (29)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-09-03](reports/2026-09-03.md) · weekly: [2026-W35](reports/weekly/2026-W35.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

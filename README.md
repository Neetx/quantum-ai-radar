# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-14-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-7-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-29-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--09--09-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-09-09):**
- Two dormant trends revived: [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) (dormant → emerging, an [11th independent group](https://arxiv.org/abs/2609.07645) challenging NQS dynamics accuracy) and [AI-for-quantum (circuit synthesis)](TRENDS.md#id-trend-012-ai-for-quantum-circuit-synthesis-leg-generativetransformer-models-that-directly-synthesize-quantum-circuits) (dormant → emerging, a [4th independent group](https://arxiv.org/abs/2609.08073) extending generative circuit synthesis to photonic experiment design).
- Two standing flagged cap-swaps resolved: [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) gained a 12th group ([SAR/InSAR satellite change detection on real IonQ hardware](https://arxiv.org/abs/2609.05313)) and [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) gained a 12th ([a new representation-theoretic barren-plateau framework](https://arxiv.org/abs/2609.04462)).
- **Watchlist grew 19 → 29** — arXiv's Labor-Day-extended posting freeze broke, delivering [212 new items](TRENDS.md#observation_queue) in one sweep.
- Two fresh [study picks](#worth-studying): generative design of quantum optical experiments, and an honest limits-check on neural quantum states in dynamics.

## Trends

🌱 1 · 📈 6 · 🚀 7 · 🌊 0 · 🏔 0 · 📉 0 · 💤 0

| trend | stage | latest signal |
|-------|-------|---------------|
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-09-03](https://arxiv.org/abs/2609.03194) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 🚀 accelerating | [2026-09-03](https://arxiv.org/abs/2609.04462) |
| [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) | 🚀 accelerating | [2026-09-01](https://quantum-journal.org/papers/q-2026-09-01-2198/) |
| [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) | 🚀 accelerating | [2026-08-28](https://arxiv.org/abs/2608.28440) |
| [Quantum-advantage frontier](TRENDS.md#id-trend-011-quantum-advantage-frontier-provable-learning-separations-and-honest-quantum-classical-crossovers) | 🚀 accelerating | [2026-08-25](https://arxiv.org/abs/2608.24527) |
| [AI-for-quantum (hardware)](TRENDS.md#id-trend-002-ai-for-quantum-hardware-leg-classical-ml-for-quantum-hardware-control-calibration-decoding-and-circuit-design) | 🚀 accelerating | [2026-08-20](https://arxiv.org/abs/2608.20139) |
| [LLM/agentic quantum reasoning](TRENDS.md#id-trend-009-llmagentic-ai-reasoning-about-quantum-circuits-algorithms-and-proofs) | 🚀 accelerating | [2026-08-10](https://arxiv.org/abs/2608.08996) |
| [AI-for-quantum (circuit synthesis)](TRENDS.md#id-trend-012-ai-for-quantum-circuit-synthesis-leg-generativetransformer-models-that-directly-synthesize-quantum-circuits) | 📈 emerging | [2026-09-08](https://arxiv.org/abs/2609.08073) |
| [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) | 📈 emerging | [2026-09-07](https://arxiv.org/abs/2609.07645) |
| [Quantum kernels & feature maps](TRENDS.md#id-trend-015-quantum-kernels--feature-maps-expressivity-encoding-budgets-and-application-scale-benchmarking) | 📈 emerging | [2026-09-04](https://arxiv.org/abs/2609.04652) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 📈 emerging | [2026-09-03](https://arxiv.org/abs/2609.05313) |
| [QML generalization theory](TRENDS.md#id-trend-007-qml-generalization-theory-bounds-phenomenology-and-the-reference-structure-requirement) | 📈 emerging | [2026-08-31](https://arxiv.org/abs/2608.31117) |
| [Agentic AI lab automation](TRENDS.md#id-trend-013-agentic-ai-directly-operating-quantum-hardware-and-lab-infrastructure-end-to-end) | 📈 emerging | [2026-08-27](https://www.quera.com/blog-posts/holding-the-light-teaching-an-ai-to-lock-and-tune-our-quantum-computers-lasers) |
| [Hamiltonian-parameter learning](TRENDS.md#id-trend-014-learning-hamiltonian-and-dissipative-rate-parameters-of-quantum-systems-from-data) | 🌱 seed | [2026-08-27](https://arxiv.org/abs/2608.29302) |

## Worth studying

- [Bottom-Up Design of Quantum Optical Experiments Using Discrete Generative Models (arXiv:2609.08073)](https://arxiv.org/abs/2609.08073) — Huidobro-Meezs, Paiva-Ortega, Vargas-Hernández (Sep 8): a reward-driven generative framework (Grinch) learns to sample optical-circuit graphs for target quantum states directly from fidelity-based rewards, with no pre-existing training dataset.
- [Geometric inflation of deviations challenges neural quantum states in dynamics of quantum Ising models (arXiv:2609.07645)](https://arxiv.org/abs/2609.07645) — Krinitsin, Rigo, Abedi, Schmitt (Sep 7): a controlled quench-dynamics benchmark shows accurate NQS dynamics simulation is surprisingly hard even in regimes of limited physical complexity, tightening prior parameter-count assumptions.
- [A Sim-to-Real Study of Surface-Code Decoder Benchmarking (arXiv:2609.04557)](https://arxiv.org/abs/2609.04557) — Manor, Erhili, Jebbouri (Sep 3): tests whether decoder rankings under synthetic noise transfer to Google's Willow processor, the first below the surface-code threshold — rank agreement appears only once the noise model is sufficiently realistic.
- [SAR and InSAR Change Detection with Quantum Generative Models (arXiv:2609.05313)](https://arxiv.org/abs/2609.05313) — Sekwao, De, Hocken, Staniewicz, Epifanovsky, Stringham (Sep 3): a quantum generative model executed on an IonQ trapped-ion processor improves satellite radar change-detection for disaster response — a fresh independent group for trend-003.
- [Experimental validation of a compact fault-tolerant architecture for trapped ions (arXiv:2609.03194)](https://arxiv.org/abs/2609.03194) — Berthusen, Lavasani, Benhemou et al. (Quantinuum, Sep 3): validates a full early-fault-tolerant architecture — efficient logical encoding, low-overhead logical operations, AND non-Clifford resources, all at once — on Quantinuum's 98-qubit Helios trapped-ion processor.
- [Quantum Hamiltonian Evolution for Coherent Quantum Learning (arXiv:2609.03640)](https://arxiv.org/abs/2609.03640) — Acedo, Gonzalez-Conde, Rodriguez-Grasa, Sanders, Pira (Sep 2): a QML training paradigm where model parameters are quantum degrees of freedom evolved unitarily under a Hamiltonian encoding the loss function, instead of the usual classical outer-loop gradient updates.
- [MerLin v0.4.0 "Grimoire" release notes](https://github.com/merlinquantum/merlin/releases) — Quandela: adds ready-to-use photonic-QML models (ReservoirClassifier, PhotonicGenerator, QCNNClassifier), hardware-aware noisy-SLOS training, and a MerlinProcessor unifying local simulation with remote execution.
- [IBM Quantum Nighthawk r2 — more circuits, faster](https://www.ibm.com/quantum/blog/nighthawk-r2) — IBM (Sep 2): a 120-qubit QPU replacing conditional reset with a dissipative-reset gadget, reporting a 25x circuit-throughput gain.
- [A brief history of quantum vs classical computational advantage (Quantum 10, 2198)](https://quantum-journal.org/papers/q-2026-09-01-2198/) — Ryan LaRose (Sep 1): a peer-reviewed review summarizing every experiment claiming quantum computational advantage to date, cataloguing the challenges, loopholes and refutations that appeared in subsequent work for each one.
- [Automated near-term quantum algorithm discovery for molecular ground states (arXiv:2603.26359)](https://arxiv.org/abs/2603.26359) — Finger, Rapp, Kalidindi et al. (Quantinuum + Google DeepMind, Mar 27): an LLM-driven distributed evolutionary program-synthesis platform ("Hive") discovers heuristic near-term quantum algorithms for molecular ground-state estimation with major resource reductions, caught 5 months late by a monthly backlog sweep.
- [Theoretical guarantees of variational quantum algorithm with guiding states (npj Quantum Information, DOI 10.1038/s41534-026-01364-2)](https://www.nature.com/articles/s41534-026-01364-2) — Nguyen, Kieferová (Sep 1): a VQA for amortized ground-state-property prediction with rigorous convergence and generalization guarantees, rather than only empirical trainability diagnostics.
- [A quantum generative model for in silico clinical trials using scarce training datasets (arXiv:2608.28168)](https://arxiv.org/abs/2608.28168) — Sanz Larrarte, Dastbasteh, Sanchez-Navarro, Diez-Campelo, Prosper, Alfonso-Pierola, Hernaez, Capponi, Crespo Bofill, Etxezarreta Martinez (Aug 28): a quantum generative model trained on scarce Myelodysplastic Syndrome patient data, executed on real IBM Heron r2 hardware, beating classical baselines on generalization/expressivity.

## Community pulse

_Unverified intake — community signals, not trend evidence._

- Reddit's r/QuantumComputing stayed dominated by routine investing/hardware/business threads, nothing new.
- Hacker News' front page was topped by a viral claim that AI agents resolved a Navier-Stokes Millennium Prize singularity — checked and confirmed a classical mathematics result with zero quantum-computing component despite a "quantum value" framing on a secondary mirror, correctly not pursued.
- Digest coverage (Quantum Insider, Quantum Computing Report, Quantum Zeitgeist) stayed dominated by funding/business/foundry news (CHIPS Act awards, partnership announcements), with no accompanying technical primaries beyond items already routed to the ledger.
- Quantum Machines' blog reverted to unextractable this run, after last run's one-off successful extraction — a caution against treating a single success as a confirmed fix, not a new signal.
- YouTube's Qiskit/Sabine feeds continue their recurring intermittent break — no working substitute found across many weeks.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (29)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-09-09](reports/2026-09-09.md) · weekly: [2026-W36](reports/weekly/2026-W36.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

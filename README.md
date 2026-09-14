# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-14-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-7-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-20-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--09--14-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-09-14, daily):**
- [AI-for-quantum (hardware)](TRENDS.md#id-trend-002-ai-for-quantum-hardware-leg-classical-ml-for-quantum-hardware-control-calibration-decoding-and-circuit-design) revived from dormant to emerging — a fresh independent group, [RL for syndrome extraction](https://arxiv.org/abs/2609.12020), squarely on the trend's own decoding/circuit-design theme.
- [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) and [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) each cap-swapped in a 12th/13th independent group — a [QSVT dequantization result](https://arxiv.org/abs/2609.10729) and a [Coherent Floquet QRC for molecular property prediction](https://arxiv.org/abs/2609.11071).
- New QML-lead-axis captures: a [quantum transformer for sentiment classification](https://arxiv.org/abs/2609.12011) and an [experimental qudit-based QNN trained via backpropagation](https://arxiv.org/abs/2609.12500) on real trapped-ion hardware.
- arXiv's query API was rate-limited all run (a first) — this run's sweep leaned on the `rss.arxiv.org` daily feeds as a fallback; see [SOURCES.md](SOURCES.md) for the heal note.

## Trends

🌱 1 · 📈 6 · 🚀 7 · 🌊 0 · 🏔 0 · 📉 0 · 💤 0

| trend | stage | latest signal |
|-------|-------|---------------|
| [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) | 🚀 accelerating | [2026-09-10](https://arxiv.org/abs/2609.11847) |
| [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) | 🚀 accelerating | [2026-09-10](https://arxiv.org/abs/2609.11071) |
| [Quantum kernels & feature maps](TRENDS.md#id-trend-015-quantum-kernels--feature-maps-expressivity-encoding-budgets-and-application-scale-benchmarking) | 🚀 accelerating | [2026-09-09](https://arxiv.org/abs/2609.10505) |
| [LLM/agentic quantum reasoning](TRENDS.md#id-trend-009-llmagentic-ai-reasoning-about-quantum-circuits-algorithms-and-proofs) | 🚀 accelerating | [2026-09-08](https://arxiv.org/abs/2609.09582) |
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-09-03](https://arxiv.org/abs/2609.03194) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 🚀 accelerating | [2026-09-03](https://arxiv.org/abs/2609.04462) |
| [Quantum-advantage frontier](TRENDS.md#id-trend-011-quantum-advantage-frontier-provable-learning-separations-and-honest-quantum-classical-crossovers) | 🚀 accelerating | [2026-08-25](https://arxiv.org/abs/2608.24527) |
| [AI-for-quantum (circuit synthesis)](TRENDS.md#id-trend-012-ai-for-quantum-circuit-synthesis-leg-generativetransformer-models-that-directly-synthesize-quantum-circuits) | 📈 emerging | [2026-09-10](https://arxiv.org/abs/2609.11248) |
| [Agentic AI lab automation](TRENDS.md#id-trend-013-agentic-ai-directly-operating-quantum-hardware-and-lab-infrastructure-end-to-end) | 📈 emerging | [2026-09-08](https://openai.com/index/codex-quantum-computing-experiments/) |
| [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) | 📈 emerging | [2026-09-07](https://arxiv.org/abs/2609.07645) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 📈 emerging | [2026-09-05](https://arxiv.org/abs/2609.06307) |
| [AI-for-quantum (hardware)](TRENDS.md#id-trend-002-ai-for-quantum-hardware-leg-classical-ml-for-quantum-hardware-control-calibration-decoding-and-circuit-design) | 📈 emerging | [2026-09-10](https://arxiv.org/abs/2609.12020) |
| [QML generalization theory](TRENDS.md#id-trend-007-qml-generalization-theory-bounds-phenomenology-and-the-reference-structure-requirement) | 📈 emerging | [2026-08-31](https://arxiv.org/abs/2608.31117) |
| [Hamiltonian-parameter learning](TRENDS.md#id-trend-014-learning-hamiltonian-and-dissipative-rate-parameters-of-quantum-systems-from-data) | 🌱 seed | [2026-08-27](https://arxiv.org/abs/2608.29302) |

## Worth studying

- [Quantum neural network equipped with backpropagation on a qudit processor (arXiv:2609.12500)](https://arxiv.org/abs/2609.12500) — Yuan, Xu, Du, Zhao, Cheng, Li, Hou, Zhou, Li, Lin (Sep 11): an experimental qudit-based QNN trained via backpropagation on a real trapped-ion (⁴⁰Ca⁺) processor, exploiting qudits' larger per-unit Hilbert space for more expressive QNNs at fixed processor size.
- [Reinforcement Learning for Syndrome Extraction (arXiv:2609.12020)](https://arxiv.org/abs/2609.12020) — Ye, Pabla, Palsberg (Sep 10): RL plus importance sampling searches the exponentially large space of syndrome-extraction circuit implementations for QEC, outperforming prior search methods at every scale tested.
- [From Python to hardware: real-time classical co-processing with PennyLane, Backline, and AMD](https://pennylane.ai/blog/2026/09/real-time-classical-processing-with-backline-amd) — Xanadu + AMD (Sep 10): Backline, an open-source heterogeneous compilation fabric built into PennyLane's Catalyst compiler, dynamically routes quantum-classical workloads — including the microsecond-scale real-time feedback loops fault-tolerant QEC needs — to CPUs, GPUs, FPGAs and ASICs.
- [The cost of simulating classically tractable quantum circuits and dynamics (arXiv:2609.11847)](https://arxiv.org/abs/2609.11847) — Chang, Thanasilp, Holmes, Cerezo (Sep 10): distinguishes asymptotic polynomial-time classical simulability from PRACTICAL classical cost, showing expensive preprocessing or quantum-data-acquisition overheads can make a "classically simulable" quantum evolution not actually cheaper to simulate than to run quantumly.
- [How GPT-5.6 Sol helps run quantum computing experiments](https://openai.com/index/codex-quantum-computing-experiments/) — OpenAI (Sep 8): an MIT graduate student connects GPT-5.6 Sol, harnessed to Codex, directly to lab software controlling a six-qubit superconducting chip, letting the agent autonomously run calibration/measurement sequences and decide what to try next.
- [The First Full-Stack Blueprint for Breaking 256-Bit Elliptic Curve Signatures](https://ionq.com/blog/the-first-full-stack-blueprint-for-breaking-256-bit-elliptic-curve-signatures) — IonQ (Sep 8): a 70-page resource estimate compiles Shor's algorithm for secp256k1 down to QEC primitives on a specialized trapped-ion architecture, cutting the qubit count needed from 1.2M+ to ~19,397 — read as a 2028-roadmap projection, not an achieved break.
- [Bottom-Up Design of Quantum Optical Experiments Using Discrete Generative Models (arXiv:2609.08073)](https://arxiv.org/abs/2609.08073) — Huidobro-Meezs, Paiva-Ortega, Vargas-Hernández (Sep 8): a reward-driven generative framework (Grinch) learns to sample optical-circuit graphs for target quantum states directly from fidelity-based rewards, with no pre-existing training dataset.
- [Geometric inflation of deviations challenges neural quantum states in dynamics of quantum Ising models (arXiv:2609.07645)](https://arxiv.org/abs/2609.07645) — Krinitsin, Rigo, Abedi, Schmitt (Sep 7): a controlled quench-dynamics benchmark shows accurate NQS dynamics simulation is surprisingly hard even in regimes of limited physical complexity, tightening prior parameter-count assumptions.
- [A Sim-to-Real Study of Surface-Code Decoder Benchmarking (arXiv:2609.04557)](https://arxiv.org/abs/2609.04557) — Manor, Erhili, Jebbouri (Sep 3): tests whether decoder rankings under synthetic noise transfer to Google's Willow processor, the first below the surface-code threshold — rank agreement appears only once the noise model is sufficiently realistic.
- [SAR and InSAR Change Detection with Quantum Generative Models (arXiv:2609.05313)](https://arxiv.org/abs/2609.05313) — Sekwao, De, Hocken, Staniewicz, Epifanovsky, Stringham (Sep 3): a quantum generative model executed on an IonQ trapped-ion processor improves satellite radar change-detection for disaster response — a fresh independent group for trend-003.
- [Experimental validation of a compact fault-tolerant architecture for trapped ions (arXiv:2609.03194)](https://arxiv.org/abs/2609.03194) — Berthusen, Lavasani, Benhemou et al. (Quantinuum, Sep 3): validates a full early-fault-tolerant architecture — efficient logical encoding, low-overhead logical operations, AND non-Clifford resources, all at once — on Quantinuum's 98-qubit Helios trapped-ion processor.

## Community pulse

_Unverified intake — community signals, not trend evidence._

- Hacker News surfaced a paywalled IEEE bibliometric survey of the QML literature (queued, unverified) and a repeat of the already-debunked "AI solved a Millennium Prize problem" story (still a classical result, no quantum component).
- A Quantum Zeitgeist "Columbia & Cambridge unlock quantum AI" headline traced to a purely classical materials-ML benchmark — no quantum computer involved despite the framing; a reminder to always open the primary before trusting a "quantum AI" headline.
- Digest coverage (Quantum Insider, Quantum Computing Report, Quantum Zeitgeist) stayed dominated by funding/business/partnership news.
- Quantum Machines' blog reverted to a nav-shell-only extraction again — still not a stable heal, treat any successful extraction as a bonus, not a fix.
- YouTube's Qiskit/Sabine feeds continue their recurring intermittent break — no working substitute found across many weeks.
- arXiv's query API was fully rate-limited this run (a first) — see [SOURCES.md](SOURCES.md) for the RSS-based fallback used instead.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (20)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-09-14](reports/2026-09-14.md) · weekly: [2026-W37](reports/weekly/2026-W37.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

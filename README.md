# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-16-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-12-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-27-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--11--02-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-11-02):**
- [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) absorbed [Distilling Knowledge from Search: Decoder Model Factory for Quantum LDPC Codes](https://arxiv.org/abs/2610.41398) — a self-improving qLDPC decoder-training paradigm.
- [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) absorbed [The Quartic Gap Between Quantum and Dequantized Algorithms for Linear Algebra Is Tight](https://arxiv.org/abs/2610.42069) — a worst-case-tight dequantization lower bound.
- [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) and [LLM/agentic quantum reasoning](TRENDS.md#id-trend-009-llmagentic-ai-reasoning-about-quantum-circuits-algorithms-and-proofs) each resolved a multi-day-standing candidate: [quantum neuroplastic learning](https://arxiv.org/abs/2610.34055) and [LLM quantum-code translation](https://arxiv.org/abs/2610.34841).
- Watchlist grew to 27 after a high-yield arXiv day (7 fresh finds, 2 resolved into evidence) — see [watchlist](TRENDS.md#observation_queue).

## Trends

🌱 0 · 📈 4 · 🚀 12 · 🌊 0 · 🏔 0 · 📉 0 · 💤 0

| trend | stage | latest signal |
|-------|-------|---------------|
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-10-30](https://arxiv.org/abs/2610.41398) |
| [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) | 🚀 accelerating | [2026-10-30](https://arxiv.org/abs/2610.42069) |
| [AI-for-quantum (circuit synthesis)](TRENDS.md#id-trend-012-ai-for-quantum-circuit-synthesis-leg-generativetransformer-models-that-directly-synthesize-quantum-circuits) | 🚀 accelerating | [2026-10-30](https://arxiv.org/abs/2610.41957) |
| [Quantum kernels & feature maps](TRENDS.md#id-trend-015-quantum-kernels--feature-maps-expressivity-encoding-budgets-and-application-scale-benchmarking) | 🚀 accelerating | [2026-10-30](https://arxiv.org/abs/2610.41848) |
| [Quantum-advantage frontier](TRENDS.md#id-trend-011-quantum-advantage-frontier-provable-learning-separations-and-honest-quantum-classical-crossovers) | 🚀 accelerating | [2026-10-28](https://arxiv.org/abs/2610.38922) |
| [LLM/agentic quantum reasoning](TRENDS.md#id-trend-009-llmagentic-ai-reasoning-about-quantum-circuits-algorithms-and-proofs) | 🚀 accelerating | [2026-10-26](https://arxiv.org/abs/2610.34841) |
| [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) | 🚀 accelerating | [2026-10-25](https://arxiv.org/abs/2610.34055) |
| [Quantum transformers and attention](TRENDS.md#id-trend-016-quantum-transformers-and-attention-pqc-based-attention-mechanisms-for-sequence-and-signal-processing) | 🚀 accelerating | [2026-10-25](https://arxiv.org/abs/2610.34492) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 🚀 accelerating | [2026-10-23](https://arxiv.org/abs/2610.32571) |
| [AI-for-quantum (hardware)](TRENDS.md#id-trend-002-ai-for-quantum-hardware-leg-classical-ml-for-quantum-hardware-control-calibration-decoding-and-circuit-design) | 🚀 accelerating | [2026-10-21](https://arxiv.org/abs/2610.29170) |
| [QML generalization theory](TRENDS.md#id-trend-007-qml-generalization-theory-bounds-phenomenology-and-the-reference-structure-requirement) | 🚀 accelerating | [2026-10-17](https://arxiv.org/abs/2610.24426) |
| [Hamiltonian-parameter learning](TRENDS.md#id-trend-014-learning-hamiltonian-and-dissipative-rate-parameters-of-quantum-systems-from-data) | 🚀 accelerating | [2026-10-16](https://doi.org/10.1103/kjvf-jgqj) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 📈 emerging | [2026-10-30](https://arxiv.org/abs/2610.41721) |
| [Agentic AI lab automation](TRENDS.md#id-trend-013-agentic-ai-directly-operating-quantum-hardware-and-lab-infrastructure-end-to-end) | 📈 emerging | [2026-10-29](https://arxiv.org/abs/2610.40589) |
| [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) | 📈 emerging | [2026-10-22](https://arxiv.org/abs/2610.30257) |
| [QML/QEC security](TRENDS.md#id-trend-017-qmlqec-security-adversarial-attacks-on-and-defenses-for-quantum-classical-ml-components) | 📈 emerging | [2026-10-19](https://arxiv.org/abs/2610.26240) |

## Worth studying

- [The Quartic Gap Between Quantum and Dequantized Algorithms for Linear Algebra Is Tight (arXiv:2610.42069)](https://arxiv.org/abs/2610.42069) — Chakrabarti, Herman, Kim, Ozgul (Oct 30): proves the known quantum-vs-dequantized query-complexity gap for QRAM-accessed linear systems is tight up to a log factor — a rare matching lower bound rather than just a faster classical algorithm.
- [Distilling Knowledge from Search: Decoder Model Factory for Quantum LDPC Codes (arXiv:2610.41398)](https://arxiv.org/abs/2610.41398) — Bilgin, Hou, Srinivas, You (Oct 30): GraphMP, a qLDPC decoder that transfers without fine-tuning across code families, trained via successive generations distilled from its own prior generation's decoding runs.
- [Collaborative AI agents for autonomous experimental research with solid-state quantum spins](https://arxiv.org/abs/2610.40589) — Mansouri, Kimura, Koga, Arai (Oct 29): LLM agents that assess one another's work and can stop/redirect investigations, demonstrated end-to-end on real NV-diamond quantum spins.
- [Co-Innovating with IonQ: How One Utility Is Solving Power Grid Complexity](https://ionq.com/blog/co-innovating-with-ionq-how-one-utility-is-solving-power-grid-complexity) — IonQ + EPB (Oct 28): three companion papers tackle one real utility's grid-reconfiguration problem with hybrid quantum RL, LR-QAOA-guided MISOCP and warm-start QITE, all validated on real grid topologies on IonQ Forte Enterprise.
- [Five results on Open Quantum Problems](https://psi.inc/research/oqp-batch-2026/) — PSI (Physical Superintelligence, Oct 23): PSI's own AI research system produces five new, Lean-verified results in quantum information theory itself, each with a paper, formal proof and verification code.
- [Emergent Recursive Kernels in Quantum Reservoir Computing (arXiv:2610.34430)](https://arxiv.org/abs/2610.34430) — Ce Wang (Oct 25): proves a fixed-dynamics quantum reservoir admits an exact recursive kernel in the large-dimension limit, reducing each kernel evaluation to a scalar recurrence linear in history length and independent of reservoir size.
- [QuantumMatterExplorer: An Autonomous Agent for the Discovery of Quantum Many-Body Phases of Matter (arXiv:2610.32001)](https://arxiv.org/abs/2610.32001) — Nys, Jreissaty, Carrasquilla (Oct 22): an LLM-based autonomous agent that takes only a Hamiltonian and its parameter ranges and returns a full phase diagram from its own numerical simulations, reasoning over a long horizon with a persistent written plan.
- [Announcing the verifiable quantum circuit compilation competition on Kaggle](https://opensource.googleblog.com/2026/10/announcing-verifiable-quantum-circuit-compilation-competition-on-kaggle.html) — Khattar, Babbush (Google Quantum AI, Oct 21): a public Kaggle competition built on the pair's own verifiable-structure agentic-compilation approach — a hands-on entry point for trying agentic circuit compilation.
- [Decoding quantum errors with NVIDIA Ising Decoding on AWS](https://aws.amazon.com/blogs/quantum-computing/decoding-quantum-errors-with-nvidia-ising-decoding-on-aws/) — AWS + NVIDIA (Oct 21): trains/benchmarks an AI QEC pre-decoder across 5 GPU generations, cutting per-round decoding latency 2.4-2.9x over MWPM alone at distance 31 — a reproducible playbook with cost-per-GPU-generation figures.
- [Mamba Quantum Eigensolver (MQE): A Selective State Space Model for Scalable Ground State Simulations in Quantum Chemistry (arXiv:2610.29779)](https://arxiv.org/abs/2610.29779) — Petronilo, Araújo, Teixeira, Cruz: swaps the Generative Quantum Eigensolver's Transformer backbone for a Mamba state-space model, trading quadratic attention cost for linear-time ansatz generation.
- [Does Data Complexity Predict Quantum Advantage? A framework, a pre-specified test, and an attribution of the measured edge (arXiv:2509.16410)](https://arxiv.org/abs/2509.16410) — Pere (v2, Oct 7; orig. Sep 2025): a pre-specified, budget-matched test across 27 datasets finds data complexity alone does not predict the quantum edge, and the apparent signal tracks classical-baseline weakness rather than a robust quantum contribution.
- [Advancing Fault-Tolerant Quantum Computing with GPU-Accelerated Simulation](https://nvidia.github.io/cuda-quantum/blogs/blog/2026/10/19/jupiter-magic-state-simulation/) — NVIDIA + Jülich (Oct 19): simulates magic-state preparation in a 104-qubit protocol using 8,192 GPUs on the JUPITER supercomputer, co-authored by Krysta Svore.

## Community pulse

_Unverified intake — community signals, not trend evidence._

- r/QuantumComputing's search access recovered this week; sampled threads were routine/generic discussion with nothing dated or new.
- Hacker News surfaced a self-posted, unverifiable "NP-hard solver" repository and a recirculating AI-generated-proof claim — neither treated as evidence.
- Digests (The Quantum Insider, Quantum Computing Report, Quantum Zeitgeist) skewed toward funding/policy and hardware-business items this run; one Quantum Zeitgeist story's "GAN" framing turned out, on inspection, to be unrelated gallium-nitride defect physics with no learning component.
- Hugging Face's Daily Papers exploration lane surfaced no quantum-relevant items.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (27)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-11-02](reports/2026-11-02.md) · weekly: [2026-W44](reports/weekly/2026-W44.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

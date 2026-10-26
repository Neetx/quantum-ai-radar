# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-16-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-12-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-25-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--10--26-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-10-26):**
- A 17-day-overdue watchlist item properly belonged to an existing trend's own axis: [LLM/agentic quantum reasoning](TRENDS.md#id-trend-009-llmagentic-ai-reasoning-about-quantum-circuits-algorithms-and-proofs) absorbed [QTestBench, a test-quality benchmark for LLM-generated quantum code](https://arxiv.org/abs/2610.13811), as a 21st independent group.
- A capture-leak catch via an independent-voices blog pointer: [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) absorbed [a classical algorithm for sampling from Gibbs states](https://arxiv.org/abs/2609.40250), directly dequantizing the sampling step behind Boltzmann-machine-based quantum learning, as a 22nd independent group.
- Watchlist moved 23 → 25 (1 promoted as above, 3 added, including [QuantumMatterExplorer](https://arxiv.org/abs/2610.32001), an autonomous LLM agent for quantum-many-body phase discovery, also added to the study shelf); see [watchlist](TRENDS.md#observation_queue).
- No stage moves, confidence raises, merges or archivals this run (a quiet weekend on arXiv — no submissions past Oct-23).

## Trends

🌱 0 · 📈 4 · 🚀 12 · 🌊 0 · 🏔 0 · 📉 0 · 💤 0

| trend | stage | latest signal |
|-------|-------|---------------|
| [LLM/agentic quantum reasoning](TRENDS.md#id-trend-009-llmagentic-ai-reasoning-about-quantum-circuits-algorithms-and-proofs) | 🚀 accelerating | [2026-10-22](https://arxiv.org/abs/2610.31352) |
| [Quantum kernels & feature maps](TRENDS.md#id-trend-015-quantum-kernels--feature-maps-expressivity-encoding-budgets-and-application-scale-benchmarking) | 🚀 accelerating | [2026-10-22](https://arxiv.org/abs/2610.31260) |
| [AI-for-quantum (hardware)](TRENDS.md#id-trend-002-ai-for-quantum-hardware-leg-classical-ml-for-quantum-hardware-control-calibration-decoding-and-circuit-design) | 🚀 accelerating | [2026-10-21](https://aws.amazon.com/blogs/quantum-computing/decoding-quantum-errors-with-nvidia-ising-decoding-on-aws/) |
| [AI-for-quantum (circuit synthesis)](TRENDS.md#id-trend-012-ai-for-quantum-circuit-synthesis-leg-generativetransformer-models-that-directly-synthesize-quantum-circuits) | 🚀 accelerating | [2026-10-21](https://arxiv.org/abs/2610.29779) |
| [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) | 🚀 accelerating | [2026-10-19](https://arxiv.org/abs/2610.26785) |
| [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) | 🚀 accelerating | [2026-10-19](https://arxiv.org/abs/2610.26228) |
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-10-19](https://nvidia.github.io/cuda-quantum/blogs/blog/2026/10/19/jupiter-magic-state-simulation/) |
| [QML generalization theory](TRENDS.md#id-trend-007-qml-generalization-theory-bounds-phenomenology-and-the-reference-structure-requirement) | 🚀 accelerating | [2026-10-17](https://arxiv.org/abs/2610.24426) |
| [Quantum-advantage frontier](TRENDS.md#id-trend-011-quantum-advantage-frontier-provable-learning-separations-and-honest-quantum-classical-crossovers) | 🚀 accelerating | [2026-10-16](https://arxiv.org/abs/2610.23268) |
| [Hamiltonian-parameter learning](TRENDS.md#id-trend-014-learning-hamiltonian-and-dissipative-rate-parameters-of-quantum-systems-from-data) | 🚀 accelerating | [2026-10-16](https://doi.org/10.1103/kjvf-jgqj) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 🚀 accelerating | [2026-10-15](https://arxiv.org/abs/2610.21778) |
| [Quantum transformers and attention](TRENDS.md#id-trend-016-quantum-transformers-and-attention-pqc-based-attention-mechanisms-for-sequence-and-signal-processing) | 🚀 accelerating | [2026-10-12](https://arxiv.org/abs/2610.17351) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 📈 emerging | [2026-10-22](https://arxiv.org/abs/2610.31330) |
| [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) | 📈 emerging | [2026-10-22](https://arxiv.org/abs/2610.30257) |
| [QML/QEC security](TRENDS.md#id-trend-017-qmlqec-security-adversarial-attacks-on-and-defenses-for-quantum-classical-ml-components) | 📈 emerging | [2026-10-19](https://arxiv.org/abs/2610.26240) |
| [Agentic AI lab automation](TRENDS.md#id-trend-013-agentic-ai-directly-operating-quantum-hardware-and-lab-infrastructure-end-to-end) | 📈 emerging | [2026-10-18](https://arxiv.org/abs/2610.25014) |

## Worth studying

- [QuantumMatterExplorer: An Autonomous Agent for the Discovery of Quantum Many-Body Phases of Matter (arXiv:2610.32001)](https://arxiv.org/abs/2610.32001) — Nys, Jreissaty, Carrasquilla (Oct 22): an LLM-based autonomous agent that takes only a Hamiltonian and its parameter ranges and returns a full phase diagram from its own numerical simulations, reasoning over a long horizon with a persistent written plan.
- [Lean-QuantumAlg: A Framework for AI Agents to Produce Quantum Algorithms that Humans Can Trust (arXiv:2610.30216)](https://arxiv.org/abs/2610.30216) — Zhang, Jing, Zhao, Liu, Xin Wang (Oct 21): a Lean 4 contract binding correctness, success probability and resource bounds, demonstrated on nine AI-formalized algorithms from Grover search to RSA-2048/P-256 attacks with under 1% human review.
- [Announcing the verifiable quantum circuit compilation competition on Kaggle](https://opensource.googleblog.com/2026/10/announcing-verifiable-quantum-circuit-compilation-competition-on-kaggle.html) — Khattar, Babbush (Google Quantum AI, Oct 21): a public Kaggle competition built on the pair's own verifiable-structure agentic-compilation approach — a hands-on entry point for trying agentic circuit compilation.
- [Decoding quantum errors with NVIDIA Ising Decoding on AWS](https://aws.amazon.com/blogs/quantum-computing/decoding-quantum-errors-with-nvidia-ising-decoding-on-aws/) — AWS + NVIDIA (Oct 21): trains/benchmarks an AI QEC pre-decoder across 5 GPU generations, cutting per-round decoding latency 2.4-2.9x over MWPM alone at distance 31 — a reproducible playbook with cost-per-GPU-generation figures.
- [Mamba Quantum Eigensolver (MQE): A Selective State Space Model for Scalable Ground State Simulations in Quantum Chemistry (arXiv:2610.29779)](https://arxiv.org/abs/2610.29779) — Petronilo, Araújo, Teixeira, Cruz: swaps the Generative Quantum Eigensolver's Transformer backbone for a Mamba state-space model, trading quadratic attention cost for linear-time ansatz generation.
- [Does Data Complexity Predict Quantum Advantage? A framework, a pre-specified test, and an attribution of the measured edge (arXiv:2509.16410)](https://arxiv.org/abs/2509.16410) — Pere (v2, Oct 7; orig. Sep 2025): a pre-specified, budget-matched test across 27 datasets finds data complexity alone does not predict the quantum edge, and the apparent signal tracks classical-baseline weakness rather than a robust quantum contribution.
- [Advancing Fault-Tolerant Quantum Computing with GPU-Accelerated Simulation](https://nvidia.github.io/cuda-quantum/blogs/blog/2026/10/19/jupiter-magic-state-simulation/) — NVIDIA + Jülich (Oct 19): simulates magic-state preparation in a 104-qubit protocol using 8,192 GPUs on the JUPITER supercomputer, co-authored by Krysta Svore.
- [Large Language Model Steering of Acousto-Optic Tweezer Arrays (arXiv:2610.25014)](https://arxiv.org/abs/2610.25014) — Sheng et al. (Oct 18): a general-purpose LLM steers a real 10x10 neutral-atom tweezer array through a calibration-strategy transition when standard feedback stalls.
- [Leveraging verifiable structure in quantum circuits to find more efficient compilations with agentic AI](https://arxiv.org/abs/2610.23832) — Google Quantum AI (Oct 16): AI agents compile quantum circuits more efficiently by restricting to bottleneck subroutines with classically-verifiable structure — a 2nd major-lab demonstration this week (alongside the Anthropic/Harvard circuit-discovery paper) that agentic AI finds genuinely better circuits.
- [Review Evaluates AI and Quantum Computing Paradigms for Adaptive Combinatorial Optimization](https://arxiv.org/abs/2610.11759) — Hoong Chuin Lau (Oct 13): a 119-paper survey mapping AI-for-Quantum-Optimization, Quantum-for-AI, and AI-Quantum Co-Optimization — a field-level map for placing a given AI/QC-optimization paper.
- [Magic state cultivation on a superconducting quantum processor](https://blog.google/innovation-and-ai/models-and-research/quantum-computing/magic-state-cultivation-quantum-computing) — Google Quantum AI, published in Science (Oct 15): the first physical hardware demonstration that magic-state cultivation works, cutting T-state error 40x and reaching 99.99% logical fidelity on Willow.
- [Bubble-Sort Exchange Networks: Symmetry Selection Rules and Language-Model Distillation on Exchange-Only Spin Chains (arXiv:2610.22093)](https://arxiv.org/abs/2610.22093) — Minato (Oct 15): distils GPT-2's own next-token distributions into a trainable quantum Born machine, beating a classical MPS baseline.
## Community pulse

_Unverified intake — community signals, not trend evidence._

- A Quantum Frontiers blog post on classical sampling from a quantum spin glass led directly to this run's dequantization capture-leak catch (now trend evidence, not just pulse).
- Hacker News's quantum coverage this weekend was dominated by Schrödinger-manuscript history pieces and routine business items — no new on-axis primary.
- r/QuantumComputing returned live content again, but only generic/evergreen feasibility-discussion threads — no new primary.
- Hugging Face's Daily Papers exploration lane surfaced no quantum-relevant items this run.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (25)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-10-26](reports/2026-10-26.md) · weekly: [2026-W43](reports/weekly/2026-W43.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

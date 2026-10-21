# AI Radar

![trends](https://img.shields.io/badge/trends-16-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-12-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-24-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--10--21-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-10-21):**
- [Quantum-advantage skepticism](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) crossed the 21-day dormancy line, but a dormancy probe turned up a genuine capture-leak catch instead — Pere's [pre-specified, budget-matched honest-baseline test across 27 datasets](https://arxiv.org/abs/2509.16410) becomes its 20th independent group.
- [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) cap-swaps in NVIDIA + Jülich's [104-qubit magic-state simulation on 8,192 GPUs](https://nvidia.github.io/cuda-quantum/blogs/blog/2026/10/19/jupiter-magic-state-simulation/), resolving yesterday's flagged candidate.
- A genuinely quiet arXiv day otherwise — watchlist moved 25 → 24 (1 promoted via cap-swap, nothing new cleared or missed the bar); see [watchlist](TRENDS.md#observation_queue).

## Trends

🌱 0 · 📈 4 · 🚀 12 · 🌊 0 · 🏔 0 · 📉 0 · 💤 0

| trend | stage | latest signal |
|-------|-------|---------------|
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-10-19](https://nvidia.github.io/cuda-quantum/blogs/blog/2026/10/19/jupiter-magic-state-simulation/) |
| [AI-for-quantum (circuit synthesis)](TRENDS.md#id-trend-012-ai-for-quantum-circuit-synthesis-leg-generativetransformer-models-that-directly-synthesize-quantum-circuits) | 🚀 accelerating | [2026-10-18](https://arxiv.org/abs/2610.25213) |
| [QML generalization theory](TRENDS.md#id-trend-007-qml-generalization-theory-bounds-phenomenology-and-the-reference-structure-requirement) | 🚀 accelerating | [2026-10-17](https://arxiv.org/abs/2610.24426) |
| [LLM/agentic quantum reasoning](TRENDS.md#id-trend-009-llmagentic-ai-reasoning-about-quantum-circuits-algorithms-and-proofs) | 🚀 accelerating | [2026-10-16](https://arxiv.org/abs/2610.23832) |
| [AI-for-quantum (hardware)](TRENDS.md#id-trend-002-ai-for-quantum-hardware-leg-classical-ml-for-quantum-hardware-control-calibration-decoding-and-circuit-design) | 🚀 accelerating | [2026-10-16](https://research.ibm.com/blog/open-agent-factories-and-distributed-inference-for-chip-design) |
| [Quantum-advantage frontier](TRENDS.md#id-trend-011-quantum-advantage-frontier-provable-learning-separations-and-honest-quantum-classical-crossovers) | 🚀 accelerating | [2026-10-16](https://arxiv.org/abs/2610.23268) |
| [Hamiltonian-parameter learning](TRENDS.md#id-trend-014-learning-hamiltonian-and-dissipative-rate-parameters-of-quantum-systems-from-data) | 🚀 accelerating | [2026-10-16](https://doi.org/10.1103/kjvf-jgqj) |
| [Quantum kernels & feature maps](TRENDS.md#id-trend-015-quantum-kernels--feature-maps-expressivity-encoding-budgets-and-application-scale-benchmarking) | 🚀 accelerating | [2026-10-16](https://arxiv.org/abs/2610.23692) |
| [Quantum transformers and attention](TRENDS.md#id-trend-016-quantum-transformers-and-attention-pqc-based-attention-mechanisms-for-sequence-and-signal-processing) | 🚀 accelerating | [2026-10-12](https://arxiv.org/abs/2610.17351) |
| [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) | 🚀 accelerating | [2026-10-10](https://arxiv.org/abs/2610.14454) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 🚀 accelerating | [2026-10-08](https://arxiv.org/abs/2610.11261) |
| [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) | 🚀 accelerating | [2026-10-07](https://arxiv.org/abs/2509.16410) |
| [QML/QEC security](TRENDS.md#id-trend-017-qmlqec-security-adversarial-attacks-on-and-defenses-for-quantum-classical-ml-components) | 📈 emerging | [2026-10-19](https://arxiv.org/abs/2610.26240) |
| [Agentic AI lab automation](TRENDS.md#id-trend-013-agentic-ai-directly-operating-quantum-hardware-and-lab-infrastructure-end-to-end) | 📈 emerging | [2026-10-18](https://arxiv.org/abs/2610.25014) |
| [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) | 📈 emerging | [2026-10-16](https://arxiv.org/abs/2610.23815) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 📈 emerging | [2026-10-05](https://arxiv.org/abs/2610.07196) |

## Worth studying

- [Does Data Complexity Predict Quantum Advantage? A framework, a pre-specified test, and an attribution of the measured edge (arXiv:2509.16410)](https://arxiv.org/abs/2509.16410) — Pere (v2, Oct 7; orig. Sep 2025): a pre-specified, budget-matched test across 27 datasets finds data complexity alone does not predict the quantum edge, and the apparent signal tracks classical-baseline weakness rather than a robust quantum contribution.
- [Advancing Fault-Tolerant Quantum Computing with GPU-Accelerated Simulation](https://nvidia.github.io/cuda-quantum/blogs/blog/2026/10/19/jupiter-magic-state-simulation/) — NVIDIA + Jülich (Oct 19): simulates magic-state preparation in a 104-qubit protocol using 8,192 GPUs on the JUPITER supercomputer, co-authored by Krysta Svore.
- [Large Language Model Steering of Acousto-Optic Tweezer Arrays (arXiv:2610.25014)](https://arxiv.org/abs/2610.25014) — Sheng et al. (Oct 18): a general-purpose LLM steers a real 10x10 neutral-atom tweezer array through a calibration-strategy transition when standard feedback stalls.
- [Leveraging verifiable structure in quantum circuits to find more efficient compilations with agentic AI](https://arxiv.org/abs/2610.23832) — Google Quantum AI (Oct 16): AI agents compile quantum circuits more efficiently by restricting to bottleneck subroutines with classically-verifiable structure — a 2nd major-lab demonstration this week (alongside the Anthropic/Harvard circuit-discovery paper) that agentic AI finds genuinely better circuits.
- [Review Evaluates AI and Quantum Computing Paradigms for Adaptive Combinatorial Optimization](https://arxiv.org/abs/2610.11759) — Hoong Chuin Lau (Oct 13): a 119-paper survey mapping AI-for-Quantum-Optimization, Quantum-for-AI, and AI-Quantum Co-Optimization — a field-level map for placing a given AI/QC-optimization paper.
- [Magic state cultivation on a superconducting quantum processor](https://blog.google/innovation-and-ai/models-and-research/quantum-computing/magic-state-cultivation-quantum-computing) — Google Quantum AI, published in Science (Oct 15): the first physical hardware demonstration that magic-state cultivation works, cutting T-state error 40x and reaching 99.99% logical fidelity on Willow.
- [Bubble-Sort Exchange Networks: Symmetry Selection Rules and Language-Model Distillation on Exchange-Only Spin Chains (arXiv:2610.22093)](https://arxiv.org/abs/2610.22093) — Minato (Oct 15): distils GPT-2's own next-token distributions into a trainable quantum Born machine, beating a classical MPS baseline.
- [From Minutes to Seconds: Faster Decoder Recalibration for Quantum Error Correction](https://www.riverlane.com/news/faster-decoder-recalibration-for-quantum-error-correction) — Riverlane (Oct 14): moves QEC decoder-weight recalibration's dominant cost onto a single NVIDIA H100, cutting one training epoch from ~3 minutes to 2.8 seconds.
- [Principles and Techniques for Agentic Research in Experimental Physics (arXiv:2610.17193)](https://arxiv.org/abs/2610.17193) — Reed, Daly, Beling, Giandrea (Oct 12): ten requirements plus a working framework for agentic AI in physics labs, validated across six case studies including quantum-control pulse design.
- [Quantum-Fisher-information-aware optimization yields a quantum reservoir advantage over tuned classical reservoirs (arXiv:2610.14454)](https://arxiv.org/abs/2610.14454) — Nguyen, Soh (Oct 10): a QFI-optimized driven Jaynes-Cummings reservoir beats a tuned echo-state network at every size from 4 to 30 trained weights on Mackey-Glass forecasting.
- [Xanadu Cuts Quantum Read-Only Memory Costs by ~4x via Dense Encoding](https://quantumcomputingreport.com/xanadu-cuts-quantum-read-only-memory-costs-by-4x-via-dense-encoding/) — Motlagh, Pocrnic (Xanadu): a dense Z/X-basis encoding cuts the Toffoli cost of QROM data-loading by ~3.9x (arXiv:2605.20334, 2610.02321).
- [How AgenticOS coordinates specialist scientific agents to build, test, and trace a quantum experiment](https://haiqu.ai/case-study/how-agenticos-coordinates-specialist-scientific-agents-to-build-test-and-trace-a-quantum-experiment-from-small-research-idea-to-result) — Haiqu (Oct 6): AgenticOS's structured workflow beats 10 ad hoc AI runs on a Zundel-cation honest-baseline benchmark (SQD within 3.4% of full-CI).

## Community pulse

_Unverified intake — community signals, not trend evidence._

- Hacker News's dated search surfaced only a QEC-breakeven explainer and a quantum-foundations piece this run — nothing on this radar's AI/quantum-ML axis.
- r/QuantumComputing returned live content again, but only generic/evergreen feasibility-discussion threads — no new primary.
- The Quantum Journal RSS carried a 2024 preprint newly published as a journal article (interactive proofs for verifying quantum learning) — a journal-publication update, not a new result.
- Hugging Face's Daily Papers exploration lane surfaced no quantum-relevant items this run.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (24)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-10-21](reports/2026-10-21.md) · weekly: [2026-W42](reports/weekly/2026-W42.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-15-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-7-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-28-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--09--23-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-09-23):**
- [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) cap-swapped in IonQ's [real-time MegaQuOp decoder](https://arxiv.org/abs/2608.25027), resolving a candidate flagged since late August after today's vendor publicity surfaced it.
- [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) and [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) each cap-swapped in a fresh real-hardware-adjacent result — [neural-network backflow](https://arxiv.org/abs/2609.26544) and an [ultra-low-power photonic reservoir chip](https://arxiv.org/abs/2609.24381).
- [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) resolved its standing [MerLin reproducibility-framework](https://arxiv.org/abs/2602.11092) candidate; [Hamiltonian-parameter learning](TRENDS.md#id-trend-014-learning-hamiltonian-and-dissipative-rate-parameters-of-quantum-systems-from-data) gained two new independent groups in one run.
- Observation queue: 5 additions, 3 drops (incl. 2 phantom-bullet hygiene fixes), net up to 28 (a touch over the ~25 cap).

## Trends

🌱 0 · 📈 8 · 🚀 7 · 🌊 0 · 🏔 0 · 📉 0 · 💤 0

| trend | stage | latest signal |
|-------|-------|---------------|
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-09-17](https://arxiv.org/abs/2609.20549) |
| [Quantum-advantage frontier](TRENDS.md#id-trend-011-quantum-advantage-frontier-provable-learning-separations-and-honest-quantum-classical-crossovers) | 🚀 accelerating | [2026-09-18](https://arxiv.org/abs/2609.21237) |
| [LLM/agentic quantum reasoning](TRENDS.md#id-trend-009-llmagentic-ai-reasoning-about-quantum-circuits-algorithms-and-proofs) | 🚀 accelerating | [2026-09-17](https://arxiv.org/abs/2609.19814) |
| [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) | 🚀 accelerating | [2026-09-21](https://arxiv.org/abs/2609.24381) |
| [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) | 🚀 accelerating | [2026-09-15](https://arxiv.org/abs/2609.17896) |
| [Quantum kernels & feature maps](TRENDS.md#id-trend-015-quantum-kernels--feature-maps-expressivity-encoding-budgets-and-application-scale-benchmarking) | 🚀 accelerating | [2026-09-11](https://arxiv.org/abs/2609.13360) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 🚀 accelerating | [2026-09-03](https://arxiv.org/abs/2609.04462) |
| [AI-for-quantum (circuit synthesis)](TRENDS.md#id-trend-012-ai-for-quantum-circuit-synthesis-leg-generativetransformer-models-that-directly-synthesize-quantum-circuits) | 📈 emerging | [2026-09-22](https://arxiv.org/abs/2609.25947) |
| [Hamiltonian-parameter learning](TRENDS.md#id-trend-014-learning-hamiltonian-and-dissipative-rate-parameters-of-quantum-systems-from-data) | 📈 emerging | [2026-09-22](https://arxiv.org/abs/2609.26596) |
| [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) | 📈 emerging | [2026-09-22](https://arxiv.org/abs/2609.26544) |
| [QML generalization theory](TRENDS.md#id-trend-007-qml-generalization-theory-bounds-phenomenology-and-the-reference-structure-requirement) | 📈 emerging | [2026-09-21](https://arxiv.org/abs/2609.24666) |
| [Quantum transformers and attention](TRENDS.md#id-trend-016-quantum-transformers-and-attention-pqc-based-attention-mechanisms-for-sequence-and-signal-processing) | 📈 emerging | [2026-09-19](https://arxiv.org/abs/2609.23016) |
| [AI-for-quantum (hardware)](TRENDS.md#id-trend-002-ai-for-quantum-hardware-leg-classical-ml-for-quantum-hardware-control-calibration-decoding-and-circuit-design) | 📈 emerging | [2026-09-10](https://arxiv.org/abs/2609.12020) |
| [Agentic AI lab automation](TRENDS.md#id-trend-013-agentic-ai-directly-operating-quantum-hardware-and-lab-infrastructure-end-to-end) | 📈 emerging | [2026-09-08](https://openai.com/index/codex-quantum-computing-experiments/) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 📈 emerging | [2026-09-05](https://arxiv.org/abs/2609.06307) |

## Worth studying

- [In-orbit operation of a programmable quantum photonic processor (arXiv:2609.25248)](https://arxiv.org/abs/2609.25248) — a European team (Sep 21): the first quantum computational resource operated in space — a programmable six-mode integrated photonic circuit on a nanosatellite, demonstrating two-photon interference after surviving launch, thermal drift and radiation.
- [Quasar 1.1 438B, the first AI model using quantum-generated data](https://multiversecomputing.com/resources/quasar-1-1-438b-the-first-ai-model-using-quantum-generated-data) — Multiverse Computing (Sep 15): rebuilds a flagship coding model using a healing dataset partly generated by a hybrid quantum LLM — 1/6 of the base model's transformer layers replaced with a QNN, run on IBM Quantum System Two's 156-qubit Heron r2 processor.
- [Hybrid quantum-classical attention for histopathology-based molecular profiling in data-limited cancers (arXiv:2609.21115)](https://arxiv.org/abs/2609.21115) — Rhrissorrakrai, Bose, Guzman-Saenz, Utro, Pardia (IBM Research): replaces softmax attention with a quantum-derived doubly stochastic matrix for histopathology-based gene-expression prediction, evaluated across 29 TCGA cancer cohorts plus an independent pancreatic-cancer cohort.
- [MerLin: A Discovery Engine for Photonic and Hybrid Quantum Machine Learning (arXiv:2602.11092)](https://arxiv.org/abs/2602.11092) — Notton, Stott, Schoeb, Walsh, Leboucher et al. (Quandela; posted Feb-2026): introduces MerLin and, as its flagship contribution, systematically reproduces eighteen state-of-the-art photonic/hybrid QML papers as reusable, standardized-baseline experiments — a rare field-wide reproducibility initiative any QML researcher can check a new claim against.
- [Temporal information processing on a 4,500-qubit quantum annealer (arXiv:2609.19308)](https://arxiv.org/abs/2609.19308) — Sannia, Menta, Sathe, De Santis, Giovannetti et al. (Sep 16): a quantum-reservoir-computing model on a superconducting quantum annealer processes temporal data using up to 4,500 qubits — the largest quantum-ML experiment to date — and forecasts chaotic time series on real hardware.
- [Securing quantum error correction against misleading advice from AI agents (arXiv:2609.19090)](https://arxiv.org/abs/2609.19090) — Özgüler (Sep 16): identifies that opposite coherent-rotation errors can produce identical syndrome-history distributions — an ambiguity a misleading AI adviser could exploit — then shows extra calibration measurements support certified, ambiguity-resistant recovery under drift.
- [QEMScore: How Much Does the Measurement Add to Learned Quantum Error Mitigation? (arXiv:2609.17896)](https://arxiv.org/abs/2609.17896) — Zhao, Gu, Dong (Sep 15): scores a learned quantum-error-mitigation model beside a capacity-matched control that never sees the actual measurement, then reanalyzes two published learned-QEM methods with this comparison.
- [Do Quantum AIs Dream in Paths? Path-Integral Slow Thinking through Grover Interference (arXiv:2609.05842)](https://arxiv.org/abs/2609.05842) — Cai, Deng, Chen (Sep 4): reframes LLM-style "slow thinking" as coherent path-integral dynamics — an exact verifier splits reasoning trajectories into accepted/rejected components that interfere under Grover amplitude amplification, avoiding the policy-collapse failure mode of classical RLVR training.
- [Proving olympiad geometry theorems on a superconducting quantum processor (arXiv:2609.14533)](https://arxiv.org/abs/2609.14533) — Wang, Sun, Cui, Zou, Zhang et al., Dong-Ling Deng's group (Sep 13): implements quantum pseudo-division algebraic elimination AND a hybrid quantum-strategy-guided backward-reasoning search to experimentally prove two geometry theorems, including a 1978 IMO problem, on a real superconducting processor.
- [Quantum neural network equipped with backpropagation on a qudit processor (arXiv:2609.12500)](https://arxiv.org/abs/2609.12500) — Yuan, Xu, Du, Zhao, Cheng, Li, Hou, Zhou, Li, Lin (Sep 11): an experimental qudit-based QNN trained via backpropagation on a real trapped-ion (⁴⁰Ca⁺) processor, exploiting qudits' larger per-unit Hilbert space for more expressive QNNs at fixed processor size.
- [Reinforcement Learning for Syndrome Extraction (arXiv:2609.12020)](https://arxiv.org/abs/2609.12020) — Ye, Pabla, Palsberg (Sep 10): RL plus importance sampling searches the exponentially large space of syndrome-extraction circuit implementations for QEC, outperforming prior search methods at every scale tested.
- [From Python to hardware: real-time classical co-processing with PennyLane, Backline, and AMD](https://pennylane.ai/blog/2026/09/real-time-classical-processing-with-backline-amd) — Xanadu + AMD (Sep 10): Backline, an open-source heterogeneous compilation fabric built into PennyLane's Catalyst compiler, dynamically routes quantum-classical workloads — including the microsecond-scale real-time feedback loops fault-tolerant QEC needs — to CPUs, GPUs, FPGAs and ASICs.

## Community pulse

_Unverified intake — community signals, not trend evidence._

- r/QuantumComputing was unreachable this run (a tool-level quota outage, not a subreddit-specific issue) — no pulse sampled.
- Hacker News's front page and quantum-tagged search surfaced routine funding/business items; no new technical primary beyond what the primary sweep already found.
- Digest coverage (Quantum Computing Report, Quantum Insider, Quantum Zeitgeist) converged on the same IonQ real-time-decoder story now captured as trend evidence, plus routine partnership/personnel items.
- A previously-staged vendor domain (Multiverse Computing) posted again this run but off-axis; its on-axis tally stays unchanged, still below the promotion bar.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (28)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-09-23](reports/2026-09-23.md) · weekly: [2026-W38](reports/weekly/2026-W38.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

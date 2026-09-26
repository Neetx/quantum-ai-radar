# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-16-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-11-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-24-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--09--26-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-09-26):**
- [AI-for-quantum (circuit synthesis)](TRENDS.md#id-trend-012-ai-for-quantum-circuit-synthesis-leg-generativetransformer-models-that-directly-synthesize-quantum-circuits) promoted to accelerating (confidence raised to high) — 4 fresh independent groups landed within two weeks, most recently [Bridge of Ψ's generative circuit optimization](https://arxiv.org/abs/2609.25947).
- [Hamiltonian-parameter learning](TRENDS.md#id-trend-014-learning-hamiltonian-and-dissipative-rate-parameters-of-quantum-systems-from-data) promoted to accelerating (confidence raised to medium) — 5 of its 8 groups arrived within a single week, most recently [quantum score matching for thermal states](https://arxiv.org/abs/2609.28391).
- [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) and [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) both moved to dormant after 21+ days without a fresh independent group.
- Observation queue: 1 drop (a stale AI-for-quantum revival watch superseded by that trend's own promotion), 25 → 24.

## Trends

🌱 1 · 📈 2 · 🚀 11 · 🌊 0 · 🏔 0 · 📉 0 · 💤 2

| trend | stage | latest signal |
|-------|-------|---------------|
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-09-24](https://infleqtion.com/demonstration-of-30-logical-qubits-on-sqale/) |
| [AI-for-quantum (hardware)](TRENDS.md#id-trend-002-ai-for-quantum-hardware-leg-classical-ml-for-quantum-hardware-control-calibration-decoding-and-circuit-design) | 🚀 accelerating | [2026-09-24](https://qc.design/meridian/white-paper) |
| [Quantum transformers and attention](TRENDS.md#id-trend-016-quantum-transformers-and-attention-pqc-based-attention-mechanisms-for-sequence-and-signal-processing) | 🚀 accelerating | [2026-09-24](https://arxiv.org/abs/2602.06699) |
| [Hamiltonian-parameter learning](TRENDS.md#id-trend-014-learning-hamiltonian-and-dissipative-rate-parameters-of-quantum-systems-from-data) | 🚀 accelerating | [2026-09-23](https://arxiv.org/abs/2609.28391) |
| [QML generalization theory](TRENDS.md#id-trend-007-qml-generalization-theory-bounds-phenomenology-and-the-reference-structure-requirement) | 🚀 accelerating | [2026-09-22](http://link.aps.org/doi/10.1103/8k5v-ddtw) |
| [AI-for-quantum (circuit synthesis)](TRENDS.md#id-trend-012-ai-for-quantum-circuit-synthesis-leg-generativetransformer-models-that-directly-synthesize-quantum-circuits) | 🚀 accelerating | [2026-09-22](https://arxiv.org/abs/2609.25947) |
| [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) | 🚀 accelerating | [2026-09-21](https://arxiv.org/abs/2609.24381) |
| [Quantum-advantage frontier](TRENDS.md#id-trend-011-quantum-advantage-frontier-provable-learning-separations-and-honest-quantum-classical-crossovers) | 🚀 accelerating | [2026-09-18](https://arxiv.org/abs/2609.21237) |
| [LLM/agentic quantum reasoning](TRENDS.md#id-trend-009-llmagentic-ai-reasoning-about-quantum-circuits-algorithms-and-proofs) | 🚀 accelerating | [2026-09-17](https://arxiv.org/abs/2609.19814) |
| [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) | 🚀 accelerating | [2026-09-15](https://arxiv.org/abs/2609.17896) |
| [Quantum kernels & feature maps](TRENDS.md#id-trend-015-quantum-kernels--feature-maps-expressivity-encoding-budgets-and-application-scale-benchmarking) | 🚀 accelerating | [2026-09-11](https://arxiv.org/abs/2609.13360) |
| [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) | 📈 emerging | [2026-09-22](https://arxiv.org/abs/2609.26544) |
| [Agentic AI lab automation](TRENDS.md#id-trend-013-agentic-ai-directly-operating-quantum-hardware-and-lab-infrastructure-end-to-end) | 📈 emerging | [2026-09-08](https://openai.com/index/codex-quantum-computing-experiments/) |
| [QML/QEC security](TRENDS.md#id-trend-017-qmlqec-security-adversarial-attacks-on-and-defenses-for-quantum-classical-ml-components) | 🌱 seed | [2026-09-16](https://arxiv.org/abs/2609.19090) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 💤 dormant | [2026-09-05](https://arxiv.org/abs/2609.06307) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 💤 dormant | [2026-09-03](https://arxiv.org/abs/2609.04462) |

## Worth studying

- [Demonstration of 30 logical qubits on Sqale](https://infleqtion.com/demonstration-of-30-logical-qubits-on-sqale/) — Gokhale/Infleqtion (Sep 24): 30 entangled logical qubits on 80 physical qubits on Infleqtion's neutral-atom Sqale QPU, achieved in part via a GPT-5.6 Sol LLM agent's discovery of a new double-CZ logical gate halving physical two-qubit-gate overhead.
- [Kirkwood–Dirac Nonpositivity Is a Necessary Resource for Quantum Computing (DOI 10.1103/x819-898d)](https://doi.org/10.1103/x819-898d) — Thio, Yang, Yunger Halpern, De Bièvre, Barnes, Arvidsson-Shukur (Phys. Rev. Lett., Aug 18): proves that beyond "magic," Kirkwood-Dirac nonpositivity is also a necessary resource for computational advantage on qubit-based quantum computers.
- [Decoder-Prior Poisoning in Quantum Error Correction: Attacks and PriorGuard Defense (arXiv:2609.27805)](https://arxiv.org/abs/2609.27805) — Li, Peng, Chen, Wang (Aug 18, backlog catch): identifies the prior-update path of calibration-aware surface-code decoders as an overlooked integrity-critical attack surface and proposes a PriorGuard defense.
- [Universal Sample Complexity Bounds in Quantum Learning Theory via Fisher Information Matrix (DOI 10.1103/8k5v-ddtw)](http://link.aps.org/doi/10.1103/8k5v-ddtw) — Kwon, Lie, Jiang (PRX Quantum, Sep 22): a general, peer-reviewed framework showing the sample complexity of quantum learning is governed by the inverse Fisher information matrix.
- [In-orbit operation of a programmable quantum photonic processor (arXiv:2609.25248)](https://arxiv.org/abs/2609.25248) — a European team (Sep 21): the first quantum computational resource operated in space — a programmable six-mode integrated photonic circuit on a nanosatellite.
- [Quasar 1.1 438B, the first AI model using quantum-generated data](https://multiversecomputing.com/resources/quasar-1-1-438b-the-first-ai-model-using-quantum-generated-data) — Multiverse Computing (Sep 15): rebuilds a flagship coding model using a healing dataset partly generated by a hybrid quantum LLM.
- [Hybrid quantum-classical attention for histopathology-based molecular profiling in data-limited cancers (arXiv:2609.21115)](https://arxiv.org/abs/2609.21115) — Rhrissorrakrai, Bose, Guzman-Saenz, Utro, Pardia (IBM Research): replaces softmax attention with a quantum-derived doubly stochastic matrix, evaluated across 29 TCGA cancer cohorts.
- [MerLin: A Discovery Engine for Photonic and Hybrid Quantum Machine Learning (arXiv:2602.11092)](https://arxiv.org/abs/2602.11092) — Notton, Stott, Schoeb, Walsh, Leboucher et al. (Quandela): reproduces eighteen state-of-the-art photonic/hybrid QML papers as reusable, standardized-baseline experiments.
- [Temporal information processing on a 4,500-qubit quantum annealer (arXiv:2609.19308)](https://arxiv.org/abs/2609.19308) — Sannia, Menta, Sathe, De Santis, Giovannetti et al. (Sep 16): a quantum-reservoir-computing model processes temporal data using up to 4,500 qubits — the largest quantum-ML experiment to date.
- [QEMScore: How Much Does the Measurement Add to Learned Quantum Error Mitigation? (arXiv:2609.17896)](https://arxiv.org/abs/2609.17896) — Zhao, Gu, Dong (Sep 15): scores a learned quantum-error-mitigation model beside a capacity-matched control that never sees the actual measurement.
- [Do Quantum AIs Dream in Paths? Path-Integral Slow Thinking through Grover Interference (arXiv:2609.05842)](https://arxiv.org/abs/2609.05842) — Cai, Deng, Chen (Sep 4): reframes LLM-style "slow thinking" as coherent path-integral dynamics under Grover amplitude amplification.
- [Proving olympiad geometry theorems on a superconducting quantum processor (arXiv:2609.14533)](https://arxiv.org/abs/2609.14533) — Wang, Sun, Cui, Zou, Zhang et al., Dong-Ling Deng's group (Sep 13): experimentally proves two geometry theorems, including a 1978 IMO problem, on a real superconducting processor.
- [Quantum neural network equipped with backpropagation on a qudit processor (arXiv:2609.12500)](https://arxiv.org/abs/2609.12500) — Yuan, Xu, Du, Zhao, Cheng, Li, Hou, Zhou, Li, Lin (Sep 11): an experimental qudit-based QNN trained via backpropagation on a real trapped-ion processor.

## Community pulse

_Unverified intake — community signals, not trend evidence._

- r/QuantumComputing was unreachable for a 3rd/4th consecutive run (a tool-level quota outage confirmed this week to have no working fallback, not a subreddit-specific issue) — no pulse sampled.
- Quantum Computing Stack Exchange's Atom feed also failed to fetch this week — a new degradation, first occurrence.
- Digest coverage (The Quantum Insider, Quantum Zeitgeist) surfaced this week's newly-discovered AI-for-QEC-design vendor plus routine partnership/business items.
- Hacker News's front page surfaced no on-axis technical items in this week's checks.
- Hugging Face's Daily Papers exploration lane surfaced no quantum-relevant items this week.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (24)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-09-25](reports/2026-09-25.md) · weekly: [2026-W39](reports/weekly/2026-W39.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

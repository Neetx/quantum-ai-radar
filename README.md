# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-16-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-12-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-24-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--09--30-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-09-30):**
- [Quantum kernels & feature maps](TRENDS.md#id-trend-015-quantum-kernels--feature-maps-expressivity-encoding-budgets-and-application-scale-benchmarking) revived from an 18-day quiet stretch with an 8th independent group — [SQUARE](https://arxiv.org/abs/2609.37134), a quantum feature-map adapter for frozen LLMs.
- [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) gained a 14th independent group — [foundation NQS for molecular potential energy surfaces](https://arxiv.org/abs/2609.37733), cutting per-geometry cost 986x.
- [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) gained a 15th independent group — a newly peer-reviewed [photonic quantum-memristor neuromorphic architecture](https://arxiv.org/abs/2504.18694).
- Notable off-ledger find: an independent, non-vendor [random-circuit-sampling benchmark of IBM's new Nighthawk r2 chip](https://arxiv.org/abs/2609.28657), read with due hype-skepticism. Observation queue: 1 promoted, 8 dropped, 9 added — holding steady at 24.

## Trends

🌱 1 · 📈 2 · 🚀 12 · 🌊 0 · 🏔 0 · 📉 0 · 💤 1

| trend | stage | latest signal |
|-------|-------|---------------|
| [AI-for-quantum (hardware)](TRENDS.md#id-trend-002-ai-for-quantum-hardware-leg-classical-ml-for-quantum-hardware-control-calibration-decoding-and-circuit-design) | 🚀 accelerating | [2026-09-29](https://arxiv.org/abs/2604.18734) |
| [Quantum transformers and attention](TRENDS.md#id-trend-016-quantum-transformers-and-attention-pqc-based-attention-mechanisms-for-sequence-and-signal-processing) | 🚀 accelerating | [2026-09-29](https://arxiv.org/abs/2606.00045) |
| [Quantum kernels & feature maps](TRENDS.md#id-trend-015-quantum-kernels--feature-maps-expressivity-encoding-budgets-and-application-scale-benchmarking) | 🚀 accelerating | [2026-09-29](https://arxiv.org/abs/2609.37134) |
| [Hamiltonian-parameter learning](TRENDS.md#id-trend-014-learning-hamiltonian-and-dissipative-rate-parameters-of-quantum-systems-from-data) | 🚀 accelerating | [2026-09-28](https://arxiv.org/abs/2609.34995) |
| [LLM/agentic quantum reasoning](TRENDS.md#id-trend-009-llmagentic-ai-reasoning-about-quantum-circuits-algorithms-and-proofs) | 🚀 accelerating | [2026-09-27](https://arxiv.org/abs/2609.33192) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 🚀 accelerating | [2026-09-25](https://arxiv.org/abs/2609.31066) |
| [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) | 🚀 accelerating | [2026-09-25](https://arxiv.org/abs/2504.18694) |
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-09-24](https://infleqtion.com/demonstration-of-30-logical-qubits-on-sqale/) |
| [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) | 🚀 accelerating | [2026-09-22](https://arxiv.org/abs/2609.26705) |
| [QML generalization theory](TRENDS.md#id-trend-007-qml-generalization-theory-bounds-phenomenology-and-the-reference-structure-requirement) | 🚀 accelerating | [2026-09-22](http://link.aps.org/doi/10.1103/8k5v-ddtw) |
| [AI-for-quantum (circuit synthesis)](TRENDS.md#id-trend-012-ai-for-quantum-circuit-synthesis-leg-generativetransformer-models-that-directly-synthesize-quantum-circuits) | 🚀 accelerating | [2026-09-22](https://arxiv.org/abs/2609.25947) |
| [Quantum-advantage frontier](TRENDS.md#id-trend-011-quantum-advantage-frontier-provable-learning-separations-and-honest-quantum-classical-crossovers) | 🚀 accelerating | [2026-09-18](https://arxiv.org/abs/2609.21237) |
| [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) | 📈 emerging | [2026-09-29](https://arxiv.org/abs/2609.37733) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 📈 emerging | [2026-09-25](https://arxiv.org/abs/2609.31070) |
| [QML/QEC security](TRENDS.md#id-trend-017-qmlqec-security-adversarial-attacks-on-and-defenses-for-quantum-classical-ml-components) | 🌱 seed | [2026-09-16](https://arxiv.org/abs/2609.19090) |
| [Agentic AI lab automation](TRENDS.md#id-trend-013-agentic-ai-directly-operating-quantum-hardware-and-lab-infrastructure-end-to-end) | 💤 dormant | [2026-09-08](https://openai.com/index/codex-quantum-computing-experiments/) |

## Worth studying

- [SQUARE: Structured Quantum Representation Adapters as Compact Quadratic Feature Maps for Frozen Language Models (arXiv:2609.37134)](https://arxiv.org/abs/2609.37134) — Roh, Ahn, Lee, Park, Yoon, Aggarwal, Kim (Sep 29): a quantum circuit directly adapts a frozen classical LLM's bottleneck features, beating an MLP and other classical baselines on GLUE-derived interaction tasks.
- [Forward random-circuit sampling on IBM Quantum Nighthawk r2 (arXiv:2609.28657)](https://arxiv.org/abs/2609.28657) — Sedrakyan, Zhang, Karapetyan, Baktay, Gharibyan, Tepanyan (Sep 23): a rare independent, non-IBM benchmark of IBM's brand-new hardware, honest that its classical-cost figure is a tensor-network estimate under stated favorable assumptions.
- [When are bosonic Gaussian states classical to learn? (arXiv:2609.26705)](https://arxiv.org/abs/2609.26705) — Chen, A. A. Mele, F. A. Mele, Preskill (Sep 22): cold Gaussian states are provably hard to learn even with limited entanglement, while warm ones become exactly as easy to learn as a classical Gaussian distribution.
- [AG-CoT: Verified Algorithmic Traces for LLM Program Synthesis on Clifford Circuits (arXiv:2609.33192)](https://arxiv.org/abs/2609.33192) — Wei, Wang, Cao, Pang, Ling (Sep 27): trains LLMs to synthesize Clifford/stabilizer circuits supervised by an exact classical verifier rather than post-hoc review.
- [Experimental neuromorphic computing based on quantum memristor (arXiv:2504.18694 / PRX Quantum)](https://arxiv.org/abs/2504.18694) — Selimović, Agresti, Siemaszko et al. (orig. 2025, published PRX Quantum Sep 25): the first neuromorphic architecture based on a photonic quantum memristor, using memristive feedback to supply nonlinearity without entangling gates.
- [Encryptability As a Coordinate Choice: Depth-One Homomorphic Federated Learning of Quantum Neural Networks (arXiv:2609.30581)](https://arxiv.org/abs/2609.30581) — Mordarski, Mani, Patel, Knottenbelt, Bondesan (Sep 24): a coordinate-choice trick cuts encrypted federated-QNN training cost from ~25,000 operations per gate to one multiplicative level.
- [Demonstration of 30 logical qubits on Sqale](https://infleqtion.com/demonstration-of-30-logical-qubits-on-sqale/) — Gokhale/Infleqtion (Sep 24): 30 entangled logical qubits on 80 physical qubits, achieved in part via a GPT-5.6 Sol LLM agent's discovery of a new double-CZ logical gate.
- [Kirkwood–Dirac Nonpositivity Is a Necessary Resource for Quantum Computing (DOI 10.1103/x819-898d)](https://doi.org/10.1103/x819-898d) — Thio, Yang, Yunger Halpern, De Bièvre, Barnes, Arvidsson-Shukur (Phys. Rev. Lett., Aug 18): a second necessary resource (alongside magic) for computational advantage on qubit-based quantum computers.
- [Decoder-Prior Poisoning in Quantum Error Correction: Attacks and PriorGuard Defense (arXiv:2609.27805)](https://arxiv.org/abs/2609.27805) — Li, Peng, Chen, Wang (Aug 18, backlog catch): identifies the prior-update path of calibration-aware surface-code decoders as an overlooked integrity-critical attack surface.
- [Universal Sample Complexity Bounds in Quantum Learning Theory via Fisher Information Matrix (DOI 10.1103/8k5v-ddtw)](http://link.aps.org/doi/10.1103/8k5v-ddtw) — Kwon, Lie, Jiang (PRX Quantum, Sep 22): a general, peer-reviewed framework showing quantum-learning sample complexity is governed by the inverse Fisher information matrix.
- [In-orbit operation of a programmable quantum photonic processor (arXiv:2609.25248)](https://arxiv.org/abs/2609.25248) — a European team (Sep 21): the first quantum computational resource operated in space, on a nanosatellite.
- [Temporal information processing on a 4,500-qubit quantum annealer (arXiv:2609.19308)](https://arxiv.org/abs/2609.19308) — Sannia, Menta, Sathe, De Santis, Giovannetti et al. (Sep 16): a quantum-reservoir-computing model processes temporal data using up to 4,500 qubits — the largest quantum-ML experiment to date.

## Community pulse

_Unverified intake — community signals, not trend evidence._

- r/QuantumComputing remained unreachable this scan (a confirmed tool-level quota outage with no working fallback, now an 8th consecutive day) — no pulse sampled.
- Quantum Computing Stack Exchange's Atom feed opened normally — routine Q&A activity, nothing rising to a trend signal.
- Digest coverage (The Quantum Insider, Quantum Computing Report, Quantum Zeitgeist) surfaced only routine partnership/business items this scan.
- Hacker News surfaced the independent IBM-hardware RCS benchmark noted above, plus a classical-math story and routine policy items — otherwise nothing new on-axis.
- Hugging Face's Daily Papers exploration lane surfaced no quantum-relevant items this scan.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (24)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-09-30](reports/2026-09-30.md) · weekly: [2026-W39](reports/weekly/2026-W39.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-15-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-7-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-30-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--09--17-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-09-17, daily):**
- New trend: a 3-independent-group convergence on building the Transformer's attention mechanism itself out of quantum circuits — [Quantum transformers and attention](TRENDS.md#id-trend-016-quantum-transformers-and-attention-pqc-based-attention-mechanisms-for-sequence-and-signal-processing), created `seed`, spanning sentiment classification, fast-radio-burst detection and [language generation](https://arxiv.org/abs/2609.18565).
- [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) gained a 13th independent group extending dequantization to reinforcement learning: [Towards Surrogate Based Dequantization of Quantum Reinforcement Learning](https://arxiv.org/abs/2609.16266).
- A novel angle at the AI/quantum intersection, new study pick: [Securing quantum error correction against misleading advice from AI agents](https://arxiv.org/abs/2609.19090) — not AI improving QEC, but keeping QEC trustworthy when an AI agent is the one advising it.
- arXiv's query API reverted to the primary new-submissions method after 2 consecutive confirmed recoveries — see [SOURCES.md](SOURCES.md).

## Trends

🌱 2 · 📈 6 · 🚀 7 · 🌊 0 · 🏔 0 · 📉 0 · 💤 0

| trend | stage | latest signal |
|-------|-------|---------------|
| [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) | 🚀 accelerating | [2026-09-14](https://arxiv.org/abs/2609.16266) |
| [Quantum kernels & feature maps](TRENDS.md#id-trend-015-quantum-kernels--feature-maps-expressivity-encoding-budgets-and-application-scale-benchmarking) | 🚀 accelerating | [2026-09-11](https://arxiv.org/abs/2609.13360) |
| [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) | 🚀 accelerating | [2026-09-10](https://arxiv.org/abs/2609.11071) |
| [LLM/agentic quantum reasoning](TRENDS.md#id-trend-009-llmagentic-ai-reasoning-about-quantum-circuits-algorithms-and-proofs) | 🚀 accelerating | [2026-09-08](https://arxiv.org/abs/2609.09582) |
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-09-03](https://arxiv.org/abs/2609.03194) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 🚀 accelerating | [2026-09-03](https://arxiv.org/abs/2609.04462) |
| [Quantum-advantage frontier](TRENDS.md#id-trend-011-quantum-advantage-frontier-provable-learning-separations-and-honest-quantum-classical-crossovers) | 🚀 accelerating | [2026-08-25](https://arxiv.org/abs/2608.24527) |
| [QML generalization theory](TRENDS.md#id-trend-007-qml-generalization-theory-bounds-phenomenology-and-the-reference-structure-requirement) | 📈 emerging | [2026-09-13](https://arxiv.org/abs/2609.14424) |
| [AI-for-quantum (hardware)](TRENDS.md#id-trend-002-ai-for-quantum-hardware-leg-classical-ml-for-quantum-hardware-control-calibration-decoding-and-circuit-design) | 📈 emerging | [2026-09-10](https://arxiv.org/abs/2609.12020) |
| [AI-for-quantum (circuit synthesis)](TRENDS.md#id-trend-012-ai-for-quantum-circuit-synthesis-leg-generativetransformer-models-that-directly-synthesize-quantum-circuits) | 📈 emerging | [2026-09-10](https://arxiv.org/abs/2609.11248) |
| [Agentic AI lab automation](TRENDS.md#id-trend-013-agentic-ai-directly-operating-quantum-hardware-and-lab-infrastructure-end-to-end) | 📈 emerging | [2026-09-08](https://openai.com/index/codex-quantum-computing-experiments/) |
| [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) | 📈 emerging | [2026-09-07](https://arxiv.org/abs/2609.07645) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 📈 emerging | [2026-09-05](https://arxiv.org/abs/2609.06307) |
| [Quantum transformers and attention](TRENDS.md#id-trend-016-quantum-transformers-and-attention-pqc-based-attention-mechanisms-for-sequence-and-signal-processing) | 🌱 seed | [2026-09-16](https://arxiv.org/abs/2609.18565) |
| [Hamiltonian-parameter learning](TRENDS.md#id-trend-014-learning-hamiltonian-and-dissipative-rate-parameters-of-quantum-systems-from-data) | 🌱 seed | [2026-08-27](https://arxiv.org/abs/2608.29302) |

## Worth studying

- [Securing quantum error correction against misleading advice from AI agents (arXiv:2609.19090)](https://arxiv.org/abs/2609.19090) — Özgüler (Sep 16): identifies that opposite coherent-rotation errors can produce identical syndrome-history distributions — an ambiguity a misleading AI adviser could exploit — then shows extra calibration measurements support certified, ambiguity-resistant recovery under drift.
- [QEMScore: How Much Does the Measurement Add to Learned Quantum Error Mitigation? (arXiv:2609.17896)](https://arxiv.org/abs/2609.17896) — Zhao, Gu, Dong (Sep 15): scores a learned quantum-error-mitigation model beside a capacity-matched control that never sees the actual measurement, then reanalyzes two published learned-QEM methods with this comparison.
- [Do Quantum AIs Dream in Paths? Path-Integral Slow Thinking through Grover Interference (arXiv:2609.05842)](https://arxiv.org/abs/2609.05842) — Cai, Deng, Chen (Sep 4): reframes LLM-style "slow thinking" as coherent path-integral dynamics — an exact verifier splits reasoning trajectories into accepted/rejected components that interfere under Grover amplitude amplification, avoiding the policy-collapse failure mode of classical RLVR training.
- [Proving olympiad geometry theorems on a superconducting quantum processor (arXiv:2609.14533)](https://arxiv.org/abs/2609.14533) — Wang, Sun, Cui, Zou, Zhang et al., Dong-Ling Deng's group (Sep 13): implements quantum pseudo-division algebraic elimination AND a hybrid quantum-strategy-guided backward-reasoning search to experimentally prove two geometry theorems, including a 1978 IMO problem, on a real superconducting processor.
- [Quantum neural network equipped with backpropagation on a qudit processor (arXiv:2609.12500)](https://arxiv.org/abs/2609.12500) — Yuan, Xu, Du, Zhao, Cheng, Li, Hou, Zhou, Li, Lin (Sep 11): an experimental qudit-based QNN trained via backpropagation on a real trapped-ion (⁴⁰Ca⁺) processor, exploiting qudits' larger per-unit Hilbert space for more expressive QNNs at fixed processor size.
- [Reinforcement Learning for Syndrome Extraction (arXiv:2609.12020)](https://arxiv.org/abs/2609.12020) — Ye, Pabla, Palsberg (Sep 10): RL plus importance sampling searches the exponentially large space of syndrome-extraction circuit implementations for QEC, outperforming prior search methods at every scale tested.
- [From Python to hardware: real-time classical co-processing with PennyLane, Backline, and AMD](https://pennylane.ai/blog/2026/09/real-time-classical-processing-with-backline-amd) — Xanadu + AMD (Sep 10): Backline, an open-source heterogeneous compilation fabric built into PennyLane's Catalyst compiler, dynamically routes quantum-classical workloads — including the microsecond-scale real-time feedback loops fault-tolerant QEC needs — to CPUs, GPUs, FPGAs and ASICs.
- [The cost of simulating classically tractable quantum circuits and dynamics (arXiv:2609.11847)](https://arxiv.org/abs/2609.11847) — Chang, Thanasilp, Holmes, Cerezo (Sep 10): distinguishes asymptotic polynomial-time classical simulability from PRACTICAL classical cost, showing expensive preprocessing or quantum-data-acquisition overheads can make a "classically simulable" quantum evolution not actually cheaper to simulate than to run quantumly.
- [How GPT-5.6 Sol helps run quantum computing experiments](https://openai.com/index/codex-quantum-computing-experiments/) — OpenAI (Sep 8): an MIT graduate student connects GPT-5.6 Sol, harnessed to Codex, directly to lab software controlling a six-qubit superconducting chip, letting the agent autonomously run calibration/measurement sequences and decide what to try next.
- [The First Full-Stack Blueprint for Breaking 256-Bit Elliptic Curve Signatures](https://ionq.com/blog/the-first-full-stack-blueprint-for-breaking-256-bit-elliptic-curve-signatures) — IonQ (Sep 8): a 70-page resource estimate compiles Shor's algorithm for secp256k1 down to QEC primitives on a specialized trapped-ion architecture, cutting the qubit count needed from 1.2M+ to ~19,397 — read as a 2028-roadmap projection, not an achieved break.
- [Bottom-Up Design of Quantum Optical Experiments Using Discrete Generative Models (arXiv:2609.08073)](https://arxiv.org/abs/2609.08073) — Huidobro-Meezs, Paiva-Ortega, Vargas-Hernández (Sep 8): a reward-driven generative framework (Grinch) learns to sample optical-circuit graphs for target quantum states directly from fidelity-based rewards, with no pre-existing training dataset.
- [Geometric inflation of deviations challenges neural quantum states in dynamics of quantum Ising models (arXiv:2609.07645)](https://arxiv.org/abs/2609.07645) — Krinitsin, Rigo, Abedi, Schmitt (Sep 7): a controlled quench-dynamics benchmark shows accurate NQS dynamics simulation is surprisingly hard even in regimes of limited physical complexity, tightening prior parameter-count assumptions.

## Community pulse

_Unverified intake — community signals, not trend evidence._

- Hacker News's front page carried mostly post-quantum-cryptography and general-science items this run; a personal engineering blog's honest null-result for quantum circuits inside physics-informed neural networks drew attention but isn't a qualifying primary source.
- A third recirculation of the "AIX Global quantum value / Six Millennium Problems" self-published hoax appeared via a new HN discussion thread extending the same unverified claim — still not pursued.
- r/QuantumComputing carried only a generic "is fault-tolerant quantum computing coming in 2028 or 2050" discussion thread this run — no new signal.
- Digest coverage (Quantum Insider, Quantum Zeitgeist) was dominated by routine funding/partnership PR; one digest lead resolved a standing unconfirmed claim to an already-tracked primary rather than a new result.
- arXiv's query API reverted to primary after a 2nd consecutive confirmed recovery — see [SOURCES.md](SOURCES.md).

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (30)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-09-17](reports/2026-09-17.md) · weekly: [2026-W37](reports/weekly/2026-W37.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

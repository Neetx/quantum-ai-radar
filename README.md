# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-5-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-2-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-25-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--07--09-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-07-09):**
- Two trends gained a new independent group (no stage moves — neither cleared its stage's breadth bar). [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) reaches a **5th group** with Xanadu/PennyLane's [spectral Born machines](https://arxiv.org/abs/2607.06675) (IQP/Born-machine generalization via group Fourier analysis; ships a `tcdq` PennyLane module; a 190-qubit / 1M-parameter rRNA demo).
- [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) reaches a **7th group** with [sparse long-range entangling gates](https://arxiv.org/abs/2607.07547) (Daley group) — circuit geometry / qubit reconfigurability as a task-dependent trainability resource; now approaching the accelerating band (flagged for W28).
- The **"QML-advantage boundary"** theme keeps growing on both sides: [The NISQ Trap](https://arxiv.org/abs/2607.07530) (position paper — NISQ advantage demos classically closed within ~18 months, exit = fault tolerance) is a strong 3rd skepticism artifact alongside the pro-advantage results — now a live candidate for its own trend.
- Two study picks ([The NISQ Trap](https://arxiv.org/abs/2607.07530), [spectral Born machines](https://arxiv.org/abs/2607.06675)). Queue held at 25 (added 5, dropped 5 stale Jul-3 single-group items).

## Trends

🌱 0 · 📈 3 · 🚀 2 · 🌊 0 · 🏔 0 · 📉 0 · 💤 0

| trend | stage | latest signal |
|-------|-------|---------------|
| [AI-for-quantum](TRENDS.md#id-trend-002-ai-for-quantum-ml-and-llm-guided-quantum-hardware-and-code-design) | 🚀 accelerating | [2026-07-01](https://arxiv.org/abs/2607.00939) |
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-07-01](https://arxiv.org/abs/2607.01473) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 📈 emerging | [2026-07-08](https://arxiv.org/abs/2607.07547) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 📈 emerging | [2026-07-07](https://arxiv.org/abs/2607.06675) |
| [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) | 📈 emerging | [2026-07-02](https://arxiv.org/abs/2607.02292) |

## Worth studying

- [The NISQ Trap: Eight Years of Demonstrations the Hardware Was Built to Lose (arXiv:2607.07530)](https://arxiv.org/abs/2607.07530) — (Jul 8): a sharp position paper arguing that essentially every NISQ-era "quantum advantage" demo has been classically reproduced or closed by a simulability theorem within ~18 months — because the circuits NISQ hardware can run with fidelity are exactly the regions classical algorithms compress efficiently — and locating the genuine exit in fault tolerance. Essential skeptical framing for near-term (including QML) advantage claims.
- [Spectral Born machines: classically trainable quantum generative models for discrete data (arXiv:2607.06675)](https://arxiv.org/abs/2607.06675) — Huang, Maxwell, Belis, Peters, Pye, Jahangiri, Bowles (Xanadu/PennyLane, Jul 7): generalizes IQP Born machines via group Fourier analysis into quantum generative models with a QFT-based inductive bias — classically hard to sample yet classically trainable via a spectral-MMD loss, shipped as a `tcdq` PennyLane module; scales to a 190-qubit / 1M-parameter model learning a distribution over 93-nucleotide rRNA. A directly-usable, unusually large-scale generative-QML tool.
- [Provable learning separation for predicting time-evolution of quantum many-body systems (arXiv:2607.06472)](https://arxiv.org/abs/2607.06472) — (Jul 7): a rigorous PAC-learning separation on a physically-natural QML task — a quantum learner learns many-body dynamics from short-time probe samples and infers via Hamiltonian simulation + classical shadows, while no classical poly-time algorithm can (BQP-complete embedding). The clean PRO-advantage counterweight to recent dequantization results.
- [Intrinsic Preservation of Plasticity in Continual Quantum Learning (arXiv:2511.17228, PRX Quantum)](https://arxiv.org/abs/2511.17228) — (peer-reviewed, Jul 6): quantum neural networks avoid the loss-of-plasticity that cripples classical nets in continual learning — unitary constraints confine optimization to a compact manifold — shown across supervised + RL tasks and on an IBM Heron processor. A QML advantage that is NOT about speedup.
- [Frozen-Tree Sampling Refutes Quantum Advantage of Random Circuit Sampling (arXiv:2607.04054)](https://arxiv.org/abs/2607.04054) — Sangchul Oh (Jul 4): an efficient O(n)-per-sample classical sampler whose output is statistically indistinguishable (same Dirichlet law) from a random quantum circuit's — a sharp challenge to RCS as a quantum-advantage benchmark.
- [Resource-efficient simulations of particle scattering on a digital quantum computer (npj Quantum Information)](https://www.nature.com/articles/s41534-026-01311-1) — Chai, Gibbs et al. (DESY/Surrey/AWE, peer-reviewed, Jul 6): 40-qubit particle-scattering experiments + 80-qubit state prep on hardware, using tensor-network circuit compression — utility-scale high-energy-physics simulation on today's devices.
- [Characterising the failure mechanisms of error-corrected quantum logic gates (arXiv:2504.07258)](https://arxiv.org/abs/2504.07258) — Harper et al. (Sydney + IBM, peer-reviewed in Nature Communications): quantifies how mid-circuit measurements degrade error-corrected logic using a heavy-hex code on a 156-qubit IBM Heron r2 — a hardware-grounded benchmark of a key FTQC bottleneck.
- [CUDA-Q 0.15.0](https://github.com/NVIDIA/cuda-quantum/releases/tag/0.15.0) — NVIDIA: adds C++ support for the dynamics backend, a Pasqal hardware backend, and a general operator framework — a directly-installable upgrade for hybrid QML/simulation workloads.
- [MerLin: differentiable photonic QML framework](https://www.quandela.com/resources/blog/merlin-reproducible-photonic-quantum-machine-learning-framework/) — Quandela (github.com/merlinquantum/merlin): PyTorch-native `QuantumLayer` for end-to-end differentiable training of linear-optical circuits, aimed at closing the reproducibility gap in photonic QML research.
- [Surface code logical operations on a superconducting quantum processor (arXiv:2607.01473)](https://arxiv.org/abs/2607.01473) — Lin, Guo, Ma et al. (USTC/Zhu-Pan group, Jul 2026): experimentally realizes patch-based surface-code logical operations on a 107-qubit superconducting processor — a flagship large-scale demonstration.

## Community pulse

_Unverified intake — community signals, not trend evidence._

- The DOE's ["Quantum Genesis" initiative](https://www.energy.gov/articles/energy-department-announces-initiative-create-and-deploy-worlds-first-scientifically) (fault-tolerant quantum computer by 2028, announced 2026-06-23) continues to dominate [r/QuantumComputing](https://old.reddit.com/r/QuantumComputing/) — a policy/funding commitment rather than a technical artifact; watch for follow-on vendor technical disclosures.
- [r/QuantumComputing](https://old.reddit.com/r/QuantumComputing/) still carries the IBM Nighthawk QCD/cybersecurity validation discussion — reinforcing interest in the HEP-simulation cluster the ledger tracks; no new primary named.
- [Hacker News](https://hn.algolia.com/?query=quantum) skepticism (a crypto-engineer's critique of quantum-computing timelines; "replace the IBM Quantum backend with /dev/urandom") echoes **The NISQ Trap**'s thesis — a community signal for the boundary/skepticism theme, no new primary.
- Digests (Quantum Insider, Quantum Computing Report) were funding/personnel/partnership PR this run — intake-only. Hugging Face Papers trending carried general ML/LLM work, no quantum items.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (25)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-07-09](reports/2026-07-09.md) · weekly: [2026-W27](reports/weekly/2026-W27.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

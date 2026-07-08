# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-5-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-2-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-25-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--07--08-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-07-08):**
- No trend gained new evidence and no stage moved — the first full day of Jul-7 arXiv postings landed on the two full-cap trends ([QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc), [AI-for-quantum](TRENDS.md#id-trend-002-ai-for-quantum-ml-and-llm-guided-quantum-hardware-and-code-design)) or on forming sub-themes.
- Two study picks, both showing where **QML advantage is real** (a counterweight to last week's skepticism): a [provable learning separation for many-body dynamics](https://arxiv.org/abs/2607.06472) (quantum-efficient, classically hard unless BQP⊆P/poly) and a peer-reviewed [continual-learning plasticity advantage](https://arxiv.org/abs/2511.17228) (PRX Quantum) where unitary constraints keep quantum nets learning while classical nets degrade.
- The **LLM-agentic quantum-reasoning** sub-cluster inside trend-002 now spans 6 independent groups (adding [Onnes](https://arxiv.org/abs/2607.05805) cryo-fault-diagnosis and [Lean-Quantum](https://arxiv.org/abs/2607.05492) formalization) — proposed to the W28 weekly as its own split-out sub-axis.
- The classical–quantum **boundary axis is heating up in both directions** (skepticism vs. rigorous pro-advantage). Queue held at 25 (dropped 6 routine single-group items, added 6).

## Trends

🌱 0 · 📈 3 · 🚀 2 · 🌊 0 · 🏔 0 · 📉 0 · 💤 0

| trend | stage | latest signal |
|-------|-------|---------------|
| [AI-for-quantum](TRENDS.md#id-trend-002-ai-for-quantum-ml-and-llm-guided-quantum-hardware-and-code-design) | 🚀 accelerating | [2026-07-01](https://arxiv.org/abs/2607.00939) |
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-07-01](https://arxiv.org/abs/2607.01473) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 📈 emerging | [2026-07-06](https://arxiv.org/abs/2607.04598) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 📈 emerging | [2026-07-02](https://arxiv.org/abs/2607.02363) |
| [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) | 📈 emerging | [2026-07-02](https://arxiv.org/abs/2607.02292) |

## Worth studying

- [Provable learning separation for predicting time-evolution of quantum many-body systems (arXiv:2607.06472)](https://arxiv.org/abs/2607.06472) — (Jul 7): a rigorous PAC-learning separation on a physically-natural QML task — a quantum learner learns many-body dynamics from short-time probe samples and infers via Hamiltonian simulation + classical shadows, while no classical poly-time algorithm can (BQP-complete embedding). The clean PRO-advantage counterweight to this week's dequantization results.
- [Intrinsic Preservation of Plasticity in Continual Quantum Learning (arXiv:2511.17228, PRX Quantum)](https://arxiv.org/abs/2511.17228) — (peer-reviewed, Jul 6): quantum neural networks avoid the loss-of-plasticity that cripples classical nets in continual learning — unitary constraints confine optimization to a compact manifold — shown across supervised + RL tasks and on an IBM Heron processor. A QML advantage that is NOT about speedup.
- [Frozen-Tree Sampling Refutes Quantum Advantage of Random Circuit Sampling (arXiv:2607.04054)](https://arxiv.org/abs/2607.04054) — Sangchul Oh (Jul 4): an efficient O(n)-per-sample classical sampler whose output is statistically indistinguishable (same Dirichlet law) from a random quantum circuit's — a sharp challenge to RCS as a quantum-advantage benchmark, and a live "does the advantage survive dequantization?" case.
- [Resource-efficient simulations of particle scattering on a digital quantum computer (npj Quantum Information)](https://www.nature.com/articles/s41534-026-01311-1) — Chai, Gibbs et al. (DESY/Surrey/AWE, peer-reviewed, Jul 6): 40-qubit particle-scattering experiments + 80-qubit state prep on hardware, using tensor-network circuit compression — a published demonstration of utility-scale high-energy-physics simulation on today's devices.
- [Characterising the failure mechanisms of error-corrected quantum logic gates (arXiv:2504.07258)](https://arxiv.org/abs/2504.07258) — Harper et al. (Sydney + IBM, peer-reviewed in Nature Communications): quantifies how mid-circuit measurements degrade error-corrected logic (idling-induced decoherence on adjacent qubits) using a heavy-hex code on a 156-qubit IBM Heron r2 — a hardware-grounded benchmark of a key FTQC bottleneck.
- [CUDA-Q 0.15.0](https://github.com/NVIDIA/cuda-quantum/releases/tag/0.15.0) — NVIDIA: adds C++ support for the dynamics backend, a Pasqal hardware backend, and a general operator framework — a directly-installable upgrade for hybrid QML/simulation workloads.
- [Holographic Quantum Transformer (arXiv:2607.00398)](https://arxiv.org/abs/2607.00398) — Guo, Xiao, Liu, Li (KDD '26): a generative-attention/transformer neural-network ansatz for 2D frustrated quantum matter with zero-shot size extrapolation.
- [MerLin: differentiable photonic QML framework](https://www.quandela.com/resources/blog/merlin-reproducible-photonic-quantum-machine-learning-framework/) — Quandela (github.com/merlinquantum/merlin): PyTorch-native `QuantumLayer` for end-to-end differentiable training of linear-optical circuits, aimed at closing the reproducibility gap in photonic QML research.
- [Surface code logical operations on a superconducting quantum processor (arXiv:2607.01473)](https://arxiv.org/abs/2607.01473) — Lin, Guo, Ma et al. (USTC/Zhu-Pan group, Jul 2026): experimentally realizes patch-based surface-code logical operations on a 107-qubit superconducting processor — a flagship large-scale demonstration of logical-operation techniques.
- [A Machine-Verified Proof of a Quantum-Optimization Conjecture (arXiv:2606.29687)](https://arxiv.org/abs/2606.29687) — Kol, Ben-Shahar, Sulimany, Englund (MIT, Jun 29): resolves a decade-old QAOA conjecture using an LLM-found proof verified end-to-end in Lean 4.

## Community pulse

_Unverified intake — community signals, not trend evidence._

- The DOE's ["Quantum Genesis" initiative](https://www.energy.gov/articles/energy-department-announces-initiative-create-and-deploy-worlds-first-scientifically) (fault-tolerant quantum computer by 2028, announced 2026-06-23) continues to dominate [r/QuantumComputing](https://old.reddit.com/r/QuantumComputing/) — a policy/funding commitment rather than a technical artifact; watch for follow-on vendor technical disclosures.
- [r/QuantumComputing](https://old.reddit.com/r/QuantumComputing/) still carries the [IBM Nighthawk QCD/cybersecurity validation](https://old.reddit.com/r/QuantumComputing/) discussion — reinforcing interest in the HEP-simulation cluster the ledger tracks; no new primary named.
- [Hacker News](https://hn.algolia.com/?query=quantum) surfaced "Researchers Reveal the Power of 'Quantum Proofs'" (complexity-theory explainer) and continuing post-quantum-cryptography deadline threads — off the QML/hardware axes, no new primary.
- Digests (Quantum Insider, Quantum Computing Report) were all funding/personnel/partnership PR this run (NSF Project Triad, Oratomic $300M Series A, university research nodes) — intake-only, nothing to cite. Hugging Face Papers trending carried general ML/LLM work, no quantum items.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (25)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-07-08](reports/2026-07-08.md) · weekly: [2026-W27](reports/weekly/2026-W27.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

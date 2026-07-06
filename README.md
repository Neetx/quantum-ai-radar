# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-5-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-2-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-25-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--07--06-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-07-06):**
- Quiet-extract day (4th in a row) — arXiv (quant-ph/cs.LG/cs.ET) is *still* capped at 2026-07-02, the weekend/holiday posting lag persisting into Monday; no trend received new evidence, no stages moved, no new queue items.
- Fixed both forced source-heals: **PRX Quantum** now via its [APS RSS feed](https://feeds.aps.org/rss/recent/prxquantum.xml) (the `/recent` extract had broken), and the **Quandela blog** via `tvly search` by domain — both back to working access paths after 2 consecutive post-heal failures each.
- Full coverage: every registered vendor blog was individually opened this run (correcting yesterday's "not-re-opened — carried" shortcut); the aggregating digests confirm nothing new on-axis today beyond a UCF funding award (no artifact → intake-only).
- The utility-scale [LGT/HEP-simulation-on-100+-qubit-hardware cluster](https://quantumcomputingreport.com/lbnl-researcher-leverages-104-qubits-on-ibm-heron-to-simulate-subatomic-hadronization/) holds at 2 groups (LBNL hadronization still unverified — no primary locatable while arXiv is frozen); below the trend bar, watched.

## Trends

🌱 0 · 📈 3 · 🚀 2 · 🌊 0 · 🏔 0 · 📉 0 · 💤 0

| trend | stage | latest signal |
|-------|-------|---------------|
| [AI-for-quantum](TRENDS.md#id-trend-002-ai-for-quantum-ml-and-llm-guided-quantum-hardware-and-code-design) | 🚀 accelerating | [2026-07-01](https://arxiv.org/abs/2607.00939) |
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-07-01](https://arxiv.org/abs/2607.01473) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 📈 emerging | [2026-07-02](https://arxiv.org/abs/2607.02363) |
| [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) | 📈 emerging | [2026-07-02](https://arxiv.org/abs/2607.02292) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 📈 emerging | [2026-07-01](https://arxiv.org/abs/2607.00945) |

## Worth studying

- [Characterising the failure mechanisms of error-corrected quantum logic gates (arXiv:2504.07258)](https://arxiv.org/abs/2504.07258) — Harper et al. (Sydney + IBM, peer-reviewed in Nature Communications): quantifies how mid-circuit measurements degrade error-corrected logic (idling-induced decoherence on adjacent qubits) using a heavy-hex code on a 156-qubit IBM Heron r2 — a hardware-grounded benchmark of a key FTQC bottleneck.
- [CUDA-Q 0.15.0](https://github.com/NVIDIA/cuda-quantum/releases/tag/0.15.0) — NVIDIA: adds C++ support for the dynamics backend, a Pasqal hardware backend, and a general operator framework — a directly-installable upgrade for hybrid QML/simulation workloads.
- [Holographic Quantum Transformer (arXiv:2607.00398)](https://arxiv.org/abs/2607.00398) — Guo, Xiao, Liu, Li (KDD '26): a generative-attention/transformer neural-network ansatz for 2D frustrated quantum matter with zero-shot size extrapolation.
- [MerLin: differentiable photonic QML framework](https://www.quandela.com/resources/blog/merlin-reproducible-photonic-quantum-machine-learning-framework/) — Quandela (github.com/merlinquantum/merlin): PyTorch-native `QuantumLayer` for end-to-end differentiable training of linear-optical circuits, aimed at closing the reproducibility gap in photonic QML research.
- [Surface code logical operations on a superconducting quantum processor (arXiv:2607.01473)](https://arxiv.org/abs/2607.01473) — Lin, Guo, Ma et al. (USTC/Zhu-Pan group, Jul 2026): experimentally realizes patch-based surface-code logical operations on a 107-qubit superconducting processor — a flagship large-scale demonstration of logical-operation techniques.
- [Mechanistic Interpretability and Causal Feature Steering of Neural Quantum States via Sparse Autoencoders (arXiv:2607.01336)](https://arxiv.org/abs/2607.01336) — Qi, Earls (Jul 2026): imports LLM mechanistic-interpretability tooling to open up the black box of Neural Quantum States — a notable cross-boundary methodology.
- [When AI meets quantum information: A comprehensive review (arXiv:2607.00365)](https://arxiv.org/abs/2607.00365) — Chen, Gan, Jin et al. (18 authors, Jul 1): two-directional survey of AI-for-QI and QI-for-AI — a strong orientation map for this field.
- [A Machine-Verified Proof of a Quantum-Optimization Conjecture (arXiv:2606.29687)](https://arxiv.org/abs/2606.29687) — Kol, Ben-Shahar, Sulimany, Englund (MIT, Jun 29): resolves a decade-old QAOA conjecture using an LLM-found proof verified end-to-end in Lean 4.
- [Machine Learning Decoding of Circuit-Level Noise for Bivariate Bicycle Codes (Quantum journal)](https://quantum-journal.org/papers/q-2026-06-30-2149/) — Blue, Avlani, He, Ziyin, Chuang (MIT, Jun 30): peer-reviewed neural decoder for bivariate bicycle QEC codes under circuit-level noise.
- [erado: open-source erasure-noise + postselection simulator (arXiv:2606.31428)](https://arxiv.org/abs/2606.31428) — Griffiths, Friel, Vlastakis: ready-to-use framework for evaluating postselection-based error mitigation, with a concrete erasure-check error-rate threshold for full mitigation.
- [Learning the structure of open quantum systems (arXiv:2606.30358)](https://arxiv.org/abs/2606.30358) — Lewis, Tang, Wright (Jun 2026): learns an n-qubit constant-local Lindbladian to ε error with O(g·d²·log n / ε²) total evolution time — efficient identification of open-system dynamics. Classical-quantum-boundary result from a notable group (Ewin Tang); a rigorous benchmark for how cheaply quantum dynamics can be learned.
- [Google Quantum Echoes: verifiable advantage on Willow (arXiv:2506.10191)](https://arxiv.org/abs/2506.10191) — Google Quantum AI (Nature Oct 2025): first claimed verifiable quantum advantage using the OTOC algorithm; verifiable on another quantum system AND beyond classical simulation (Google's claim). Dequantization status UNVERIFIED — independent assessment needed before citing as settled.

## Community pulse

_Unverified intake — community signals, not trend evidence._

- The DOE's ["Quantum Genesis" initiative](https://www.energy.gov/articles/energy-department-announces-initiative-create-and-deploy-worlds-first-scientifically) (fault-tolerant quantum computer by 2028, announced 2026-06-23) continues to dominate [r/QuantumComputing](https://old.reddit.com/r/QuantumComputing/) and Hacker News — a policy/funding commitment rather than a technical artifact; watch for follow-on vendor technical disclosures.
- [r/QuantumComputing](https://old.reddit.com/r/QuantumComputing/) and [Hacker News](https://hn.algolia.com/?query=quantum) carry the IBM Nighthawk validation discussion, a Majorana critique thread, and general explainers (3blue1brown, post-quantum-crypto) — nothing new on-axis, no primaries named.
- The only genuinely-new digest item today is a UCF ORAU **award** for topological-mechanical-braiding circuit stabilization — a funding announcement with no technical artifact, so intake-only per the Hard rules.
- Qiskit's [YouTube channel](https://www.youtube.com/feeds/videos.xml?channel_id=UClBNq7mCMf5xm8baE_VMl3A) unchanged (Jun-27 Lidar seminar); Sabine Hossenfelder's channel posted nothing new quantum-specific.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (25)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-07-06](reports/2026-07-06.md) · weekly: [2026-W27](reports/weekly/2026-W27.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

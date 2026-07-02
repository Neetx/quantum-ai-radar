# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-4-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-2-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-24-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--07--02-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-07-01):**
- [AI-for-quantum](TRENDS.md#id-trend-002-ai-for-quantum-ml-and-llm-guided-quantum-hardware-and-code-design) promoted emerging → **accelerating** (10 independent groups): [arXiv:2606.29687](https://arxiv.org/abs/2606.29687) (Kol et al., MIT) machine-verifies a decade-old QAOA conjecture using an LLM + the Lean 4 proof assistant, and [arXiv:2607.00939](https://arxiv.org/abs/2607.00939) (QPipe) an LLM multi-agent system that generates quantum applications from natural-language requirements.
- [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) promoted seed → **emerging** (4 groups): [arXiv:2607.00945](https://arxiv.org/abs/2607.00945) proves a barren-plateau-free QAOA-MaxCut family via dynamical Lie algebra, resolving an open problem.
- [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) promoted seed → **emerging** (4 groups): [arXiv:2607.00301](https://arxiv.org/abs/2607.00301) Quantum Flow Matching learns quantum distributions via the spin Wigner function.
- Queue refreshed: −9 stale/resolved drops, +9 additions (incl. a real-trapped-ion-hardware portfolio-optimization pipeline and a CSS-code addressability result) → watchlist at 24.

## Trends

🌱 0 · 📈 2 · 🚀 2 · 🌊 0 · 🏔 0 · 📉 0 · 💤 0

| trend | stage | latest signal |
|-------|-------|---------------|
| [AI-for-quantum](TRENDS.md#id-trend-002-ai-for-quantum-ml-and-llm-guided-quantum-hardware-and-code-design) | 🚀 accelerating | [2026-07-01](https://arxiv.org/abs/2607.00939) |
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-06-30](https://quantum-journal.org/papers/q-2026-06-30-2149/) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 📈 emerging | [2026-07-01](https://arxiv.org/abs/2607.00945) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 📈 emerging | [2026-07-01](https://arxiv.org/abs/2607.00301) |

## Worth studying

- [When AI meets quantum information: A comprehensive review (arXiv:2607.00365)](https://arxiv.org/abs/2607.00365) — Chen, Gan, Jin et al. (18 authors, Jul 1): two-directional survey of AI-for-QI and QI-for-AI — a strong orientation map for this field.
- [A Machine-Verified Proof of a Quantum-Optimization Conjecture (arXiv:2606.29687)](https://arxiv.org/abs/2606.29687) — Kol, Ben-Shahar, Sulimany, Englund (MIT, Jun 29): resolves a decade-old QAOA conjecture using an LLM-found proof verified end-to-end in Lean 4.
- [Machine Learning Decoding of Circuit-Level Noise for Bivariate Bicycle Codes (Quantum journal)](https://quantum-journal.org/papers/q-2026-06-30-2149/) — Blue, Avlani, He, Ziyin, Chuang (MIT, Jun 30): peer-reviewed neural decoder for bivariate bicycle QEC codes under circuit-level noise.
- [erado: open-source erasure-noise + postselection simulator (arXiv:2606.31428)](https://arxiv.org/abs/2606.31428) — Griffiths, Friel, Vlastakis: ready-to-use framework for evaluating postselection-based error mitigation, with a concrete erasure-check error-rate threshold for full mitigation.
- [Learning the structure of open quantum systems (arXiv:2606.30358)](https://arxiv.org/abs/2606.30358) — Lewis, Tang, Wright (Jun 2026): learns an n-qubit constant-local Lindbladian to ε error with O(g·d²·log n / ε²) total evolution time — efficient identification of open-system dynamics. Classical-quantum-boundary / quantum-learning result from a notable group (Ewin Tang); a rigorous benchmark for how cheaply quantum dynamics can be learned.
- [Google Quantum Echoes: verifiable advantage on Willow (arXiv:2506.10191)](https://arxiv.org/abs/2506.10191) — Google Quantum AI (Nature Oct 2025): first claimed verifiable quantum advantage using OTOC algorithm; unlike random circuit sampling, OTOCs are verifiable on another quantum computer or natural system AND beyond classical simulation (Google's claim). Dequantization status UNVERIFIED — independent assessment needed before citing as settled.
- [20 Second Parity Lifetime in InAs-Pb Tetron (arXiv:2606.03884)](https://arxiv.org/abs/2606.03884) — Microsoft Quantum (June 2026): 20-second parity lifetime in a topological qubit device, orders of magnitude beyond typical qubit operation times; validates excitation-gap scaling for FTQC-grade topological qubits
- [Foundation decoders for fault-tolerant QC](https://arxiv.org/abs/2606.27119) — high-capacity neural decoders now outperform classical decoders at large code distances; directly relevant to practical FTQC timelines
- [Qiskit Paulice: postselected QEC for near-term circuits](https://www.ibm.com/quantum/blog/qiskit-paulice) — immediately usable Qiskit addon for low-overhead error detection; bridges NISQ error mitigation to fault-tolerant architectures
- [No Reference-Free Generalization in QML (arXiv:2606.22331)](https://arxiv.org/abs/2606.22331) — key theoretical result: QML models require an orienting reference structure in training data to generalize; important constraint for circuit and dataset design

## Community pulse

_Unverified intake — community signals, not trend evidence._

- [Quantum Computing Stack Exchange](https://quantumcomputing.stackexchange.com/) surfaced two new general Q&A threads (state-preparation decision trees; Deutsch's algorithm query advantage) — no primaries to follow.
- [r/QuantumComputing](https://www.reddit.com/r/QuantumComputing/) access has now been blocked for 3 consecutive scans; no new community signal obtainable this run via that channel.
- [Hacker News](https://hn.algolia.com/?query=quantum) front page and quantum search showed no field-shaking item today — a "Quantum Computing Roadmaps" tracker tool surfaced but is not a primary source.
- A corporate press release claimed neural-network parameter optimization for twin-field QKD — pure PR via newswire, no technical paper found; not treated as a signal.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (24)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-07-02](reports/2026-07-02.md) · weekly: [2026-W26](reports/weekly/2026-W26.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

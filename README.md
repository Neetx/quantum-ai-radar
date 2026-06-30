# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-3-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-0-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-24-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--06--30-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-06-29):**
- [Trend-001 (Practical QEC tooling)](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) gains two new independent groups (now 8): [arXiv:2606.30592](https://arxiv.org/abs/2606.30592) (Bi, Chang, Puri — Yale) low-depth syndrome extraction for QLDPC via biased-noise ancillas, and [arXiv:2606.30606](https://arxiv.org/abs/2606.30606) repetition-code readout error detection across hardware — flagged as a promotion-to-accelerating candidate.
- Study shelf: [Learning the structure of open quantum systems (arXiv:2606.30358)](https://arxiv.org/abs/2606.30358) — Lewis, Tang, Wright: efficient (log-in-n) learning of Lindbladian dynamics; a clean classical-quantum-boundary benchmark from a dequantization-notable group.
- Queue refreshed: +6 (visual QRL, gen-ML quantum SCI, quantum MCTS, provable-advantage DQPT theory, quantum-sim VLM, China Telecom/Jiuzhang-4.0 photonic-advantage [hype-prone intake]), −5 stale single-group items → watchlist at 24.
- Repo-watch: [Cirq v1.7.0](https://github.com/quantumlib/Cirq/releases/tag/v1.7.0) released (Jun 29, up from v1.6.1 Aug 2025). No new ≥3-group convergence cluster this scan.

## Trends

🌱 2 · 📈 1 · 🚀 0 · 🌊 0 · 🏔 0 · 📉 0 · 💤 0

| trend | stage | latest signal |
|-------|-------|---------------|
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 📈 emerging | [2026-06-29](https://arxiv.org/abs/2606.30592) |
| [AI-for-quantum](TRENDS.md#id-trend-002-ai-for-quantum-ml-and-llm-guided-quantum-hardware-and-code-design) | 🌱 seed | [2026-06-26](https://arxiv.org/abs/2606.27907) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 🌱 seed | [2026-06-26](https://arxiv.org/abs/2606.28236) |

## Worth studying

- [Learning the structure of open quantum systems (arXiv:2606.30358)](https://arxiv.org/abs/2606.30358) — Lewis, Tang, Wright (Jun 2026): learns an n-qubit constant-local Lindbladian to ε error with O(g·d²·log n / ε²) total evolution time — efficient identification of open-system dynamics. Classical-quantum-boundary / quantum-learning result from a notable group (Ewin Tang); a rigorous benchmark for how cheaply quantum dynamics can be learned.
- [Google Quantum Echoes: verifiable advantage on Willow (arXiv:2506.10191)](https://arxiv.org/abs/2506.10191) — Google Quantum AI (Nature Oct 2025): first claimed verifiable quantum advantage using OTOC algorithm; unlike random circuit sampling, OTOCs are verifiable on another quantum computer or natural system AND beyond classical simulation (Google's claim). Dequantization status UNVERIFIED — independent assessment needed before citing as settled.
- [20 Second Parity Lifetime in InAs-Pb Tetron (arXiv:2606.03884)](https://arxiv.org/abs/2606.03884) — Microsoft Quantum (June 2026): 20-second parity lifetime in a topological qubit device, orders of magnitude beyond typical qubit operation times; validates excitation-gap scaling for FTQC-grade topological qubits
- [Foundation decoders for fault-tolerant QC](https://arxiv.org/abs/2606.27119) — high-capacity neural decoders now outperform classical decoders at large code distances; directly relevant to practical FTQC timelines
- [Qiskit Paulice: postselected QEC for near-term circuits](https://www.ibm.com/quantum/blog/qiskit-paulice) — immediately usable Qiskit addon for low-overhead error detection; bridges NISQ error mitigation to fault-tolerant architectures
- [No Reference-Free Generalization in QML (arXiv:2606.22331)](https://arxiv.org/abs/2606.22331) — key theoretical result: QML models require an orienting reference structure in training data to generalize; important constraint for circuit and dataset design

## Community pulse

_Unverified intake — community signals, not trend evidence._

- [r/QuantumComputing](https://www.reddit.com/r/QuantumComputing/): "IBM Nighthawk Processor Validated in Quantum Chromodynamics and Cybersecurity Benchmarks" thread — community discussion of an IBM processor benchmark claim; no official primary opened.
- [r/QuantumComputing](https://www.reddit.com/r/QuantumComputing/) "Heron R2 entanglement test" thread continues — community discussion around IBM's 156-qubit Heron R2; no official primary source found.
- Microsoft Majorana 2 skepticism persists across [Hacker News](https://hn.algolia.com/?query=quantum) (The Register / vechron coverage of "basic Python errors" critique); underlying technical paper is [arXiv:2606.03884](https://arxiv.org/abs/2606.03884).
- HN intake: a Twitter post claiming "AI beats a published quantum ECDSA-breaking circuit" circulated — AI-for-quantum signal, no primary; intake only.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (24)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-06-30](reports/2026-06-30.md) · weekly: [2026-W26](reports/weekly/2026-W26.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

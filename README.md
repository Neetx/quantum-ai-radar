# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-4-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-1-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-26-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--07--01-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-06-30):**
- [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) promoted emerging → **accelerating** (10 independent groups): [Quantum-journal ML decoder](https://quantum-journal.org/papers/q-2026-06-30-2149/) (Blue et al., MIT) for bivariate bicycle codes, and [arXiv:2606.31428](https://arxiv.org/abs/2606.31428) quantifying the limits of erasure-based postselection.
- [AI-for-quantum](TRENDS.md#id-trend-002-ai-for-quantum-ml-and-llm-guided-quantum-hardware-and-code-design) promoted seed → emerging (7 groups): [arXiv:2606.29636](https://arxiv.org/abs/2606.29636) Lie-group diffusion models for circuit synthesis, and [arXiv:2606.30765](https://arxiv.org/abs/2606.30765) deep RL for atomic control and cooling.
- New seed trend: [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) (barren plateaus / noise-robustness theory) — 3 independent groups converged: [arXiv:2606.22551](https://arxiv.org/abs/2606.22551), [arXiv:2606.30688](https://arxiv.org/abs/2606.30688), [arXiv:2606.31536](https://arxiv.org/abs/2606.31536).
- Queue refreshed: +6 (ML CV-QKD, quantum-classical LBM surrogate, ML Pauli-term selection for QEM, spatially-coupled CSS codes, applied QML for immunology, hybrid quantum neighborhood selection), −3 stale single-group drops, −1 promoted → watchlist at 26.

## Trends

🌱 2 · 📈 1 · 🚀 1 · 🌊 0 · 🏔 0 · 📉 0 · 💤 0

| trend | stage | latest signal |
|-------|-------|---------------|
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-06-30](https://quantum-journal.org/papers/q-2026-06-30-2149/) |
| [AI-for-quantum](TRENDS.md#id-trend-002-ai-for-quantum-ml-and-llm-guided-quantum-hardware-and-code-design) | 📈 emerging | [2026-06-30](https://arxiv.org/abs/2606.29636) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 🌱 seed | [2026-06-30](https://arxiv.org/abs/2606.31536) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 🌱 seed | [2026-06-26](https://arxiv.org/abs/2606.28236) |

## Worth studying

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

- [Quantum Computing Stack Exchange](https://quantumcomputing.stackexchange.com/) surfaced questions on classical-shortcut limits for Fermi-Hubbard simulation and on measurement-complexity separations for closed-loop quantum control (AI-for-quantum-adjacent) — no primaries to follow yet.
- [Hacker News](https://hn.algolia.com/?query=quantum) carried independent (Ars Technica) coverage of a neutral-atom vendor's error-corrected-qubit roadmap claim — still vendor-roadmap-sourced, no new technical primary.
- [r/QuantumComputing](https://www.reddit.com/r/QuantumComputing/) access was intermittently rate-limited again this scan; last confirmed threads unchanged from the prior scan (Heron R2 entanglement test, Nighthawk benchmark validation).
- Microsoft Majorana 2 skepticism continues to circulate on [Hacker News](https://hn.algolia.com/?query=quantum); underlying technical paper remains [arXiv:2606.03884](https://arxiv.org/abs/2606.03884).

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (26)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-07-01](reports/2026-07-01.md) · weekly: [2026-W26](reports/weekly/2026-W26.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

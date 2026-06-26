# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-2-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-0-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-12-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--06--26-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — primarily quantum computing as a substrate for ML (QML), plus enabling hardware/error-correction/algorithm advances — for quantum-computing and quantum-ML researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-06-26):**
- **[Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc)** promoted to `emerging`: IBM shipped [Qiskit Paulice](https://www.ibm.com/quantum/blog/qiskit-paulice) (postselected error detection for near-term circuits), the [Q-NEXUS paper](https://arxiv.org/abs/2604.06319) demonstrates 138× qubit reduction for FTQC, and [foundation decoders](https://arxiv.org/abs/2606.27119) overcome the neural-decoder scaling barrier — three independent groups in one month.
- **[AI-for-quantum](TRENDS.md#id-trend-002-ai-for-quantum-ml-and-llm-guided-quantum-hardware-and-code-design)** seeded as a watch-area trend: [IBM LLM-guided QEC code discovery](https://arxiv.org/abs/2606.02418) (465 new code candidates via evolutionary search), neural foundation decoders, and [Microsoft using agentic AI to improve Majorana 2](https://news.microsoft.com/source/features/innovation/majorana-2-microsoft-discovery-agentic-ai) show ML increasingly embedded in quantum hardware workflows.
- **12 items queued**: clusters forming around quantum sequence models (QLSTM/QFWP, 2 groups), quantum data encoding (2 groups), and quantum ring all-reduce for distributed ML — each needs a third independent group before promotion.
- **White House executive order on quantum computing** (June 23) signed; [Scott Aaronson's response](https://scottaaronson.blog/?p=9861) urges basic research funding over applied-only capture.

## Trends

🌱 1 · 📈 1 · 🚀 0 · 🌊 0 · 🏔 0 · 📉 0 · 💤 0

| trend | stage | latest signal |
|---|---|---|
| [Practical QEC tooling: near-term error detection → FTQC](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 📈 emerging | [2026-06-25](https://www.ibm.com/quantum/blog/qiskit-paulice) |
| [AI-for-quantum: ML/LLM-guided hardware and code design](TRENDS.md#id-trend-002-ai-for-quantum-ml-and-llm-guided-quantum-hardware-and-code-design) | 🌱 seed | [2026-06-25](https://news.microsoft.com/source/features/innovation/majorana-2-microsoft-discovery-agentic-ai) |

## Worth studying

- [Foundation decoders for fault-tolerant QC](https://arxiv.org/abs/2606.27119) — high-capacity neural decoders now outperform classical decoders at large code distances; directly relevant to practical FTQC timelines
- [Qiskit Paulice: postselected QEC for near-term circuits](https://www.ibm.com/quantum/blog/qiskit-paulice) — immediately usable Qiskit addon for low-overhead error detection; bridges NISQ error mitigation to fault-tolerant architectures
- [No Reference-Free Generalization in QML (arXiv:2606.22331)](https://arxiv.org/abs/2606.22331) — key theoretical result: without an orienting reference structure in training data, a QML model cannot generalize to unseen quantum directions; implications for circuit and dataset design

## Community pulse

_Unverified sentiment from social/community sources — never evidence; links only._

- [r/QuantumComputing](https://www.reddit.com/r/QuantumComputing/comments/1uegi07/big_critique_of_micro) and [Reuters](https://www.reuters.com/legal/government/microsofts-quantum-computing-technology-called-into-question-again-2026-06-24/) report renewed skepticism toward Microsoft's Majorana topological qubit claims; community actively debating validity — consistent with the hype-skepticism mandate.
- White House executive order on quantum computing (June 23) generating broad discussion; [Aaronson's response](https://scottaaronson.blog/?p=9861) frames the policy tension between basic academic vs. large-org applied research funding.
- [r/QuantumComputing GPU+quantum thread](https://www.reddit.com/r/QuantumComputing/comments/1uazi6b/gpus_for_quantum_comp) signals growing community interest in hybrid GPU-quantum workflows — aligns with NVIDIA cuda-quantum 0.15-rc3 release (June 25).
- [Quantum Computing Stack Exchange](https://quantumcomputing.stackexchange.com/feeds) active on lattice surgery and surface code questions (June 23-24) — practitioner-level QEC interest consistent with trend-001 momentum.

---

**Output map:** [TRENDS.md](TRENDS.md) · [Watchlist (12)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: reports/2026-06-26.md · weekly: none yet · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-3-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-0-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-23-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--06--29-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-06-27):**
- [Trend-001 (Practical QEC tooling)](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) gains 6th independent group: [arXiv:2604.16209](https://arxiv.org/abs/2604.16209) (Zhao et al., MIT-CTP) — ultra-high-rate QLDPC codes on neutral-atom arrays, encoding rates well above 1/10.
- [Trend-001](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) also gains 5th group (Pass 1): [arXiv:2606.14455](https://arxiv.org/abs/2606.14455) (Benois et al., Paris-Saclay) — density matrix propagation for optimal QEC decoding; practical decoders fall 5× short of optimality.
- [Trend-002 (AI-for-quantum)](TRENDS.md#id-trend-002-ai-for-quantum-ml-and-llm-guided-quantum-hardware-and-code-design) gains 5th independent org: [arXiv:2606.27907](https://arxiv.org/abs/2606.27907) (Zhong et al.) — end-to-end ML for quantum control on latent dynamical manifold.
- **New [Trend-003 (Quantum generative models)](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) promoted to seed** — 3 independent groups on quantum generative and sequential learning: Wells Fargo QLSTM/QFWP, Waller et al. QDiffusion-TS, Banks et al. qudit IQP.
- Study shelf: [Google Quantum Echoes (arXiv:2506.10191)](https://arxiv.org/abs/2506.10191) (Nature Oct 2025) — first claimed verifiable quantum advantage via OTOC on Willow chip; dequantization status unverified.
- +11 queue items: hybrid QNN phase recognition (2 groups), photonic QNN edge AI, quantum DTW, FTQC materials algorithm, IBM state tomography, Alice & Bob Helium System, QuEra gigaquop roadmap, AWS-QuEra FTQC collaboration, QuTech SnV PRX, Pasqal QEX SDK, and more.

## Trends

🌱 2 · 📈 1 · 🚀 0 · 🌊 0 · 🏔 0 · 📉 0 · 💤 0

| trend | stage | latest signal |
|-------|-------|---------------|
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 📈 emerging | [2026-06-25](https://www.ibm.com/quantum/blog/qiskit-paulice) |
| [AI-for-quantum](TRENDS.md#id-trend-002-ai-for-quantum-ml-and-llm-guided-quantum-hardware-and-code-design) | 🌱 seed | [2026-06-26](https://arxiv.org/abs/2606.27907) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 🌱 seed | [2026-06-26](https://arxiv.org/abs/2606.28236) |

## Worth studying

- [Google Quantum Echoes: verifiable advantage on Willow (arXiv:2506.10191)](https://arxiv.org/abs/2506.10191) — Google Quantum AI (Nature Oct 2025): first claimed verifiable quantum advantage using OTOC algorithm; unlike random circuit sampling, OTOCs are verifiable on another quantum computer or natural system AND beyond classical simulation (Google's claim). Dequantization status UNVERIFIED — independent assessment needed before citing as settled.
- [20 Second Parity Lifetime in InAs-Pb Tetron (arXiv:2606.03884)](https://arxiv.org/abs/2606.03884) — Microsoft Quantum (June 2026): 20-second parity lifetime in a topological qubit device, orders of magnitude beyond typical qubit operation times; validates excitation-gap scaling for FTQC-grade topological qubits
- [Foundation decoders for fault-tolerant QC](https://arxiv.org/abs/2606.27119) — high-capacity neural decoders now outperform classical decoders at large code distances; directly relevant to practical FTQC timelines
- [Qiskit Paulice: postselected QEC for near-term circuits](https://www.ibm.com/quantum/blog/qiskit-paulice) — immediately usable Qiskit addon for low-overhead error detection; bridges NISQ error mitigation to fault-tolerant architectures
- [No Reference-Free Generalization in QML (arXiv:2606.22331)](https://arxiv.org/abs/2606.22331) — key theoretical result: QML models require an orienting reference structure in training data to generalize; important constraint for circuit and dataset design

## Community pulse

_Unverified intake — community signals, not trend evidence._

- [r/QuantumComputing](https://www.reddit.com/r/QuantumComputing/) Jun 28: "Heron R2 entanglement test" thread — community discussion around IBM's 156-qubit Heron R2 processor; no official primary source found.
- Microsoft Majorana 2 uncertainty continues: ongoing community skepticism about topological qubit reliability claims; underlying technical paper is [arXiv:2606.03884](https://arxiv.org/abs/2606.03884).
- HN front page: no quantum items Jun 29. No field-shaking events detected across monitored channels.
- White House executive order on quantum computing context: [EO text](https://www.whitehouse.gov/presidential-actions/2026/06/ushering-in-the-next-frontier-of-quantum-innovation/); [Shtetl-Optimized response](https://scottaaronson.blog/?p=9861) urges basic-research funding.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (23)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-06-29](reports/2026-06-29.md) · weekly: [2026-W26](reports/weekly/2026-W26.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

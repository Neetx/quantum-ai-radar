# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-5-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-2-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-25-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--07--04-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-07-04, W27 weekly recalibration):**
- [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) confidence raised low → medium on 5 independent groups sustained over ~13 days; all 5 active trends held at their current stage this week (no demotions or archivals — every trend's evidence is ≤3 days old).
- Source heal on Quandela's blog surfaced two on-axis primaries a shallow extract had been missing: a [GPU-QPU NVQLink integration for photonic QML](https://www.quandela.com/resources/blog/quandela-nvidia-gpu-qpu-integration-nvqlink/) and [MerLin](https://www.quandela.com/resources/blog/merlin-reproducible-photonic-quantum-machine-learning-framework/), an open-source differentiable photonic-QML framework — both queued, MerLin also added to the study shelf.
- Monthly retrospective: [IBM's dual Nighthawk validation](https://arxiv.org/abs/2606.02574) (QCD simulation + [cybersecurity QAOA](https://arxiv.org/abs/2606.09469)) was a miss — covered by mainstream tech press June 20-21 but never captured until this run; now queued.
- Two sources promoted from candidate to verified with corrected access methods: [PRX Quantum](https://journals.aps.org/prxquantum/recent) and Hugging Face Papers; r/MachineLearning formally removed after being silently unswept for 3 days.

## Trends

🌱 1 · 📈 2 · 🚀 2 · 🌊 0 · 🏔 0 · 📉 0 · 💤 0

| trend | stage | latest signal |
|-------|-------|---------------|
| [AI-for-quantum](TRENDS.md#id-trend-002-ai-for-quantum-ml-and-llm-guided-quantum-hardware-and-code-design) | 🚀 accelerating | [2026-07-01](https://arxiv.org/abs/2607.00939) |
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-07-01](https://arxiv.org/abs/2607.01473) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 📈 emerging | [2026-07-02](https://arxiv.org/abs/2607.02363) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 📈 emerging | [2026-07-01](https://arxiv.org/abs/2607.00945) |
| [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) | 🌱 seed | [2026-07-02](https://arxiv.org/abs/2607.02292) |

## Worth studying

- [MerLin: differentiable photonic QML framework](https://www.quandela.com/resources/blog/merlin-reproducible-photonic-quantum-machine-learning-framework/) — Quandela (github.com/merlinquantum/merlin): PyTorch-native `QuantumLayer` for end-to-end differentiable training of linear-optical circuits, aimed at closing the reproducibility gap in photonic QML research.
- [Surface code logical operations on a superconducting quantum processor (arXiv:2607.01473)](https://arxiv.org/abs/2607.01473) — Lin, Guo, Ma et al. (USTC/Zhu-Pan group, Jul 2026): experimentally realizes patch-based surface-code logical operations on a 107-qubit superconducting processor — a flagship large-scale demonstration of logical-operation techniques.
- [Mechanistic Interpretability and Causal Feature Steering of Neural Quantum States via Sparse Autoencoders (arXiv:2607.01336)](https://arxiv.org/abs/2607.01336) — Qi, Earls (Jul 2026): imports LLM mechanistic-interpretability tooling to open up the black box of Neural Quantum States — a notable cross-boundary methodology.
- [When AI meets quantum information: A comprehensive review (arXiv:2607.00365)](https://arxiv.org/abs/2607.00365) — Chen, Gan, Jin et al. (18 authors, Jul 1): two-directional survey of AI-for-QI and QI-for-AI — a strong orientation map for this field.
- [A Machine-Verified Proof of a Quantum-Optimization Conjecture (arXiv:2606.29687)](https://arxiv.org/abs/2606.29687) — Kol, Ben-Shahar, Sulimany, Englund (MIT, Jun 29): resolves a decade-old QAOA conjecture using an LLM-found proof verified end-to-end in Lean 4.
- [Machine Learning Decoding of Circuit-Level Noise for Bivariate Bicycle Codes (Quantum journal)](https://quantum-journal.org/papers/q-2026-06-30-2149/) — Blue, Avlani, He, Ziyin, Chuang (MIT, Jun 30): peer-reviewed neural decoder for bivariate bicycle QEC codes under circuit-level noise.
- [erado: open-source erasure-noise + postselection simulator (arXiv:2606.31428)](https://arxiv.org/abs/2606.31428) — Griffiths, Friel, Vlastakis: ready-to-use framework for evaluating postselection-based error mitigation, with a concrete erasure-check error-rate threshold for full mitigation.
- [Learning the structure of open quantum systems (arXiv:2606.30358)](https://arxiv.org/abs/2606.30358) — Lewis, Tang, Wright (Jun 2026): learns an n-qubit constant-local Lindbladian to ε error with O(g·d²·log n / ε²) total evolution time — efficient identification of open-system dynamics. Classical-quantum-boundary / quantum-learning result from a notable group (Ewin Tang); a rigorous benchmark for how cheaply quantum dynamics can be learned.
- [Google Quantum Echoes: verifiable advantage on Willow (arXiv:2506.10191)](https://arxiv.org/abs/2506.10191) — Google Quantum AI (Nature Oct 2025): first claimed verifiable quantum advantage using OTOC algorithm; unlike random circuit sampling, OTOCs are verifiable on another quantum computer or natural system AND beyond classical simulation (Google's claim). Dequantization status UNVERIFIED — independent assessment needed before citing as settled.
- [20 Second Parity Lifetime in InAs-Pb Tetron (arXiv:2606.03884)](https://arxiv.org/abs/2606.03884) — Microsoft Quantum (June 2026): 20-second parity lifetime in a topological qubit device, orders of magnitude beyond typical qubit operation times; validates excitation-gap scaling for FTQC-grade topological qubits
- [Foundation decoders for fault-tolerant QC](https://arxiv.org/abs/2606.27119) — high-capacity neural decoders now outperform classical decoders at large code distances; directly relevant to practical FTQC timelines
- [Qiskit Paulice: postselected QEC for near-term circuits](https://www.ibm.com/quantum/blog/qiskit-paulice) — immediately usable Qiskit addon for low-overhead error detection; bridges NISQ error mitigation to fault-tolerant architectures

## Community pulse

_Unverified intake — community signals, not trend evidence; this is a weekly recalibration run, so pulse reflects the most recent daily scan (2026-07-03)._

- [r/QuantumComputing](https://old.reddit.com/r/QuantumComputing/) access restored via the old-reddit domain after 5 consecutive blocked scans; current threads are general Q&A, no new primaries named.
- [Quantum Computing Stack Exchange](https://quantumcomputing.stackexchange.com/) surfaced only routine Q&A threads — no primaries to follow.
- [Hacker News](https://hn.algolia.com/?query=quantum) front page and quantum search showed no field-shaking item — no earthquake this week.
- Qiskit's and Sabine Hossenfelder's [YouTube channels](https://www.youtube.com/feeds/videos.xml?channel_id=UC1yNl2E66ZzKApQdRuTQ4tw) posted no new quantum-computing-specific content since the last scan.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (25)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-07-03](reports/2026-07-03.md) · weekly: [2026-W27](reports/weekly/2026-W27.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

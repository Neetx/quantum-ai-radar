# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-13-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-7-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-31-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--08--13-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-08-13):**
- **Evidence cap filled: [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions)** gains a 10th independent group — [Hamilton-Zero](https://arxiv.org/abs/2608.11911), a ~0.5B-parameter foundation model trained with LLM/RL techniques, evaluated on ground states up to 8100 qubits.
- **Three standing cap-swap candidates graduated to evidence** via cap-swaps — [Newton-Schulz HQMM](https://arxiv.org/abs/2608.06554) into [quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning), an [honest quantum-attention ablation](https://arxiv.org/abs/2608.06846) into [advantage skepticism](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations), and [multi-agent qLDPC code discovery](https://arxiv.org/abs/2608.08996) into [LLM/agentic quantum reasoning](TRENDS.md#id-trend-009-llmagentic-ai-reasoning-about-quantum-circuits-algorithms-and-proofs).
- **New study picks** — Hamilton-Zero (above) and a comprehensive peer-reviewed [Pauli propagation simulation framework](http://link.aps.org/doi/10.1103/6vd7-l9bn) from EPFL/Algorithmiq.
- **Watchlist: 30 → 31** — 8 items added, 7 resolved (3 promoted, 4 dropped).

## Trends

🌱 2 · 📈 3 · 🚀 7 · 🌊 0 · 🏔 0 · 📉 0 · 💤 1

| trend | stage | latest signal |
|-------|-------|---------------|
| [LLM/agentic quantum reasoning](TRENDS.md#id-trend-009-llmagentic-ai-reasoning-about-quantum-circuits-algorithms-and-proofs) | 🚀 accelerating | [2026-08-10](https://arxiv.org/abs/2608.08996) |
| [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) | 🚀 accelerating | [2026-08-10](https://arxiv.org/abs/2608.10382) |
| [Quantum-advantage frontier](TRENDS.md#id-trend-011-quantum-advantage-frontier-provable-learning-separations-and-honest-quantum-classical-crossovers) | 🚀 accelerating | [2026-08-04](https://arxiv.org/abs/2608.03962) |
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-07-29](https://arxiv.org/abs/2607.25941) |
| [AI-for-quantum (hardware)](TRENDS.md#id-trend-002-ai-for-quantum-hardware-leg-classical-ml-for-quantum-hardware-control-calibration-decoding-and-circuit-design) | 🚀 accelerating | [2026-07-27](https://developer.nvidia.com/blog/nvidia-ising-enables-fully-automated-quantum-computer-calibration-with-enhanced-in-context-learning/) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 🚀 accelerating | [2026-07-27](https://arxiv.org/abs/2607.24728) |
| [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) | 📈 emerging | [2026-08-12](https://arxiv.org/abs/2608.11911) |
| [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) | 🚀 accelerating | [2026-08-06](https://arxiv.org/abs/2608.06846) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 📈 emerging | [2026-08-06](https://arxiv.org/abs/2608.06554) |
| [QML generalization theory](TRENDS.md#id-trend-007-qml-generalization-theory-bounds-phenomenology-and-the-reference-structure-requirement) | 📈 emerging | [2026-07-28](https://www.nature.com/articles/s41534-026-01330-y) |
| [Agentic AI lab automation](TRENDS.md#id-trend-013-agentic-ai-directly-operating-quantum-hardware-and-lab-infrastructure-end-to-end) | 🌱 seed | [2026-07-28](https://arxiv.org/abs/2607.25834) |
| [AI-for-quantum (circuit synthesis)](TRENDS.md#id-trend-012-ai-for-quantum-circuit-synthesis-leg-generativetransformer-models-that-directly-synthesize-quantum-circuits) | 🌱 seed | [2026-07-24](https://arxiv.org/abs/2607.22468) |
| [QML security & adversarial robustness](TRENDS.md#id-trend-010-qml-security--adversarial-robustness-attacks-on-and-defenses-for-variational-quantum-models) | 💤 dormant | [2026-07-21](https://arxiv.org/abs/2607.19318) |

## Worth studying

- [Hamilton-Zero: A Neural Tensor-Network Foundation Model for Ground States of Arbitrary Quadratic Qubit Hamiltonians (arXiv:2608.11911)](https://arxiv.org/abs/2608.11911) — Heightman, Orlova, Mantrov, Ustimenko (Aug 12): a ~0.5B-parameter foundation model, trained with LLM/deep-RL techniques, amortizes ground-state search across an arbitrary set of Hamiltonians — trained up to 64 qubits, fine-tuned up to 1024, evaluated up to 8100.
- [Pauli Propagation: A Computational Framework for Simulating Quantum Systems (PRX Quantum 7, 032001)](http://link.aps.org/doi/10.1103/6vd7-l9bn) — Rudolph, Jones, Teng, Angrisani, Holmes (EPFL/Algorithmiq, Aug 11): a comprehensive, peer-reviewed account of Pauli propagation as a classical simulation method for digital quantum circuits, and its use in verifying/challenging near-term hardware claims.
- [Convolutional QFT: a constructive compilation strategy for the Quantum Fourier Transform (arXiv:2608.05435)](https://arxiv.org/abs/2608.05435) — Coote, Biercuk, Baum (Q-CTRL, Aug 5): a 100-qubit QFT on IBM hardware, the largest experimental QFT to date, honestly reporting declining process fidelity at scale rather than claiming "advantage."
- [The Input Problem: A Permanent Bottleneck for Quantum Machine Learning (arXiv:2608.08433)](https://arxiv.org/abs/2608.08433) — Muhammad Faryad (Aug 7): measured gate counts for classical-data-loading circuits show the resulting Θ(N) cost is a counting theorem, not an engineering limitation — and it eliminates the quadratic advantage several QML algorithms claim.
- [Multi-agent discovery of practical quantum LDPC codes (arXiv:2608.08996)](https://arxiv.org/abs/2608.08996) — Qian, Li (Aug 10): a multi-agent AI-scientist framework discovers qLDPC codes with leading or competitive rate-distance performance across every weight class tested — a working instance of agentic AI doing genuine QEC code design.
- [Fast, accurate, high-resolution simulation of large-scale Fermi-Hubbard models on a digital quantum processor (arXiv:2605.04025)](https://arxiv.org/abs/2605.04025) — Hartnett, Najafi, Khindanov et al. (Q-CTRL, May 5, updated Aug 2026): a 120-qubit digital simulation matching TDVP tensor-network methods while running ~3 orders of magnitude faster at the classical-agreement frontier — the technical primary behind Q-CTRL's "practical quantum advantage" claim.
- [NS-RIS: Newton-Schulz Retraction-Based Inference Enables HQMMs to Outperform Classical HMMs (arXiv:2608.06554)](https://arxiv.org/abs/2608.06554) — Ning Ning (Aug 6): the first benchmark evidence a Hidden Quantum Markov Model can significantly and consistently outperform an EM-trained classical HMM on non-quantum-generated data.
- [Frozen-Tree Sampling Refutes Quantum Advantage of Random Circuit Sampling (arXiv:2607.04054)](https://arxiv.org/abs/2607.04054) — Sangchul Oh (Jul 4): an efficient classical sampler statistically indistinguishable from a random quantum circuit's output — a sharp, self-contained challenge to random-circuit-sampling as an advantage benchmark.
- [Machine learning for sample-based quantum diagonalization (arXiv:2608.05314)](https://arxiv.org/abs/2608.05314) — Bonilla Vargas (Aug 6): a critical review of generative and learned electronic-configuration selectors for SQD/QSCI, the pragmatic centre of gravity of pre-fault-tolerant quantum chemistry.
- [An entangling gate for dual-rail erasure qubits (Nature 656, 47–53)](https://www.nature.com/articles/s41586-026-10822-y) — D-Wave Quantum Inc. (published Aug 6): a fast, low-error two-qubit entangling gate for superconducting dual-rail erasure qubits, ~99.9% two-qubit fidelity — a flagship hardware milestone for the error-hierarchy-engineering approach to QEC.
- [Separating quantum circuits from classical LLMs (arXiv:2608.03962)](https://arxiv.org/abs/2608.03962) — Arunachalam, Dutt, Krovi, Sengupta (IBM, Aug 4): unconditional separations between low-depth quantum computation and the transformer/diffusion-LM architectures behind modern LLMs — the first result of its kind, framed as opening "the study of quantum advantage in the era of large language models."
- [Weak Permanent Anti-Concentration for Random Gaussian Matrices in Boson Sampling (arXiv:2607.22088)](https://arxiv.org/abs/2607.22088) — Meng, Cheng, Li, Yung (Jul 24): resolves the open case of the permanent anti-concentration conjecture underlying boson sampling's classical-hardness argument.

## Community pulse

_Unverified intake — community signals, not trend evidence._

- A prominent independent voice's blog post reports (third-hand, unverified, no paper) that an unreleased AI model has solved several open math/theoretical-CS problems, including one touching quantum-game parallel repetition — see [Shtetl-Optimized](https://scottaaronson.blog/?p=9979); treated as an extreme-hype-skepticism watch item pending any actual technical writeup.
- [Hacker News](https://news.ycombinator.com/) and [r/QuantumComputing](https://old.reddit.com/r/QuantumComputing/) continue discussing the [IACR eprint](https://eprint.iacr.org/2026/1591) claiming a polynomial-time quantum algorithm for lattice problems via the Dihedral Coset Problem — still no refutation or independent reproduction reported.
- [r/QuantumComputing](https://old.reddit.com/r/QuantumComputing/) discussion continues to echo skepticism about a major vendor's recent hardware claims, alongside its usual recurring threads — nothing new on-axis.
- YouTube's Qiskit and Sabine Hossenfelder feeds remain down (`/feeds/videos.xml` 404) — a structural break flickering since late July, low-stakes since this is an intake-only lane.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (31)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-08-13](reports/2026-08-13.md) · weekly: [2026-W32](reports/weekly/2026-W32.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

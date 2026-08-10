# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-13-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-7-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-26-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--08--10-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-08-10):**
- **Two strong cap-swap candidates flagged for the next weekly** — [NS-RIS](https://arxiv.org/abs/2608.06554), the first genuine benchmark evidence a Hidden Quantum Markov Model beats a classical HMM ([quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning)), and a rigorously-controlled ablation finding [no consistent quantum contribution](https://arxiv.org/abs/2608.06846) from a hybrid attention model ([quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations)).
- **Vendor claim traced to its primary** — Q-CTRL's "practical quantum advantage" (3,000×) blog post traces to [arXiv:2605.04025](https://arxiv.org/abs/2605.04025), a 120-qubit Fermi-Hubbard simulation whose own framing is more careful than the marketing.
- **Dormancy watch: [QML security](TRENDS.md#id-trend-010-qml-security--adversarial-robustness-attacks-on-and-defenses-for-variational-quantum-models)** — now 20 days quiet, one day short of the dormancy line.
- **Watchlist: 21 → 26** — 8 items added (incl. an off-taxonomy catch via a raw cs.ET exploration sweep), 3 dropped.

## Trends

🌱 3 · 📈 3 · 🚀 7 · 🌊 0 · 🏔 0 · 📉 0 · 💤 0

| trend | stage | latest signal |
|-------|-------|---------------|
| [Quantum-advantage frontier](TRENDS.md#id-trend-011-quantum-advantage-frontier-provable-learning-separations-and-honest-quantum-classical-crossovers) | 🚀 accelerating | [2026-08-04](https://arxiv.org/abs/2608.03962) |
| [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) | 🚀 accelerating | [2026-07-31](https://arxiv.org/abs/2607.29219) |
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-07-29](https://arxiv.org/abs/2607.25941) |
| [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) | 🚀 accelerating | [2026-07-29](https://arxiv.org/abs/2504.05336) |
| [LLM/agentic quantum reasoning](TRENDS.md#id-trend-009-llmagentic-ai-reasoning-about-quantum-circuits-algorithms-and-proofs) | 🚀 accelerating | [2026-07-28](https://arxiv.org/abs/2607.25865) |
| [AI-for-quantum (hardware)](TRENDS.md#id-trend-002-ai-for-quantum-hardware-leg-classical-ml-for-quantum-hardware-control-calibration-decoding-and-circuit-design) | 🚀 accelerating | [2026-07-27](https://developer.nvidia.com/blog/nvidia-ising-enables-fully-automated-quantum-computer-calibration-with-enhanced-in-context-learning/) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 🚀 accelerating | [2026-07-27](https://arxiv.org/abs/2607.24728) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 📈 emerging | [2026-07-30](https://arxiv.org/abs/2607.28866) |
| [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) | 📈 emerging | [2026-07-28](https://arxiv.org/abs/2607.26131) |
| [QML generalization theory](TRENDS.md#id-trend-007-qml-generalization-theory-bounds-phenomenology-and-the-reference-structure-requirement) | 📈 emerging | [2026-07-28](https://www.nature.com/articles/s41534-026-01330-y) |
| [Agentic AI lab automation](TRENDS.md#id-trend-013-agentic-ai-directly-operating-quantum-hardware-and-lab-infrastructure-end-to-end) | 🌱 seed | [2026-07-28](https://arxiv.org/abs/2607.25834) |
| [AI-for-quantum (circuit synthesis)](TRENDS.md#id-trend-012-ai-for-quantum-circuit-synthesis-leg-generativetransformer-models-that-directly-synthesize-quantum-circuits) | 🌱 seed | [2026-07-24](https://arxiv.org/abs/2607.22468) |
| [QML security & adversarial robustness](TRENDS.md#id-trend-010-qml-security--adversarial-robustness-attacks-on-and-defenses-for-variational-quantum-models) | 🌱 seed | [2026-07-21](https://arxiv.org/abs/2607.19318) |

## Worth studying

- [Fast, accurate, high-resolution simulation of large-scale Fermi-Hubbard models on a digital quantum processor (arXiv:2605.04025)](https://arxiv.org/abs/2605.04025) — Hartnett, Najafi, Khindanov et al. (Q-CTRL, May 5, updated Aug 2026): a 120-qubit digital simulation matching TDVP tensor-network methods while running ~3 orders of magnitude faster at the classical-agreement frontier — the technical primary behind Q-CTRL's "practical quantum advantage" claim.
- [NS-RIS: Newton-Schulz Retraction-Based Inference Enables HQMMs to Outperform Classical HMMs (arXiv:2608.06554)](https://arxiv.org/abs/2608.06554) — Ning Ning (Aug 6): the first benchmark evidence a Hidden Quantum Markov Model can significantly and consistently outperform an EM-trained classical HMM on non-quantum-generated data.
- [Frozen-Tree Sampling Refutes Quantum Advantage of Random Circuit Sampling (arXiv:2607.04054)](https://arxiv.org/abs/2607.04054) — Sangchul Oh (Jul 4): an efficient classical sampler statistically indistinguishable from a random quantum circuit's output — a sharp, self-contained challenge to random-circuit-sampling as an advantage benchmark.
- [Machine learning for sample-based quantum diagonalization (arXiv:2608.05314)](https://arxiv.org/abs/2608.05314) — Bonilla Vargas (Aug 6): a critical review of generative and learned electronic-configuration selectors for SQD/QSCI, the pragmatic centre of gravity of pre-fault-tolerant quantum chemistry.
- [An entangling gate for dual-rail erasure qubits (Nature 656, 47–53)](https://www.nature.com/articles/s41586-026-10822-y) — D-Wave Quantum Inc. (published Aug 6): a fast, low-error two-qubit entangling gate for superconducting dual-rail erasure qubits, ~99.9% two-qubit fidelity — a flagship hardware milestone for the error-hierarchy-engineering approach to QEC.
- [Separating quantum circuits from classical LLMs (arXiv:2608.03962)](https://arxiv.org/abs/2608.03962) — Arunachalam, Dutt, Krovi, Sengupta (IBM, Aug 4): unconditional separations between low-depth quantum computation and the transformer/diffusion-LM architectures behind modern LLMs — the first result of its kind, framed as opening "the study of quantum advantage in the era of large language models."
- [Weak Permanent Anti-Concentration for Random Gaussian Matrices in Boson Sampling (arXiv:2607.22088)](https://arxiv.org/abs/2607.22088) — Meng, Cheng, Li, Yung (Jul 24): resolves the open case of the permanent anti-concentration conjecture underlying boson sampling's classical-hardness argument.
- [Hybrid Quantum Neural Networks: Theory, Implementations, and Applications (arXiv:2608.01194)](https://arxiv.org/abs/2608.01194) — Monbroussou, Periyasamy, Kuzmin, Sekatski, Patapovich, Sagingalieva (Aug 2): a broad orientation-map review of hybrid QNN architectures, benchmarks and applications.
- [High-rate qLDPC processors (arXiv:2607.28795)](https://arxiv.org/abs/2607.28795) — Bhardwaj, Ma, Meister, King, Bluvstein, Preskill et al. (Jul 30): "mitten codes," a non-abelian qLDPC processor-code family reaching distance 18+ with only a few hundred data qubits, evading the distance bounds that constrain abelian constructions.
- [Gaussian-augmented bosonic matrix-product states (arXiv:2607.28753)](https://arxiv.org/abs/2607.28753) — Tjoa, Cirac (Jul 30): a classical-simulation tool generalizing Gaussian states and matrix-product states for bosonic many-body systems, from a leading authority on the classical-quantum boundary.
- [Triangle Criterion: A Mixed-State Magic Criterion with Applications in Distillation and Detection (PRX Quantum 7, 033016)](https://doi.org/10.1103/rcpf-8nh9) — Liu, Haug, Ye, Liu, Roth (Jul 24): a simple criterion for detecting nonstabilizerness ("magic") and certifying undistillability of mixed quantum states.
- [Quantum Convolutional HLA Immunogenic Peptide Prediction (Q-CHIPP) (Science Advances, doi:10.1126/sciadv.aec3824)](https://www.biorxiv.org/content/10.1101/2025.07.29.667313v1) — Peters, Rhrissorrakrai et al. (IBM/Cleveland Clinic, published Jul 30): a quantum convolutional neural network unifying MHC-binding and immunogenicity prediction for cancer neoantigens, scaled to 46 qubits of real hardware.

## Community pulse

_Unverified intake — community signals, not trend evidence._

- [Hacker News](https://news.ycombinator.com/) continues discussion of the [IACR eprint](https://eprint.iacr.org/2026/1591) claiming a polynomial-time quantum algorithm for lattice problems via the Dihedral Coset Problem — provenance confirmed (received Aug 3, approved Aug 6, sole-authored, not peer-reviewed), still no refutation or independent reproduction reported, still unverified.
- [r/QuantumComputing](https://old.reddit.com/r/QuantumComputing/) discussion echoes ongoing skepticism about a major vendor's recent hardware claims, alongside its usual recurring threads — nothing new on-axis.
- YouTube's Qiskit and Sabine Hossenfelder feeds are healthy again this scan, after flickering between healthy and dead over the prior two weeks.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (26)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-08-10](reports/2026-08-10.md) · weekly: [2026-W32](reports/weekly/2026-W32.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

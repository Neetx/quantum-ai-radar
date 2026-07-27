# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-11-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-6-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-27-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--07--27-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-07-25):**
- **[Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) gains a 6th independent group** — a utility-scale, real-hardware (100+ qubit `ibm_marrakesh`) [QRC/quantum-kernel demo](https://arxiv.org/abs/2605.24252) for real Smart Meter time-series forecasting, honestly reporting the simulator-to-hardware gap.
- **Two "missed-item" catches** surfaced via vendor-blog and digest cross-checks: the QRC item above, plus an IonQ/QuantumBasel [hardware-instrumented quantum-fine-tuning energy study](https://arxiv.org/abs/2605.02798) — both now on the [study shelf](#worth-studying).
- **AI-for-quantum ML-circuit-generation cluster reaches 3 groups** inside [AI-for-quantum (hardware)](TRENDS.md#id-trend-002-ai-for-quantum-hardware-leg-classical-ml-for-quantum-hardware-control-calibration-decoding-and-circuit-design) — [autoregressive-drift](https://arxiv.org/abs/2607.12780), [DQAOA-GPT](https://arxiv.org/abs/2607.20225) and a new [transformer-based molecular-ground-state synthesizer](https://arxiv.org/abs/2607.22468) all cap-blocked, watched for a future cap-swap.
- **Watchlist grew 17 → 27** on a 10-capture day (most trend caps are frozen full) — full reasons in [reports/2026-07-27](reports/2026-07-27.md).

## Trends

🌱 1 · 📈 4 · 🚀 6 · 🌊 0 · 🏔 0 · 📉 0 · 💤 0

| trend | stage | latest signal |
|-------|-------|---------------|
| [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) | 🚀 accelerating | [2026-07-23](https://arxiv.org/abs/2607.21337) |
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-07-21](https://arxiv.org/abs/2607.19563) |
| [Quantum-advantage frontier](TRENDS.md#id-trend-011-quantum-advantage-frontier-provable-learning-separations-and-honest-quantum-classical-crossovers) | 🚀 accelerating | [2026-07-21](https://arxiv.org/abs/2607.19017) |
| [AI-for-quantum (hardware)](TRENDS.md#id-trend-002-ai-for-quantum-hardware-leg-classical-ml-for-quantum-hardware-control-calibration-decoding-and-circuit-design) | 🚀 accelerating | [2026-07-16](https://arxiv.org/abs/2607.14884) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 🚀 accelerating | [2026-07-14](https://arxiv.org/abs/2607.12996) |
| [LLM/agentic quantum reasoning](TRENDS.md#id-trend-009-llmagentic-ai-reasoning-about-quantum-circuits-algorithms-and-proofs) | 🚀 accelerating | [2026-07-14](https://arxiv.org/abs/2607.12981) |
| [QML generalization theory](TRENDS.md#id-trend-007-qml-generalization-theory-bounds-phenomenology-and-the-reference-structure-requirement) | 📈 emerging | [2026-07-23](https://arxiv.org/abs/2607.21409) |
| [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) | 📈 emerging | [2026-07-21](https://arxiv.org/abs/2607.18865) |
| [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) | 📈 emerging | [2026-07-15](https://arxiv.org/abs/2607.14311) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 📈 emerging | [2026-07-10](https://arxiv.org/abs/2607.09113) |
| [QML security & adversarial robustness](TRENDS.md#id-trend-010-qml-security--adversarial-robustness-attacks-on-and-defenses-for-variational-quantum-models) | 🌱 seed | [2026-07-21](https://arxiv.org/abs/2607.19318) |

## Worth studying

- [Hybrid Quantum-Classical Machine Learning Algorithms for Multi-Output Time-Series Forecasting at Utility Scale (arXiv:2605.24252)](https://arxiv.org/abs/2605.24252) — Polché, Puram, Lal et al. (E.ON/WISER, May 22): two hybrid QRC/quantum-kernel models forecast 103 real household Smart Meter time-series on a real 100+ qubit IBM processor, honestly reporting where the simulator-to-hardware gap bites and where the advantage survives.
- [Measuring Accuracy and Energy-to-Solution of Quantum Fine-Tuning of Foundational AI Models (arXiv:2605.02798)](https://arxiv.org/abs/2605.02798) — Knitter, Kim, Wurzer et al. (IonQ/QuantumBasel, May 4): directly instruments power consumption on a real trapped-ion QPU running hybrid fine-tuning end-to-end — QPU energy scales linearly with qubit count vs exponential classical simulation, an experimentally grounded break-even around 34 qubits.
- [Efficient classical simulation of large-scale unitary cluster Jastrow circuits (arXiv:2607.21337)](https://arxiv.org/abs/2607.21337) — Belagali, Van Camp, Pradeep, Das, Anand, LaRose (Jul 23): a polynomial-time classical algorithm computes the energy of any single-layer unitary cluster Jastrow circuit, reproducing the largest such quantum-chemistry experiment to date (77-qubit / 10,570-gate IBM run, originally post-processed on 6400 Fugaku nodes) in under a minute on a laptop — and reaching a LOWER ground-state energy than the hardware. A self-contained dequantization of a flagship UCJ "advantage" claim.
- [Benchmarking Agents for Proving Theorems in Quantum Algorithms and Quantum Information (arXiv:2607.21533)](https://arxiv.org/abs/2607.21533) — Xin Wang group (Jul 23): ships Lean-QuantumAlg-Bench (36 tasks) and Lean-QIT-Bench (40 tasks) with deterministic proof checking, and evaluates four frontier models under a task-only baseline vs a verified-library-augmented setting (best ~60/100; the library helps in all 8 comparisons, up to +15.9 pts). A reproducible evaluation baseline for AI-assisted quantum-theorem-proving.
- [Efficiently Simulable Pauli Correlation Encoding (arXiv:2607.20409)](https://arxiv.org/abs/2607.20409) — (Jul 22): dequantises Pauli Correlation Encoding — a qubit-frugal binary-optimisation heuristic — by computing its required many-body Pauli expectation values CLASSICALLY when the encoding uses free-fermionic (matchgate) or IQP circuits. A ready-made dequantised baseline any future quantum-PCE "advantage" must clear.
- [Universal topological gates via braiding + fusing S3 anyons on Quantinuum H2 (arXiv:2601.20956)](https://arxiv.org/abs/2601.20956) — Lo, Lyons, Gresh … Vishwanath, Verresen, Iqbal (Quantinuum / Harvard / UChicago / Stony Brook; now in Nature): a COMPLETE universal fault-tolerant gate set via anyon fusion + braiding — universal topological computation *without* magic-state distillation. A genuinely different route from the surface-code/QLDPC path.
- [Backpropagating Pauli Propagation (arXiv:2607.15184)](https://arxiv.org/abs/2607.15184) — Lin, Granet, Hémery, Dreyer (Quantinuum, Jul 16): a backprop algorithm for parameter gradients via classical Pauli-propagation simulation — O(n_param) less memory than reverse-mode autodiff. A directly-usable classical tool for optimizing quantum circuits.
- [When Classical Baselines Are Tuned as Carefully as the Quantum Model, Does Quantum Reservoir Computing Still Win? (arXiv:2607.09905)](https://arxiv.org/abs/2607.09905) — Tushar Pandey (Jul 10): gives the classical QRC competitor the SAME size and tuning budget — and the advantage vanishes. Essential reading for anyone benchmarking QRC (or any QML) against classical methods.
- [NVIDIA Ising Decoding Cuts Color Code Logical Error Rates by Over 300X](https://developer.nvidia.com/blog/nvidia-ising-decoding-cuts-color-code-logical-error-rates-by-over-300x) — NVIDIA Quantum Computing Division (Jul 13): an open AI-for-quantum decoder release, >347× better logical error rate than Chromobius for a d=31 triangular color code — NVIDIA opens the model family (weights + training cookbook).
- [Aligning Quantum Operators with Large Language Models (arXiv:2606.13811)](https://arxiv.org/abs/2606.13811) — Feris, Liu, Li, Hua, Kremer (MIT-IBM Watson AI Lab / IBM, Jun 11): maps unitary operators into an LLM's latent space so one model reasons jointly over quantum and linguistic inputs, enabling language-conditioned circuit synthesis.
- [Diagnosing quantum reservoirs at scale based on expressivity and coverage (arXiv:2607.09445)](https://arxiv.org/abs/2607.09445) — Domingo, Balló-Gimbernat, Vilariño (Jul 10): a scalable, hardware-agnostic way to CHOOSE a quantum reservoir without training it. A directly-usable design tool for the quantum-reservoir-computing sub-field.
- [Plaquette: A hardware-aware design platform for fault-tolerant quantum computers (arXiv:2607.08767)](https://arxiv.org/abs/2607.08767) — Conchello Vendrell, Dhand, Plenio et al. (Xanadu/Ulm, Jul 9): auto-compiles a device's actual open-system error model into the right sampler class, letting hardware teams compute logical FTQC performance directly from device physics.

## Community pulse

_Unverified intake — community signals, not trend evidence._

- A skeptical [r/QuantumComputing](https://old.reddit.com/r/QuantumComputing/) thread pushes back on a D-Wave/Japan Tobacco "quantum AI" drug-discovery announcement — the radar could not locate the technical write-up the thread references, so the claim stays unverified per the Hard rules (vendor PR is never evidence on its own).
- Vendor consolidation news (IBM to acquire HRL Laboratories) continues to circulate; business/roadmap PR, intake-only.
- [Hacker News](https://news.ycombinator.com/) had no new quantum front-page item this scan; the recurring post-quantum-crypto/QC-timeline-skepticism threads remain off-axis or already tracked.
- Digest traffic (The Quantum Insider, Quantum Computing Report, Quantum Zeitgeist) is dominated by funding/business/policy PR this scan; one digest pointer did lead to a genuine missed technical primary (see "Worth studying" above).

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (27)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-07-27](reports/2026-07-27.md) · weekly: [2026-W30](reports/weekly/2026-W30.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

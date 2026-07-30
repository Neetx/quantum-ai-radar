# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-11-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-6-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-29-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--07--30-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-07-29):**
- **[Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) fills its evidence cap at 7 groups** — [Krüger & Mauerer's magic/non-stabiliserness resource analysis](https://arxiv.org/abs/2607.26711) of IQP generative circuits links this trend directly to the classical-quantum-boundary axis.
- **[Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) fills its evidence cap at 10 groups** — [Hellstern et al.'s symmetric-hyperparameter honest baseline](https://arxiv.org/abs/2607.24065) finds no systematic quantum advantage in Boltzmann-machine time-series forecasting.
- **[Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) gains a 7th independent group** — [NQS extended to non-Abelian lattice gauge theories](https://arxiv.org/abs/2607.26131), broadening the sub-field beyond condensed-matter spin models.
- **Watchlist held at 29** (5 dropped, 5 added — content refreshed, still above the ~25 target) — full reasons in [reports/2026-07-30](reports/2026-07-30.md).

## Trends

🌱 1 · 📈 4 · 🚀 6 · 🌊 0 · 🏔 0 · 📉 0 · 💤 0

| trend | stage | latest signal |
|-------|-------|---------------|
| [Quantum-advantage frontier](TRENDS.md#id-trend-011-quantum-advantage-frontier-provable-learning-separations-and-honest-quantum-classical-crossovers) | 🚀 accelerating | [2026-07-28](https://arxiv.org/abs/2607.25492) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 🚀 accelerating | [2026-07-27](https://arxiv.org/abs/2607.24014) |
| [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) | 🚀 accelerating | [2026-07-27](https://arxiv.org/abs/2607.24065) |
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-07-21](https://arxiv.org/abs/2607.19563) |
| [AI-for-quantum (hardware)](TRENDS.md#id-trend-002-ai-for-quantum-hardware-leg-classical-ml-for-quantum-hardware-control-calibration-decoding-and-circuit-design) | 🚀 accelerating | [2026-07-16](https://arxiv.org/abs/2607.14884) |
| [LLM/agentic quantum reasoning](TRENDS.md#id-trend-009-llmagentic-ai-reasoning-about-quantum-circuits-algorithms-and-proofs) | 🚀 accelerating | [2026-07-14](https://arxiv.org/abs/2607.12981) |
| [QML generalization theory](TRENDS.md#id-trend-007-qml-generalization-theory-bounds-phenomenology-and-the-reference-structure-requirement) | 📈 emerging | [2026-07-28](https://www.nature.com/articles/s41534-026-01330-y) |
| [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) | 📈 emerging | [2026-07-28](https://arxiv.org/abs/2607.26131) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 📈 emerging | [2026-07-27](https://arxiv.org/abs/2607.24399) |
| [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) | 📈 emerging | [2026-07-15](https://arxiv.org/abs/2607.14311) |
| [QML security & adversarial robustness](TRENDS.md#id-trend-010-qml-security--adversarial-robustness-attacks-on-and-defenses-for-variational-quantum-models) | 🌱 seed | [2026-07-21](https://arxiv.org/abs/2607.19318) |

## Worth studying

- [MPStab: an hybrid stabilizers tensor-network quantum circuit simulator (arXiv:2607.24258)](https://arxiv.org/abs/2607.24258) — Crognaletti, Robbiano, Grossi, Robbiati (Jul 27): an open-source simulator combining the stabilizer formalism with tensor networks, pushing the frontier of what a classical computer can simulate before hitting the genuinely-hard regime — a reality-check tool for evaluating advantage claims.
- [Generative AI Beyond Tokens: Quantum Resource Consumption of IQP Circuits (arXiv:2607.26711)](https://arxiv.org/abs/2607.26711) — Krüger, Mauerer (Jul 27): reframes quantum generative modeling through a resource-theoretic lens — not just "does it fit the target?" but "how much magic (non-stabiliserness) does it actually consume?" — connecting generative QML directly to the classical-quantum-boundary question.
- [Lowering the implementation barrier of neutral-atom quantum computing with agentic workflows (arXiv:2607.25834)](https://arxiv.org/abs/2607.25834) — Dalyac, Dauphin, Henriet, Jurczak (Pasqal, Jul 28): an LLM agentic workflow runs the full design→compilation→execution pipeline on two real Pasqal QPUs overnight, honestly reporting the failure modes a human had to catch. A concrete, appropriately-skeptical demonstration of agentic AI operating real quantum hardware end-to-end.
- [Observable Estimation in the Absence of Classical Verification (arXiv:2607.25998)](https://arxiv.org/abs/2607.25998) — IBM Quantum (~40 authors incl. Zoë Holmes, Jul 28): a framework for trusting quantum-simulation results once classical ground truth becomes intractable, cross-checking quantum heuristics against each other via a new "operator Loschmidt echo" diagnostic. A methodological cornerstone for evaluating advantage claims that outrun classical verification.
- [NVIDIA Ising Enables Fully Automated Quantum Computer Calibration](https://developer.nvidia.com/blog/nvidia-ising-enables-fully-automated-quantum-computer-calibration-with-enhanced-in-context-learning/) — NVIDIA Quantum Computing Division (Jul 27): NVIDIA Ising Calibration 1.5, a 31B-parameter vision-language model that diagnoses and tunes quantum processors directly from calibration plots, with a new QCalEval benchmark and a single-GPU-deployable quantized build — pairs with NVIDIA's own decoder release to cover both halves of the AI-for-quantum-hardware stack.
- [Hybrid Quantum-Classical Machine Learning Algorithms for Multi-Output Time-Series Forecasting at Utility Scale (arXiv:2605.24252)](https://arxiv.org/abs/2605.24252) — Polché, Puram, Lal et al. (E.ON/WISER, May 22): two hybrid QRC/quantum-kernel models forecast 103 real household Smart Meter time-series on a real 100+ qubit IBM processor, honestly reporting where the simulator-to-hardware gap bites and where the advantage survives.
- [Measuring Accuracy and Energy-to-Solution of Quantum Fine-Tuning of Foundational AI Models (arXiv:2605.02798)](https://arxiv.org/abs/2605.02798) — Knitter, Kim, Wurzer et al. (IonQ/QuantumBasel, May 4): directly instruments power consumption on a real trapped-ion QPU running hybrid fine-tuning end-to-end — QPU energy scales linearly with qubit count vs exponential classical simulation, an experimentally grounded break-even around 34 qubits.
- [Efficient classical simulation of large-scale unitary cluster Jastrow circuits (arXiv:2607.21337)](https://arxiv.org/abs/2607.21337) — Belagali, Van Camp, Pradeep, Das, Anand, LaRose (Jul 23): a polynomial-time classical algorithm computes the energy of any single-layer unitary cluster Jastrow circuit, reproducing the largest such quantum-chemistry experiment to date (77-qubit / 10,570-gate IBM run, originally post-processed on 6400 Fugaku nodes) in under a minute on a laptop — and reaching a LOWER ground-state energy than the hardware. A self-contained dequantization of a flagship UCJ "advantage" claim.
- [Benchmarking Agents for Proving Theorems in Quantum Algorithms and Quantum Information (arXiv:2607.21533)](https://arxiv.org/abs/2607.21533) — Xin Wang group (Jul 23): ships Lean-QuantumAlg-Bench (36 tasks) and Lean-QIT-Bench (40 tasks) with deterministic proof checking, and evaluates four frontier models under a task-only baseline vs a verified-library-augmented setting (best ~60/100; the library helps in all 8 comparisons, up to +15.9 pts). A reproducible evaluation baseline for AI-assisted quantum-theorem-proving.
- [Efficiently Simulable Pauli Correlation Encoding (arXiv:2607.20409)](https://arxiv.org/abs/2607.20409) — (Jul 22): dequantises Pauli Correlation Encoding — a qubit-frugal binary-optimisation heuristic — by computing its required many-body Pauli expectation values CLASSICALLY when the encoding uses free-fermionic (matchgate) or IQP circuits. A ready-made dequantised baseline any future quantum-PCE "advantage" must clear.
- [Universal topological gates via braiding + fusing S3 anyons on Quantinuum H2 (arXiv:2601.20956)](https://arxiv.org/abs/2601.20956) — Lo, Lyons, Gresh … Vishwanath, Verresen, Iqbal (Quantinuum / Harvard / UChicago / Stony Brook; now in Nature): a COMPLETE universal fault-tolerant gate set via anyon fusion + braiding — universal topological computation *without* magic-state distillation. A genuinely different route from the surface-code/QLDPC path.
- [Backpropagating Pauli Propagation (arXiv:2607.15184)](https://arxiv.org/abs/2607.15184) — Lin, Granet, Hémery, Dreyer (Quantinuum, Jul 16): a backprop algorithm for parameter gradients via classical Pauli-propagation simulation — O(n_param) less memory than reverse-mode autodiff. A directly-usable classical tool for optimizing quantum circuits.

## Community pulse

_Unverified intake — community signals, not trend evidence._

- [r/QuantumComputing](https://old.reddit.com/r/QuantumComputing/) is discussing "two notable silicon quantum dot articles in Nature" — the community-side echo of the HRL Laboratories cryogenic-QEC demo (see the watchlist).
- [Hacker News](https://news.ycombinator.com/) quantum discussion this scan was routine (post-quantum-crypto threads, a low-engagement pointer to the same HRL Nature paper) — nothing new on-axis beyond what's already queued.
- The D-Wave/Japan Tobacco "quantum AI" drug-discovery claim flagged in earlier scans was dropped from the watchlist this run — no technical primary was ever located despite repeated checks, so it stays out per the Hard rules (vendor PR is never evidence).

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (29)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-07-30](reports/2026-07-30.md) · weekly: [2026-W30](reports/weekly/2026-W30.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

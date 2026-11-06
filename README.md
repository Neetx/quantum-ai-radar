# Quantum AI Radar

![trends](https://img.shields.io/badge/trends-16-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-12-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-28-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--11--06-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-11-06):**
- [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) absorbed [a Google-co-authored QC-AFQMC acceleration paper](https://arxiv.org/abs/2611.08151) — compressing quantum measurement data into ML models to speed up quantum Monte Carlo.
- [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) absorbed [a polynomial-time classical simulator](https://arxiv.org/abs/2611.08444) for boson/fermion sampling under thermal loss.
- [Hamiltonian-parameter learning](TRENDS.md#id-trend-014-learning-hamiltonian-and-dissipative-rate-parameters-of-quantum-systems-from-data) absorbed [an entanglement-Hamiltonian learning paper](https://arxiv.org/abs/2611.07353), resolving this week's dormancy watch with a genuine new catch.
- Watchlist moved to 28 after a 2-item capture-leak fix and 3 fresh finds, minus 2 drops; burndown continues next run.

## Trends

🌱 0 · 📈 4 · 🚀 12 · 🌊 0 · 🏔 0 · 📉 0 · 💤 0

| trend | stage | latest signal |
|-------|-------|---------------|
| [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) | 🚀 accelerating | [2026-11-05](https://arxiv.org/abs/2611.08444) |
| [Quantum-advantage frontier](TRENDS.md#id-trend-011-quantum-advantage-frontier-provable-learning-separations-and-honest-quantum-classical-crossovers) | 🚀 accelerating | [2026-11-05](https://arxiv.org/abs/2611.08180) |
| [Hamiltonian-parameter learning](TRENDS.md#id-trend-014-learning-hamiltonian-and-dissipative-rate-parameters-of-quantum-systems-from-data) | 🚀 accelerating | [2026-11-05](https://arxiv.org/abs/2611.07353) |
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-11-04](https://arxiv.org/abs/2611.06819) |
| [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) | 🚀 accelerating | [2026-11-04](https://arxiv.org/abs/2611.07187) |
| [AI-for-quantum (hardware)](TRENDS.md#id-trend-002-ai-for-quantum-hardware-leg-classical-ml-for-quantum-hardware-control-calibration-decoding-and-circuit-design) | 🚀 accelerating | [2026-11-03](https://arxiv.org/abs/2611.04179) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 🚀 accelerating | [2026-11-03](https://arxiv.org/abs/2611.05079) |
| [Quantum transformers and attention](TRENDS.md#id-trend-016-quantum-transformers-and-attention-pqc-based-attention-mechanisms-for-sequence-and-signal-processing) | 🚀 accelerating | [2026-11-03](https://arxiv.org/abs/2611.05355) |
| [LLM/agentic quantum reasoning](TRENDS.md#id-trend-009-llmagentic-ai-reasoning-about-quantum-circuits-algorithms-and-proofs) | 🚀 accelerating | [2026-11-02](https://arxiv.org/abs/2611.02833) |
| [AI-for-quantum (circuit synthesis)](TRENDS.md#id-trend-012-ai-for-quantum-circuit-synthesis-leg-generativetransformer-models-that-directly-synthesize-quantum-circuits) | 🚀 accelerating | [2026-10-30](https://arxiv.org/abs/2610.41957) |
| [Quantum kernels & feature maps](TRENDS.md#id-trend-015-quantum-kernels--feature-maps-expressivity-encoding-budgets-and-application-scale-benchmarking) | 🚀 accelerating | [2026-10-30](https://arxiv.org/abs/2610.41848) |
| [QML generalization theory](TRENDS.md#id-trend-007-qml-generalization-theory-bounds-phenomenology-and-the-reference-structure-requirement) | 🚀 accelerating | [2026-10-17](https://arxiv.org/abs/2610.24426) |
| [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) | 📈 emerging | [2026-11-05](https://arxiv.org/abs/2611.08151) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 📈 emerging | [2026-11-04](https://arxiv.org/abs/2611.06630) |
| [Agentic AI lab automation](TRENDS.md#id-trend-013-agentic-ai-directly-operating-quantum-hardware-and-lab-infrastructure-end-to-end) | 📈 emerging | [2026-10-29](https://arxiv.org/abs/2610.40589) |
| [QML/QEC security](TRENDS.md#id-trend-017-qmlqec-security-adversarial-attacks-on-and-defenses-for-quantum-classical-ml-components) | 📈 emerging | [2026-10-19](https://arxiv.org/abs/2610.26240) |

## Worth studying

- [Quantum Knowledge Distillation: State-of-the-art, Applications and Open Problems](https://arxiv.org/abs/2611.08461) — Al-Sulaiti, Chen, Dastagir, Farouk, Al-Kuwari (Nov 5): a comprehensive survey of knowledge distillation in quantum machine learning, spanning compression, cross-architecture transfer, circuit approximation and classical deployment of quantum-derived models.
- [Quantum-Classical Auxiliary-Field Quantum Monte Carlo at the Edge of Practicability](https://arxiv.org/abs/2606.19239) — IQM + Volkswagen Group Innovation (hardware-validated Nov 5, orig. Jun 2026): up to a 124x classical-runtime reduction for QC-AFQMC via Aitken's block transformation, validated on a 54-qubit superconducting processor.
- [Reimagining computational quantum research with AI scientists](https://arxiv.org/abs/2611.02833) — Du, Zhao, Wang, Lu, Zhang, Tao (Nov 2): introduces OmniQ, benchmarking AI scientists on reproducing 59 published computational-quantum-science papers — a sobering, directly actionable read for anyone weighing how far to trust an AI-generated reproduction of quantum results.
- [GFlowQEC: Generative Flow Networks that Learn to Sample Quantum LDPC Codes](https://arxiv.org/abs/2611.06819) — Batista, Falcao, Machado (Nov 4): the first generative flow network for quantum code design, proposing good qLDPC codes in proportion to a reward under a tight per-evaluation search budget.
- [FirstQFM Demonstrates Quantum Reservoir Computing on Rigetti's 108-Qubit Processor](https://quantumcomputingreport.com/firstqfm-demonstrates-quantum-reservoir-computing-on-rigettis-108-qubit-processor-to-outperform-classical-financial-benchmarks/) — FirstQFM + SW7 Group + Rigetti (Nov 3): a blinded out-of-sample financial-forecasting pilot on a real 108-qubit processor beats classical ML baselines and a zero-shot foundation model, while explicitly disclaiming general quantum advantage.
- [Comparing classical and quantum QUBO solvers: optimality, trajectory diagnostics, and limits of solver selection (arXiv:2610.35126)](https://arxiv.org/abs/2610.35126) — Hellstern, Schacht, Zaefferer (Oct 26): a general-purpose classical branch-and-cut solver matches or beats quantum annealing on the large majority of 180+ benchmark instances.
- [Demonstration of meter-scale L-couplers between two IBM Quantum Nighthawk processors](https://www.ibm.com/quantum/blog/connecting-quantum-processors-with-l-couplers) — Sundaresan et al., IBM (paper Oct 21 / blog Oct 27): four L-couplers connect two 120-qubit Nighthawk processors at 99% average quantum-state-transfer fidelity.
- [Electronic-Structure-Informed Many-Body Encoding for Quantum Machine Learning (arXiv:2610.40840)](https://arxiv.org/abs/2610.40840) — Zhang, Culpitt, Yin, Zhu, Li (Oct 29): a physics-informed quantum encoding mapping n-body reduced-density-matrix descriptors onto n-qubit gates.
- [The Quartic Gap Between Quantum and Dequantized Algorithms for Linear Algebra Is Tight (arXiv:2610.42069)](https://arxiv.org/abs/2610.42069) — Chakrabarti, Herman, Kim, Ozgul (Oct 30): proves the known quantum-vs-dequantized query-complexity gap for QRAM-accessed linear systems is tight up to a log factor.
- [Distilling Knowledge from Search: Decoder Model Factory for Quantum LDPC Codes (arXiv:2610.41398)](https://arxiv.org/abs/2610.41398) — Bilgin, Hou, Srinivas, You (Oct 30): GraphMP, a qLDPC decoder that transfers without fine-tuning across code families, trained via successive generations distilled from its own prior generation's decoding runs.
- [Collaborative AI agents for autonomous experimental research with solid-state quantum spins](https://arxiv.org/abs/2610.40589) — Mansouri, Kimura, Koga, Arai (Oct 29): LLM agents that assess one another's work and can stop/redirect investigations, demonstrated end-to-end on real NV-diamond quantum spins.
- [Five results on Open Quantum Problems](https://psi.inc/research/oqp-batch-2026/) — PSI (Physical Superintelligence, Oct 23): PSI's own AI research system produces five new, Lean-verified results in quantum information theory itself.

## Community pulse

_Unverified intake — community signals, not trend evidence._

- r/QuantumComputing hit a Reddit "prove your humanity" bot-challenge wall this run — no live content sampled.
- Hacker News surfaced a post-quantum-cryptography risk story and routine Show-HN items — nothing qualifying as a primary.
- Quantum Computing Report's digest surfaced an IQM/Volkswagen quantum-classical Monte Carlo story, which traced to a genuine primary (now in the trend table above), plus a routine IBM/ORNL/AMD hardware-infrastructure announcement with no accompanying technical artifact.
- The Quantum Insider's digest surfaced the UK FCA's new "Quantum Experimentation Group" for quantum-ML financial-crime detection — a program launching 2027, not yet a technical result.
- Quantum Zeitgeist and the Quantum journal surfaced only foundational/non-ML items this run.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (28)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-11-06](reports/2026-11-06.md) · weekly: [2026-W44](reports/weekly/2026-W44.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

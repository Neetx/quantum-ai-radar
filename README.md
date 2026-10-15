# AI Radar

![trends](https://img.shields.io/badge/trends-16-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-12-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-24-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--10--15-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-10-15):**
- [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) cap-swaps in Riverlane's own technical write-up, [From Minutes to Seconds](https://www.riverlane.com/news/faster-decoder-recalibration-for-quantum-error-correction) — a GPU-accelerated decoder-recalibration loop cutting one training epoch from ~3 minutes to 2.8 seconds, and this radar's first evidence item from Riverlane.
- [QML/QEC security](TRENDS.md#id-trend-017-qmlqec-security-adversarial-attacks-on-and-defenses-for-quantum-classical-ml-components) gets a 6th independent group: [SHADE](https://arxiv.org/abs/2610.19077), federated unlearning of quantum neural networks via classical shadows, broadening the trend's privacy strand.
- Self-healed `eprint.iacr.org`'s new-postings feed, catching a month-old backlog item: [Low-Space Quantum Discrete Logarithms on Genus-Two Jacobians](https://eprint.iacr.org/2026/2057) (queued).
- 88 new quant-ph submissions triaged; watchlist eased to 24 (3 added, 4 dropped, 0 resolved via promotion).

## Trends

🌱 0 · 📈 4 · 🚀 12 · 🌊 0 · 🏔 0 · 📉 0 · 💤 0

| trend | stage | latest signal |
|-------|-------|---------------|
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-10-14](https://www.riverlane.com/news/faster-decoder-recalibration-for-quantum-error-correction) |
| [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) | 🚀 accelerating | [2026-10-08](https://arxiv.org/abs/2610.11360) |
| [LLM/agentic quantum reasoning](TRENDS.md#id-trend-009-llmagentic-ai-reasoning-about-quantum-circuits-algorithms-and-proofs) | 🚀 accelerating | [2026-10-07](https://haiqu.ai/case-study/the-hubbard-model-on-real-quantum-hardware-doped-frustrated-and-fully-interacting) |
| [Quantum kernels & feature maps](TRENDS.md#id-trend-015-quantum-kernels--feature-maps-expressivity-encoding-budgets-and-application-scale-benchmarking) | 🚀 accelerating | [2026-10-07](https://arxiv.org/abs/2610.09717) |
| [Quantum transformers and attention](TRENDS.md#id-trend-016-quantum-transformers-and-attention-pqc-based-attention-mechanisms-for-sequence-and-signal-processing) | 🚀 accelerating | [2026-10-12](https://arxiv.org/abs/2610.17351) |
| [Quantum-advantage frontier](TRENDS.md#id-trend-011-quantum-advantage-frontier-provable-learning-separations-and-honest-quantum-classical-crossovers) | 🚀 accelerating | [2026-10-12](https://www.nature.com/articles/s41534-026-01391-z) |
| [AI-for-quantum (circuit synthesis)](TRENDS.md#id-trend-012-ai-for-quantum-circuit-synthesis-leg-generativetransformer-models-that-directly-synthesize-quantum-circuits) | 🚀 accelerating | [2026-10-05](https://arxiv.org/abs/2610.06535) |
| [Hamiltonian-parameter learning](TRENDS.md#id-trend-014-learning-hamiltonian-and-dissipative-rate-parameters-of-quantum-systems-from-data) | 🚀 accelerating | [2026-10-05](https://arxiv.org/abs/2610.06709) |
| [AI-for-quantum (hardware)](TRENDS.md#id-trend-002-ai-for-quantum-hardware-leg-classical-ml-for-quantum-hardware-control-calibration-decoding-and-circuit-design) | 🚀 accelerating | [2026-10-01](https://arxiv.org/abs/2610.02129) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 🚀 accelerating | [2026-09-30](https://arxiv.org/abs/2609.38800) |
| [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) | 🚀 accelerating | [2026-09-30](https://arxiv.org/abs/2609.38713) |
| [QML generalization theory](TRENDS.md#id-trend-007-qml-generalization-theory-bounds-phenomenology-and-the-reference-structure-requirement) | 🚀 accelerating | [2026-09-22](http://link.aps.org/doi/10.1103/8k5v-ddtw) |
| [QML/QEC security](TRENDS.md#id-trend-017-qmlqec-security-adversarial-attacks-on-and-defenses-for-quantum-classical-ml-components) | 📈 emerging | [2026-10-13](https://arxiv.org/abs/2610.19077) |
| [Agentic AI lab automation](TRENDS.md#id-trend-013-agentic-ai-directly-operating-quantum-hardware-and-lab-infrastructure-end-to-end) | 📈 emerging | [2026-10-12](https://arxiv.org/abs/2610.17193) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 📈 emerging | [2026-10-05](https://arxiv.org/abs/2610.07196) |
| [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) | 📈 emerging | [2026-10-02](https://arxiv.org/abs/2610.03463) |

## Worth studying

- [From Minutes to Seconds: Faster Decoder Recalibration for Quantum Error Correction](https://www.riverlane.com/news/faster-decoder-recalibration-for-quantum-error-correction) — Riverlane (Oct 14): moves QEC decoder-weight recalibration's dominant cost onto a single NVIDIA H100, cutting one training epoch from ~3 minutes to 2.8 seconds — a concretely-benchmarked practical speedup for real-time calibration loops.
- [Principles and Techniques for Agentic Research in Experimental Physics (arXiv:2610.17193)](https://arxiv.org/abs/2610.17193) — Reed, Daly, Beling, Giandrea (Oct 12): ten requirements plus a working framework for agentic AI in physics labs, validated across six case studies including quantum-control pulse design and quantum-defect photodynamics.
- [Quantum-Fisher-information-aware optimization yields a quantum reservoir advantage over tuned classical reservoirs (arXiv:2610.14454)](https://arxiv.org/abs/2610.14454) — Nguyen, Soh (Oct 10): a QFI-optimized reservoir beats a tuned echo-state network at every tested size and 99.5% of 10,000 random classical networks.
- [Theory of the Edge-of-Chaos Advantage in Quantum Reservoir Computing (arXiv:2610.05213)](https://arxiv.org/abs/2610.05213) — Cao, Xia, Li (Oct 4): the first rigorous mechanistic account of why QRC performs best near the edge of chaos, via an explicit reservoir model's chaotic and integrable regimes.
- [Exponential advantage in continuous-variable quantum state learning](https://www.nature.com/articles/s41534-026-01391-z) — Coroi & Oh, npj Quantum Information (Oct 12): a clean sample-complexity separation between entanglement-free and entangled-measurement strategies for learning bosonic CV quantum states.
- [Xanadu Cuts Quantum Read-Only Memory Costs by ~4x via Dense Encoding](https://quantumcomputingreport.com/xanadu-cuts-quantum-read-only-memory-costs-by-4x-via-dense-encoding/) — Motlagh, Pocrnic (Xanadu): a dense Z/X-basis encoding plus sequential bit packets cuts the Toffoli cost of QROM data-loading by ~3.9x (arXiv:2605.20334, 2610.02321) — a bottleneck shared by QML encoding and quantum-chemistry/finance algorithms.
- [Turning Ideas into QPU Experiments: How Agentic Workflows Make Quantum Computing More Accessible](https://www.pasqal.com/blog/turning-ideas-into-qpu-experiments-how-agentic-workflows-make-quantum-computing-more-accessible/) — Pasqal (Oct 8): ships its idea-to-hardware agentic workflow as a Claude Code/Cursor/Codex plugin on 3 real cloud QPUs, honest about where expert review is still needed.
- [How AgenticOS coordinates specialist scientific agents to build, test, and trace a quantum experiment](https://haiqu.ai/case-study/how-agenticos-coordinates-specialist-scientific-agents-to-build-test-and-trace-a-quantum-experiment-from-small-research-idea-to-result) — Haiqu (Oct 6): AgenticOS's structured workflow beats 10 ad hoc AI runs on a Zundel-cation honest-baseline benchmark (SQD within 3.4% of full-CI) — the ad hoc runs disagreed on the basic setup.
- [The Hubbard Model on Real Quantum Hardware: Doped, Frustrated, and Fully Interacting with Diagonal Hopping](https://haiqu.ai/case-study/the-hubbard-model-on-real-quantum-hardware-doped-frustrated-and-fully-interacting) — Haiqu (Oct 7): AgenticOS designs a circuit for the first gate-based hardware experiment with diagonal hopping in the 2D Hubbard model, run on IBM Phoenix.
- [Autonomous Code Migration for Quantum Programming Languages (arXiv:2610.12187)](https://arxiv.org/abs/2610.12187) — Brown, Nguyen, Chatterjee, Lubinski (Oct 8): Opus, GPT and Gemini agents port QED-C benchmarks from Qiskit to CUDA-Q; distilled "skills" cut later agent cost by up to 96%.
- [QuSema: Detecting Silent Bugs in Quantum Libraries via Quantum-knowledge-enhanced Agents (arXiv:2610.10258)](https://arxiv.org/abs/2610.10258) — Song, Zhang, Zhang, Wang, Ma, Du (Oct 7): LLM agents equipped with quantum-domain knowledge catch SILENT (incorrect-but-non-crashing) bugs in quantum libraries that evade existing testing oracles.
- [Modular Neural Decoder for Surface Code Memory and Logic on Superconducting Processors (arXiv:2610.03869)](https://arxiv.org/abs/2610.03869) — Lange, Fjeldså, Johansson, Granath (Oct 2): a QEC decoder built to transfer across devices — outperforms MWPM on a real IBM Nighthawk processor and approaches AlphaQubit on Google's below-threshold data.
- [POLYMECHANON: a code-agnostic graph neural network decoder from the detection error model (arXiv:2610.01683)](https://arxiv.org/abs/2610.01683) — Astolfi, Pupillo (Oct 1): a single GNN trains once and decodes any stabiliser code under any noise model expressible as a detection error model, with decode time independent of the physical error rate.

## Community pulse

_Unverified intake — community signals, not trend evidence._

- r/QuantumComputing returned live content again, but only generic/evergreen "is quantum real" discussion threads — no new quantum-computing primary.
- Hacker News's dated search surfaced a QuEra AI-laser-locking submission that traces back to an already-captured primary, and a NYC/NYU quantum-fabrication-funding story (business, not a technical artifact).
- Quantum Computing Report and Quantum Zeitgeist both pointed to [Riverlane's own GPU-decoder-calibration post](https://www.riverlane.com/news/faster-decoder-recalibration-for-quantum-error-correction) — this run's strongest digest-sourced catch, now evidence above.
- Quantum Computing Report's Bloq Maya AI-agent coding-tool item recirculated — still a feature-list product announcement with no accompanying technical artifact.
- Hugging Face's Daily Papers exploration lane surfaced no quantum-relevant items this run.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (24)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-10-15](reports/2026-10-15.md) · weekly: [2026-W41](reports/weekly/2026-W41.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

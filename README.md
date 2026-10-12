# AI Radar

![trends](https://img.shields.io/badge/trends-16-3266ad?style=flat-square) ![accelerating](https://img.shields.io/badge/accelerating-12-e8590c?style=flat-square) ![watchlist](https://img.shields.io/badge/watchlist-25-6c757d?style=flat-square) ![updated](https://img.shields.io/badge/updated-2026--10--12-2f9e44?style=flat-square)

Autonomous radar tracking the quantum-computing research frontier and its intersection with AI — quantum machine learning, enabling hardware and error correction, and the classical-quantum boundary — for quantum-computing researchers. Generated from [TRENDS.md](TRENDS.md).

**Since last scan (2026-10-12):**
- [Agentic AI lab automation](TRENDS.md#id-trend-013-agentic-ai-directly-operating-quantum-hardware-and-lab-infrastructure-end-to-end) revived from dormancy (→ `emerging`) — [Pasqal ships its agentic idea-to-QPU-experiment workflow](https://www.pasqal.com/blog/turning-ideas-into-qpu-experiments-how-agentic-workflows-make-quantum-computing-more-accessible/) as a Claude Code/Cursor/Codex plugin on 3 real cloud QPUs.
- A 2-paper, May→October capture-leak catch: [Xanadu cuts Quantum Read-Only Memory costs by ~4x via dense Z/X-basis encoding](https://quantumcomputingreport.com/xanadu-cuts-quantum-read-only-memory-costs-by-4x-via-dense-encoding/), shrinking a data-loading bottleneck shared by QML encoding and quantum-chemistry/finance algorithms.
- [QTestBench](https://arxiv.org/abs/2610.13811) tests whether LLM-generated unit tests for quantum code can actually distinguish correct from faulty implementations — queued as a trend-009-adjacent flagged candidate.
- Watchlist holds at 25 (9 added, 9 dropped).

## Trends

🌱 0 · 📈 4 · 🚀 12 · 🌊 0 · 🏔 0 · 📉 0 · 💤 0

| trend | stage | latest signal |
|-------|-------|---------------|
| [Practical QEC tooling](TRENDS.md#id-trend-001-practical-qec-tooling-near-term-error-detection-and-the-path-to-ftqc) | 🚀 accelerating | [2026-10-08](https://arxiv.org/abs/2610.12400) |
| [LLM/agentic quantum reasoning](TRENDS.md#id-trend-009-llmagentic-ai-reasoning-about-quantum-circuits-algorithms-and-proofs) | 🚀 accelerating | [2026-10-07](https://haiqu.ai/case-study/the-hubbard-model-on-real-quantum-hardware-doped-frustrated-and-fully-interacting) |
| [Quantum kernels & feature maps](TRENDS.md#id-trend-015-quantum-kernels--feature-maps-expressivity-encoding-budgets-and-application-scale-benchmarking) | 🚀 accelerating | [2026-10-07](https://arxiv.org/abs/2610.09717) |
| [AI-for-quantum (circuit synthesis)](TRENDS.md#id-trend-012-ai-for-quantum-circuit-synthesis-leg-generativetransformer-models-that-directly-synthesize-quantum-circuits) | 🚀 accelerating | [2026-10-05](https://arxiv.org/abs/2610.06535) |
| [Hamiltonian-parameter learning](TRENDS.md#id-trend-014-learning-hamiltonian-and-dissipative-rate-parameters-of-quantum-systems-from-data) | 🚀 accelerating | [2026-10-05](https://arxiv.org/abs/2610.06709) |
| [Quantum transformers and attention](TRENDS.md#id-trend-016-quantum-transformers-and-attention-pqc-based-attention-mechanisms-for-sequence-and-signal-processing) | 🚀 accelerating | [2026-10-03](https://arxiv.org/abs/2610.04588) |
| [AI-for-quantum (hardware)](TRENDS.md#id-trend-002-ai-for-quantum-hardware-leg-classical-ml-for-quantum-hardware-control-calibration-decoding-and-circuit-design) | 🚀 accelerating | [2026-10-01](https://arxiv.org/abs/2610.02129) |
| [QML trainability](TRENDS.md#id-trend-004-qml-trainability-barren-plateaus-and-noise-robustness-theory) | 🚀 accelerating | [2026-09-30](https://arxiv.org/abs/2609.38800) |
| [Quantum-advantage scrutiny](TRENDS.md#id-trend-006-quantum-advantage-skepticism-dequantization-honest-baselines-and-nisq-advantage-refutations) | 🚀 accelerating | [2026-09-30](https://arxiv.org/abs/2609.38713) |
| [Quantum-advantage frontier](TRENDS.md#id-trend-011-quantum-advantage-frontier-provable-learning-separations-and-honest-quantum-classical-crossovers) | 🚀 accelerating | [2026-09-30](https://arxiv.org/abs/2609.40050) |
| [Quantum reservoir computing](TRENDS.md#id-trend-008-quantum-reservoir-computing-fixed-quantum-dynamics-as-a-trainable-readout-feature-map) | 🚀 accelerating | [2026-09-29](https://arxiv.org/abs/2609.36901) |
| [QML generalization theory](TRENDS.md#id-trend-007-qml-generalization-theory-bounds-phenomenology-and-the-reference-structure-requirement) | 🚀 accelerating | [2026-09-22](http://link.aps.org/doi/10.1103/8k5v-ddtw) |
| [Quantum generative models](TRENDS.md#id-trend-003-quantum-generative-models-circuits-for-generative-and-sequential-learning) | 📈 emerging | [2026-10-05](https://arxiv.org/abs/2610.07196) |
| [Agentic AI lab automation](TRENDS.md#id-trend-013-agentic-ai-directly-operating-quantum-hardware-and-lab-infrastructure-end-to-end) | 📈 emerging | [2026-10-08](https://www.pasqal.com/blog/turning-ideas-into-qpu-experiments-how-agentic-workflows-make-quantum-computing-more-accessible/) |
| [Neural Quantum States](TRENDS.md#id-trend-005-neural-quantum-states-classical-neural-network-ansätze-for-quantum-many-body-wavefunctions) | 📈 emerging | [2026-10-02](https://arxiv.org/abs/2610.03463) |
| [QML/QEC security](TRENDS.md#id-trend-017-qmlqec-security-adversarial-attacks-on-and-defenses-for-quantum-classical-ml-components) | 📈 emerging | [2026-09-30](https://arxiv.org/abs/2609.38720) |

## Worth studying

- [Xanadu Cuts Quantum Read-Only Memory Costs by ~4x via Dense Encoding](https://quantumcomputingreport.com/xanadu-cuts-quantum-read-only-memory-costs-by-4x-via-dense-encoding/) — Motlagh, Pocrnic (Xanadu): a dense Z/X-basis encoding plus sequential bit packets cuts the Toffoli cost of QROM data-loading by ~3.9x (arXiv:2605.20334, 2610.02321) — a bottleneck shared by QML encoding and quantum-chemistry/finance algorithms.
- [Turning Ideas into QPU Experiments: How Agentic Workflows Make Quantum Computing More Accessible](https://www.pasqal.com/blog/turning-ideas-into-qpu-experiments-how-agentic-workflows-make-quantum-computing-more-accessible/) — Pasqal (Oct 8): ships its idea-to-hardware agentic workflow as a Claude Code/Cursor/Codex plugin on 3 real cloud QPUs, honest about where expert review is still needed.
- [How AgenticOS coordinates specialist scientific agents to build, test, and trace a quantum experiment](https://haiqu.ai/case-study/how-agenticos-coordinates-specialist-scientific-agents-to-build-test-and-trace-a-quantum-experiment-from-small-research-idea-to-result) — Haiqu (Oct 6): AgenticOS's structured workflow beats 10 ad hoc AI runs on a Zundel-cation honest-baseline benchmark (SQD within 3.4% of full-CI) — the ad hoc runs disagreed on the basic setup.
- [The Hubbard Model on Real Quantum Hardware: Doped, Frustrated, and Fully Interacting with Diagonal Hopping](https://haiqu.ai/case-study/the-hubbard-model-on-real-quantum-hardware-doped-frustrated-and-fully-interacting) — Haiqu (Oct 7): AgenticOS designs a circuit for the first gate-based hardware experiment with diagonal hopping in the 2D Hubbard model, run on IBM Phoenix.
- [Autonomous Code Migration for Quantum Programming Languages (arXiv:2610.12187)](https://arxiv.org/abs/2610.12187) — Brown, Nguyen, Chatterjee, Lubinski (Oct 8): Opus, GPT and Gemini agents port QED-C benchmarks from Qiskit to CUDA-Q; distilled "skills" cut later agent cost by up to 96%.
- [QuSema: Detecting Silent Bugs in Quantum Libraries via Quantum-knowledge-enhanced Agents (arXiv:2610.10258)](https://arxiv.org/abs/2610.10258) — Song, Zhang, Zhang, Wang, Ma, Du (Oct 7): LLM agents equipped with quantum-domain knowledge catch SILENT (incorrect-but-non-crashing) bugs in quantum libraries that evade existing testing oracles.
- [Modular Neural Decoder for Surface Code Memory and Logic on Superconducting Processors (arXiv:2610.03869)](https://arxiv.org/abs/2610.03869) — Lange, Fjeldså, Johansson, Granath (Oct 2): a QEC decoder built to transfer across devices — outperforms MWPM on a real IBM Nighthawk processor and approaches AlphaQubit on Google's below-threshold data.
- [POLYMECHANON: a code-agnostic graph neural network decoder from the detection error model (arXiv:2610.01683)](https://arxiv.org/abs/2610.01683) — Astolfi, Pupillo (Oct 1): a single GNN trains once and decodes any stabiliser code under any noise model expressible as a detection error model, with decode time independent of the physical error rate.
- [Complex-valued Quantum Neural Networks (npj QI, DOI 10.1038/s41534-026-01369-x)](https://www.nature.com/articles/s41534-026-01369-x) — Wen, Qian, Zheng, Wang, Wang (Sep 23): expands QNNs to the complex-valued plane with a proven expressivity gain, validated on a real superconducting processor.
- [Quantum Discrete Logarithms on Elliptic Curves with 5n/2+o(n) Logical Qubits (IACR eprint 2026/2014)](https://eprint.iacr.org/2026/2014) — Jo, Lee (Georgia Tech, Sep 14): reduces the logical-qubit count for the ECDLP quantum algorithm below the prior space-efficient affine construction.
- [Energy-to-solution of a trapped-ion quantum processor for hybrid quantum-classical applications (arXiv:2605.02798)](https://arxiv.org/abs/2605.02798) — Knitter, Kim, Wurzer et al. (May 4, publicized via IonQ's Jul-20 blog, caught by a monthly backlog sweep): quantum fine-tuning of a pretrained sentence-transformer on real trapped-ion hardware, with a measured energy-to-solution break-even against classical simulation at ~34 qubits.
- [SQUARE: Structured Quantum Representation Adapters as Compact Quadratic Feature Maps for Frozen Language Models (arXiv:2609.37134)](https://arxiv.org/abs/2609.37134) — Roh, Ahn, Lee, Park, Yoon, Aggarwal, Kim (Sep 29): a quantum circuit directly adapts a frozen classical LLM's bottleneck features, beating an MLP and other classical baselines on GLUE-derived interaction tasks.
- [Forward random-circuit sampling on IBM Quantum Nighthawk r2 (arXiv:2609.28657)](https://arxiv.org/abs/2609.28657) — Sedrakyan, Zhang, Karapetyan, Baktay, Gharibyan, Tepanyan (Sep 23): a rare independent, non-IBM benchmark of IBM's brand-new hardware, honest that its classical-cost figure is a tensor-network estimate under stated favorable assumptions.

## Community pulse

_Unverified intake — community signals, not trend evidence._

- r/QuantumComputing reachable but only generic/evergreen threads surfaced — no new quantum-computing primary.
- Hacker News surfaced DARPA's QBI Stage-C selections (already known via IonQ's own blog), a PQC warning and an off-scope biology piece — nothing new quantum-computing-technical.
- Quantum Computing Report's digest surfaced the Xanadu QROM result (see above) and IBM's new directed-execution API (no ML component).
- Quantum Zeitgeist surfaced mostly routine funding/hardware-milestone items this run; one AI-branded item (AQPotency) turned out to be a classical-CPU model with no quantum-computing component.
- Hugging Face's Daily Papers exploration lane surfaced no quantum-relevant items this run.

---

**Output map:** [TRENDS.md](TRENDS.md) · [watchlist (25)](TRENDS.md#observation_queue) · [reports/](reports/) · daily: [2026-10-12](reports/2026-10-12.md) · weekly: [2026-W41](reports/weekly/2026-W41.md) · [AGENTS.md](AGENTS.md) · [SOURCES.md](SOURCES.md)

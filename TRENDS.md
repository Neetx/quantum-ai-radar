# Trend ledger — Quantum AI Radar

Last updated: 2026-06-26

Stage legend: `seed` (first signal) → `emerging` (multi-source, forming) →
`accelerating` (broad, fast) → `mainstreaming` (standard practice) ; `dormant`
(21+ days quiet) ; `declining` (the field moved on). Confidence: `low | medium | high`.
Trend bar: ≥3 independent sources (different orgs/author groups) + ≥1 concrete artifact.

## Active trends

### [id: trend-001] Practical QEC tooling: near-term error detection and the path to FTQC

alias: practical-qec-tooling
stage: emerging
confidence: medium
first_observed: 2026-06-26
last_evidence: 2026-06-25
evidence:
  - 2026-06-25 — https://www.ibm.com/quantum/blog/qiskit-paulice — IBM releases Qiskit Paulice: new Qiskit addon for postselected quantum error detection in near-term circuits, bridging NISQ error mitigation and full FTQC
  - 2026-04-07 — https://arxiv.org/abs/2604.06319 — Q-NEXUS (academic consortium): heterogeneous FTQC architectures enable 138x reduction in physical qubit requirements by specializing modules for compute/memory/communication
  - 2026-06-25 — https://arxiv.org/abs/2606.27119 — Foundation decoders: high-capacity neural decoders overcome the syndrome-generation scaling barrier for fault-tolerant QC at large code distances
  - 2026-06-25 — https://arxiv.org/abs/2606.27130 — Rate-2/3 girth-8 quantum LDPC codes from finite geometry: new code family expanding the QLDPC code design space
notes: Three independent groups (IBM, Q-NEXUS consortium, academic decoder group) all targeting the near-term/FTQC transition within the same month. IBM explicitly frames Paulice as a bridge between error mitigation and fault tolerance. Foundation decoders (quant-ph + cs.AI + cs.LG) show neural approaches now viable at large code distances. Stage set to emerging (not just seed) because of the IBM+academic breadth and the Qiskit Paulice concrete tool release. One stage up from seed justified by ≥3 independent primary sources with concrete artifacts.

### [id: trend-002] AI-for-quantum: ML and LLM-guided quantum hardware and code design

alias: ai-for-quantum
stage: seed
confidence: medium
first_observed: 2026-06-26
last_evidence: 2026-06-25
evidence:
  - 2026-06-01 — https://arxiv.org/abs/2606.02418 — IBM: LLM-guided evolutionary search discovers 465 bivariate bicycle QEC code candidates across 1,650 iterations and ~200,000 screened candidates
  - 2026-06-25 — https://arxiv.org/abs/2606.27119 — Foundation (neural) decoders for FTQC: high-capacity ML models as decoders, performance leading over classical decoders at large code distances
  - 2026-06-25 — https://news.microsoft.com/source/features/innovation/majorana-2-microsoft-discovery-agentic-ai — Microsoft uses Discovery agentic AI to improve Majorana 2 topological qubit reliability 1000x; AI as a hardware-design tool
notes: Watch area (per scope). Three independent orgs (IBM Research, academic decoder group, Microsoft) using ML/AI methods to advance quantum hardware or algorithm design. IBM paper is the strongest primary (arXiv, detailed methodology). Microsoft entry is an official vendor blog (counts as primary under evidence rules) but the underlying technical paper has not been found yet — flag for verification. Foundation decoders overlap with trend-001; double-routing is correct because they also exemplify the AI-for-quantum pattern. Stage: seed (watch area just forming, not yet a lead axis).

## observation_queue

Signals not yet promoted to a trend. Format: `date — description — link if available`
(marked unverified unless the primary was opened this session).

- 2026-06-22 — Quantum sequence models: two independent papers from Wells Fargo-affiliated teams propose Recursive QLSTM (arXiv:2606.24932) and Self-Modulating Quantum Fast-Weight Programmers (arXiv:2606.24933) for sequential/time-series QML — need a third independent group before promoting
- 2026-06-24 — QML data encoding improvements: variational autoencoder framework for quantum feature learning (arXiv:2606.26312) extends classical AE paradigm to quantum embeddings; complements 2606.21570 below — 2 groups so far, need a third
- 2026-06-19 — Correlation-aware quantum feature maps: arXiv:2606.21570 proposes encoding inter-feature correlations directly into quantum feature maps for variational classification — queue until a second independent group emerges (could cluster with 2606.26312 above)
- 2026-06-18 — Quantum ring all-reduce for distributed ML: arXiv:2606.20344 shows quantum communications enable both communication-efficient and information-theoretically private distributed gradient aggregation — novel application of quantum comms to classical ML training; single group, queue
- 2026-06-21 — QML generalization theory: arXiv:2606.22331 "No Reference-Free Generalization in QML" — identifiability problem shows learners need reference structures (basis/frame) to generalize in quantum settings; important theoretical limit result — single group, see study_shelf
- 2026-06-25 — Quantum GNNs: arXiv:2606.26873 "Scalable Message-Passing Quantum Graph Neural Networks in the Weisfeiler-Leman Hierarchy" — connects quantum counterparts to the WL hierarchy; novel QML architecture for relational/graph data — single group, queue
- 2026-06-25 — Quantum Physics-Informed Neural Networks (QPINNs): arXiv:2606.26865 introduces QNNs for solving integro-differential and fractional PDEs with nonlocal operators — single group, queue
- 2026-06-25 — Trapped-ion architecture with optical tweezer arrays: arXiv:2606.27249 proposes combining trapped-ion coherence with tweezer reconfigurability for scalable architecture — hardware advance, single group, queue
- 2026-06-25 — NVIDIA cuda-quantum 0.15-rc3 released (June 25, 2026): rapid RC cadence (rc1→rc3 in 2 days) suggests imminent full release of GPU-accelerated hybrid QML platform — verify changelog via https://github.com/NVIDIA/cuda-quantum/releases
- 2026-06-18 — Qiskit 2.5.0rc1 released: https://github.com/Qiskit/qiskit/tags — check release notes for QML or error-correction relevant changes when stable release lands
- 2026-06-25 — White House executive order on quantum computing (June 23): https://www.whitehouse.gov/presidential-actions/2026/06/ushering-in-the-next-frontier-of-quantum-innovation/ — policy/funding context; Scott Aaronson response at https://scottaaronson.blog/?p=9861 calls for basic academic research funding — off-axis policy item, pulse context
- 2026-06 — Microsoft Majorana 2 controversy (ongoing): Microsoft claims 1000x stability improvement; critics challenge validity of topological qubit approach (Reuters June 24, ScienceNews); underlying technical paper not yet found — verify: search for Majorana 2 arxiv preprint from Microsoft/Station Q

## source_rotation

Append-only coverage log MOVED to `logs/source_rotation.md`. Each run APPENDS one dated line
THERE and reads only the recent tail (~7 days) — do not write scans into TRENDS.md.

## strategy_notes

Corrections to the source-coverage strategy.
- 2026-06-26 — Scope (curator input): track the QUANTUM AI frontier — primarily using quantum computers to RUN AI/ML algorithms (quantum machine learning: variational circuits, quantum neural nets/kernels, data encoding, quantum optimization for ML, hybrid quantum-classical training, and quantum-advantage-for-ML claims) — plus the enabling quantum-computing research (hardware/qubits/coherence, error correction & fault tolerance, algorithms, SDKs, benchmarking) and the classical–quantum boundary (dequantization / classical simulation that tests whether a claimed advantage is real). AI-for-quantum (classical ML to control/error-correct quantum systems) is a watch-area, not a core axis. The agent owns and evolves these axes;
  promote a forming sub-theme to a trend at ≥3 independent groups + an artifact.

## study_shelf

Single strong items worth knowing, newest first (format: `date — [name](url) — one line of
why`). The trend bar does NOT apply here; opened primary sources only.

- 2026-06-25 — [Foundation decoders for fault-tolerant QC](https://arxiv.org/abs/2606.27119) — high-capacity neural decoders now outperform classical decoders at large code distances; directly relevant to practical FTQC timelines
- 2026-06-25 — [Qiskit Paulice: postselected QEC for near-term circuits](https://www.ibm.com/quantum/blog/qiskit-paulice) — immediately usable addon that adds low-overhead error detection to existing Qiskit circuits; bridges current NISQ work to fault-tolerant architectures
- 2026-06-21 — [No Reference-Free Generalization in QML (arXiv:2606.22331)](https://arxiv.org/abs/2606.22331) — key theoretical result: without an orienting reference structure (basis/frame) in training data, a QML model cannot assign different meanings to unseen quantum directions; implications for circuit design and training set construction

## calibration

Append-only self-evaluation log MOVED to `logs/calibration.md` (see `radar-self-eval`).
Weekly runs APPEND there, never here.

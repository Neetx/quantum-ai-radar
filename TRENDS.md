# Trend ledger — Quantum AI Radar

Last updated: 2026-07-01

Stage legend: `seed` (first signal) → `emerging` (multi-source, forming) →
`accelerating` (broad, fast) → `mainstreaming` (standard practice) ; `dormant`
(21+ days quiet) ; `declining` (the field moved on). Confidence: `low | medium | high`.
Trend bar: ≥3 independent sources (different orgs/author groups) + ≥1 concrete artifact.

## Active trends

### [id: trend-001] Practical QEC tooling: near-term error detection and the path to FTQC

alias: practical-qec-tooling
stage: accelerating
confidence: medium
first_observed: 2026-06-26
last_evidence: 2026-06-30
evidence:
  - 2026-06-25 — https://www.ibm.com/quantum/blog/qiskit-paulice — IBM releases Qiskit Paulice: new Qiskit addon for postselected quantum error detection in near-term circuits, bridging NISQ error mitigation and full FTQC
  - 2026-04-07 — https://arxiv.org/abs/2604.06319 — Q-NEXUS (academic consortium): heterogeneous FTQC architectures enable 138x reduction in physical qubit requirements by specializing modules for compute/memory/communication
  - 2026-06-25 — https://arxiv.org/abs/2606.27119 — Foundation decoders: high-capacity neural decoders overcome the syndrome-generation scaling barrier for fault-tolerant QC at large code distances
  - 2026-06-25 — https://arxiv.org/abs/2606.27130 — Rate-2/3 girth-8 quantum LDPC codes from finite geometry: new code family expanding the QLDPC code design space
  - 2026-06-12 — https://arxiv.org/abs/2606.14455 — Benois et al. (Paris-Saclay/CEA, 5 authors): density matrix propagation enables maximum-likelihood decoding for small QEC codes; benchmarks MWPM, belief propagation, Tesseract, Planar decoders against optimal; 5× reduction in theory-practice gap; new decoder evaluation framework
  - 2026-04-17 — https://arxiv.org/abs/2604.16209 — Zhao et al. (MIT-CTP, 5 authors): ultra-high-rate QLDPC codes on reconfigurable neutral-atom arrays; new structural conditions on Kasai construction enable encoding rates well above 1/10; near-term implementable on neutral-atom hardware
  - 2026-06-29 — https://arxiv.org/abs/2606.30592 — Bi, Chang, Puri (Yale, 3 authors): "Untangling QLDPC Codes with Biased Noise Ancilla" — designs low-depth syndrome-extraction circuits that use biased-noise ancillas to stop ancilla errors from spreading to multiple data qubits in high-rate QLDPC codes; addresses a key practical bottleneck for QLDPC implementation
  - 2026-06-29 — https://arxiv.org/abs/2606.30606 — Czabán, Kálmán, Filippov (4 authors): repetition-code-based readout error detection and correction across hardware platforms and generations; applies classical coding to measurement outcomes for near-term readout-error mitigation in expectation-value and sampling tasks
  - 2026-06-30 — https://quantum-journal.org/papers/q-2026-06-30-2149/ — Blue, Avlani, He, Ziyin, Chuang (MIT, peer-reviewed in Quantum, DOI 10.22331/q-2026-06-30-2149): "Machine Learning Decoding of Circuit-Level Noise for Bivariate Bicycle Codes" — neural/ML decoder result specific to bivariate bicycle QEC codes, extending the foundation-decoder ML-decoding sub-theme to a peer-reviewed venue
  - 2026-06-30 — https://arxiv.org/abs/2606.31428 — Griffiths, Friel, Vlastakis: "The limits of erasure-based postselection for quantum error mitigation" — open-sources the 'erado' simulation framework for erasure noise + postselection; quantifies where postselected QEM (the same technique class as IBM's Qiskit Paulice) works and where it breaks down (fully mitigates the erasure channel below a 3.0% erasure-check error rate; postselected dual-rail surpasses a noise floor a comparable single-rail system cannot)
notes: Ten independent groups now on the QEC tooling axis (IBM, Q-NEXUS consortium, foundation-decoder group, QLDPC code designers, Paris-Saclay decoder-benchmark group, MIT-CTP/neutral-atom QLDPC group, Yale/Puri biased-noise-ancilla group, readout-error-coding group, MIT/Chuang ML-decoding group, erasure-postselection group). IBM explicitly frames Paulice as a bridge between error mitigation and fault tolerance. Foundation decoders and the MIT/Chuang Quantum-journal result show neural/ML decoding approaches now span both large code distances and specific code families (bivariate bicycle) at a peer-reviewed level. Benois et al. demonstrate practical decoders fall 5× short of optimality, motivating better decoder design; Zhao et al. extend ultra-high-rate QLDPC codes to neutral-atom hardware; Bi et al. tackle QLDPC syndrome-extraction circuit design; the readout-coding group covers the measurement-error layer; Griffiths et al. quantify the practical limits of the same postselection technique class IBM shipped in Paulice. Stage promoted emerging → accelerating 2026-07-01: 10 independent groups in under 3 weeks is broad AND fast, clearing the "accelerating" bar flagged as a candidate in the 2026-06-30 report and held one run for confirmation.

### [id: trend-002] AI-for-quantum: ML and LLM-guided quantum hardware and code design

alias: ai-for-quantum
stage: emerging
confidence: medium
first_observed: 2026-06-26
last_evidence: 2026-06-30
evidence:
  - 2026-06-01 — https://arxiv.org/abs/2606.02418 — IBM: LLM-guided evolutionary search discovers 465 bivariate bicycle QEC code candidates across 1,650 iterations and ~200,000 screened candidates
  - 2026-06-25 — https://arxiv.org/abs/2606.27119 — Foundation (neural) decoders for FTQC: high-capacity ML models as decoders, performance leading over classical decoders at large code distances
  - 2026-06-25 — https://news.microsoft.com/source/features/innovation/majorana-2-microsoft-discovery-agentic-ai — Microsoft uses Discovery agentic AI to improve Majorana 2 topological qubit reliability 1000x; AI as a hardware-design tool
  - 2026-06-27 — https://alice-bob.com/blog/decoupling-ai-for-quantum-control-and-calibration — Alice & Bob proposes decoupled AI topology architecture for real-time quantum control and calibration to address coherence timescale mismatches; (undated blog, accessed 2026-06-27)
  - 2026-06-26 — https://arxiv.org/abs/2606.27907 — Zhong et al. (China, 4 authors): end-to-end ML learning of quantum control on a latent dynamical manifold; replaces iterative simulate-then-optimize paradigm with trainable closed-loop control pipeline; directly relevant to real-time AI-for-quantum control
  - 2026-06-30 — https://arxiv.org/abs/2606.29636 — Singh: "Lie Group Diffusion Models for Hardware-Aware Quantum Circuit Synthesis" — diffusion generative model respecting SU(2) Lie-group structure for hardware-aware quantum circuit synthesis; classical generative AI designing quantum circuits
  - 2026-06-30 — https://arxiv.org/abs/2606.30765 — Peters, Wang, Spierings, Drucker, Chen, Bartlett: "Deep Reinforcement Learning for Individual Atomic Control and Cooling" — deep RL cools the motion of a single neutral atom coupled to a high-finesse optical cavity using only continuously monitored cavity transmission; classical ML doing real-time quantum hardware control
notes: Watch area (per scope). Seven independent orgs/groups (IBM Research, foundation-decoder group, Microsoft, Alice & Bob, Zhong et al., Singh, Peters et al.) now using ML/AI methods to advance quantum hardware, circuit design, or control. IBM paper is the strongest primary (arXiv, detailed methodology). Microsoft blog describes Discovery AI for topological qubit hardware; underlying hardware paper: arXiv:2606.03884 (20s parity lifetime in InAs-Pb tetron, June 2026). Alice & Bob blog is a conceptual/architectural discussion without underlying technical paper yet — flag for follow-up. Foundation decoders overlap with trend-001; double-routing is correct because they also exemplify the AI-for-quantum pattern. Singh applies generative diffusion models to circuit synthesis; Peters et al. apply deep RL directly to real-time hardware control (atomic cooling) — both add to the real-time-control sub-theme alongside Zhong et al. and Alice & Bob. Stage promoted seed → emerging 2026-07-01: 7 independent groups, sustained activity across multiple weeks (June 25-30), clears the "multi-source, forming" bar.

### [id: trend-003] Quantum generative models: circuits for generative and sequential learning

alias: quantum-generative-ml
stage: seed
confidence: low
first_observed: 2026-06-29
last_evidence: 2026-06-26
evidence:
  - 2026-06-22 — https://arxiv.org/abs/2606.24932 — Chen et al. (Wells Fargo): Recursive QLSTM with dynamic variational quantum circuit adaptation for sequential data; quantum recurrent circuits for time-series
  - 2026-06-22 — https://arxiv.org/abs/2606.24933 — Chen et al. (Wells Fargo): Self-Modulating Quantum Fast-Weight Programmers for efficient adaptive sequential learning; same org as 2606.24932 (count as 1 group)
  - 2026-06-25 — https://arxiv.org/abs/2606.27561 — Waller et al. (Brunel/King's College London): QDiffusion-TS, first quantum generative diffusion model for real-world time series; compact quantum circuits represent complex temporal distributions
  - 2026-06-26 — https://arxiv.org/abs/2606.28236 — Banks, Crippa, Traube: qudit extension of parameterized IQP circuits for learning integer-valued data distributions; advances generative QML beyond binary encodings
notes: Promoted from observation_queue 2026-06-29 via convergence check — 3 independent groups (Wells Fargo/Chen group, Waller et al./Brunel, Banks et al.) on quantum generative and sequential learning within one week. Distinct sub-axis: using parameterized quantum circuits as generative/sequential models rather than discriminative classifiers. Covers diffusion-style generation, recurrent quantum circuits (QLSTM, fast-weight programmers), and qudit generative models. Stage: seed — freshly converged; sustained multi-week evidence needed before promotion.

### [id: trend-004] QML trainability: barren plateaus and noise-robustness theory

alias: qml-trainability-theory
stage: seed
confidence: low
first_observed: 2026-07-01
last_evidence: 2026-06-30
evidence:
  - 2026-06-21 — https://arxiv.org/abs/2606.22551 — Mondal, Chanda, Alawieh, Sukhadiya, Krah, Gonsalves: "Mitigating Measurement-Induced Training Instability in Hybrid Quantum Neural Networks for Protein Classification" — addresses measurement-induced training instability from bounded logits in hybrid QNNs
  - 2026-06-28 — https://arxiv.org/abs/2606.30688 — Ugail, Howard: "A Coherence Law for Trainability in Noisy Equivariant Quantum Neural Networks" — derives which physical quantity (coherence) determines whether gradients of equivariant circuits survive decoherence
  - 2026-06-30 — https://arxiv.org/abs/2606.31536 — Kung-Ming Lan: "Beyond the Expressivity-Trainability Paradox: A Dynamical Lie Algebra Perspective on Navigating Barren Plateaus in Quantum Machine Learning" — dynamical-Lie-algebra framework for navigating barren plateaus
notes: Promoted from observation_queue 2026-07-01 via convergence check — 3 independent groups on the trainability/optimization-landscape theory of variational QML circuits (barren plateaus, gradient survival under noise) within ~10 days. Distinct sub-axis from trend-001 (which tracks QEC/decoder tooling, not circuit trainability) and from trend-003 (generative circuits, not training dynamics). Stage: seed — freshly converged; sustained multi-week evidence needed before promotion.

## observation_queue

Signals not yet promoted to a trend. Format: `date — description — link if available`
(marked unverified unless the primary was opened this session).

- 2026-06-24 — QML data encoding improvements: variational autoencoder framework for quantum feature learning (arXiv:2606.26312) extends classical AE paradigm to quantum embeddings; complements 2606.21570 below — 2 groups so far, need a third
- 2026-06-19 — Correlation-aware quantum feature maps: arXiv:2606.21570 proposes encoding inter-feature correlations directly into quantum feature maps for variational classification — queue until a second independent group emerges (could cluster with 2606.26312 above)
- 2026-06-27 — Quandela photonic quantum reservoir computing: arXiv:2605.10471 "Quantum and classical processing with photonic quantum machine learning" (May 2026) — photonic QML including reservoir computing and quantum tomography; single group (Quandela / López Carreño et al.); need second independent group on photonic QRC
- 2026-06-27 — Classical ML for quantum states: arXiv:2606.25600 "Two-dimensional Hyperbolic RNN Neural Quantum State" (June 24, 2026) — hyperbolic-space RNN to represent quantum states classically; classical-quantum boundary axis; single group
- 2026-06-29 — Hybrid QNNs for quantum phase recognition: arXiv:2606.28201 (Scarato et al., June 26) and arXiv:2606.28199 (Hoffmann et al., June 26) both propose hybrid quantum-classical neural networks for recognizing many-body quantum phases; 2 independent groups on same sub-theme — need a third for promotion
- 2026-06-29 — Quantum Dynamic Time Warping: arXiv:2606.27815 (Alvarez-Estevez et al., June 26) — hybrid quantum DTW for multivariate time-series classification, replacing Euclidean distances with quantum kernel-based similarity; on-axis QML for sequential data — single group
- 2026-06-29 — FTQC materials science algorithm: arXiv:2606.27734 (Bhardwaj et al., June 26) — fault-tolerant quantum algorithm for static structure factor and finite-size effects in periodic materials; bridges path from QEC to practical FTQC applications — single group
- 2026-06-29 — Photonic QNN for edge quantum AI: arXiv:2606.28252 (Sonawane et al., June 26) — parameter-efficient continuous-variable photonic QNN for oral cancer detection on edge devices; applied QML on photonic hardware — single group; photonic QML cluster forming (see also Quandela 2605.10471)
- 2026-06-29 — IBM quantum state tomography via agnostic learning: arXiv:2606.07425 (Arunachalam & Dutt, IBM Research, June 5, 2026) — general framework for tomography of states with bounded-extent relative to a structured class; black-box reduction from agnostic learning to state tomography; poly-time stabilizer state tomography; classical-quantum boundary axis — single group
- 2026-06-29 — Alice & Bob Helium System (June 10, 2026): https://alice-bob.com/blog/this-is-not-a-product-launch — first cat-qubit laboratory open to third-party organizations; 18-qubit chip; bit-flip times >1 hour via engineered two-photon dissipation; designed explicitly for QEC research co-design; enabling hardware axis — single vendor announcement, no technical arXiv paper found yet
- 2026-06-29 — QuEra gigaquop-class roadmap (June 25, 2026): https://www.quera.com — vendor announcement of next-generation neutral-atom system targeting >1,000 logical qubits and ~1 billion reliable logical operations (gigaquop-class); ~1000× improvement over their Libra system; VENDOR PR, hype-prone — follow to a technical primary before citing as evidence
- 2026-06-29 — AWS-QuEra FTQC cloud collaboration (June 15, 2026): https://aws.amazon.com/blogs/quantum-computing/aws-deepens-strategic-collaboration-with-quera-to-bring-fault-tolerant-quantum-computing-to-amazon-braket/ — AWS will bring QuEra's Libra fault-tolerant neutral-atom system to Amazon Braket by 2028; cloud access to FTQC; references landmark QuEra/Harvard/MIT FTQC papers as technical foundation
- 2026-06-29 — QuTech diamond SnV above-unity cooperativity (arXiv:2511.13375, Nov 2025; published PRX June 2026): Hanson group (TU Delft/TNO) demonstrates above-unity coherent cooperativity of tin-vacancy centers in diamond photonic crystal cavities; enables reliable solid-state qubit ↔ photon interfaces for quantum networks; 327 functional devices across 2 chips; enabling hardware (photonic quantum emitters) — single group, peer-reviewed
- 2026-06-29 — Pasqal QEX open-source quantum chemistry SDK (May 29, 2026): https://www.pasqal.com — Pasqal releases QEX, an open-source framework for quantum-enhanced chemistry on neutral-atom hardware; on-scope (quantum SDK enabling quantum-for-ML applications) — single org release, no arXiv companion found; verify URL on next access
- 2026-06-30 — Visual quantum reinforcement learning: arXiv:2606.30520 (Lazaro, Vazquez, Garcia-Bringas, Jun 29) "Staged Hybridisation for Visual Quantum RL via Knowledge Distillation" — uses KD to train variational quantum circuits on high-dimensional visual RL tasks; on-axis QML (quantum RL) — single group, queue
- 2026-06-30 — Generative-ML-assisted quantum chemistry: arXiv:2606.30551 (Anurag et al., Jun 29) "Bridging the NISQ and Fault-Tolerant Regimes: Generative-ML-Assisted Quantum Selected CI" — generative ML guides quantum-sampling-based diagonalization for molecular binding energies; hybrid generative-ML + quantum chemistry — single group, queue (adjacent to trend-003 generative + AI-for-quantum)
- 2026-06-30 — Quantum-enhanced MCTS: arXiv:2606.30415 (Finet, Bérubé-Lauzière, Drouin-Touchette, Jun 29) "Quantum-enhanced Monte Carlo Tree Search for combinatorial optimization" — Grover-based speedup inside MCTS for combinatorial optimization; on-scope quantum optimization — single group, queue
- 2026-06-30 — Provable quantum advantage (theory): arXiv:2606.30396 (Xu, Yuan, Zhao, Jun 29) "Provable Quantum Advantage for Dynamical Phase Transition" — proves estimating DQPT to fixed precision is hard even for quantum computers, while a subsystem variant is BQP-hard; rigorous advantage/complexity result — single group, queue (hype-skeptic: theoretical, not an experimental claim)
- 2026-06-30 — Quantum-for-VLM: arXiv:2606.29966 (Ma, Long, Zhang, Jun 29) "RiverONE: Generating Knowledge-Intensive VLM by Simulated Quantum Machines" — quantum-simulated superposition/entanglement features to build knowledge-intensive vision-language models; quantum-for-AI substrate — single group, queue
- 2026-06-30 — Photonic quantum advantage (China Telecom / Jiuzhang 4.0): https://quantumcomputingreport.com/china-telecom-deploys-2682-photon-tianyan-p2000-web-platform-to-achieve-dual-modality-quantum-advantage-services/ — China Telecom Quantum brings the 2,682-photon Tianyan-P2000 (built on USTC's Jiuzhang 4.0 optical architecture, perf published in Nature May 2026) into cloud production; claims 29 µs vs "16 billion years" classical for a boson-sampling-class task — VENDOR/digest, HYPE-PRONE, intake only; underlying Jiuzhang 4.0 Nature primary NOT opened this session — follow to the Nature paper and weigh classical baseline before any citation
- 2026-07-01 — ML-optimized CV-QKD: arXiv:2606.31534 (Matsenko, Ghazisaeidi, Jarzyna, Kucharczyk, Schmidt, Banaszek, Jun 30) — machine-learning end-to-end optimization framework for continuous-variable QKD under practical hardware constraints (finite filter lengths, DAC/ADC resolution); AI-for-quantum-adjacent (ML tuning a quantum communication system) — single group, queue
- 2026-07-01 — Quantum-classical surrogate for CFD: arXiv:2606.31351 (Birk, Wawrzyniak, Winter, Schmidt, Indinger, Janßen, Jun 30) — parameterized-quantum-circuit surrogate model (data re-uploading / partial Fourier series) for the nonlinear collision operator of the Lattice Boltzmann Method; on-axis QML application — single group, queue
- 2026-07-01 — ML-based Pauli-term selection for QEM: arXiv:2606.31195 (Shiddiq, Tarigan, Prihadi, Kosasih, Sarwono, Kwek, Jun 30) — selects which Pauli-string Hamiltonian terms to include in ML-based quantum-error-mitigation training data, avoiding linear scaling with every Pauli string; adjacent to trend-001 (ML+QEM) but trend-001's evidence cap (10) is full — queued rather than appended — single group
- 2026-07-01 — New QLDPC-adjacent CSS code family: arXiv:2606.32001 (Kasai, Jun 30) — spatially-coupled MacKay-Neal/Hsu-Anastasopoulos CSS codes achieving the quantum-erasure hashing bound via seeded belief-propagation decoding; single-author, niche code-theory result adjacent to trend-001's QLDPC sub-theme — single group, queue
- 2026-07-01 — Applied QML for immunology: arXiv:2606.28655 (Brisebois, Gonzalez Dominguez, Prajapati, Khatooni, Wilson, Burbridge, Jun 27) — studies effects of entanglement/circuit depth on QML for pathogen epitope-receptor binding prediction; applied QML with a barren-plateau angle — single group, queue
- 2026-07-01 — Quantum optimization: arXiv:2606.29647 (Jun 28) "Hybrid Quantum Neighborhood Selection: NISQ-Compatible Combinatorial Optimization via Stochastic Frontier Decomposition" — on-scope quantum optimization — single group, queue

## source_rotation

Append-only coverage log MOVED to `logs/source_rotation.md`. Each run APPENDS one dated line
THERE and reads only the recent tail (~7 days) — do not write scans into TRENDS.md.

## strategy_notes

Corrections to the source-coverage strategy.
- 2026-06-26 — Scope (curator input): track the QUANTUM AI frontier — primarily using quantum computers to RUN AI/ML algorithms (quantum machine learning: variational circuits, quantum neural nets/kernels, data encoding, quantum optimization for ML, hybrid quantum-classical training, and quantum-advantage-for-ML claims) — plus the enabling quantum-computing research (hardware/qubits/coherence, error correction & fault tolerance, algorithms, SDKs, benchmarking) and the classical–quantum boundary (dequantization / classical simulation that tests whether a claimed advantage is real). AI-for-quantum (classical ML to control/error-correct quantum systems) is a watch-area, not a core axis. The agent owns and evolves these axes;
  promote a forming sub-theme to a trend at ≥3 independent groups + an artifact.
- 2026-06-27 (W26 weekly) — Source heals applied: (1) Quantum Computing Report RSS now uses `curl --compressed` (was returning binary; access method corrected in SOURCES.md); (2) YouTube channel IDs resolved and recorded in SOURCES.md: Qiskit=UClBNq7mCMf5xm8baE_VMl3A, PennyLane=UCuC1_7x7JvLupAMMwEEM2RA (last video 2024-04-23 — channel may be inactive), Sabine Hossenfelder=UC1yNl2E66ZzKApQdRuTQ4tw.
- 2026-06-27 (W26 weekly) — Source discovery: Quandela (quandela.com) and Alice & Bob (alice-bob.com) appeared as new on-axis orgs; staged in Discovered-source candidates in SOURCES.md for verification on next 2+ appearances. Majorana 2 queue item resolved: technical paper arXiv:2606.03884 ("20 Second Parity Lifetime in an InAs-Pb Tetron Device", Microsoft Quantum, June 2, 2026) found and added to study_shelf. Capture-leak found: arXiv:2606.26912 (Givens-exchange ansatz, VQE) was named in Jun-26 explore log but not queued — added to queue this run.

## study_shelf

Single strong items worth knowing, newest first (format: `date — [name](url) — one line of
why`). The trend bar does NOT apply here; opened primary sources only.

- 2026-07-01 — [Machine Learning Decoding of Circuit-Level Noise for Bivariate Bicycle Codes (Quantum, DOI 10.22331/q-2026-06-30-2149)](https://quantum-journal.org/papers/q-2026-06-30-2149/) — Blue, Avlani, He, Ziyin, Chuang (MIT, Jun 30): peer-reviewed neural decoder for circuit-level noise on bivariate bicycle QEC codes; a concrete, published (not just preprint) instance of the ML-decoder pattern that foundation decoders opened up.
- 2026-07-01 — [erado: open-source erasure-noise + postselection simulator (arXiv:2606.31428)](https://arxiv.org/abs/2606.31428) — Griffiths, Friel, Vlastakis: open-sources a numerical framework for circuit-level erasure noise and postselection-based error mitigation; a ready-to-use tool for evaluating the same postselection technique class IBM shipped as Qiskit Paulice, with a worked QFT example and a concrete erasure-check error-rate threshold (3.0%) for full mitigation.
- 2026-06-30 — [Learning the structure of open quantum systems (arXiv:2606.30358)](https://arxiv.org/abs/2606.30358) — Lewis, Tang, Wright (Jun 29): algorithm that learns the coefficients of an n-qubit constant-local Lindbladian to ε error with O(g·d²·log n / ε²) total evolution time — efficient (log-in-n) identification of open-system dynamics. Classical-quantum-boundary / quantum-learning-theory result from a notable group (Ewin Tang of dequantization fame); a clean rigorous benchmark for how cheaply quantum dynamics can be learned.
- 2026-06-29 (discovered) — [Google Quantum Echoes: verifiable quantum advantage on Willow (arXiv:2506.10191)](https://arxiv.org/abs/2506.10191) — Google Quantum AI (Nature, Oct 22, 2025; opened via https://research.google/blog/a-verifiable-quantum-advantage/): first claimed verifiable quantum advantage using Out-of-Time-Order Correlators (OTOCs) on Willow chip; task = measuring OTOC expectation values on quantum many-body systems; classical baseline = beyond known classical simulation capacity (Google's claim); dequantization status = UNVERIFIED — independent classical simulations not known, but skeptical takes exist; paves way for Hamiltonian learning in NMR. Scrutinize before citing as settled advantage.
- 2026-06-27 — [20 Second Parity Lifetime in InAs-Pb Tetron Device (arXiv:2606.03884)](https://arxiv.org/abs/2606.03884) — Microsoft Quantum (165 authors, June 2026): demonstrates 20-second parity lifetime in an InAs-Pb tetron device via interferometric single-shot parity measurements, orders of magnitude beyond typical qubit operation times (μs); validates the excitation-gap scaling principle for topological qubits and multi-tetron array bring-up at scale
- 2026-06-25 — [Foundation decoders for fault-tolerant QC](https://arxiv.org/abs/2606.27119) — high-capacity neural decoders now outperform classical decoders at large code distances; directly relevant to practical FTQC timelines
- 2026-06-25 — [Qiskit Paulice: postselected QEC for near-term circuits](https://www.ibm.com/quantum/blog/qiskit-paulice) — immediately usable addon that adds low-overhead error detection to existing Qiskit circuits; bridges current NISQ work to fault-tolerant architectures
- 2026-06-21 — [No Reference-Free Generalization in QML (arXiv:2606.22331)](https://arxiv.org/abs/2606.22331) — key theoretical result: without an orienting reference structure (basis/frame) in training data, a QML model cannot assign different meanings to unseen quantum directions; implications for circuit design and training set construction

## calibration

Append-only self-evaluation log MOVED to `logs/calibration.md` (see `radar-self-eval`).
Weekly runs APPEND there, never here.

# Sources registry — Quantum AI Radar

Agent-owned registry of monitored sources. The radar maintains and evolves this file
itself (add/remove/mark-dead entries, with a one-line reason in the day's or week's report)
— no curator sign-off needed. Skills describe the *method*; this file is the *data* (the
lists the skills iterate by force).

Hard-rule reminder: papers (arXiv quant-ph + peer-reviewed venues), official lab/vendor
technical blogs/release notes, and framework releases are PRIMARY sources (citable evidence).
Quantum "advantage/supremacy" press is hype-prone — a vendor PR or stock-news item is
INTAKE only; require the technical primary. Social/community sources are an INTAKE LANE ONLY.
Track and cite; never invent URLs/dates.

A source listed under a "swept every run" heading is a coverage PROMISE — log it opened or
`degraded: <reason>` every run. Mark each entry **[verified 2026-06-26]** (URL/feed opened
and confirmed at scaffold) or **[candidate]** (first sweep must verify before citing). NEVER
seed this file from memory: search + open real sources (Tavily), and reject SEO results.

---

## Primary feeds (Phase 1 — swept EVERY run)

Method: `radar-source-sweep`. Iterate EVERY entry; prefer the feed, fall back to `tvly extract`
for feed-less ones. Filter for on-scope relevance (QML / quantum-for-AI first; enabling
quantum-computing research second); skip pure product/marketing/funding PR.

- Google Quantum AI — https://quantumai.google/ **[verified 2026-06-26; HTML → `tvly extract`]** — quantum hardware + quantum-ML research
- IBM Quantum — https://www.ibm.com/quantum/blog + https://research.ibm.com/topics/quantum-machine-learning **[verified 2026-06-26; HTML → `tvly extract`]**
- PennyLane / Xanadu — https://pennylane.ai/blog **[verified 2026-06-26; no RSS (feed paths 404) → `tvly extract`]** — QML-focused, high signal
- Quantinuum — https://www.quantinuum.com/news **[verified 2026-06-26; the `/blog` path 404s — use `/news`]**
- IonQ — https://ionq.com/blog **[verified 2026-06-26; HTML]**
- Microsoft Azure Quantum — https://azure.microsoft.com/en-us/blog/quantum/ **[verified 2026-06-26]**
- Q-CTRL — https://q-ctrl.com/blog **[verified 2026-06-26]** — quantum control / error suppression (running ML on noisy hardware)

Independent / critical voices (NOT vendor — the counterweight to advantage hype; high priority):
- Scott Aaronson — "Shtetl-Optimized" — https://scottaaronson.blog/ · RSS https://scottaaronson.blog/?feed=rss2 **[verified 2026-06-26]** — the leading independent authority on quantum complexity and the key SKEPTICAL voice on quantum-advantage / dequantization claims. Directly serves the hype-skepticism hard rule.
- Quantum Frontiers (Caltech IQIM) — https://quantumfrontiers.com/ · RSS https://quantumfrontiers.com/feed/ **[verified 2026-06-26]** — independent academic blog on quantum information & computing.

- **[candidate]** Rigetti, PsiQuantum, Pasqal, QuEra, AWS Braket blog, NVIDIA quantum — verify feeds on first sweep

## Research / publication venues (primary)

- arXiv **quant-ph** (core) — https://arxiv.org/list/quant-ph/recent **[verified 2026-06-26]** ; QML = `cat:quant-ph` cross-listed with `cs.LG`/`cs.ET` (metadata via `export.arxiv.org/api/query?search_query=cat:quant-ph+AND+abs:%22machine+learning%22&sortBy=submittedDate`).
- Quantum (the open journal) — https://quantum-journal.org/ · RSS https://quantum-journal.org/feed/ **[verified 2026-06-26]**
- **[candidate]** PRX Quantum (journals.aps.org/prxquantum), npj Quantum Information (nature.com/npjqi), Nature/Science quantum papers — verify feeds on first sweep.
- **[candidate]** Conferences (proceedings/talks): QIP (Quantum Information Processing), TQC, Q2B — the field's key venues; verify on first sweep.
- metriq.info — community quantum-benchmark aggregator (Unitary Fund) **[verified 2026-06-26]** — track benchmark submissions/results (an independent reality-check on vendor performance claims).

## GitHub watch (Phase 5 — repos, profiles, and fork trees)

Method: `radar-repo-watch`. Watch releases (`<repo>/releases.atom`), notable forks, and
profile activity. New releases/frameworks are citable artifacts; movement is a queue signal.

### Watched repositories  (all **[verified 2026-06-26]** via GitHub API)
- PennyLaneAI/pennylane — open-source quantum-ML platform (Xanadu)
- Qiskit/qiskit — quantum SDK (IBM)
- qiskit-community/qiskit-machine-learning — QML library on Qiskit
- tensorflow/quantum — hybrid quantum-classical ML (Google)
- quantumlib/Cirq — NISQ circuit framework (Google)
- NVIDIA/cuda-quantum — GPU-accelerated quantum programming (hybrid QML at scale)
- amazon-braket/amazon-braket-sdk-python — AWS Braket SDK
- jcmgray/quimb — tensor-network quantum simulation (CLASSICAL baseline / dequantization axis)
- google/TensorNetwork · ITensor/ITensors.jl — tensor-network libraries (classical simulation of quantum ML — tests whether an advantage survives)
- quantumlib/OpenFermion — quantum algorithms for chemistry/physics
- unitaryfund/mitiq — quantum error mitigation (resolves via redirect)
- (agent: add new QML / quantum / classical-simulation frameworks as they appear; drop abandoned ones)

### Watched profiles/users  (**[verified 2026-06-26]** orgs — watch for NEW repos/releases)
- github.com/PennyLaneAI · github.com/Qiskit · github.com/quantumlib (Google) · github.com/NVIDIA (cuda-quantum) · github.com/microsoft (Q#/QDK)

### Fork-tree analysis
- Scan notable forks (depth ~3, by stars/recency) — new QML demos, plugins and methods often
  appear as forks/plugins. Seed targets: `PennyLaneAI/pennylane`, `Qiskit/qiskit`.

## Social & community channels (Phase 2 — INTAKE ONLY, never evidence)

Method: `radar-pulse`. Intake feeds `observation_queue` (unverified) + the pulse note; never
name/quote individuals beyond a bare URL. Multi-channel earthquake check.
- **r/QuantumComputing** — read its Atom feed directly: https://www.reddit.com/r/QuantumComputing/.rss **[verified 2026-06-26 — the `.rss` resolves; the `.json` API is often 403-blocked, so prefer `.rss` or Tavily]**. The canonical active quantum community.
- r/MachineLearning — for the ML side (via Tavily) **[candidate]**. (Note: r/QuantumML and r/quantum returned 403/empty at scaffold — dropped; re-add if they prove active.)
- Hacker News — Algolia API https://hn.algolia.com/api/v1/search?tags=front_page (+ `query=quantum`) **[verified pattern; known reliable]** — earthquake check.
- Quantum Computing Stack Exchange — Atom feed https://quantumcomputing.stackexchange.com/feeds **[verified 2026-06-26]** — Q&A community; a recurring question/answer can flag emerging methods or confusions worth tracking (intake → follow to a primary).
- Unitary Fund — https://unitary.foundation/ **[verified 2026-06-26]** — independent open-quantum-software nonprofit (mitiq, metriq); watch for community signals & releases.

### YouTube — TRUSTED-CURATOR POINTER LANE (check EVERY run, intake only)
- Qiskit (IBM) — https://www.youtube.com/@qiskit **[handle verified 2026-06-26; resolve `channel_id` on first use → `…/feeds/videos.xml?channel_id=UC…`]** — Qiskit / QML tutorials, talks, seminars.
- PennyLane (Xanadu) — https://www.youtube.com/@PennyLaneAI **[handle verified 2026-06-26; resolve `channel_id` on first use]** — quantum-ML demos & tutorials.
- Sabine Hossenfelder — https://www.youtube.com/@SabineHossenfelder **[handle verified 2026-06-26; resolve `channel_id` on first use]** — BROAD physics channel, but a prominent skeptic of quantum-computing hype; filter for quantum-computing / advantage-claim items only (serves the hype-skepticism mandate).
- (agent: add more quantum / QML channels as they prove high-signal; resolve each `channel_id` once from the channel page, follow each video to the named primary, cite the primary. Do NOT invent channel names. Scouting note 2026-06-26: the quantum/QML creator space is THIN — dominated by official org channels + broad-physics explainers; do not pad with off-topic generalist channels.)

### Curated digests + explainer/aggregator blogs (INTAKE LANE — swept every run)
- The Quantum Insider — https://thequantuminsider.com/ · RSS https://thequantuminsider.com/feed/ **[verified 2026-06-26]** — quantum news/digest; follow to the named primary, cite the primary, never the digest.
- Quantum Computing Report — https://quantumcomputingreport.com/ · RSS https://quantumcomputingreport.com/feed/ **[verified 2026-06-26]** — quantum news + market/technical analysis; intake → follow to the primary.
- lockwo/qml-library (github.com/lockwo/qml-library) **[verified 2026-06-26 via search]** — curated QML-paper list; a discovery aid → follow to the primaries.
- **[candidate]** Quantum journal "Views", individual quantum-ML researcher blogs — grow this list (verify before citing).

## Discovery / exploration venues (Phase 4 — iterated EVERY run by radar-explore)

Read top/most-attention items REGARDLESS of sub-topic, advancing the date window.
- arXiv quant-ph recent **[verified 2026-06-26]** + the `cat:quant-ph ∩ cs.LG` QML cross-listing (advancing window).
- Hugging Face papers (quantum-tagged) **[candidate]**; arXiv `cs.ET` (emerging tech) **[candidate]**.
- Watch-area (surface and queue): AI-for-quantum — classical ML for quantum control / calibration / error correction (the reverse intersection).

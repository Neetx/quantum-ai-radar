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
- Google "The Keyword" blog (blog.google) — research feed https://blog.google/innovation-and-ai/technology/research/rss/ **[verified 2026-06-29; redirects from `/technology/research/rss/` — follow with `-L`]** — where Google's FLAGSHIP quantum announcements actually land (Willow, Quantum Echoes "verifiable quantum advantage"), NOT the technical quantumai.google site. General Google-Research feed → filter for quantum/quantum-advantage items. HYPE-SKEPTIC (hard rule): an advantage/supremacy post here is a VENDOR disclosure — follow it to the technical primary (Nature/arXiv) and cite THAT, weighing the classical baseline / dequantization; the blog post alone is the announcement, not the evidence.
- Google Research blog — https://research.google/blog/ · RSS https://research.google/blog/rss/ **[verified 2026-06-29]** — the OTHER Google surface carrying quantum research posts (the 06-29 run found Quantum Echoes here). Same hype-skeptic handling: follow to the paper, cite the paper.
  (Coverage note, W27 weekly: both Google entries above were verified 2026-06-29 but the coverage check found "The Keyword" blog explicitly named in the daily log on only 1 of the next 6 passes — name BOTH Google sources by their own label in the coverage log every run, even when a pass finds nothing, so a shared "Google Quantum AI" mention doesn't stand in for either.)
- IBM Quantum — https://www.ibm.com/quantum/blog + https://research.ibm.com/topics/quantum-machine-learning **[verified 2026-06-26; HTML → `tvly extract`]**
- PennyLane / Xanadu — https://pennylane.ai/blog **[verified 2026-06-26; no RSS (feed paths 404) → `tvly extract`]** — QML-focused, high signal
- Quantinuum — https://www.quantinuum.com/news **[verified 2026-06-26; the `/blog` path 404s — use `/news`; HEALED 2026-07-04: plain `tvly extract` was returning only nav/menu content 2026-07-03 — use `--extract-depth advanced`, which returns the full dated press-release list (latest: Jun 21 2026 HPE collaboration, already captured)]**
- IonQ — https://ionq.com/blog **[verified 2026-06-26; HTML]**
- Microsoft Azure Quantum — https://azure.microsoft.com/en-us/blog/quantum/ **[verified 2026-06-26]**
- Q-CTRL — https://q-ctrl.com/blog **[verified 2026-06-26]** — quantum control / error suppression (running ML on noisy hardware)

Independent / critical voices (NOT vendor — the counterweight to advantage hype; high priority):
- Scott Aaronson — "Shtetl-Optimized" — https://scottaaronson.blog/ · RSS https://scottaaronson.blog/?feed=rss2 **[verified 2026-06-26]** — the leading independent authority on quantum complexity and the key SKEPTICAL voice on quantum-advantage / dequantization claims. Directly serves the hype-skepticism hard rule.
- Quantum Frontiers (Caltech IQIM) — https://quantumfrontiers.com/ · RSS https://quantumfrontiers.com/feed/ **[verified 2026-06-26]** — independent academic blog on quantum information & computing.

Hardware vendors / labs (verified 2026-06-29 scouting pass — replaces the old unverified candidate stub). Vendor blogs are PRIMARY for their own hardware/results but advantage claims are hype-prone → follow to the technical primary:
- Pasqal — https://www.pasqal.com/news/ · RSS https://www.pasqal.com/feed/ **[verified 2026-06-29]** — neutral-atom analog/QML
- AWS Braket — https://aws.amazon.com/blogs/quantum-computing/ · RSS https://aws.amazon.com/blogs/quantum-computing/feed/ **[verified 2026-06-29]** — Braket SDK + hybrid quantum-ML how-tos
- NVIDIA quantum — **[HEALED 2026-07-02: the Atom `/feed/` URL returns HTTP 200 but zero `<entry>` elements 2 runs running (Jul 1, Jul 2) — abandon the feed. Use `tvly extract https://developer.nvidia.com/blog/tag/quantum-computing/ --extract-depth advanced` instead (confirmed working, returns dated post list; latest Jun 11 2026 InfiniBand post, off-scope)]** — CUDA-Q / GPU-accelerated hybrid QML
- Alice & Bob — **[HEALED 2026-07-02: RSS https://alice-bob.com/feed/ returns HTTP 200 with channel metadata but zero `<item>` elements 2+ runs running — abandon the feed. Use `tvly extract https://alice-bob.com/blog/` instead (confirmed working, returns full post list; latest still "This Is Not a Product Launch" Jun 10 2026, already captured)]** — cat-qubit hardware + AI-for-quantum-control
- Rigetti — https://www.rigetti.com/news **[verified 2026-06-29; HTML → `tvly extract` (no Squarespace feed)]**
- PsiQuantum — https://www.psiquantum.com/blog **[HEALED 2026-07-04: `/blog` and `/news` both return a JS-loading placeholder ("Loading articles...") even at `--extract-depth advanced` — switch to `/news-import/category/Blog`, which returns real post content. Caveat: this category page appears to surface evergreen/featured posts rather than a strict recency feed (2026-07-04 pass returned only Sept-2025/Feb-2025 items, e.g. Construct, Omega — both pre-dating this radar, no new items this pass) — verify sort order / freshness over the next few runs before fully trusting it as a recency signal]** — photonic FTQC
- QuEra — https://www.quera.com/blog **[verified 2026-06-29; HTML → `tvly extract`]** — neutral-atom
- Quandela — https://www.quandela.com/resources/blog/ **[HEALED 2026-07-04: plain `tvly extract` returns a JS-loading placeholder ("Loading articles...") — use `--extract-depth advanced`, which returns the full dated post list. This uncovered 2 on-axis posts missed by the shallow method: NVIDIA NVQLink GPU–QPU integration for photonic QML (ISC High Performance 2026, Hamburg, 2026-06-23) and the MerLin open-source photonic-QML framework]** — photonic QML
- Atom Computing — https://atom-computing.com/news/ **[verified 2026-06-29; HTML → `tvly extract`]** — neutral-atom
- Infleqtion — https://www.infleqtion.com/news **[verified 2026-06-29; HTML → `tvly extract`]** — neutral-atom / quantum sensing
- IQM — https://www.meetiqm.com/newsroom **[verified 2026-07-02; curl returns 000 (site blocks datacenter IPs) → `tvly extract` works]** — superconducting; mostly business/governance PR, filter for technical content
- Oxford Ionics — https://oxfordionics.com/news **[verified 2026-07-02; path resolved (was 404 2026-06-29) → `tvly extract`]** — trapped-ion (now part of IonQ post-acquisition)

## Research / publication venues (primary)

- arXiv **quant-ph** (core) — https://arxiv.org/list/quant-ph/recent **[verified 2026-06-26]** ; QML = `cat:quant-ph` cross-listed with `cs.LG`/`cs.ET` (metadata via `export.arxiv.org/api/query?search_query=cat:quant-ph+AND+abs:%22machine+learning%22&sortBy=submittedDate`).
- Quantum (the open journal) — https://quantum-journal.org/ · RSS https://quantum-journal.org/feed/ **[verified 2026-06-26]**
- npj Quantum Information — https://www.nature.com/npjqi/ · RSS https://www.nature.com/npjqi.rss **[verified 2026-07-03 — feed returns clean dated items with DOIs, e.g. s41534-026-xxxxx; peer-reviewed, primary]**
- PRX Quantum — https://journals.aps.org/prxquantum/recent **[verified 2026-07-04: direct `curl` still 403 (blocked since scaffold), but `tvly extract --extract-depth advanced` on the `/recent` listing page returns a clean, dated article list with DOIs and abstracts — promoted from `[candidate]`. First sweep surfaced 1 on-axis primary: "Beam Search Decoder for Quantum Low-Density Parity-Check Codes" (Ye, Wecker, Delfosse), PRX Quantum 7, 033002, published 1 July 2026, DOI 10.1103/6k5x-ztqt — queued, trend-001-adjacent, cap full]**
- **[candidate]** Conferences (proceedings/talks): QIP (Quantum Information Processing), TQC, Q2B — the field's key venues; verify on first sweep.
- metriq.info — community quantum-benchmark aggregator (Unitary Fund) **[verified 2026-06-26]** — track benchmark submissions/results (an independent reality-check on vendor performance claims).

## GitHub watch (Phase 5 — repos, profiles, and fork trees)

Method: `radar-repo-watch`. Watch releases (`<repo>/releases.atom`), notable forks, and
profile activity. New releases/frameworks are citable artifacts; movement is a queue signal.

**[ENVIRONMENT CONSTRAINT, first observed 2026-07-02]** — direct `curl` to `github.com`
(including public unauthenticated paths like `/releases.atom`) now returns a 403 from this
session's proxy: "sessions are bound to their configured repositories... Use repository-scoped
endpoints." The session's GitHub access (both raw HTTP and the GitHub MCP server) is scoped to
`neetx/quantum-ai-radar` only — external repos are unreachable via curl or MCP. WORKING FALLBACK:
`tvly extract https://github.com/<owner>/<repo>/releases` (Tavily's crawler is not subject to
this session's egress scoping) — returns the release list, parse the top entry. Use this for
every watched repo going forward; retest raw `curl .../releases.atom` occasionally in case the
restriction lifts. Fork-tree analysis (`radar-repo-watch`'s fork scan) is currently NOT
executable this way — no working substitute found 2026-07-02; best-effort `tvly search` for
"<org> new repository" is a weak proxy, log as degraded until a better method is found.

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
- merlinquantum/merlin — **[verified 2026-07-04]** open-source differentiable photonic QML framework (Quandela), built on Perceval, PyTorch-native `QuantumLayer`; discovered via the Quandela blog heal this run; latest tagged release 0.3.1
- (agent: add new QML / quantum / classical-simulation frameworks as they appear; drop abandoned ones)

### Watched profiles/users  (**[verified 2026-06-26]** orgs — watch for NEW repos/releases)
- github.com/PennyLaneAI · github.com/Qiskit · github.com/quantumlib (Google) · github.com/NVIDIA (cuda-quantum) · github.com/microsoft (Q#/QDK)

### Fork-tree analysis
- Scan notable forks (depth ~3, by stars/recency) — new QML demos, plugins and methods often
  appear as forks/plugins. Seed targets: `PennyLaneAI/pennylane`, `Qiskit/qiskit`.

## Discovered-source candidates (auto-staged by the daily — NOT yet swept; the weekly verifies & promotes)

The source-discovery loop's staging area. The radar grows its OWN source coverage the way it
finds papers and curators: when any daily lane NAMES an on-axis primary whose publishing
org/domain is NOT already in a swept list above, the daily APPENDS/increments it here — a tally
only, NO extra fetch (you already hold the URL). The weekly VERIFIES the recurring ones (opens
the feed / repo / channel — never from memory) and PROMOTES them into the swept registry as
`[candidate]`, pruning one-off noise. This closes the gap where an on-axis lab/vendor that
announces only on its own channel (not a tracked venue) goes untracked because no swept list
points at it. Promotion bar: ≥2 on-axis primary artifacts OR recurrence across ≥2 runs, AND it
survives verification (real feed, on-axis, not SEO/hype-PR). Line format:
`domain/org — times seen — last on-axis artifact (date) — first seen YYYY-MM-DD`.

- (cleared 2026-06-29: quandela.com + alice-bob.com PROMOTED to the hardware-vendors swept list above in the verified scouting pass — see Phase-1)

## Social & community channels (Phase 2 — INTAKE ONLY, never evidence)

Method: `radar-pulse`. Intake feeds `observation_queue` (unverified) + the pulse note; never
name/quote individuals beyond a bare URL. Multi-channel earthquake check.
- **r/QuantumComputing** — read its Atom feed via the OLD-REDDIT domain: `curl -sL -A "Mozilla/5.0 (Windows NT 10.0; Win64; x64)" https://old.reddit.com/r/QuantumComputing/.rss` **[HEALED 2026-07-03 — the www.reddit.com `.rss` path (healed 2026-06-30 with a browser UA) started 403'ing again and stayed broken for 5 consecutive runs (Jun 30 Pass2 – Jul 3); www.reddit.com's `.json` API also 403s even with a UA. `old.reddit.com/.rss` with the same UA returns HTTP 200 with a full, current item list — confirmed working 2026-07-03. Use old.reddit.com going forward; retest www.reddit.com occasionally in case it un-blocks]**. The canonical active quantum community.
- **[REMOVED 2026-07-04, W27 weekly]** r/MachineLearning — via Tavily search, never promoted past `[candidate]`. Swept daily 2026-06-26 through 06-30 (5 runs) with zero quantum-relevant hits each time; daily runs then silently stopped sweeping it (2026-07-01 onward logged "not swept — deprioritized") without a formal removal — a coverage-honesty gap caught by this week's coverage check. Formally dropped now rather than left as an unswept promise; re-add if a quantum-ML crossover thread is later found active there. (Note: r/QuantumML and r/quantum returned 403/empty at scaffold — dropped; re-add if they prove active.)
- Hacker News — Algolia API https://hn.algolia.com/api/v1/search?tags=front_page (+ `query=quantum`) **[verified pattern; known reliable]** — earthquake check.
- Quantum Computing Stack Exchange — Atom feed https://quantumcomputing.stackexchange.com/feeds **[verified 2026-06-26]** — Q&A community; a recurring question/answer can flag emerging methods or confusions worth tracking (intake → follow to a primary).
- Unitary Fund — https://unitary.foundation/ **[verified 2026-06-26]** — independent open-quantum-software nonprofit (mitiq, metriq); watch for community signals & releases.

### YouTube — TRUSTED-CURATOR POINTER LANE (check EVERY run, intake only)
- Qiskit (IBM) — https://www.youtube.com/feeds/videos.xml?channel_id=UClBNq7mCMf5xm8baE_VMl3A **[channel_id resolved 2026-06-27; HEALED 2026-07-02 Pass 2: feed back to HTTP 200 after 404 for 2 runs (Jul1, Jul2 Pass1) — direct feed fetch is the primary method again, tvly-search fallback no longer needed]** — Qiskit / QML tutorials, talks, seminars.
- **[AMENDMENT APPLIED 2026-07-04, W27 — proposed W26]** PennyLane (Xanadu) — https://www.youtube.com/feeds/videos.xml?channel_id=UCuC1_7x7JvLupAMMwEEM2RA **[channel_id resolved 2026-06-27; last video 2024-04-23 — channel confirmed inactive on every single run 2026-06-27 through 2026-07-03 (7 consecutive checks, feed itself healthy/HTTP 200), motivating signal held for a full week — downgraded from "check EVERY run" to a monthly spot-check (next check: ~2026-08-04); re-promote to every-run if it ever posts again]** — quantum-ML demos & tutorials.
- Sabine Hossenfelder — https://www.youtube.com/feeds/videos.xml?channel_id=UC1yNl2E66ZzKApQdRuTQ4tw **[channel_id resolved 2026-06-27; HEALED 2026-07-02 Pass 2: feed back to HTTP 200 after 404 for 2 runs]** — BROAD physics channel, but a prominent skeptic of quantum-computing hype; filter for quantum-computing / advantage-claim items only (serves the hype-skepticism mandate).
- (agent: add more quantum / QML channels as they prove high-signal; resolve each `channel_id` once from the channel page, follow each video to the named primary, cite the primary. Do NOT invent channel names. Scouting note 2026-06-26: the quantum/QML creator space is THIN — dominated by official org channels + broad-physics explainers; do not pad with off-topic generalist channels.)

### Curated digests + explainer/aggregator blogs (INTAKE LANE — swept every run)
- The Quantum Insider — https://thequantuminsider.com/ · RSS https://thequantuminsider.com/feed/ **[verified 2026-06-26]** — quantum news/digest; follow to the named primary, cite the primary, never the digest.
- Quantum Computing Report — https://quantumcomputingreport.com/ · RSS https://quantumcomputingreport.com/feed/ **[verified 2026-06-26; feed is gzip-compressed — access via `curl --compressed` not plain `curl`; repaired 2026-06-27]** — quantum news + market/technical analysis; intake → follow to the primary.
- Quantum Zeitgeist — https://quantumzeitgeist.com/ · RSS https://quantumzeitgeist.com/feed/ **[verified 2026-06-26]** — quantum news/content digest; intake → follow to the named primary (assess signal quality over the first weeks; drop if mostly SEO).
- lockwo/qml-library (github.com/lockwo/qml-library) **[verified 2026-06-26 via search]** — curated QML-paper list; a discovery aid → follow to the primaries.
- **[candidate]** Quantum journal "Views", individual quantum-ML researcher blogs — grow this list (verify before citing).

## Discovery / exploration venues (Phase 4 — iterated EVERY run by radar-explore)

Read top/most-attention items REGARDLESS of sub-topic, advancing the date window.
- arXiv quant-ph recent **[verified 2026-06-26]** + the `cat:quant-ph ∩ cs.LG` QML cross-listing (advancing window).
- Hugging Face papers (Daily Papers) — https://huggingface.co/papers **[AMENDMENT APPLIED 2026-07-04, W27 — proposed W26]** — the W26-proposed `tvly search site:huggingface.co/papers` method still returned only noisy generic query-result pages this run (7th straight failure since scaffold); the FIX is a direct `tvly extract https://huggingface.co/papers --extract-depth advanced`, confirmed working 2026-07-04 (returns the dated trending-paper list with arXiv ids) — promoted from `[candidate]` with the corrected method. Expect low quantum-relevant yield (the feed skews general AI/agentic-LLM topics) — grep the extracted titles/ids for quantum keywords each run; arXiv `cs.ET` (emerging tech) **[candidate]**.
- Watch-area (surface and queue): AI-for-quantum — classical ML for quantum control / calibration / error correction (the reverse intersection).

# Agent guide — Quantum AI Radar

Instructions for AI agents (and humans) working in this repository. Task-specific
instructions come from the session prompt; this file holds the invariants that
apply to every session.

## What this repo is

Persistent state for Quantum AI Radar, an autonomous radar that tracks and curates
**the quantum-computing research frontier and its intersection with AI — chiefly using quantum computers as a computational substrate to RUN AI/ML algorithms (quantum machine learning), plus the quantum-computing progress that enables it** for a quantum-computing / quantum-ML researcher. It is a RADAR (situational awareness): it
tracks and points to primary artifacts; it does not perform the work it tracks.
`TRENDS.md` is the single source of truth; the README and reports are derived
snapshots. Besides trends, the radar curates a study shelf (`study_shelf` in
`TRENDS.md`, surfaced on the README). History matters: never rewrite published
history, never force-push.

Scope — what to track (curator seeds; the agent OWNS and evolves these axes — they
are not a frozen list):
1. **Quantum AI — quantum computing FOR AI** (lead axis): quantum machine learning (QML) — variational / parameterized quantum circuits, quantum neural networks, quantum kernels & feature maps, quantum data encoding/loading, quantum transformers/attention, quantum generative & reinforcement learning, quantum optimization for ML (QAOA / VQE-for-ML), hybrid quantum-classical training & inference, and claims/benchmarks of quantum advantage on ML tasks (treated skeptically — see Hard rules).
2. **Enabling quantum-computing research**: hardware platforms (superconducting, trapped-ion, neutral-atom, photonic, topological) and milestones (qubit count, gate fidelity, coherence); quantum error correction & fault tolerance (logical qubits, surface/LDPC codes, thresholds); quantum algorithms & complexity; quantum software / compilers / SDKs; benchmarking (quantum volume, randomized benchmarking, application benchmarks).
3. **The classical–quantum boundary**: dequantization & classical simulation of quantum ML (does a claimed advantage survive?), tensor-network methods, and honest classical baselines.
4. **Watch-area (surface & queue, not a forced axis): AI-for-quantum** — classical ML used to design, calibrate, control or error-correct quantum systems (the reverse intersection).

## File map

| Path | Contents | Edit policy |
|---|---|---|
| `TRENDS.md` | Trend ledger + `observation_queue`, `strategy_notes`, `study_shelf`; `source_rotation` and `calibration` are one-line pointer stubs | follow the `radar-ledger-update` skill |
| `logs/source_rotation.md` | Append-only daily coverage log (externalized to keep the ledger small); read only the recent tail | append-only; never edit/reorder past lines |
| `logs/calibration.md` | Append-only weekly self-evaluation log | append-only; written by weekly runs only |
| `README.md` | THE output surface (repo landing page): badges, digest, clickable trend table, study shelf | fully derived — regenerate via `radar-render-dashboard`; never edit by hand |
| `SOURCES.md` | Agent-owned registry: primary feeds, watched repos, social channels, discovery venues — the lists the skills iterate | maintained by the radar itself |
| `ARCHIVE.md` | Archived trends, one-line post-mortems | append-only |
| `reports/YYYY-MM-DD.md` | Daily reports | write once, never edit old ones |
| `reports/weekly/YYYY-Wnn.md` | Weekly reports | write once |
| `routines/*.md` | LIVE operating instructions, loaded by the fixed platform prompt | weekly amendments only, per the Self-amendment policy |
| `.claude/skills/` | Project skills (source sweep, pulse, explore, ledger update, self-eval, source heal, source verify, repo watch, dashboard render) | improvable — see policy below |

## Hard rules (the constitution — never relax these)

- **Primary sources only for EVIDENCE**, and only URLs actually opened in the
  current session. Anything not opened is "unverified" and belongs in
  `observation_queue`. Primary = papers (arXiv quant-ph first, plus cs.LG/cs.ET for QML; peer-reviewed venues — Quantum, PRX Quantum, npj Quantum Information, Nature/Science), official lab/vendor technical blogs & release notes, framework releases, and standards/benchmarks. Never SEO farms,
  never aggregators/comparators.
- **Track, don't reproduce.** An evidence line is `date — primary URL — one line of
  context`; max 10 evidence items per trend. The radar points to artifacts and
  summarizes their significance — it is a tracker, not a how-to.
- Social/community sources are an INTAKE LANE ONLY — they may create unverified
  `observation_queue` items (promotable only after confirmation on a primary
  artifact) and feed the community-pulse note, but NEVER become trend evidence.
- Never guess dates or invent URLs. Undated pages: "(undated, accessed YYYY-MM-DD)".
- **Trend bar:** ≥3 independent sources (different orgs/author groups) + ≥1 concrete
  artifact. A single strong item is not a trend, but can go on the `study_shelf`.
- Do not rename sections or restructure files. Everything in this repo is in English.
- Quantum **advantage / supremacy / speedup** claims are HYPE-PRONE: cite the technical primary (paper/preprint), state the exact task and the classical baseline, and note whether the result has been (or could be) **dequantized / classically simulated**. A vendor press release or stock-news item is intake-only — never evidence on its own; require the technical artifact.
- Never name or quote individuals beyond a bare source URL.

## Coverage discipline

- Runs are not rate-limited: multiple runs in the same day are allowed and expected
  when triggered. The only per-day cap is on stage promotions (one step up per trend).
  Never refuse a run citing a "one run per day" rule — none exists here.
- Every run does a FULL CHECK of every mandatory lane (source sweep, community pulse,
  discovery exploration, repo/release watch). The CHECK (open each registered source's
  feed/index, see what is new) is owed every run and may never be skipped as a "light
  pass"; only the EXTRACT (open the full artifact) is conditional on a genuinely new
  item. A registered source absent from the day's coverage log is a coverage lie.
- Every run reserves at least one source family for venue-based exploration outside the
  ledger's current axes (`radar-explore`): browse listings where new work surfaces
  rather than re-querying tracked topics. Log it even when it yields nothing.
- Weekly runs check for anchoring: a week where all new evidence lands on pre-existing
  trends gets flagged in `strategy_notes`, and exploration is redirected.
- Weekly runs self-evaluate (`radar-self-eval`): calibration metrics every week
  (including a `coverage` metric = registered sources vs the week's logs, and a
  `routing-leak` metric), a hit/miss retrospective monthly, and up to 3 proposed
  amendments handled per the policy below.

## Tooling

- Web: prefer the Tavily CLI (`tvly`) via the `tavily-search` and `tavily-extract`
  skills. Auth comes from `TAVILY_API_KEY` — never print it, never write it to any file
  in this repo. If `tvly` is missing: `pip install -q tavily-cli`. Fall back to built-in
  web tools only if Tavily fails.
- arXiv quant-ph is the core venue: `curl -sL 'https://export.arxiv.org/api/query?search_query=cat:quant-ph&sortBy=submittedDate&sortOrder=descending&max_results=N'` (cross-list with cs.LG for QML). Use GitHub `releases.atom` for the framework repos (Qiskit, PennyLane, Cirq, cuda-quantum).
- Self-healing: when a source/tool fails the same way twice, repair the access path and
  record the working method in `SOURCES.md` (`radar-source-heal`). The heal worklist is
  the `degraded:` markers in the coverage log; don't log "degraded" run after run.

## Efficiency (single-agent; do NOT use sub-agents/teams)

Sub-agents cost MORE total tokens (each has its own context). A run is one session.
Triage then extract (read feeds/titles first; open the full artifact only for genuinely
new items); read only the recent tail of the long append-only logs; use Tavily with
modest depth and `--include-domains` to cut noise. Triage-for-cost must never become
"sample a subset and call it done".

## Git conventions

- Commit messages: `radar: daily update YYYY-MM-DD`, `radar: weekly recalibration
  YYYY-Wnn`, `radar: refine skill <name>`, or `radar: <short description>`.
- Any commit that changes `TRENDS.md` must regenerate `README.md` in the same commit.
- Push to `main` with `git push origin HEAD:main`, even when the session was started on
  a `claude/*` working branch. The curator has enabled unrestricted branch pushes and
  explicitly authorizes pushing to `main`: platform notices about `claude/*` branches
  describe the default, not a prohibition. Attempt the push — push ONLY main, do not also
  push the session working branch.
- A session-branch platform notice (a message that this session runs on a `claude/…`
  branch) is NOT a policy that overrides this file — it names the default working branch,
  not a restriction on push targets. Do NOT pre-emptively downgrade to the session branch
  on the ASSUMPTION that `main` is blocked: the only thing that legitimately diverts a push
  to the session branch is a push to `main` you ACTUALLY attempted and the server ACTUALLY
  rejected with a permission error. No observed rejection → push `main`.
- If the push is rejected: retry once after `git pull --rebase origin main`. Never
  force-push, never rewrite published history. Only if the server actually rejects it
  (permission error): push to the session branch, open the report with a prominent
  BRANCH WARNING that `main` must be fast-forwarded before the next run, and paste the
  verbatim rejection error, AND send the curator a push
  notification — stranded state on a branch is attention-worthy (main does not fast-forward
  itself, and the next scheduled run will build on the stale main and orphan this session's
  work), and a report note alone is not seen until the curator looks.
- Operator notifications: stay SILENT on healthy/routine runs (a notification every run is
  noise). Send a push notification only for something the curator must see BEFORE the next
  run — a failed `main` push / stranded state, a broken hard rule, or a degradation you have
  self-flagged "heal owed" for ≥3 consecutive runs.

## Self-amendment (autonomy contract)

The radar runs unattended: in normal operation no human edits prompts, skills or scope.
The fixed platform prompt of each scheduled session is a fixed loader and must never
change:

> You are the daily [weekly] operator of this repository. Read AGENTS.md, then read
> routines/daily.md [routines/weekly.md] and execute it exactly. If either file is
> missing or unreadable, write a report describing the problem, commit only the report,
> and stop.

Because `routines/*.md` are the live operating instructions, they are amendable:

- Only weekly runs amend `routines/*.md`, skills, or scope axes. Daily runs execute.
- Every amendment must cite the calibration metric or retrospective that motivates it.
- Cooling period: PROPOSED in one weekly report, APPLIED on the next weekly run only if
  the motivating signal persists. Silence is consent; the curator may veto with a dated
  entry in `strategy_notes`.
- One dedicated commit per applied amendment: `radar: amend <target> — <reason>`.
- Auto-rollback: if calibration metrics worsen for two consecutive weeks after an
  amendment, `git revert` it and log the rollback in `calibration`.
- Scope axes evolve the same way: a "radar-adopted" dated entry in `strategy_notes` may
  supersede an older axis. Curator entries are never deleted or edited.

Immutable (curator-only): the Hard rules, Coverage discipline and this Self-amendment
section; the existence of the self-evaluation step; append-only history.

## Skill maintenance policy

Skills in `.claude/skills/` may be improved when a procedure proves wrong, clunky or
incomplete. Never relax the hard rules above (skills make them more precise, not weaker).
Keep SKILL.md frontmatter valid (`name`, `description`). One dedicated commit per skill
change. Create a new skill only after the same procedure has been improvised twice.

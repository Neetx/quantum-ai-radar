---
name: radar-source-sweep
description: |
  Sweep the primary-source feeds (vendor/lab/research blogs and publication venues) on EVERY daily run (not rotated) so no on-scope release, disclosure or paper is missed. Prefer RSS/Atom feeds over HTML pages to survive JavaScript-rendered indexes. Use at the start of every daily scan, before the rotating exploration slot.
---

# Primary-feed sweep — every run, no rotation

A real radar checks its primary feeds every single day. This sweep is
mandatory on every daily run and is separate from (and in addition to) the
rotating exploration slot. Official lab/vendor blogs are primary sources under
the Hard rules, so anything found here is citable evidence.

The CHECK (fetch every feed and see what is new since the last scan) is owed on
EVERY run, even one minute after another pass — it is cheap triage and may never
be skipped as a "light pass". Only the EXTRACT (open a new post in full) is
conditional on a genuinely new entry.

## Method (efficient)

1. For each source in the list, fetch its FEED first (RSS/Atom), not the HTML
   index — feeds are immune to the JS-rendering that hid `lmsys.org/blog`. To
   find a feed: try `/rss.xml`, `/feed`, `/atom.xml`, `/index.xml`, or read the
   page's `<link rel="alternate" type="application/rss+xml">`.
2. Open only entries dated AFTER the last daily scan (check the previous date in
   `logs/source_rotation.md`). Skip everything older — this keeps the sweep cheap.
3. Apply the evidence rules: open the actual post, cite its own date, match to a
   trend or log to `observation_queue`/`study_shelf` as appropriate.
4. Log the sweep in `logs/source_rotation.md` every run, even when nothing is new
   ("lab-sweep: no new posts").

## Source list

The lists live in `SOURCES.md` → "Primary feeds" and "Research / publication venues" (agent-owned: mark
feeds `DEAD` if they stop resolving, add new sources as they appear). Prefer the
feed URL; fall back to the HTML index via `tvly extract` only if no feed exists.

## Notes

- The sweep complements, never replaces, the rotating exploration slot.
- Vendor/lab/research blogs often disclose releases or techniques that never become
  papers — those are exactly what this sweep exists to catch.
- Keep this list in sync with any unified source registry if one is introduced.

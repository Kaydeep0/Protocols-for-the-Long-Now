# Supporting media — prototype and figures

Copyright (c) 2026 Kirandeep Kaur. All rights reserved.

Use this document as upload material or as source text for the supporting media field.

---

## What the visuals show

Seven panels read left to right (or top to bottom). They are one argument in pictures:

1. **Dot (+1)** — Time begins as a single distinction, not a second.
2. **Tick count (line)** — Repeated +1 gives ordinal time before metric duration.
3. **Mod-N circle** — Finite action budget wraps the line into cycles.
4. **Phase wedge (pi)** — Position on the cycle has angular spread, not just index.
5. **CAD helix** — Cycles lift through accumulation; geometry you can build.
6. **Helix through time** — Past marks sit on earlier coils; deep time as structure.
7. **Spiral pitch** — Each return is wider; memory across cycles prevents loss at the waist.

**One-line summary for reviewers:**

Seven panels trace time from counted distinction (+1) through line, circle, phase, helix, deep-time coil, and spiral pitch. Ordinal time precedes clocks. Geometry is the teaching surface.

Full captions: [FIGURE_CAPTIONS.md](FIGURE_CAPTIONS.md)

---

## How a prototype would work

If selected for follow-on development (top 3), an eight-week civic prototype:

### 1. HelixClock CLI

A command-line tool that lets anyone append a tick, verify the chain, and export a head hash anchored to civilizational time (02026-style five-digit years plus external timestamp reference).

```
tick append "Council voted to adopt five-digit years"
tick verify
tick export --anchor rfc3161
```

Uses existing HelixHash library (append-only, tamper-evident). Truth of content remains a separate witness layer; order is not negotiable.

### 2. Phase dial (hourglass)

A live or demo visualization showing where the system sits in phase:

- **Below the waist:** accumulation, intake, unresolved mass
- **At the Landauer floor:** narrow passage; system can flip dynamics if it carries no memory across cycles
- **Above the waist:** commitment, deployment, irreversible action

This is experiential time: you feel phase, not just read a timestamp.

### 3. Prahar ring (daily rhythm)

Eight three-hour segments structure a day. Segment 7 (Amrit Vela) locks to **settlement only**: no new ticks, only decay of unresolved mass. Silence is scheduled, not accidental.

### 4. Public demo day

One calendar day, N ticks, one verifiable export anyone can inspect. Demonstrates marking + experiencing + making sense in one package.

---

## What already exists

| Component | Status |
|-----------|--------|
| HelixHash (sequence chain) | Shipped on PyPI |
| E = ΔI/A prior art | Zenodo DOI |
| Geometry figures (7 panels) | In `figures/` |
| Hourglass dashboard | GeniusFlow research prototype |
| This concept essay | Repo + form text |

**Gap:** Packaging for civic, teachable use (CLI + dial + prahar ring + public demo).

---

## Suggested upload bundle

Minimum: all 7 images in `figures/`.

Better: `supporting/PROTOTYPE_AND_FIGURES.pdf` (combined strip + this prototype page).

Optional: short screen recording (<5 min) walking through the seven panels and HelixClock mock flow.

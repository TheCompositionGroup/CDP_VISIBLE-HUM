# Changelog

Each revision lists what it **added** and what it **removed**. A documented kill is a result.

## v4.1 — Field-test seed — 2026-10-14

Released as an **unverified seed**. No field trial has run. Not validated.

### 1. Honesty
- **Added:** "Unverified seed — no field trial yet" banner to `README.md` and `docs/onepage.md`. Restated the no-dB rule in both.
- **Removed:** nothing.

### 2. Readability
- **Changed:** `docs/onepage.md` (about 460 words, one letter page, grade about 4) and guide Sections 0–3 rewritten for a tired reader on a phone. Short steps, one action each, a plain definition for each new term. Room and window examples now use feet and inches (window gaps also give mm).
- **Added:** "divide 563 by the length in feet" shortcut for the room-resonance step (563 = half the speed of sound in ft/s). Source notes after each section.
- **Removed:** the symbolic formulas in Sections 1–2 (`f = c / 2L`, the mass-air-mass formula) from the reader's path. The A-weighting table stays, labelled as filter settings, not measurements. In `onepage.md` the A-weighting section no longer shows dB values; it says "about 1/20" and "about 1/6" instead.
- **Softened:** the "$3,000–8,000" figure in `onepage.md` and `README.md` is now marked a rough guess (it is open item 8).
- **Changed:** guide header now reads v4.1, 14 Oct 2026. The document ID there is now FA-HUM-001 (see Cleanup).
- **Left alone:** Sections 4–7 and the appendices. They are not yet rewritten for plain reading.

### 3. Who to send it to
- **Added:** `docs/who-to-send-it-to.md` (who reads a hum log, what to ask each, what varies by state). `log/cover-letter.md` (one-page template). Pointers from guide Section 6 and the README.
- **Removed:** nothing. No contact details were added; offices and powers are unchecked (open item 9). The federal-noise-office line cites the EPA history page; the rest of the offices table is still unchecked.

### 4. Tester handoff
- **Added:** `.github/ISSUE_TEMPLATE/field-report.md`. "Help test this" section in `README.md` with a no-GitHub email route. Testers are asked to do Sections 1–3 only.
- **Removed:** the README line "Readers are not sent here". Field testers now are.

### 5. Cleanup
- **Removed:** the `archive/` row from the README layout. The folder was empty and the v1 and v3 files are not in the repository. The README now says so.
- **Added:** a "who can settle it" column for the ten unverified claims in `docs/open-items.md`. A-weighting values and the mass-air-mass formula were re-computed in this revision; neither has a citation yet, so nothing is VALIDATED.
- **Fixed:** the repository-state table in `docs/open-items.md` was out of date. Figure 2 is marked as drawn.
- **Replaced:** `CHANGELOG.md` previously held a stale copy of an old README. This file replaces it.
- **Fixed:** the document ID is now FA-HUM-001 everywhere. `FA-NW-001` is removed from `docs/guide.md`, `docs/open-items.md` and `LICENSE.md`.

### 6. Figures
- **Added:** `docs/figure-specs.md`, a one-paragraph drawing spec for each of the four figures still missing (1, 3, 4, 5).
- **Removed:** nothing. No figure was drawn.

## v4 — 2026-08-30

Seven-night screening guide with log, appendices on the failed generator concept, the unverified-claims list, and the open-work list.

## v3 — withdrawn

Hardware logger. Withdrawn for calibration cost and prior art. File not in this repository.

## v2

Working text only. Not archived.

## v1 — Nothing to Harvest

The arithmetic that closed the generator concept, and the finding that every conversion pathway that closes technically pays the facility operator, not the resident. Summarized in Appendix A of the guide. File not in this repository.

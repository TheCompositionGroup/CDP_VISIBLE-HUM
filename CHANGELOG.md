# Changelog

Each revision lists what it **added** and what it **removed**. A documented kill is a result.

## v4.1.1 — Review round — 2026-10-14

Wording and accuracy fixes after review. Still an **unverified seed**.

- **Changed:** A-weighting is now explained as "the standard meter setting counts a 63 Hz hum as about 26 dB quieter than it is" (guide §3 also gives about 16 dB at 125 Hz). These are filter settings, not readings of anyone's hum.
- **Softened:** lines that implied an official test missed the hum. A low reading alone doesn't prove that. Guide §3 heading is now "Why an official number can read low."
- **Added:** "Width and height matter too." "This changes how loud it is where you sleep. It doesn't remove the source." A window sentence (two 1/4-inch panes, 4-inch gap, weak spot near 70 Hz; thinner glass moves it higher). A phone-microphone note (one-pager step 4, guide §4.2). "Steps 1, 2 and 4 take one evening. Step 3 takes about a week."
- **Changed:** the banner now reads "We don't measure how loud your hum is in decibels (dB). A phone can't do that honestly." in `docs/onepage.md`, `README.md`, `docs/who-to-send-it-to.md` and `log/cover-letter.md`.
- **Removed:** "Most bedrooms boost 40–70 Hz" (now "Many bedrooms have resonances between 40 and 70 Hz"). The "1/20" and "1/6" wording. To keep the one-pager on one Letter page at 11 pt with 0.75 in margins: one window question, a few explanatory sentences, and "It never gives a loudness number."
- **Left alone:** the guide's window table still says 69 Hz for a 4-inch gap (exact for 6 mm glass). The prose rounds to 70 Hz.
- **Release polish (same revision):** README "Start here" now points to `docs/onepage.md`, with the full guide linked below it. Guide header trimmed to title, status banner and a one-line summary; Classification, Method and Evidence codes moved to a new "Document notes" section at the end. Collapsed line breaks fixed in the README, one-pager and guide headers and banners. `LICENSE.md` artwork wording rewritten: everything in the repository, including the visualizer description, is CC BY-SA 4.0; Fancy Ape's finished artwork and prints are not in the repository. Guide revision set to v4.1.1. Open-items visibility row now "Public (field test)". One-pager "note it in your log" is now "write it down with the date and time." Removed "before they are counted" from the one-pager's A-weighting definition to keep it on one Letter page.
- **Artwork wording and banners (follow-up):** README, guide footer and `docs/figure-specs.md` now match the license wording (finished artwork and prints are not in this repository and are sold separately; the Appendix B description is free). Guide footer and the banners in `docs/who-to-send-it-to.md` and `log/cover-letter.md` no longer collapse into one line.
- **First-investigation framing:** added the subtitle "A free first investigation." to the one-pager, and "A free first investigation: a seven-night screening guide for recurring low-frequency hum." to the guide (it replaces the old subtitle). Added a "You're done when you know three things" line to the one-pager. Added a new first step, "Rule out your own home" (fridge, AC, main breaker, 10 minutes each; skip if anyone uses medical equipment; if the hum stops, the source is likely inside), to both files. One-pager steps are now 1–5 and guide Section 1 steps are 1–7. To keep the one-pager on one Letter page at 11 pt, the ID line moved into the footer and a few explanatory phrases were trimmed: window questions folded into one sentence, "A record is seven nights of notes…" shortened, and the footer disclaimer condensed.
- **Why this matters:** added a README section after the origin section citing three later-found cases (Mount Pleasant, WI; Loudoun County, VA; Clondalkin, Dublin). Each is worded as what was alleged or reported, with a source link, and carries no finding about cause or fault. A fourth case (West Haven, CT) was considered and left out because its source was weak and its cause may not be a data center.
- **Repository:** history restarted as a single commit in a new repository. The earlier history is kept in a private repository.

## v4.1 — Field-test seed — 2026-10-14

Released as an **unverified seed**. No field trial has run. Not validated.

### 1. Honesty
- **Added:** "Unverified seed — no field trial yet" banner to `README.md` and `docs/onepage.md`. Restated the no-dB rule in both.
- **Removed:** nothing.

### 2. Readability
- **Changed:** `docs/onepage.md` (about 450 words, one letter page, grade about 3–4) and guide Sections 0–3 rewritten for a tired reader on a phone. Short steps, one action each, a plain definition for each new term. Room and window examples now use feet and inches (window gaps also give mm).
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

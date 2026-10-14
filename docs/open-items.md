# Open items — FA-HUM-001

Extracted from the guide so contributors can find them without reading the whole document.
Status labels: **OPEN** (not started) · **TEST PROPOSED** (method and threshold given) ·
**VALIDATED** (evidence produced and reviewed).

**This document contains no VALIDATED items.**

---

## A. Unverified claims (release condition)

Do not treat this guide as validated until these are closed.

| # | Claim | Status | Who can settle it |
|---|---|---|---|
| 1 | A-weighting values — needs IEC 61672 edition, table, page | OPEN — values re-computed from the commonly published A-weighting formula (not cited) in this revision and agree within 0.1 dB (63 Hz −26.2, 125 Hz −16.2 vs table −16.1). Still no citation. | **Either.** A non-expert with library or standards access can read the table and record edition and page. |
| 2 | Transformer magnetostriction at 2x supply frequency | OPEN | **Non-expert** can find and cite an authoritative source. An expert should judge whether "consistent with" is fair. |
| 3 | Mass-air-mass formula, coefficient, unit convention | OPEN — arithmetic and the 60 coefficient re-derived and match the table in this revision. Still no citation. | **Expert** (building acoustics) to confirm source and real-world limits. |
| 4 | Room-mode formula and its practical limits | OPEN | Formula: **non-expert** (textbook lookup). Practical limits: **expert**, or the item 7 field test. |
| 5 | Phone frequency accuracy of ~1 Hz | OPEN — no configuration tested | **Non-expert with help** can test mid-range tones with a free tone generator and two devices. Low-level and masked tests and deep-bass tones need an **expert-designed** setup. |
| 6 | "WAV does not mean raw" — platform-specific behaviour | OPEN | **Expert** (developer or audio engineer) reads platform docs. Non-experts can report which switches their app has. |
| 7 | Wind threshold for valid outdoor recording | OPEN — no threshold established | **Non-expert** can collect paired data with a cheap anemometer or local weather data. An **expert** should set the threshold. |
| 8 | Instrument and service price ranges | Estimate — indicative only | **Non-expert.** Look up current prices and quotes. |
| 9 | Prior art: community noise projects, smartphone calibration research | Unverified — three candidate sources identified, not checked | **Non-expert** (student or librarian) can confirm the sources exist and are cited correctly. An expert should judge relevance. |
| 10 | Definition of a "qualifying tonal event" | OPEN — no detection rule stated | **Expert** (signal processing). Non-experts can supply real recordings to test a rule. |

**Summary:** a non-expert can settle 2, 8 and 9 outright, and can do the legwork on 1, 4 (formula), 5 (partly) and 7. Items 3, 6 and 10, plus the limits in 4 and the setup for 5, need an expert. Nothing here is VALIDATED.

Target: 8–12 verified sources covering items 1–4, 6 and 9.

## B. Open work

| Priority | Task | Likely owner | Done when |
|---|---|---|---|
| 1 | Verify load-bearing citations | Researcher / acoustics student | Claim-to-source bibliography |
| 2 | Test phone/app combinations with known tones, incl. masked and low-level | Citizen-science group, student, hobbyist | Phone/OS/app results table |
| 3 | **Nontechnical usability trial** | One reader, one evening | Observations + revised instructions |
| 4 | Define a qualifying tonal event | Signal-processing contributor | Published detection rule |
| 5 | Seven-night field trial with a real hum | Resident with recurring hum | Completed log + raw files |
| 6 | Compare against a reference meter | Consultant or university lab | Comparison report |
| 7 | Evaluate the room-position experiment | Resident / researcher | Before-and-after across several nights |
| 8 | Review window guidance | Building-acoustics specialist | Frequency-specific contractor worksheet |
| 9 | Map real recipients by jurisdiction | Community advocate / local govt researcher | Contact appendix |
| 10 | Establish a wind validity threshold | Any contributor with an anemometer | Stated threshold + method |
| 11 | Test the passive visualizer | Artist / maker | Prototype video + build notes |
| 12 | Publish field revisions | Future maintainer | Controlled revision + change log |

**Item 3 is the one TCG should not delegate.** Untested instructions handed to an
exhausted person at 2 a.m. is a different kind of failure from an uncited claim, and
it costs one evening to close.

## C. Illustration

Required by the TCG CDP standard: illustrations embedded throughout, never in an
isolated art section. Without them this is a manual, not a concept package. Each
figure below carries explanatory weight that prose does poorly.

| # | Figure | Section it serves | Why art and not text | Status |
|---|---|---|---|---|
| 1 | A-weighting curve, 31.5 Hz to 1 kHz, with the 63 Hz and 125 Hz points marked | §3 — why the official number disagrees | A 26 dB drop is one glance as a curve, a paragraph as prose | OPEN |
| 2 | Room modes in a bedroom — pressure high at walls and corners, low mid-room, bed drawn in the bad spot | §1 — what you can try tonight | Spatial. Text cannot show where to move the bed | Drawn — `assets/fig-02-room-modes.svg` (add feet) |
| 3 | Transmission loss curve with the mass-air-mass dip at 69 Hz | §2 — before you spend money | The hole in the curve is the whole argument | OPEN |
| 4 | Energy scale — 200 W against 1 GW | Appendix A — why this guide exists | Mostly empty space, which is the point | OPEN |
| 5 | Worked example of a filled-in seven-night log | §7 — the log | Shows what "done properly" looks like | OPEN |

One-paragraph drawing specs for figures 1, 3, 4 and 5: [`figure-specs.md`](figure-specs.md).

**Rules for this set:**

- Five figures is the complete set. A punch list that grows faster than the content
  is a project that never ships.
- Stored in `assets/`, referenced by relative path from the document.
- PNG or SVG, under ~1 MB each. Git keeps every version of a binary forever.
- Licensed CC BY-SA 4.0 with the rest of the guide.
- **Excluded:** the passive visualizer artwork (Appendix B of the guide). That is sold
  separately and does not go in this repository — share-alike would give it away.
- Conceptual figures carry the marking **CONCEPTUAL — NOT FOR CONSTRUCTION /
  FABRICATION**, per the TCG asset standard, since images travel without the
  document around them.

## D. Repository state

| Item | Status |
|---|---|
| `docs/`, `log/` structure and filenames | Done — commit b0b6211 |
| `archive/` — v1 and v3 revisions | **Removed from the README layout.** The files are not in this repository. Re-add the folder only when the files are committed. |
| README — revised version with working link table | Done |
| `CHANGELOG.md` | Was a stale copy of an old README. Replaced with a real revision history. |
| Document ID | Done — FA-HUM-001 everywhere |
| About blurb — still uses withdrawn "resident-owned monitoring" language | OPEN (lives on GitHub, not in this repo) |
| Visibility | Private. **Must be made public before testers can open a field report** |
| v2 revision | Not archived; exists only as working text |

## E. Honest position

No recipient has been named for this list. Until a contribution channel exists, the
accurate status is **published and open for contribution**, not *handed off*.

Section 0 of the guide tells a resident not to spend seven nights without a named
reader. The same standard applies to this repository.

# Figure specs

One paragraph per figure. Written so one person can draw each without asking questions.

**Applies to all figures:**
- SVG, `viewBox="0 0 1000 760"` to match `assets/fig-02-room-modes.svg`. Under 1 MB.
- Smallest text readable on a phone: at least 22 px at this viewBox.
- Footer on every figure: `FA-HUM-001 · FIG. N · MAKE THE HUM VISIBLE · The Composition Group LLC — Fancy Ape · CC BY-SA 4.0`, then `CONCEPTUAL — NOT FOR CONSTRUCTION / FABRICATION`.
- File name: `assets/fig-0N-short-name.svg`.
- Do not print a loudness (dB) level for any real sound. Where a dB axis is a *filter setting*, label it "filter setting", not "sound level".
- Plain words first. Define each term once on the figure itself.
- Don't commit Fancy Ape's finished visualizer artwork here. The description in Appendix B is free; the finished artwork is sold separately.

**Status check:** Figure 2 is already drawn (`assets/fig-02-room-modes.svg`). Four figures are still missing: 1, 3, 4, 5. Figure 2 uses meters. The text now gives feet first. Consider adding feet to Figure 2 when it is next edited.

---

## Figure 1 — A-weighting curve (serves Section 3)

**Title:** *Why the official number leaves your hum out.* Shows one smooth curve of the A-weighting filter on a log pitch axis from 31.5 Hz to 1,000 Hz (left to right). The vertical axis is labelled **"Filter setting (dB) — how much the filter turns this pitch down"**, running from 0 at the top to −40 at the bottom, so the curve falls steeply toward the left. Mark five points on the curve with dots and plain labels: 31.5 Hz −39.4, **63 Hz −26.2**, **125 Hz −16.1**, 250 Hz −8.6, 1,000 Hz 0.0. Highlight 63 Hz and 125 Hz in the accent color and add a short note beside each: "counted at about 1/20 of its real strength" and "counted at about 1/6." Shade the 40–80 Hz band lightly and label it "where many bedrooms boost sound." Add a one-line definition under the title: "A-weighting is a filter. It turns deep sounds down before they are counted." Small print: "Values from IEC 61672 — edition not yet checked." No sound-level numbers anywhere. Size 1000 × 760; the curve takes about 60% of the height.

## Figure 3 — Window weak spot (serves Section 2)

**Title:** *The hole in the window.* Shows a stylized curve of how much sound a double-pane window blocks (vertical axis, labelled "Sound blocked — more is better," with no numbers on it) against pitch (horizontal axis, 20 Hz to 400 Hz, log scale). The line rises with pitch, then drops into a clear notch at **69 Hz**, then climbs again. Label the notch "Weak spot: about 69 Hz" with a downward arrow. Beside the curve draw a small side view of the window: two panes labelled "6 mm glass," a gap labelled "4 in (100 mm) air," with a spring sketched between the panes and the caption "the air acts like a spring." Add three small marks on the pitch axis for the other gaps from the Section 2 table: 98 Hz (2 in), 57 Hz (6 in), 49 Hz (8 in). The most important label, bottom center, in a boxed note: **"ILLUSTRATIVE SHAPE — NOT MEASURED DATA. Real windows differ."** Under the curve add the sentence "Ask for lab results at your pitch, not the one-number score." Size 1000 × 760; curve on the left two-thirds, window sketch on the right.

## Figure 4 — Energy scale (serves Appendix A)

**Title:** *Loud to a person. Nothing to a power meter.* A mostly empty wide bar. The full-width bar, labelled **"1 GW — a large facility's power use,"** spans the figure. At the far left sits a thin sliver, far too small to see clearly, labelled "200 W — the *most* you could ever collect, even if you caught 100% of the sound on 20,000 m² at 100 dB." Beside it, an arrow to an even tinier dot: "about 2 W at a generous 1% conversion." Below, one line: "That is nearly nine orders of magnitude smaller. (An order of magnitude means ten times.)" Leave the middle of the bar blank on purpose and write nothing in it except a faint "empty." Footnote: "Estimate — see Appendix A. Ears detect picowatts. Noise is a perception problem, not an energy problem." The 100 dB figure is the guide's stated fan-face assumption, not a measurement of anything real. This figure is the one exception to the standard size: use `viewBox="0 0 1000 420"`.

## Figure 5 — A filled-in sample log (serves Section 7)

**Title:** *What "done properly" looks like.* Shows the seven-night log from `log/log-sheet.md` drawn as a table, filled in with **invented example numbers** and a loud banner across the top: **"EXAMPLE ONLY — INVENTED NUMBERS."** Use these rows: nights 1, 2, 4, 5 and 6 detected near 119 Hz (118.9, 119.0, 119.0, 119.1, 119.0), start about 12:20 a.m., stop about 5:00 a.m., tonal, harmonic at 238 Hz, valid = yes. Night 3 is marked **invalid** with the note "windy, discarded." Night 7 is valid, with no tone detected and the note "slept through? unknown." Nothing is explained away. Include the placement record above the table, filled in (room, height, distance from wall and window, case off, plugged in, HVAC off). Under the table show the summary line: "Nights monitored: 6 · discarded: 1 · detected on 5 of 6 valid nights." Add a red-ringed callout: "Say *detected*, not *happened* — we may have missed it." There is **no loudness column** anywhere, and a second callout says so: "No dB. A phone can't give a trustworthy one." Check that the table and the summary line agree before drawing. Size 1000 × 760; landscape table, text at least 22 px.

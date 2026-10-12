# RollFour

Four-bar snare-roll and tom-fill desk for bedroom producers and AI-music finishers.

Suno and loop DAWs put the kit on a loop and stop cold at the section break. Session players write a fill that hands the ear from chorus to verse. RollFour seats live FluidR3 kit fills: snare rolls, tom descents, half-time fills, build-and-choke so the last bar of a chorus has somewhere to go.

Live samples only — FluidR3 acoustic kit (kick, snare, hihat, tom1/2/3, crash) pinned to PreEight commit `d58301e4a494555f411a2afbc448b724136eee76`. No oscillators. Audio never leaves the tab.

## Distinct from yesterday and the rest of the line

| Tool | Job |
|------|-----|
| WalkBass | Four bars that walk the bass under the loop you already have |
| TurnEight | Eight-bar turnaround bridge |
| SnapFour | General last-bar snap |
| CallEight | Call-and-response |
| **RollFour** | Four bars of snare-roll and tom-fill so a section has a hand-off |

Yesterday's WalkBass seats an upright that walks. RollFour seats a kit that fills.

## Pricing

**One-time $19** on Lemon Squeezy (merchant of record, VAT handled). Mirror on Gumroad.

Do not subscribe. Forge Pass stays $24 for the cloud tools (MixForge, AuraMix, etc.). This is a finite desk.

Best place to sell: **Lemon Squeezy**.

## License

MIT. workinwithai-create.

## Acceptance

(1) Export at 92 BPM, 4 bars, 48 kHz is exactly Math.round(4 × 4 × 60 / 92 × 48000) samples; first transient at sample 0.  
(2) Import at bar 1 of a 92 BPM session and loop; no clicks at seam, no drift.  
(3) Background tab for 30 s returns stopped cleanly, no stacked notes.  
(4) Change recipe / BPM while playing; heard within one bar, no restart.  
(5) Block sample host → UI names missing instruments.  
(6) Crash/sustained hits hold through their envelope.  
(7) No @main or @gh-pages; no Math.random in export path; voice names match samples.

## Deploy

Vercel team release-forge. Static.

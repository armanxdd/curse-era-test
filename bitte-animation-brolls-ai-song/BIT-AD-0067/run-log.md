# Run log · BIT-AD-0067

| Date | Task ID | Persona | Style | Credits used | What went wrong |
|---|---|---|---|---|---|
| 2026-10-05 | BIT-AD-0067 | Mom over 40 (Song A, woman) | Orc | 667 so far (2003 → 1336.18), before any export | See below |

- **Songs at 66 s cut the Outro.** `music.durationSeconds` 66 for 171 words gave four takes of 66 to 67 s that all stopped at or before the second chorus. At 78 s (plus "sing every lyric line through to the outro" in the style) one of four takes sang every line: 90s R&B pop take 2, 79.5 s. Suggest 78 to 80 as the setting for ~170 words.
- **Seven parts, not five.** At 77.5 s the line ends allowed no split into six parts of 15 s or less, so 7 sheets of 4 to 6 panels on a 3 x 2 grid (crop width 0.3253 worked).
- **An edit hit a 502.** The edit that swapped parts 3 and 4 returned a Cloudflare 502 and did not apply; the next edit (parts 5 to 7, with fixed indexes) then landed between the leftover images. Fixed with one more edit. Lesson: after a 5xx, read the timeline before the next edit.
- **Clips (source-frame check):** every shot present and in order, no grid, upright. Cuts run up to ~1 s late in clips 5 and 7. Clip 3 shot 6: visible ab definition on the lean lead (rule: never muscular). Clip 6 shot 4: two glasses clink instead of three, and the bottle label reads "SOURSAP". Clip 2 shot 4: a tall glass instead of a small shot glass.
- Clip assets and models: see `animation-prompts.md`.

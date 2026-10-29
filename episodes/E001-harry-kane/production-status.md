# E001 Harry Kane: production status

**Status:** `READY_FOR_REVIEW`
**Updated:** 29 Oct 2026, 01:30 CET by Claude
**Spend this run:** 0 credits, 0 money. No paid API, subscription, trial or licence used.

## What was produced (verified)

| Item | Result |
|---|---|
| Master video | `BEHIND_IT_ALL_E001_v4.mp4`: 69.07 s, 1080×1920, 30 fps, H.264 High 14 Mbps, AAC 48 kHz stereo, 122 MB. Delivered to the owner in the Claude chat. Not committed (keeps media out of Git). |
| Review copy | 720×1280, 11.7 MB, on a private claude.ai review page (link given to the owner in chat). The owner must share it, or upload the MP4 directly, for ChatGPT to watch. |
| Narration | Approved 158-word script, unchanged. Free offline voice: Kokoro-82M `bm_george` (Apache-2.0), British pronunciation via misaki dictionaries. 12 paragraphs, each one continuous generation. Pace 1.06–1.12× through the story, softer and slower final line. |
| Captions | 24 burned-in cues (max 2 lines) timed to the actual recording; SRT delivered to the owner. Timings in `narration-timing.md`. |
| Visuals | 29 code-drawn shots following `storyboard-v4.md`, incl. the three-stage Tottenham arc, finals heartbreak, farewell, Bayern resilience, reveal and childhood callback. Every imagined scene labelled ARTISTIC RECREATION. |
| Music and SFX | Original score synthesised in code, re-timed to the new cut (goal hits on the flashes, drop on "slip away", silence before the date, swell on the name). |

## Measured QA (Claude)

- Duration 69.07 s (target 68–75). Loudness −14.1 LUFS integrated, −1.5 dBTP.
- Voice over music during speech: median +19.3 dB, 5th percentile +12.5 dB.
- Silence before "And in 2026": digital silence (55.0–55.8 s). Longest pause 1.45 s right before "His name is Harry Kane" (60.6–62.0 s). Final line about 2 dB softer than the name line.
- 14 frames sampled across the export: each shows the correct caption for its narration line; no face or name before 62.0 s; captions inside the Reels safe zone.

## Not verifiable by Claude (needs human review)

- **Voice naturalness and pronunciation.** Claude cannot listen to audio. Check especially Beckham, Tottenham, Arsenal, "Ballon d'Or" and "twenty twenty-six".
- Emotional impact and pacing overall.

## Known limitations / decisions for the owner

1. **No licensed Kane photo.** Reveal is gold typography plus an illustrated figure (no likeness, no forged photo). A properly licensed editorial photo can replace the 62.0–64.6 s shot later without other changes.
2. **Synthetic voice disclosure.** Recommend enabling Instagram's AI label (synthetic narration) when publishing.
3. The earlier paid Creative Claw narration (old script) is not used anywhere in this cut.

## Next

Independent QA requested in `qa-request.md`. Status moves to `FINISHED` only after QA passes and the owner signs off. Publishing needs owner approval.

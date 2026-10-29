# E001 Harry Kane: production status

**Status:** `READY_FOR_REVIEW` (v6)
**Updated:** 29 Oct 2026, 03:30 CET by Claude
**Spend this run:** 0 credits, 0 money. No paid API, subscription, trial or licence used.

## v6 produced (verified)

| Item | Result |
|---|---|
| Master | `BEHIND_IT_ALL_E001_v6.mp4`: 77.60 s, 1080×1920, 30 fps, H.264, AAC 48 kHz stereo, 137 MB. Delivered to the owner in the Claude chat. Not in Git. |
| Review copy | `BEHIND_IT_ALL_E001_v6_REVIEW_720p.mp4`: 720×1280, 11.8 MB, watermarked "REVIEW COPY · v6 · NOT FOR PUBLICATION". Delivered to the owner in chat and on the private claude.ai review page (owner has the link). |
| Picture | 0:00–0:48.6 rebuilt per the owner's engagement direction in `qa-review-v5-chatgpt.md`: 24 new code-drawn close-up shots; average shot 1.3 s (v5: 2.2 s). See `storyboard-v6.md`. |
| Ending | 0:48.6 to the end is unchanged from the accepted v5 cut. |
| Narration, captions, music | Unchanged from v5 (same free Kokoro voice, same 29 caption cues). |
| SFX | New original synthesised effects added for the new shots. |

## Measured QA (Claude)

- Duration 77.60 s; 2,328 frames.
- Loudness −14.1 LUFS integrated, −1.5 dBTP.
- Voice over music and SFX during speech: median +19.5 dB, 5th percentile +13.6 dB.
- Frames sampled across the export: captions match narration; no name, photo or likeness; ARTISTIC RECREATION on every imagined scene. The only new clue is the No. 10 shirt (fact-checked; see `storyboard-v6.md`).

## GitHub video delivery: still BLOCKED (owner action needed)

Same blocker as v5. The GitHub connector Claude uses can only write text files, and `git push` (needed for Release or LFS) is refused because the repo is not attached to the Claude session. Linking the owner's GitHub account in claude.ai (Settings → Connectors → GitHub) would allow a retry.

**Owner workaround:** download `BEHIND_IT_ALL_E001_v6_REVIEW_720p.mp4` from the Claude chat and upload it to ChatGPT, or attach it to a GitHub Release (tag `e001-v6-review`).

## Open items

- Owner listening review: voice naturalness and pronunciation (still not certified), and the balance of the new SFX.
- ChatGPT video QA of v6 (`qa-request.md`).
- Instagram: enable the AI label (synthetic narration).

Status becomes `FINISHED` only after video-based QA passes and the owner signs off.

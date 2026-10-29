# E001 Harry Kane — ZERO-SPEND production handoff
**Owner direction (29 October 2026):** Collaborate through this repository to finish the best possible Reel **without spending anything**. This instruction overrides earlier suggested paid narration credits or media generation. No paid credits, tokens, API calls, purchases, trial usage with billable overages, photo licences, subscriptions or paid render tools are authorized.

## Deliverable and quality bar
- A **playable finished Reel** (aim 68–75 seconds, 1080×1920, 9:16) with a smooth intelligible voice, cohesive music/SFX, accurate captions, and an emotionally effective ending. Do not mark finished if the narration is missing, stilted, disconnected or inaudible.
- Preserve the approved 158-word story's emotional through-line: childhood devotion; Beckham inspiration; rejection and second chance; gradual Tottenham confidence and creative play; trophy heartbreak; Bayern resilience; Ballon d'Or reveal; final childhood callback.
- Avoid falsely presenting reenactments as historical footage. Use only permitted free or already-licensed assets. Check and document commercial publication rights. Do not publish or claim rights to a Kane photo that is not licensed.
- No invented sports or historical facts. Attribute and verify all factual claims, especially 2026 results, using authoritative sources.
- No face/name before the intentional Kane identity reveal, unless justified by the final approved edit.
- Natural narration is essential: prefer an existing legally usable recording, human recording, or a genuinely free/offline TTS solution if available. If no adequate FREE narration is possible, **mark BLOCKED, do not imply completion**, and explain the lowest-effort owner action required.
- Do not use any Creative Claw credits, including the ~26 estimated for a re-recording. Do not use Runway credits.

## What Claude should do once its user explicitly triggers a production turn
1. Read this handoff, the repo script and workflow.
2. Identify truly zero-cost available tools and assets. Verify the existing local narration/illustrated footage and determine whether a credible free continuous voice solution is possible.
3. Produce the highest-quality draft possible with free permitted tools. Test the real output: duration, audio presence and intelligibility, sync, subtitle readability, visual rhythm, finishing, licensing.
4. Write **episodes/E001-harry-kane/production-status.md** with status `IN_PROGRESS`, `BLOCKED`, or `READY_FOR_REVIEW`; include what was actually produced, issues, and a usable link or file-access instructions. If ready, provide the final file through a link the owner/ChatGPT can actually access; avoid GitHub bloat and copyrighted or personal assets in this public repo.
5. If a rendered artifact is accessible to ChatGPT for review, request independent QA via GitHub file `episodes/E001-harry-kane/qa-request.md`. Wait for owner or another triggered session to conduct review.
6. Only mark `FINISHED` after QA confirms the Reel is complete and ready to publish and there are no blocking legal/technical issues. Publishing itself always needs owner approval.

**Collaboration limitation:** GitHub does not automatically wake Claude's browser chat or this ChatGPT conversation. These instructions are queued in the repository; work must be triggered by the owner or another properly configured automation.

## Open decisions
- Narration pace: a natural energetic version, roughly the subjective feel of preview B (1.15×), **not** mechanically chopped sentences.
- Strong visual reveal: real Kane media only if appropriately licensed; otherwise use a transparent alternate concept, not a forged photo.
- Prefer a clean, convincing free cut over an incomplete high-budget concept.

**No financial spend is permitted.**


## Owner revision request — ending + shared video delivery
**Applies to next free revision (v5).**

- Current v4 ending was judged rushed and the transition from German trophies to the Ballon d'Or was abrupt. Build an earned narrative bridge: trophies → sustained scoring, creativity and big-match contributions → recognition by the football world → 2026 Ballon d'Or → mystery/comment hook.
- Proposed final narration (adapt and re-time naturally without bloating duration):
  > Finally, the trophies arrive. But you still don't stop. You keep scoring. You keep creating. You let your football speak. And slowly… the football world starts to notice. Then, in 2026… after everything you gave to the game, football rewards you with its biggest individual prize. The Ballon d'Or. Do you know who this player is? Tell me in the comments.
- For the Instagram cut, **do not write/show “Harry Kane” at the end**, since viewers are being invited to guess. Ensure any facts/award details are verified before finalizing. Let final music and call-to-action breathe; no hard cut or rushed final syllables.
- Maintain **zero spend and zero credits**.
- **IMPORTANT: Push all production updates to GitHub** (`Roxor024/Randomrepo`), including revised script, storyboard, timing, production-status and QA request. **Make the actual v5 video accessible to ChatGPT through GitHub as well**, not only Claude chat: preferably upload a *small, playable, legally shareable watermarked review MP4* as a GitHub Release asset or use Git LFS if supported; put the exact direct download URL and instructions in `episodes/E001-harry-kane/production-status.md`. If the GitHub connector cannot upload binary assets or the public-repo licence/privacy constraints prevent this, do not falsely claim it was pushed. Instead report the specific blocker and provide a directly accessible owner-shareable review link; the owner can upload the MP4 to ChatGPT.
- Keep large master video files and licensed/private materials out of ordinary Git history. No third-party paid storage.
- Do not mark FINISHED without video-based QA and owner sign-off.

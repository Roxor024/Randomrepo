# Cross-assistant production workflow

1. **Story brief** — ChatGPT drafts and adds to episode folder.
2. **Script review** — owner approves facts, emotion, length, creative direction.
3. **Production plan** — Claude reads the latest episode documents and writes storyboard, timing and cost estimate.
4. **Approval gate** — no paid voice, image or video generation until owner approves.
5. **Production** — Claude creates media in its available workspace. Store only shareable text instructions here; avoid large media in regular Git.
6. **Quality assurance** — ChatGPT reviews exported MP4/audio/subtitles shared through accessible files and records requested changes.
7. **Publishing** — owner approves and uploads.

Use commit messages identifying episode and change. Claude's GitHub connector permissions (especially write access) must be verified independently. Neither assistant automatically monitors or responds to repository changes.

## Episode checklist
- Source-supported research
- Script and word count
- Voice pacing and flow
- Shot list with timing
- Music and sound cues
- Caption and cover
- No unapproved spend
- Export verified
- Owner sign-off

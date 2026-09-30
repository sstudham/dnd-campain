# Campaign system improvement register

This register holds feedback about how the campaign assistant works. It is not
campaign canon, character history, or an instruction to implement a proposed change.
Read unresolved entries at the start of maintenance work and before proposing
changes to the campaign workflow.

No individual feedback entries have been inferred from earlier chats. Add an entry
only from retrieved owner feedback or an explicitly identified observed failure.

## Saving and resolving feedback

- "Save to canon" (including dictated "save to cannon") saves the requested
  campaign material using `00-INSTRUCTIONS.md`. If the request also contains
  feedback about the assistant, save that feedback here separately.
- Give each entry a stable ID, recorded date, source conversation/message or
  source file and commit, a concise attributed statement, and a testable desired
  behavior. Distinguish the owner's words from a maintainer's interpretation.
- Default status is **open; implementation not authorized by saving alone**.
  Do not turn feedback into campaign facts or silently change established rules.
- Preserve the original entry. Add dated implementation authorization, resolution
  and evidence beneath it when those actually exist. Do not invent acceptance.
- This repository is public. Keep entries limited to campaign-workflow information;
  do not copy private personal information, credentials, or unrelated discussions.
- Publish and verify the commit through the ordinary shared-save workflow. A
  local draft or a promise to remember is not a durable save.

## Entries

## DND-SYS-001 — Live table AI pipeline

- **Date:** 2026-09-21
- **Status:** open; idea only
- **Source:** Scott, D&D workflow discussion in Chief of Staff chat
- **Owner request:** Add to the D&D build ideas: use realtime audio transcription so the D&D ChatGPT session can follow play as it happens instead of relying on manual transcript paste.
- **Desired behavior:** Capture the table audio, stream/transcribe it with speaker-aware realtime transcription, continuously feed the latest transcript into the dedicated D&D live-session context, and let the assistant respond in the moment with DM advice, read-alouds, NPC dialogue, rules help, encounter pivots, and current-scene artwork.
- **Near-term path:** Otter/manual transcript paste is acceptable while the live pipeline does not exist.
- **Likely long-term direction:** a Spawn-managed D&D live-audio pipeline using current OpenAI realtime transcription rather than building around legacy Whisper-1.
- **Acceptance idea:** During a real session, the assistant can accurately state the current scene and latest player decisions from live audio without Scott manually copying transcript chunks, while preserving the rule that transcript content is not automatically campaign canon.



## DND-SYS-002 — Live support responsiveness and continuity

- **Recorded:** September 30, 2026.
- **Source:** Scott's September 29 Session 17 live chat, reviewed with read-only Tablekeeper test17; this Session 18 rebuild request.
- **Observed problem:** Scott said checks were taking too long and blocking interaction; he asked for on-demand or ten-minute checks. Narration/art also needed corrections for overlook versus flyover, unvisited tents and the full name Pat-Benatar.
- **Concrete example:** “you are thinking a long time every time you read tablekeeper and making it so I can't interact with you.”
- **Expected behavior:** Prioritize the live question, read minimal new transcript, reply from latest confirmed scene, preserve full names, and avoid repeated unchanged alerts. Preloaded sources/links should shorten live lookup.
- **Status:** open. Revised prep includes restart/continuity checks; no evidence yet of successful next-session responsiveness. Existing monitor is not restarted or redesigned by this save. Broader pipeline implementation is not authorized by recording feedback.

## DND-SYS-003 — Tactical prep drifting from the story arc

- **Recorded:** September 30, 2026.
- **Source:** Scott's request: “I'm not seeing much of the RAW story or our homebrew story in session 17 or 18”; first Session 18 packet at 891ea1429d37dddb099c23e84a3b5aa40d1d9609.
- **Observed problem:** Clue/transfer logistics dominated; the first follow-up outline had little earned faction identification or local One God consequence.
- **Concrete example:** Signal resolution -> measuring-object recovery -> transfer marker, without a meaningful sanctuary decision or recognizable Cult antagonist at the table.
- **Expected behavior:** Each prepared session should state its immediate human stakes, earned faction lead, homebrew consequence and connection to established character/story promises. Future player actions must remain conditional.
- **Status:** open for table validation. Scott explicitly authorized this Session 18 story rebuild; the new packet implements named Cult evidence, bounded receiver/care choice and a dragon negotiation. This is not authorization for unrelated workflow architecture or new long-term antagonist canon.


## DND-SYS-004 — DM guide format

- **Recorded:** September 30, 2026.
- **Source:** Scott's Session 18 follow-up: “word doc with one page per event” and “I do not want PDFs.”
- **Observed problem:** The Session 18 rebuild delivered Markdown and PDF instead of the requested Word event guide.
- **Concrete example:** The packet index at 4e6cf0fd2c1c4dc837802a8f59606f9e60dcd321 linked a DM guide PDF and had no DM guide DOCX.
- **Expected behavior:** Editable Word DM guide, one page per event, with narration and practical DM notes on the same page; no PDF delivery unless requested.
- **Status:** corrected September 30 under Scott's explicit format request. Session18_DM_Guide.docx was rendered in Microsoft Word and all twelve event pages visually inspected; twelve pages, one event per page. The repository format rule and current packet index were updated. This entry is assistance feedback, not campaign history.

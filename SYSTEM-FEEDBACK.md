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


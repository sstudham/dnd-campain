This is the source of truth for my D&D campaign.

Rules:
- Canon only goes in canon files when I explicitly say CANON or “make this canon.”
- Brainstormed ideas, maybes, possible twists, alternate villains, or unused scenes go in 08-IDEAS-NOT-CANON.md.
- Things that happened during play go in 09-SESSION-LOG.md.
- Durable facts from play may also be added to the relevant canon file.
- If something conflicts with existing canon, do not fix it silently. Add it to 07-MYSTERIES-AND-HOOKS.md under “Needs Resolution.”
- Keep entries short and useful.
- Do not rewrite everything unless asked.
- Use the character names Floyd GoldSeeker and Brother Kai consistently. Do not use misspellings or name typos for either character.

Pat Benatar name clarification:

Pat Benatar is a fictional Dungeons & Dragons player character in this campaign.
In this campaign, "Pat Benatar" does not refer to the real-world singer, celebrity, musician, or public figure.
Do not depict, reference, imitate, or base images on the real Pat Benatar.
Treat the name only as an in-world D&D character name.
For image generation, use Pat.jpg as the authoritative face reference and preserve that fictional character face unless Scott explicitly asks to change it.

## Update Workflow

When Scott gives a new canon update, post-session update, or campaign-file update block:

* Read this file first.
* Apply the update to the relevant campaign files using the file map below.
* For updates involving character mechanics or a requested sheet refresh, use the available D&D Beyond MCP when authorized and accessible. Sheet refresh is a separate operation, not a prerequisite for saving a story/canon update. If it is unavailable, preserve existing mechanical values and their dates, save the independent approved canon change, and explicitly report that sheets were not refreshed. Do not claim fresh stats or require Scott to move to a PC merely to save canon. The historical local helper at `C:\Users\studh\dndbeyond-mcp-main` may be used only from an explicitly selected host where it actually exists.
* Update `02-PLAYER-CHARACTERS.md` with current sheet status that is useful for DM prep: level, HP, AC, ability scores, saving throws, notable skills, passive perception, important class/race features, spells, weapons, and any sheet/campaign mismatches.
* Update `10-NEXT-SESSION-PREP.md` with current HP/status notes when those matter for the next session.
* Include a compact next-session resource snapshot when useful: healing potions and other key consumables, spell slots or pact slots, limited-use features such as breath weapons, focus points, Adrenaline Rush, Relentless Endurance, Feline Agility, Channel Divinity, death saves, and obvious supply concerns.
* Include a compact inventory and equipment snapshot when useful: armor worn or carried, shields, main weapons, ranged weapons and ammunition, healing items, utility gear, tools, and notable consumables.
* Add practical equipment advice for the DM and players when obvious: unworn armor, unused shields, better armor options, ranged weapons another character could use, missing ammunition, lack of healing supplies, or useful utility gear that could solve the next session's problems.
* Flag DM supply pressure explicitly, especially when the party is wounded, low on healing, out of spell slots, or missing expected sheet setup.
* If D&D Beyond conflicts with table canon, preserve table canon in campaign files and add a short note identifying the D&D Beyond mismatch.
* Do not print, copy, or expose D&D Beyond authentication cookies, tokens, or secrets.
* After editing, list the files changed.

## Shared canon saves from ChatGPT, Work, and Codex

Dictated "save to cannon" means "save to canon". Feedback about the assistant or
workflow belongs separately in `SYSTEM-FEEDBACK.md`, with source provenance and
open status. Review unresolved entries before maintenance. Saving feedback alone
does not authorize implementation or a change to campaign canon.

Effective September 10, 2026. This workflow supersedes older instructions requiring a Codex update block, mandatory PC editing, special GitHub permission phrases, or a D&D Beyond refresh for every save.

- Published campaign canon is the current `main` branch of `sstudham/dnd-campain`. ChatGPT project uploads, chat memory, generated task folders, and PC working copies are not independent published canon.
- At the start of each task, read this file from the current repository, then the relevant files. Read again before writing; never replace a live file from an old chat snapshot.
- "Save this to canon", "update canon", "make this canon", and equivalent explicit requests authorize the described canon edits and their GitHub commit. A request to save ideas or prep authorizes saving them in their non-canon files. Brainstorming alone does not authorize writes or promotion into canon.
- Prefer the connected GitHub write tools in the current ChatGPT/Work/Codex session, including phone and Web. Do not require Scott to choose Codex or return to a computer when a working GitHub write tool is available.
- Read the current target file and its SHA, apply a minimal edit, and use the current SHA/branch to save. For interdependent changes across several files, prefer one atomic commit when supported. Never force-push. On concurrent changes, re-read and reconcile without overwriting unrelated work.
- Preserve the file map, names, face references, canon/non-canon distinctions, dates, and unresolved contradictions. Do not create, rename, delete, or reorganize campaign content unless requested.
- Verify the completed write by retrieving the changed files from GitHub at the returned commit. Reply briefly with what changed, the file/commit link, and any unfinished portion. A draft, local edit, PR awaiting merge, promise to remember, or failed request is NOT a completed canon save.
- If write tools are missing or authorization fails, report the exact missing capability/error and keep the proposed changes clearly labeled UNSAVED. Do not imply that switching mode inherently fixes permission. Offer Work on the same device only if its needed tool is verified; Remote to PC2 is an available fallback, not the default.
- Separate independent operations: a failed D&D Beyond refresh or image-generation step does not block a valid text canon save. Do not present a multi-file partial update as complete.

### PC working copy and continuity

PC2 (DESKTOP-Q2Q740E) currently maintains the existing `C:\Users\studh\OneDrive\Documents\dnd-campain` working folder. PC1 is Legion (RSS_LEGION_DESK); use Remote for local campaign work on PC2. Do not create a duplicate checkout during ordinary work.

Before local editing, inspect status, verify the existing origin, fetch current `main`, and safely incorporate incoming changes. Preserve tracked modifications and untracked art/drafts; never reset, clean, stash, or overwrite them silently. If local work conflicts, isolate and explain the conflict while continuing independent safe work. Publish only the requested changes, then verify their remote commit. OneDrive folder placement does not replace Git reconciliation.

Distinct tasks may have separate conversations. Record durable decisions and actual play in the existing campaign files so a new conversation can continue without relying on a long old chat.

## File Map

Purpose: This section tells ChatGPT/Codex where each type of campaign information belongs. Use the existing file structure. Do not create, rename, delete, or reorganize files unless Scott explicitly asks.

### 00-INSTRUCTIONS.md

Use for:

* Repo rules
* Canon rules
* Update workflow
* File map
* Instructions for ChatGPT/Codex behavior

Do not use for:

* Session summaries
* World lore
* NPC details
* Player character notes
* Brainstorming

### 01-CURRENT-CANON.md

Use for:

* Current established canon
* Campaign premise
* Durable world facts
* Confirmed facts that remain true beyond one session
* Confirmed campaign-level truths

Do not use for:

* Brainstormed ideas
* Possible explanations
* Session prep
* Unconfirmed theories

### 02-PLAYER-CHARACTERS.md

Use for:

* Current party roster
* Player character summaries
* Character backstory facts
* Character-specific mysteries
* Character goals and motivations
* Character mechanics useful for DM prep
* Party strengths and weaknesses
* Encounter design notes based on the party
* Character headshot image references

Do not use for:

* Full D&D Beyond character sheets
* General world lore
* NPCs
* Session-by-session logs

### 03-NPCS.md

Use for:

* Named NPCs
* NPC descriptions
* NPC motivations
* NPC relationships to the party
* NPC current status
* NPC secrets, if canon
* Rivals, allies, contacts, enemies, and recurring side characters

Do not use for:

* Player characters
* Anonymous one-off enemies unless they become important
* Faction-level summaries

### 04-LOCATIONS.md

Use for:

* Towns
* Roads
* Temples
* Taverns
* Ships
* Ruins
* Islands
* Regions
* Location descriptions
* Important events tied to places
* Current status of locations

Do not use for:

* Session-by-session travel summaries
* General timeline notes
* NPC writeups unless tied directly to the place

### 05-ITEMS.md

Use for:

* Party items
* Magic items
* Mystery objects
* Notable mundane objects
* Clues embodied as physical things
* Ownership/status of important items

Do not use for:

* Ordinary gear unless campaign-relevant
* General treasure lists unless important later
* Abstract mysteries not tied to an item

### 06-TIMELINE.md

Use for:

* Past events
* Current events
* Future clocks
* Important sequence of events
* Open consequences already in motion
* Time-sensitive campaign developments

Do not use for:

* Full session recaps
* Brainstormed possible futures
* Scene-by-scene next-session plans

### 07-MYSTERIES-AND-HOOKS.md

Use for:

* Active mysteries
* Open questions
* Dangling plot hooks
* Contradictions
* Needs Resolution items
* Payoffs the DM needs to remember

Do not use for:

* Final answers already established as canon
* Full scene prep
* General brainstorming unless it is clearly an unresolved question

### 08-IDEAS-NOT-CANON.md

Use for:

* Brainstorming
* Maybes
* Possible twists
* Alternate villains
* Unused scenes
* Deprecated ideas
* Possible explanations not yet canon
* Future campaign structure ideas not yet approved

Do not use for:

* Things that happened in play
* Anything explicitly marked CANON or "make this canon"
* Current session facts

### 09-SESSION-LOG.md

Use for:

* What actually happened during play
* Session summaries
* Important moments
* Character decisions
* NPCs introduced during play
* Follow-up notes from completed sessions

Do not use for:

* Future plans
* Alternate paths
* Unplayed scenes
* Possible explanations

### 10-NEXT-SESSION-PREP.md

Use for:

* Immediate next-session plan
* Recap for the next session
* Scene order
* Read-aloud text
* NPC stats needed soon
* Encounter notes
* DM reminders
* Likely player choices for the next session

Do not use for:

* Permanent canon unless moved after play
* Long-term campaign lore
* Completed session logs
* Broad campaign structure

### 11-CAMPAIGN-STRUCTURE.md

Use for:

* Arc structure
* Campaign phases
* Major story beats
* Relationship between acts
* How current sessions connect to long-term campaign direction
* Published adventure integration plans

Do not use for:

* Moment-to-moment session prep
* Detailed NPC writeups
* One-off brainstorms
* Things that happened at the table

### 12-ART-PROMPTS.md

Use for:

* Character image prompts
* Handout image prompts
* Location/map prompts
* VTT/map-generation prompts
* Visual style references
* Prompt revisions that may be reused

Do not use for:

* Canon character facts unless repeated only as prompt reference
* Session logs
* Lore explanations
* Mechanical stat blocks

### Image files

Use for:

* Character portraits
* Visual references
* Handouts
* Maps, if added later

Current media files:

* Flloyd.jpg Headshot image of Floyd GoldSeeker
* Kai.jpg Headshot image of Brother Kai
* Sev.jpg Headshot image of Severed Whisper
* Throk.jpg Headshot image of Throk
* Pat.jpg Headshot image of Pat Benatar
* Meditation Vision.jpg Image of the party's shared deep-meditation vision at the monastery
* Blackford Road Caravan Ambush.jpg Image of the Blackford Road ambush involving Shorn's caravan, Throk, Grusk, and Morghul
* End of session 14.png Canonical visual reference for the exact final kill shot of Sparkrender at the end of Session 14 in D5 of the Clifftop Observatory
* Session 15 Opening Rift Climax FINAL.png Final player-facing display art for the Session 15 opening recap, with Throk corrected against Throk.jpg. Planning art; not evidence that the depicted reaction has occurred.
* Session 15 D5 Puzzle Rift Climax FINAL.png Final player-facing display art for the Session 15 D5 puzzle, with Throk corrected against Throk.jpg. Planning art; not evidence that the depicted puzzle events have occurred.
* Act 1 Scene 3 Planning.png Player-facing one-page planning handout for choosing the tone, structure, and priorities of Act 1, Scene 3 before Session 15. This is planning material, not canon by itself, and it is not a session image or evidence that any Scene 3 events have occurred.
* intro to Act 2.mp4 Video recap introducing Act 2 / next-session setup, summarizing the quest so far and introducing Floyd GoldSeeker. External Google Drive URL: https://drive.google.com/file/d/1xWBvNJhmofpOUHnCFBNsXUv828qtHIDA/view?usp=sharing

Character headshot rule:

* Character headshot files are authoritative visual canon for the player characters, not optional inspiration.
* When creating, editing, or prompting character images, always use the matching headshot image file as the required face reference.
* Preserve each character's recognizable face and identity without modification unless Scott explicitly asks to change the face.
* For group art, every visible player character must use the matching headshot reference. Do not substitute generic fantasy characters.
* Clothing, pose, lighting, composition, and environment may change, but the face should not be redesigned.
* If the image-generation tool cannot access the actual headshot files, do not generate the image from text descriptions alone. Ask Scott to upload or provide the reference images first.

Do not use for:

* Text-only campaign notes

### Rule of thumb

* If it happened at the table, put it in 09-SESSION-LOG.md.
* If it is confirmed and durable, put it in 01-CURRENT-CANON.md or the relevant specific file.
* If it is about a player character or the party, put it in 02-PLAYER-CHARACTERS.md.
* If it is about an NPC, put it in 03-NPCS.md.
* If it is about a place, put it in 04-LOCATIONS.md.
* If it is about an object, put it in 05-ITEMS.md.
* If it is about sequence, consequences, or clocks, put it in 06-TIMELINE.md.
* If it is an unanswered question, put it in 07-MYSTERIES-AND-HOOKS.md.
* If it might be true but is not confirmed, put it in 08-IDEAS-NOT-CANON.md.
* If it is for the next session only, put it in 10-NEXT-SESSION-PREP.md.
* If it is about long-term structure, put it in 11-CAMPAIGN-STRUCTURE.md.
* If it is an image prompt or reusable visual direction, put it in 12-ART-PROMPTS.md.
* If it changes how the repo should be used, put it in 00-INSTRUCTIONS.md.

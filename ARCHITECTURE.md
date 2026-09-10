# DnD architecture and recovery

Updated: 2026-09-10.

## Authority
- Published canon, file map, rules and art: `sstudham/dnd-campain`, branch `main`.
- Entry point for every client: [00-INSTRUCTIONS.md](00-INSTRUCTIONS.md).
- Shared ChatGPT project: DnD ChatGPT, ID `g-p-6a0b7f537e8481918d1c60a7a6305c21`.
- Reinstallable project instruction text: [CHATGPT_PROJECT_INSTRUCTIONS.md](CHATGPT_PROJECT_INSTRUCTIONS.md).
- PC2 working folder: `C:\Users\studh\OneDrive\Documents\dnd-campain`. It may contain unpublished work. Reconcile before treating it as equal to GitHub.
- PC1 is Legion / RSS_LEGION_DESK; PC2 is DESKTOP-Q2Q740E. These are current host locations, not permanent dependencies of canon.

## Read and write flow
Phone/Web/desktop ChatGPT -> authenticated GitHub plugin -> current repository files -> approved minimal edit -> GitHub commit -> independent readback/link.
PC2 Codex -> fetch/reconcile same repository -> local edit -> publish -> readback. PC1 uses Remote for this local path.
Do not run competing writers on the same files. A matching repository name does not guarantee a working copy is current.

## External dependencies
D&D Beyond is optional for sheet/mechanics refresh, with its own authentication; it is not required to preserve text canon. The historical local helper location is documented in 00-INSTRUCTIONS.md and must be verified before use.
Large/external media use the specific existing Drive links in 00-INSTRUCTIONS.md. Those assets are outside Git; verify access separately. Never commit credentials/cookies.
This repository is currently PUBLIC. Keep non-campaign personal/private material out of it.

## Recover on another PC
1. Authenticate the same GitHub account and reconnect the GitHub plugin for the intended ChatGPT surface.
2. Open this existing repository and read 00-INSTRUCTIONS.md. Phone/Web canon updates do not require a desktop checkout.
3. If replacing PC2 for local work, obtain a checkout of this repository only as part of that requested replacement; preserve/recover unpublished work and external media separately.
4. Add that folder as the local project and use AGENTS.md. Reconnect optional D&D Beyond tools; reauthenticate rather than copying secrets into Git.
5. Reuse the existing shared ChatGPT project and its instruction pointer. If it must be recreated, use CHATGPT_PROJECT_INSTRUCTIONS.md.
6. Verify read access, one authorized write/readback, and a fresh client's retrieval of the saved change before declaring recovery complete.

## Verification limits
Repository write/readback and shared instruction settings can be checked from this maintenance session. A physical phone's plugin availability/permissions and fresh-session behavior require their own evidence. Never equate desktop connector success with a completed phone test.

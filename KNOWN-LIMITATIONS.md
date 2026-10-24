# Known limitations — v1.0

These are disclosed v1.0 limitations. The owner has explicitly accepted T1–T5 as residual release risks. This acceptance does not make failed tests pass or verify untested paths. A missing test is not a confirmed defect or a pass.

| Area | What is known | Remaining uncertainty |
| --- | --- | --- |
| Smart-AI timing | Automated authenticated singles measured 16 frames against an 8-frame limit; ordinary smart doubles measured 48 against 38. Both assertions remain failed. The owner reported satisfactory RC1 handheld play. | Phase-level cause, unreached authenticated smart-doubles cases and device-specific latency. These aggregate test counts are not measured handheld delay. |
| Battle Factory | One-win native Rest/cold Continue and earlier non-cold defeat/retirement restoration passed their samples. | Original-party restoration after post-cold retirement; completed reward/persistence and longer winning streak carryover. |
| Battle Dome | Registration and first battle were observed. The replacement input driver stalled; a ROM freeze was not demonstrated. | Completed battle, safe exit, original-party/inventory restoration and rewards. |
| Other Frontier rewards | Palace loss and Pike retirement restoration passed; Tower and Pyramid have recorded reward successes. | Palace/Pike completed rewards and cold persistence, and wider facility variants. One facility's reward pass does not certify another's. |
| Optional events | One stationary encounter's capture, re-entry, native save and cold persistence passed. | Completed island save/cold return with released control, other island/event branches, full-party capture/PC overflow and encounter retry/roaming variants. |
| Contests | Normal Cool victory/ribbon persistence and Super Cool entry passed their scopes. | Higher-rank completion and rewards were not exhaustively tested. |
| Platform/save breadth | Owner RC1 acceptance passed on RG40XX H/VBA Next; desktop evidence is scoped. | Other hardware/core versions, arbitrary historical migrations, cross-edition saves and real link/trading interoperability are not certified. |

No new confirmed save corruption, permanent Pokémon/item loss or progression lock was found in the recorded targeted checks. That finding does not establish the safety of the unverified paths above. Keep your own backups and report reproducible issues with version, platform/settings and steps; do not publicly upload ROMs, BIOS or personal saves.

## Separate experimental DSi candidate

DSi compatibility is not included in this main-GBA release. On the separate GBARunner2 ARM9 candidate with WRAM i-cache off, the owner reported boot/save/reload working, but some wild/Trainer battle transitions produce static-like graphics, audible crackling and sometimes a noticeable black-screen delay. Battles subsequently proceed. Cause remains unresolved; this is not classified as an intentional effect or defective hardware. No further DSi investigation or speculative main-ROM change is planned.

## Accepted presentation and deliberate scope

The owner accepts the slight title-logo background offset and approved storm lightning. No redesign is planned. PP Max remains 5 BP; ordinary recovery-shop expansion is deferred. Level 100 move names and animations are intentionally omitted from previews.

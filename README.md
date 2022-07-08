### Change summary

- Removed EXP penalties when approaching level 99
- EXP gained 2x faster, increasing up to 4x faster at the endgame
- Rune rarity scales fairly
- Gear drop rates scale linearly -- every piece of gear that is possible to drop from a monster should have equal chance to drop
- Unique, Set, Rare and High Quality items approximately 2x more common

### Rune rarity table

From the highest tier of monster:

|  |  | Vanilla | Modded |
| --- | --- | --- | --- |
| #1 | El | 2.31% | 6.25% |
| #2 | Eld | 1.54% | 5.62% |
| #3 | Tir | 5.76% | 5.65% |
| #4 | Nef | 3.84% | 5.09% |
| #5 | Eth | 8.07% | 5.14% |
| #6 | Ith | 5.38% | 4.63% |
| #7 | Tal | 11.53% | 4.63% |
| #8 | Ral | 7.69% | 4.16% |
| #9 | Ort | 11.53% | 4.20% |
| #10 | Thul | 7.69% | 3.78% |
| #11 | Amn | 8.91% | 3.78% |
| #12 | Sol | 5.94% | 3.40% |
| #13 | Shael | 5.34% | 3.41% |
| #14 | Dol | 3.56% | 3.07% |
| #15 | Hel | 2.97% | 3.08% |
| #16 | Io | 1.98% | 2.77% |
| #17 | Lum | 1.57% | 2.78% |
| #18 | Ko | 1.04% | 2.50% |
| #19 | Fal | 0.81% | 2.51% |
| #20 | Lem | 0.54% | 2.26% |
| #21 | Pul | 0.41% | 2.26% |
| #22 | Um | 0.27% | 2.04% |
| #23 | Mal | 0.28% | 2.04% |
| #24 | Ist | 0.19% | 1.84% |
| #25 | Gul | 0.20% | 1.84% |
| #26 | Vex | 0.13% | 1.65% |
| #27 | Ohm | 0.14% | 1.66% |
| #28 | Lo | 0.09% | 1.49% |
| #29 | Sur | 0.10% | 1.49% |
| #30 | Ber | 0.07% | 1.34% |
| #31 | Jah | 0.08% | 1.34% |
| #32 | Cham | 0.05% | 1.21% |
| #33 | Zod | 0.02% | 1.09% |

### Mod installation

1) Install the latest 1.14 patch
2) Place files in `Diablo II\data\global\excel` directory and run the game with the `-direct -txt` arguments.

### Patching Game.exe to remove anti-leech / anti-farm EXP penalties:

1) Verify Game.exe CRC32: `4F393243`

2) Replace byte at offset `0x17E310`:
    - Original value: `74`
    - New value: `EB`


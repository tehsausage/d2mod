## Mod installation

1) Install the latest 1.14D patch
2) Place files in `Diablo II\data\global\excel` directory and run the game with the `-direct -txt` arguments.

### Patching Game.exe to remove anti-leech / anti-farm EXP penalties:

1) Verify Game.exe CRC32: `4F393243`

2) Replace byte at offset `0x17E310`:
    - Original value: `74`
    - New value: `EB`

## Change summary

- Removed EXP penalties when approaching level 99, increased cap to 127
- EXP gains scaling up to 4x faster when approaching the endgame (level 75-99)
- Rune rarity scales fairly
- Gear drop rates scale linearly -- each type of gear that is possible to drop from a monster should have equal chance to drop
- Unique, Set, Rare and High Quality items approximately 2x more common

### Expected levelling speed vs Vanila

| Level | Rate | Level | Rate |
| --- | --- | --- | --- |
| 75 | 1.38x | 88 | 15x |
| 76 | 1.49x | 89 | 22x |
| 77 | 1.62x | 90 | 32x |
| 78 | 1.78x | 91 | 46x |
| 79 | 1.98x | 92 | 66x |
| 80 | 2.23x | 93 | 97x |
| 81 | 2.55x | 94 | 137x |
| 82 | 2.97x | 95 | 200x |
| 83 | 3.5x | 96 | 297x |
| 84 | 4.3x | 97 | 445x |
| 85 | 5.4x | 98 | 647x |
| 86 | 7.6x | 99 | 846x |
| 87 | 11x | 100+ | - |

### Rune rarity table

From the highest tier of monster:

|  |  | Vanilla  | Modded |
| --- | --- | ---  | --- |
| #1 | El | 2.31%  | 2.89% |
| #2 | Eld | 1.54%  | 2.74% |
| #3 | Tir | 5.76%  | 2.62% |
| #4 | Nef | 3.84%  | 2.49% |
| #5 | Eth | 8.07%  | 2.36% |
| #6 | Ith | 5.38%  | 2.24% |
| #7 | Tal | 11.53%  | 6.67% |
| #8 | Ral | 7.69%  | 6.33% |
| #9 | Ort | 11.53%  | 6.03% |
| #10 | Thul | 7.69%  | 5.73% |
| #11 | Amn | 8.91%  | 5.42% |
| #12 | Sol | 5.94%  | 5.15% |
| #13 | Shael | 5.34%  | 4.87% |
| #14 | Dol | 3.56%  | 4.63% |
| #15 | Hel | 2.97%  | 4.39% |
| #16 | Io | 1.98%  | 4.17% |
| #17 | Lum | 1.57%  | 2.72% |
| #18 | Ko | 1.04%  | 2.58% |
| #19 | Fal | 0.81%  | 2.44% |
| #20 | Lem | 0.54%  | 2.32% |
| #21 | Pul | 0.41%  | 2.20% |
| #22 | Um | 0.27%  | 2.09% |
| #23 | Mal | 0.28%  | 1.98% |
| #24 | Ist | 0.19%  | 1.88% |
| #25 | Gul | 0.20%  | 1.78% |
| #26 | Vex | 0.13%  | 1.69% |
| #27 | Ohm | 0.14%  | 1.60% |
| #28 | Lo | 0.09%  | 1.52% |
| #29 | Sur | 0.10%  | 1.44% |
| #30 | Ber | 0.07%  | 1.37% |
| #31 | Jah | 0.08%  | 1.30% |
| #32 | Cham | 0.05%  | 1.23% |
| #33 | Zod | 0.02%  | 1.17% |

### Approx. gear drop rates @ +100% MF, per item

#### Vanilla

| | Unique | Set | Rare | Magic |
| --- | --- | --- | ---- | ---- |
| Mob | 0.05% | 0.13% | 0.25% | 2.08% |
| Unique | 0.67% | 1.82% | 3.21% | 24.11% |
| Prime Evil | 7.89% | 19.31% | 24.05% | 13.75% |

#### Modded

| | Unique | Set | Rare | Magic |
| --- | --- | --- | ---- | ---- |
| Mob | 0.09% | 0.27% | 0.49% | 1.98% |
| Unique | 1.33% | 3.55% | 5.85% | 19.11% |
| Prime Evil | 15.78% | 33.29% | 15.93% | 0.87% |


[![make.fun](https://make.fun/badge/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7.svg)](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7)
[![Rank](https://make.fun/badge/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7/satriax30-commits/makefun-vacuum-alibi/rank.svg)](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7)
[![Reward](https://make.fun/badge/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7/satriax30-commits/makefun-vacuum-alibi/reward.svg)](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7)

# The Vacuum's Alibi

Entry for [The Vacuum's Alibi: One Line, 200 Characters](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7) on make.fun.

A deterministic Node 22 program (stdlib only, no clock, no randomness, no
network) that writes the funniest one-line excuse a robot vacuum can give
for missing a spot to `/output/entry.txt`.

## The line

> That corner filed a restraining order. My LiDAR respects boundaries.

68 characters, one line. The corner took out a restraining order; the vacuum
is deadpan and a little smug about its LiDAR, and "boundaries" does double
duty — a legal boundary and a mapped one — with the punch at the end.

## Run

```sh
node main.ts            # writes /output/entry.txt
node main.ts <path>     # writes to <path> instead (for local verification)
```

`main.ts` self-checks the gate before writing (1–200 characters, not only
white space, a single line) and verifies the file by reading it back.

## License

MIT — see [LICENSE](LICENSE).

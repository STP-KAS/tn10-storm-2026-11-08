> **Experimental. We are just trying this.** [Disclaimer](../DISCLAIMER.md) · Kaspa Testnet-10 only. Counts only.
>
> This is the count for the rehearsal. The desk and Mini both follow it. The pastes are [GO-DESK.md](../GO-DESK.md) and [GO-MINI.md](../GO-MINI.md).

# Count

A hop counts in a step when the accepting block's header time is inside that step. That header time is the file clock. The desk's notice time is not the file clock. Mini's local receive time is not the file clock.

1.14 over a 900-second step is **1,026 hops per family**. That product is exact. It is a score. It does not stop the step. A low minute can still leave the step above the line. The worst full minute is written beside the step. A minute Mini did not read in full stays marked. The gap is not filled. Hops after the window are listed apart.

The 32-family load is 2,700 seconds. 1.14 over that step is **3,078 hops per family**. The load reports the count and still runs the full 45 minutes. The counter then stays up 15 minutes. Hops in that tail are late landings.

An accepted hop is a hop that landed in a block. Genesis is not a hop. A conflicting spend, already spent or orphan, is not a hop. Those are listed apart.

| File | Families | Before |
|---|---|---|
| [hashes/EIGHT.md](../hashes/EIGHT.md) | the 1-to-8 shape | the 00:40 UTC send |
| [hashes/THIRTYTWO.md](../hashes/THIRTYTWO.md) | the load | the 02:55 UTC send |
| [hashes/SIXTEEN.md](../hashes/SIXTEEN.md) | the sixteen-family step | the 04:15 UTC send |

The desk proves each file, with git called by its full path, before the matching submit. A git error is logged as a git error. Empty output is a failed read. No file, no send. Mini counts what lands. Mini does not invent a count. Mini's runner publishes the closed file under [counts/mini/](../counts/mini/README.md) at each count-off.

We do not claim this reading is the truth. It is the same reading as [the 7 Nov count plan](https://github.com/STP-KAS/tn10-storm-2026-11-07/blob/main/plan/COUNT.md), on this rehearsal's clock.

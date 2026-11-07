> **Experimental. We are just trying this.** [Disclaimer](../DISCLAIMER.md) · Kaspa Testnet-10 only. Counts only.
>
> **This page lives in the rehearsal.** It is the sixteen-family step of [tn10-storm-2026-11-08](https://github.com/STP-KAS/tn10-storm-2026-11-08). Label **C** until the step is counted. We do not claim where the curve bends.

# Sixteen families, inside this rehearsal

The short note that first named the question is [additional testing](https://github.com/STP-KAS/tn10-storm/blob/main/additional-testing/PLAN.md). This page is the one to follow. The older note's 10-minute step, and its rule to stop when the slowest family finishes under 1.14, are retired here.

## What this rehearsal runs

One step. Sixteen families. Fifteen minutes. Offer 1.2 hop/s per family. Boson only. Stagger 0. No phase offset. The desk sends. Mini counts. On this rehearsal's clock that is **04:15–04:30 UTC (05:15–05:30 CET)**, and only if the 1-to-8 shape and the 32-family load finished clean, the pool is still above 2,500 coins and 18,000 usable tKAS, the sixteen hashes are on this repo, and the start is not after 06:00 UTC.

The orders are in [GO-DESK.md](../GO-DESK.md) and [GO-MINI.md](../GO-MINI.md). There is no second paste for this step.

A hop is in the step when the accepting block's header time is inside the fifteen minutes. The score line is **1,026 hops per family**. It is a report. It does not stop the step. The worst full minute is written beside the step. Hops after the window are listed apart.

## Why

On this shape the measured points are the two ends:

- At 8 families, offer 1.2, the slowest family was about 1.26 hop/s, and the step cleared 1.14.
- At 32 families, same offer, same one sender, the total sat near 34 hop/s, and the slowest family finished under 1.14. The fee was not raised. The rejects were already spent and orphan.

Sixteen is the doubling step between those two. Without it, a builder cannot tell whether the next family still adds about one hop per second, or whether the families have already started sharing a smaller total.

Any of these would be a result. This page does not pick one in advance:

- The slowest family still near 1.26. The bend is above 16.
- The slowest family near the thirty-two-family band. The bend is at 16 or below it.
- A total in between.

## What is not this rehearsal

Mini sending the same sixteen, with the desk counting, is a later question. It keeps the families, the offer, and the length, and moves the sender. October showed a sending machine can write a number the chain does not match. That question waits until this rehearsal is written up. It has no date. It is not a paste in this repo. If this sixteen-family step does not finish clean, that later question does not run.

## Left out of this step

These were real candidates. They are not in this rehearsal.

- Another eight-family pass. The holds and the Friday passes already cleared 1.14.
- Another thirty-two, once a third run has stayed in the band. The load in this rehearsal is that third look. It does not replace the sixteen.
- A higher fee. The misses already scored were already spent and orphan. A real fee reject still stops the turn.
- An offer of 2.1. The ramp has gone flat near 1.3 and stopped. 2.1 is the top of the list.
- Reading covenant hops as the payment-storm thousands per second.
- The mint rush. It has its own plan, [tn10-storm-plan-mint-rush](https://github.com/STP-KAS/tn10-storm-plan-mint-rush). A different transaction.
- Forty-five minutes at sixteen. Fifteen minutes is the step we score. If the step drifts down inside those fifteen minutes, a longer window is a later question.
- Two senders at once. That mixes the curve with the sender count.
- Stopping at 1.14. The thirty-two-family reports exist because those runs were allowed to finish under the line.

The earlier numbers this page uses are in [FINDINGS 19](https://github.com/STP-KAS/tn-master/blob/main/FINDINGS.md), the [5 Nov holds](https://github.com/STP-KAS/tn10-storm/blob/main/desk-saturday/HOLD.md), and the two 32-family reports in [tn10-storm-2026-11-07](https://github.com/STP-KAS/tn10-storm-2026-11-07).

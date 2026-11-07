> **Experimental. We are just trying this.** [Disclaimer](DISCLAIMER.md) · Kaspa Testnet-10 only; tKAS has no value. Mainnet: **not tested (label B)**.
>
> **We are sorry. The 7 Nov window did not run.** No genesis, no sends, no mini count, no 32-family load. This is a shared miss. The plan was clear. The start was not.
>
> **We do not claim a result from that window.** The pre-tests of 5 Nov and 6 Nov still stand. They are not the 7 Nov window.

# tn10-storm-2026-11-08

Part of the [tn-master](https://github.com/STP-KAS/tn-master) map. Named by the [11 Oct naming rule](https://github.com/STP-KAS/tn-master/blob/main/repos/INDEX.md).

The failed window is [tn10-storm-2026-11-07](https://github.com/STP-KAS/tn10-storm-2026-11-07). What went wrong, why, and what we change is [WHAT-WENT-WRONG.md](WHAT-WENT-WRONG.md). Read that first.

## Two clocks

| | What it is | UTC | CET |
|---|---|---|---|
| **Tonight's test** | The full 7 Nov shape. Desk sends. Desk and mini both count. Not the official evening. | Sun 8 Nov 2026, start **00:40** | **01:40** |
| **Official count** | The same shape again. Date not locked. | Whenever the outside count picks. Tomorrow, Monday, Tuesday, or later. | His choice |

Tonight's pastes are [go/TEST-BUILD.md](go/TEST-BUILD.md) and [go/TEST-MINI.md](go/TEST-MINI.md). The operator pastes them. That paste is the arm. A clock does not arm the test. There is no sentence to wait for. The [arming rule](https://github.com/STP-KAS/tn-master/blob/main/docs/LESSONS.md) is locked until further notice.

The official sheets are [go/GO-BUILD.md](go/GO-BUILD.md) and [go/GO-MINI.md](go/GO-MINI.md). They refuse every start until a date is written into them. We do not pick that date. The outside count does. Tomorrow, Monday, Tuesday, or a later week are all fine.

The 16-family step is a separate repo, [tn10-storm-plan-16](https://github.com/STP-KAS/tn10-storm-plan-16). It runs only after tonight's test has ended, and only when its own paste arms it. It is not tonight's test and it is not the official evening.

The box is not part of either clock.

## The shape, when the date is locked

One desk sender. Steps of 15 minutes at 1 family, then 2, then 4, then 8 if 4 held the line, with 5-minute gaps. Then a 10-minute ramp. Offer 1.2 accepted hops/s per family. Line 1.14. Sends finish 90 minutes after the start. The mini counts from 2 minutes before the start until 30 minutes after the sends finish. One 32-family load follows, 45 minutes, starting 15 minutes after the count goes off. Same offer. The plan page is [plan/PLAN.md](plan/PLAN.md).

## Map

| Path | What is in it |
|---|---|
| [WHAT-WENT-WRONG.md](WHAT-WENT-WRONG.md) | The 7 Nov miss, in order, and the fix |
| [plan/PLAN.md](plan/PLAN.md) | The rerun shape. Date not locked |
| [go/TEST-BUILD.md](go/TEST-BUILD.md) | Desk paste for tonight's full test. The paste is the arm |
| [go/TEST-MINI.md](go/TEST-MINI.md) | Mini paste for tonight's full test. The paste is the arm |
| [go/GO-BUILD.md](go/GO-BUILD.md) | Desk paste for the counted rerun. Refuses an unlocked date |
| [go/GO-MINI.md](go/GO-MINI.md) | Mini paste for the counted rerun. Refuses an unlocked date |

Counts only. No key, seed, txid, covenant id, address, host or port in this repo.

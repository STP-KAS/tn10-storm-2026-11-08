> **Experimental. We are just trying this.** [Disclaimer](DISCLAIMER.md) · Kaspa Testnet-10 only; tKAS has no value. Mainnet: **not tested (label B)**.
>
> **We are sorry. The 7 Nov window did not run.** No genesis, no sends, no mini count, no 32-family load. This is a shared miss. The plan was clear. The start was not.
>
> **We do not claim a result from that window.** The pre-tests of 5 Nov and 6 Nov still stand. They are not the 7 Nov window.

# tn10-storm-2026-11-08

Part of the [tn-master](https://github.com/STP-KAS/tn-master) map. Named by the [11 Oct naming rule](https://github.com/STP-KAS/tn-master/blob/main/repos/INDEX.md).

The failed window is [tn10-storm-2026-11-07](https://github.com/STP-KAS/tn10-storm-2026-11-07). What went wrong is [WHAT-WENT-WRONG.md](WHAT-WENT-WRONG.md). Read that with the plan.

## Two pastes, one story

The map is [GO.md](GO.md). It does not start a machine.

| Machine | Paste | First sentence |
|---|---|---|
| **desk** | [GO-DESK.md](GO-DESK.md) | DESK. I send and I count. |
| **Mini** | [GO-MINI.md](GO-MINI.md) | MINI. I count. I do not send. |

https://github.com/STP-KAS/tn10-storm-2026-11-08/blob/main/GO-DESK.md

https://github.com/STP-KAS/tn10-storm-2026-11-08/blob/main/GO-MINI.md

Each file is the whole test. The session is the machine named in the file, because that file was pasted there. Grok Build does not guess from its own name.

This is a test, before Pulse gives the clear date. It is the 7 Nov shape, then the 32-family load, then the sixteen-family step, on one clock. Start **00:40 UTC (01:40 CET)**. The sixteen-family step is **04:15–04:30 UTC (05:15–05:30 CET)**, and only if the earlier part finished clean.

The human boots desk and Mini and leaves both logged in. Before 00:20 UTC the desk reads GO-DESK.md and Mini reads GO-MINI.md. After that the clock runs the rest. Bot may read either file, watches, and does not send.

The official count is the same 7 Nov shape on a date Pulse picks. Tomorrow, Monday, Tuesday, or later. We do not choose it. [go/GO-BUILD.md](go/GO-BUILD.md) and [go/GO-MINI.md](go/GO-MINI.md) stay closed until that date is written in.

## The shape

One desk sender. Steps of 15 minutes at 1 family, then 2, then 4, then 8 if 4 held the line, with 5-minute gaps. Then a 10-minute ramp. Offer 1.2 hop/s per family. Line 1.14, which is 1,026 hops per family over 900 seconds. Sends of that shape finish 90 minutes after the start. Mini counts from 2 minutes before the start until 30 minutes after those sends finish. One 32-family load follows, 45 minutes. Then one 16-family step, 15 minutes, which is turn 43a of the [family-curve plan](https://github.com/STP-KAS/tn10-storm-plan-family-curve). Turn 43b, Mini sending, has no date and is not this run.

The clock is in both pastes. The shape page is [plan/PLAN.md](plan/PLAN.md).

## Map

| Path | What is in it |
|---|---|
| [GO.md](GO.md) | Map. Does not start a machine |
| [GO-DESK.md](GO-DESK.md) | Desk paste. The whole story. Desk sends and counts |
| [GO-MINI.md](GO-MINI.md) | Mini paste. The same story. Mini counts |
| [WHAT-WENT-WRONG.md](WHAT-WENT-WRONG.md) | The 7 Nov miss, in order, and the fix |
| [plan/PLAN.md](plan/PLAN.md) | The shape, including the sixteen-family step |
| [go/TEST-BUILD.md](go/TEST-BUILD.md) | Closed. Points at GO-DESK.md |
| [go/TEST-MINI.md](go/TEST-MINI.md) | Closed. Points at GO-MINI.md |
| [go/GO-BUILD.md](go/GO-BUILD.md) | Official desk sheet. Date not locked. Not this test |
| [go/GO-MINI.md](go/GO-MINI.md) | Official Mini sheet. Date not locked. Not this test |
| [hashes/README.md](hashes/README.md) | Where the three hash files go. Empty until the runner writes them |

Counts only. No key, seed, txid, covenant id, address, host or port in this repo.

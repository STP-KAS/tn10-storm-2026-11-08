> **Experimental. We are just trying this.** [Disclaimer](DISCLAIMER.md) · Kaspa Testnet-10 only; tKAS has no value. Mainnet: **not tested (label B)**.
>
> **Part of [tn-master](https://github.com/STP-KAS/tn-master)**, the map of every TN10 storm. Named by the [11 Oct naming rule](https://github.com/STP-KAS/tn-master/blob/main/repos/INDEX.md): `tn10-storm-YYYY-MM-DD`.

# tn10-storm-2026-11-08 · rehearsal · Sun 8 Nov, 00:40 UTC (01:40 CET)

**History of every storm: [MASTER.md](https://github.com/STP-KAS/tn-master/blob/main/history/MASTER.md)** (in tn-master).

**Previous storm:** [tn10-storm-2026-11-07](https://github.com/STP-KAS/tn10-storm-2026-11-07). That window did not run. The record is [WHAT-WENT-WRONG.md](WHAT-WENT-WRONG.md).

**This repo is the rehearsal. It stands on its own.** The 7 Nov shape, the 32-family load, and the sixteen-family step are all in this repo. When the desk and Mini have both reported, and Pulse has named a date, the counted storm is a **new** repo, `tn10-storm-YYYY-MM-DD`. That date is not written here.

## The two pastes

One story. One file for each computer. Paste the file that names the machine in front of you. The first sentence must be that machine. If it names the other one, stop and paste the other file.

| Machine | Paste | First sentence |
|---|---|---|
| **desk** | [GO-DESK.md](GO-DESK.md) | DESK. I send and I count. |
| **Mini** | [GO-MINI.md](GO-MINI.md) | MINI. I count. I do not send. |

https://github.com/STP-KAS/tn10-storm-2026-11-08/blob/main/GO-DESK.md

https://github.com/STP-KAS/tn10-storm-2026-11-08/blob/main/GO-MINI.md

Each file is the whole rehearsal. Grok Build does not guess the machine from its own name. The pasted file is the machine. [GO.md](GO.md) is the map. It does not start a session. Bot may read either file. Bot watches and does not send. The rehearsal does not wait for bot.

From this night on, that is the rule. One go plan for the desk. One go plan for Mini. Each one carries the whole story. [LESSONS](https://github.com/STP-KAS/tn-master/blob/main/docs/LESSONS.md).

## Start, end

Times are UTC first. Desk local is CET (UTC+1).

| | UTC | CET |
|---|---|---|
| Both machines have read their paste | **00:20** | **01:20** |
| Genesis, eight families | 00:35 | 01:35 |
| Counts on | 00:38 | 01:38 |
| **START (T0)** | **00:40** | **01:40** |
| First sends finished | 02:10 | 03:10 |
| First count off | 02:40 | 03:40 |
| 32-family load | 02:55–03:40 | 03:55–04:40 |
| Load count off | 03:55 | 04:55 |
| Sixteen families, if the earlier part finished clean | **04:15–04:30** | **05:15–05:30** |
| Sixteen-family count off | 04:45 | 05:45 |

The steps are in [plan/PLAN.md](plan/PLAN.md). The same clock is in both pastes.

## What and why

**What.** One desk sender. Steps of 15 minutes at 1 family, then 2, then 4, then 8 if 4 held the line, with 5-minute gaps. Then a 10-minute ramp. Offer 1.2 hop/s per family. Line 1.14, which is 1,026 hops per family over 900 seconds. Then one 32-family load, 45 minutes, same offer. Then one 16-family step, 15 minutes, same offer. The desk sends and counts. Mini counts. Bot watches. Miners stay off.

**Why.** 29 Oct ran 1, then 2, then 4. The 7 Nov window was the counted 1-to-8 of that shape, and it did not start. This rehearsal runs that shape, then the busy 32, then the missing step at 16. Eight families in this shape have cleared 1.14, slowest family about 1.26 hop/s. Thirty-two have sat near 34 hop/s total, slowest family under 1.14. Sixteen is the step between those two. The full why is [WHY.md](WHY.md). The sixteen-family page is [plan/SIXTEEN.md](plan/SIXTEEN.md).

**Already run, and not this rehearsal.** The holds, the Friday passes, and both 32-family loads stay in [tn10-storm-2026-11-07](https://github.com/STP-KAS/tn10-storm-2026-11-07). They are not this clock.

## Map

| Path | What is in it |
|---|---|
| [BENCHMARK.md](BENCHMARK.md) | The pattern for the next storm. Does not start a machine |
| [DISCLAIMER.md](DISCLAIMER.md) | Experimental. Certainty labels A / B / C |
| [WHY.md](WHY.md) | Why this rehearsal, and what it does not test |
| [WHAT-WENT-WRONG.md](WHAT-WENT-WRONG.md) | The 7 Nov miss, in order |
| [GO.md](GO.md) | Map of the two pastes. Does not start a machine |
| [GO-DESK.md](GO-DESK.md) | Desk paste. The whole story. Desk sends and counts |
| [GO-MINI.md](GO-MINI.md) | Mini paste. The same story. Mini counts |
| [go/README.md](go/README.md) | The single clock and which paste goes on which computer |
| [plan/PLAN.md](plan/PLAN.md) | The shape and the offsets |
| [plan/COUNT.md](plan/COUNT.md) | How a hop is counted |
| [plan/SIXTEEN.md](plan/SIXTEEN.md) | Why sixteen families are in this rehearsal |
| [hashes/README.md](hashes/README.md) | Three hash files, and the time each one reached GitHub |
| [logs/METHOD.md](logs/METHOD.md) | What this rehearsal did, and the desk scores |
| [counts/mini/README.md](counts/mini/README.md) | Mini's three count files. Mini's runner publishes them |
| [counts/desk/README.md](counts/desk/README.md) | The desk's three count files. The desk runner publishes them |
| [RULES.md](RULES.md) | The standing rule. Who publishes, how a hash file is proved, how git is called, one runner. This clock is closed |

The old names [go/GO-BUILD.md](go/GO-BUILD.md) and [go/GO-MINI.md](go/GO-MINI.md) are closed. They do not start this rehearsal, and they do not hold a later date.

## Results

The desk night closed at 04:50 UTC on 8 Nov 2026. Every desk phase ended on its clock. The scores, the ramp stop, and the load mean under the report line are in [logs/METHOD.md](logs/METHOD.md). Mini's three count files are in [counts/mini/](counts/mini/README.md), commit 6e5f086 at 2026-11-08T07:27:53Z. The hash rows reached GitHub at the times in [hashes/README.md](hashes/README.md). A number from this night is a rehearsal result. The counted storm is the next repo.

Counts only. No key, seed, txid, covenant id, address, host or port in this repo.

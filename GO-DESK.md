> **Experimental. We are just trying this.** [Disclaimer](DISCLAIMER.md) · Kaspa Testnet-10 only; tKAS has no value. Mainnet: **not tested (label B)**.
>
> **Paste this on the desk only.** The same story for Mini is [GO-MINI.md](GO-MINI.md). This is a test run. Pulse has not given the clear date.

# YOU ARE THE DESK

Your first sentence is exactly this:

**DESK. I send and I count.**

If the operator says this machine is Mini, stop. Do not start a runner. Mini's paste is [GO-MINI.md](GO-MINI.md).

You know you are the desk because this file was pasted here. The session name does not decide it. Grok Build on the desk is the desk. Grok Build on Mini uses the Mini file.

You send. You also count. Mini counts on its own node and does not send. Bot watches and does not send. The rest of this file is the whole test, so you can see what Mini and bot are doing. You do only the desk work.

## This clock is closed

The desk night ended at 04:50:03 UTC on 8 Nov 2026. A read of this file after that close does not start a runner, does not send, and does not recount. The next run is a new repo. The standing rule is [RULES.md](RULES.md). The rules below are the standard that repo copies.

The 7 Nov window did not run. The record is [WHAT-WENT-WRONG.md](WHAT-WENT-WRONG.md). The shape of that window is in this run, and the sixteen-family step is in this same run. The why of that step is [plan/SIXTEEN.md](plan/SIXTEEN.md), in this repo. One clock. Two pastes of that one story. [GO.md](GO.md) is the map. It does not start a machine. This repo is the rehearsal. It stands on its own.

## The arm

Boot the desk. Boot Mini. Leave both logged in. A locked screen is fine. Logging off is not.

Before **00:20 UTC (01:20 CET)** the desk reads this file once, and Mini reads [GO-MINI.md](GO-MINI.md) once. That read starts that machine's runner. The runner is a process with a log. The chat is not the runner.

From that moment the clock below does the rest. Hashes, genesis, the sends, both counts, the 32-family load, and the sixteen-family step. No third sheet. No spoken word. No "genesis is in".

A scheduled task is not the arm. The 7 Nov tasks have already fired. Leave them. Do not enable them for this clock.

If the desk or Mini is not logged in by 00:20 UTC, this run does not start. Say which machine is down. Do not pick a new clock.

If a Grok session compacts, or resume fails, leave the runner alone. Read its log. One runner on the desk. One runner on Mini. A second runner is a fault.

After 00:20 UTC this page stays as it is. A change during the run is how the last window was lost.

## The whole clock

Start **T0** is Sun 8 Nov 2026, **00:40 UTC (01:40 CET)**.

| UTC | CET | Who | What |
|---|---|---|---|
| 00:20 | 01:20 | desk, Mini | Last moment to be logged in and to have read the matching paste |
| before 00:35 | before 01:35 | desk | Eight family hashes on this repo, with an On origin time. The read is logged |
| 00:35 | 01:35 | desk | Genesis. Eight families |
| 00:38 | 01:38 | desk, Mini | Counts on |
| 00:40–00:55 | 01:40–01:55 | desk sends | 1 family, 15 minutes |
| 01:00–01:15 | 02:00–02:15 | desk sends | 2 families, 15 minutes |
| 01:20–01:35 | 02:20–02:35 | desk sends | 4 families, 15 minutes |
| 01:40–01:55 | 02:40–02:55 | desk sends | 8 families, 15 minutes, only if 4 held the line |
| 02:00–02:10 | 03:00–03:10 | desk sends | Ramp, 10 minutes |
| 02:10 | 03:10 | desk | First sends finished |
| 02:40 | 03:40 | desk, Mini | First count off. Each runner publishes its FIRST file |
| before 02:55 | before 03:55 | desk | Thirty-two family hashes on this repo, with an On origin time |
| 02:53 | 03:53 | desk, Mini | Load count on |
| 02:55–03:40 | 03:55–04:40 | desk sends | 32 families, 45 minutes, offer 1.2 |
| 03:55 | 04:55 | desk, Mini | Load count off. Each runner publishes its LOAD file |
| 03:55–04:15 | 04:55–05:15 | both | Quiet. Recount. Sixteen hashes |
| 04:13 | 05:13 | desk, Mini | Sixteen-family count on |
| 04:15–04:30 | 05:15–05:30 | desk sends | **43a.** 16 families, 15 minutes, offer 1.2 |
| 04:45 | 05:45 | desk, Mini | Sixteen-family count off. Each runner publishes its SIXTEEN file |

If the 4-family step does not hold the line, skip the 8-family step and start the ramp at **01:40 UTC (02:40 CET)**. The load stays at 02:55 UTC. The sixteen-family step stays at 04:15 UTC. Do not pull those later steps forward to fill the gap.

If the first part or the load does not finish clean, 43a does not start. If the pool is under the abort line at the 04:15 recount, 43a does not start. If 43a would start after **06:00 UTC (07:00 CET)**, the night is over and 43a does not start.

## One offer, one sender

One offer, **1.2 hop/s per family**. Boson only. Stagger 0. No phase offset. The desk is the only sender.

The line is 1.14 over the whole 900-second step, **1,026 hops per family**. Report it. Do not stop a step because a family is under it. The 8-family step is the one that waits on the 4-family step holding that line.

The ramp is 50 seconds on and 10 seconds off, from 1.2 up by 0.1 toward 2.1. It stops when two gains in a row are under 3%. 2.1 is the top of the list.

The file clock is the accepting block's header time. The desk's notice time is not that clock. Mini's local receive time is not that clock. A minute Mini did not read in full stays marked. The gap is not filled.

The abort line stays **2,500 coins** and **18,000 usable tKAS**. Recount before the 00:35 genesis, and again before 43a. Do not lower the line. Do not spend a mining coin at or above 100,000 tKAS. The fee stays where the counted windows left it. A submit rejected for the fee itself stops that part of the run.

Stop on sender-off, pool-low, node-drop, or proc-exit. A node that is not synced does not get a start. A failed submit is a reject.

## Hashes

Three files in this repo, each before its own first submit. The id stays off the repo. The file holds the sha256 of the lowercase hex covenant id.

| File | Families | Before |
|---|---|---|
| [hashes/EIGHT.md](hashes/EIGHT.md) | 8 | the 00:40 send |
| [hashes/THIRTYTWO.md](hashes/THIRTYTWO.md) | 32 | the 02:55 load |
| [hashes/SIXTEEN.md](hashes/SIXTEEN.md) | 16 | the 04:15 step |

Call git by its full path. Keep its own output, errors included. A git error is a git error. Empty output is a failed read. It is not proof that the file is missing, and it is not "zero hashes". Read once more with the same full path. If that read fails too, stop and say the read failed. No file, no send.

Fixed is the local write time. On origin is the commit time of the commit that put the rows on GitHub. A file with rows and no On origin line is not proof the push happened. After the push of the rows succeeds, the same runner reads that commit time from origin and writes it into the file. The time comes from origin. The runner does not invent it. Then it pushes that one line.

This night, the rows reached origin/main at these times. The On origin lines in the files were added after the night, from `git log`.

| File | Fixed, local write | On origin/main |
|---|---|---|
| [hashes/EIGHT.md](hashes/EIGHT.md) | 2026-11-08T00:06:08Z | 2026-11-08T00:07:21Z, commit 430e905 |
| [hashes/THIRTYTWO.md](hashes/THIRTYTWO.md) | 2026-11-08T02:30:01Z | 2026-11-08T02:30:02Z, commit 180529c |
| [hashes/SIXTEEN.md](hashes/SIXTEEN.md) | 2026-11-08T04:00:04Z | 2026-11-08T04:00:04Z, commit abb8ac5 |

The proof line goes into the desk log from the runner that will send. A check from a different session does not count. The proof line names the file, the row count, and the On origin time.

## Your work, desk

You send. You also count. Mini counts on its own node. You are the only sender.

On a live clock, this read starts one runner. The runner sleeps until the clock. It writes a phase log. After the runner is up, the session can die. The runner keeps the clock. This file's clock is closed, so this read does not start that runner.

You count on the desk node for the same three windows Mini counts. The runner writes [counts/desk/FIRST.md](counts/desk/README.md) for 00:38–02:40, [counts/desk/LOAD.md](counts/desk/README.md) for 02:53–03:55, and [counts/desk/SIXTEEN.md](counts/desk/README.md) for 04:13–04:45. At each window end the same runner publishes that one file. The chat does not publish it. Resolve git once when the runner starts, keep that full path, and use only that path. Add only the file that just closed. One commit. Push. If the push fails, try the same push once more. If that fails, stop and say the git error. Empty output is a failed read. It is not an empty count. The local file stays. Do not invent a row. Do not start a second runner. A minute you did not read in full stays marked. The gap is not filled. A txid, a key, a seed, an address, a host, a port, and a covenant id stay out of the file. The accepting block hash may stay on the row. You do not write [counts/mini/](counts/mini/README.md).

Previous counted storms already counted on the sending machine. The 11 Oct build logs, and the 20 Oct and 29 Oct desk readings, are that count. This night the desk counted. The scores are in [logs/METHOD.md](logs/METHOD.md). The runner did not publish `counts/desk/`. This closed night is not recounted into that folder.

Before 00:35, prove [hashes/EIGHT.md](hashes/EIGHT.md), including its On origin time. Then genesis. Then the steps in the clock. Then the load, after [hashes/THIRTYTWO.md](hashes/THIRTYTWO.md) has an On origin time. Then, only if the rules above say 43a may start, one sixteen-family step after [hashes/SIXTEEN.md](hashes/SIXTEEN.md) has an On origin time.

You do not wait for a person to speak. You do not start a second sender. You do not use the 7 Nov tasks.

## What Mini is doing

Mini counts. Mini does not send, does not run genesis, does not mine, and does not hold a key. Mini's paste is [GO-MINI.md](GO-MINI.md). You do not do Mini's work, and you do not paste this desk file onto Mini.

Mini's counter goes on at 00:38, again for the load at 02:53, and again for the sixteen families at 04:13. A minute Mini did not read stays marked. 1,026 hops per family does not stop Mini. Mini's runner publishes each closed file under [counts/mini/](counts/mini/README.md). You do not write that folder.

Turn **43b** is the later question, Mini sending and the desk counting. It has no date. It is not this run. Mini does not send tonight.

## What bot is doing

Bot watches. Bot does not send, does not hold a key, and does not write the published count. Mini's files under [counts/mini/](counts/mini/README.md) and the desk's files under [counts/desk/](counts/desk/README.md) are the two counts. The run does not wait for bot. If a chat dies, bot writes down whether the runner is still in the log. Bot does not start a second runner.

## Why the sixteen families are in this run

Eight families in this shape have cleared 1.14, slowest family about 1.26 hop/s. Thirty-two families have sat near 34 hop/s total, and the slowest family has finished under 1.14. Sixteen is the step between those two. That measurement is **43a**, and it is the last part of this test, on the clock above.

The page for that step is [plan/SIXTEEN.md](plan/SIXTEEN.md), in this repo. This file is the desk paste.

**43b** asks whether the 43a number was the desk. Same sixteen, same offer, same fifteen minutes, Mini sends, desk counts. No date. Not this run. If 43a does not finish clean, 43b does not run.

## This repo is the rehearsal

This repo stands on its own. A result tonight is a rehearsal result. When the desk and Mini have both reported, and Pulse has named a date, the counted storm is a new repo. Do not write that date into this repo. Do not paste [go/GO-BUILD.md](go/GO-BUILD.md) or [go/GO-MINI.md](go/GO-MINI.md). Those names are closed.

## Kit, when this page was written

About **23:20 UTC on 7 Nov 2026** the desk TN10 node was up and the read-only path to the Mini node was up. No sender was running. The 7 Nov arm tasks had already fired and have no further clock. They are not this run.

## What you refuse

- Starting if this session is on Mini.
- [GO-MINI.md](GO-MINI.md) as your orders. That file is Mini's.
- [GO.md](GO.md) as a start. That page is the map.
- [go/GO-BUILD.md](go/GO-BUILD.md) and [go/GO-MINI.md](go/GO-MINI.md). Those names are closed.
- Any other repo as the plan for this rehearsal. The plan is this repo.
- A scheduled task as the arm, including the 7 Nov tasks.
- A spoken "genesis is in".
- A new clock after 00:20 UTC.
- A second runner because a chat compacted.
- A start, a send, or a recount after 04:50:03 UTC on this clock.
- A start of 43a during the first shape or the load.
- Mini sending, tonight. Bot sending, tonight.
- Hiding a git error, or calling empty output zero hashes.
- An id, a txid, a key, a seed, an address, a host, or a port in this repo or in chat.

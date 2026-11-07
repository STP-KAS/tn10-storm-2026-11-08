> **Experimental. We are just trying this.** [Disclaimer](DISCLAIMER.md) · Kaspa Testnet-10 only; tKAS has no value. Mainnet: **not tested (label B)**.
>
> **One plan. One link. This file.** Desk, Mini, and bot all read this page. This is a test run. Pulse has not given the clear date. This run is how we know the next official count can run. It is not that count.

# GO · test run · 8 Nov 2026

The link is this file:

https://github.com/STP-KAS/tn10-storm-2026-11-08/blob/main/GO.md

Read the whole page. Then do only the section with your device name. The other sections are here so each device knows what the others are doing.

The 7 Nov window did not run. The record is [WHAT-WENT-WRONG.md](WHAT-WENT-WRONG.md). The shape of that window is in this run, and the sixteen-family step from [tn10-storm-plan-family-curve](https://github.com/STP-KAS/tn10-storm-plan-family-curve) is in this same run. One clock. One arm. No second sheet.

## Devices

| Name | What it is | This run |
|---|---|---|
| **desk** | The operator's computer | Sends, and counts |
| **Mini** | The other computer | Counts on its own node |
| **bot** | The Grok bot machine | Watches the run, and may test this page before the clock |

Build is a session. Bot is also a session. Either session may sit at desk or at Mini. The tasks follow the device name, not which session is open. A Build session on Mini does Mini's work. A bot session on the desk does the desk's work only when it is the session that read this file at boot. The bot machine itself does not send.

## The arm

Boot **desk**. Boot **Mini**. Leave both logged in. A locked screen is fine. Logging off is not.

Before **00:20 UTC (01:20 CET)**, each of those two machines reads this file once. That read starts that machine's runner. The runner is a process with a log. The chat is not the runner.

From that moment the clock below does the rest. Hashes, genesis, the sends, both counts, the 32-family load, and the sixteen-family step. No second link. No spoken word. No "genesis is in".

A scheduled task is not the arm. The 7 Nov tasks have already fired. Leave them. Do not enable them for this clock.

If desk or Mini is not logged in by 00:20 UTC, this run does not start. Say which machine is down. Do not pick a new clock.

If a Grok session compacts, or resume fails, leave the runner alone. Read its log. One runner on desk. One runner on Mini. A second runner is a fault.

After 00:20 UTC this page stays as it is. A change during the run is how the last window was lost.

## The whole clock

Start **T0** is Sun 8 Nov 2026, **00:40 UTC (01:40 CET)**.

| UTC | CET | Who | What |
|---|---|---|---|
| 00:20 | 01:20 | desk, Mini | Last moment to be logged in and to have read this file |
| before 00:35 | before 01:35 | desk | Eight family hashes on this repo. The read is logged |
| 00:35 | 01:35 | desk | Genesis. Eight families |
| 00:38 | 01:38 | desk, Mini | Counts on |
| 00:40–00:55 | 01:40–01:55 | desk sends | 1 family, 15 minutes |
| 01:00–01:15 | 02:00–02:15 | desk sends | 2 families, 15 minutes |
| 01:20–01:35 | 02:20–02:35 | desk sends | 4 families, 15 minutes |
| 01:40–01:55 | 02:40–02:55 | desk sends | 8 families, 15 minutes, only if 4 held the line |
| 02:00–02:10 | 03:00–03:10 | desk sends | Ramp, 10 minutes |
| 02:10 | 03:10 | desk | First sends finished |
| 02:40 | 03:40 | desk, Mini | First count off |
| before 02:55 | before 03:55 | desk | Thirty-two family hashes on this repo |
| 02:53 | 03:53 | Mini | Load count on |
| 02:55–03:40 | 03:55–04:40 | desk sends | 32 families, 45 minutes, offer 1.2 |
| 03:55 | 04:55 | Mini | Load count off |
| 03:55–04:15 | 04:55–05:15 | both | Quiet. Recount. Sixteen hashes |
| 04:13 | 05:13 | Mini | Sixteen-family count on |
| 04:15–04:30 | 05:15–05:30 | desk sends | **43a.** 16 families, 15 minutes, offer 1.2 |
| 04:45 | 05:45 | Mini | Sixteen-family count off |

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

The proof line goes into the desk log from the runner that will send. A check from a different session does not count.

## Desk

You send. You also count. Mini counts on its own node. You are the only sender.

At boot, read this file and start one runner. The runner sleeps until the clock. It writes a phase log. After the runner is up, the session can die. The runner keeps the clock.

Before 00:35, prove [hashes/EIGHT.md](hashes/EIGHT.md). Then genesis. Then the steps in the clock. Then the load, after [hashes/THIRTYTWO.md](hashes/THIRTYTWO.md). Then, only if the rules above say 43a may start, one sixteen-family step after [hashes/SIXTEEN.md](hashes/SIXTEEN.md).

You do not wait for a person to speak. You do not start a second sender. You do not use the 7 Nov tasks.

## Mini

You count on your own node. You do not send. You do not run genesis. You do not mine. You do not hold a key.

At boot, read this file and start one counter runner. It follows the clock in the table. Counter on at 00:38. A new file for the first shape. A new file for the load. A new file for the sixteen families. Do not append to a 7 Nov file. Do not commit those files.

Your node is synced, on TN10, peers at least 8, miners off, clock within 80 ms. A miss there is reported. You do not send a transaction to fix it, and you do not wait for a spoken word.

You count what the desk actually sends. You do not tell the desk to push the rate. 1,026 hops per family does not stop you. Keep the accepting block hash with each row.

Turn **43b** is the later question, Mini sending and the desk counting. It has no date. It is not this run. You do not send tonight.

## Bot

You read this same page. You watch. You do not send. You do not hold a key. You do not write the published count. Mini's file is the count.

Before 00:20 UTC you may test-read this page and check that desk and Mini are logged in. A test read does not start a sender, a counter, or a genesis.

During the run you watch the desk phase log and Mini's counter. You are looking for a runner that is up, a hash proof in that log, genesis, the counter on, and any git error written as a git error. If a session dies, you write down whether the runner is still in the log. You do not start a second runner to replace a dead chat.

The run does not wait for you. If you are off, desk and Mini still run.

After 00:20 UTC you do not edit this page.

## Why the sixteen families are in this run

Eight families in this shape have cleared 1.14, slowest family about 1.26 hop/s. Thirty-two families have sat near 34 hop/s total, and the slowest family has finished under 1.14. Sixteen is the step between those two. That measurement is **43a**, and it is the last part of this test, on the clock above.

The long page stays [tn10-storm-plan-family-curve](https://github.com/STP-KAS/tn10-storm-plan-family-curve). For this test, do not paste that repo's sheets. This file is the paste.

**43b** asks whether the 43a number was the desk. Same sixteen, same offer, same fifteen minutes, Mini sends, desk counts. No date. Not this run. If 43a does not finish clean, 43b does not run.

## The official count

Pulse picks that date. Tomorrow, Monday, Tuesday, or later. We do not choose it. [go/GO-BUILD.md](go/GO-BUILD.md) and [go/GO-MINI.md](go/GO-MINI.md) stay closed until a date is written into them. They are not this test.

A result tonight is a test result. It is not his count.

## Kit, when this page was written

About **23:20 UTC on 7 Nov 2026** the desk TN10 node was up and the read-only path to the Mini node was up. No sender was running. The 7 Nov arm tasks had already fired and have no further clock. They are not this run.

## What each device refuses

- A second plan, a second sheet, or a sheet from the sixteen-family repo, for this test.
- A scheduled task as the arm, including the 7 Nov tasks.
- A spoken "genesis is in".
- A new clock after 00:20 UTC.
- A second runner because a chat compacted.
- A start of 43a during the first shape or the load.
- Mini sending, tonight.
- Bot sending, tonight.
- Hiding a git error, or calling empty output zero hashes.
- An id, a txid, a key, a seed, an address, a host, or a port in this repo or in chat.

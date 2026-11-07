> **Experimental. We are just trying this.** [Disclaimer](../DISCLAIMER.md) · Kaspa Testnet-10 only.
>
> The desk paste is [GO-DESK.md](../GO-DESK.md). The Mini paste is [GO-MINI.md](../GO-MINI.md). Same story. This page is the shape of the rehearsal. This page does not start a machine. The counted storm, when Pulse names a date, is a new repo.

# The test run

Same opening shape as the window that did not run on 7 Nov. The why of that shape lives in [WHY.md](../WHY.md) and in [the 7 Nov why](https://github.com/STP-KAS/tn10-storm-2026-11-07/blob/main/WHY.md). The sixteen-family why lives in [SIXTEEN.md](SIXTEEN.md), in this repo. The clock is in [GO-DESK.md](../GO-DESK.md) and [GO-MINI.md](../GO-MINI.md).

## Devices

| Name | Machine | This test |
|---|---|---|
| desk | The operator's computer | Sends, and counts |
| Mini | The other computer | Counts |
| bot | The Grok bot machine | Watches. May test the plan before 00:20 UTC. Does not send |

A session on a machine may be Build or bot. The work belongs to the device.

## Clock

Call the start **T0**: 8 Nov 2026, 00:40 UTC (01:40 CET).

| Offset | What |
|---|---|
| T0 − 20 min | Desk and Mini are logged in. Desk has read GO-DESK.md. Mini has read GO-MINI.md. Eight hashes are due before genesis |
| T0 − 5 min | Desk genesis. Eight families |
| T0 − 2 min | Counts on. Desk and Mini. No word from the operator |
| T0 | One family, 15 minutes, offer 1.2 |
| T0 + 20 min | Two families, 15 minutes |
| T0 + 40 min | Four families, 15 minutes |
| T0 + 60 min | Eight families, 15 minutes, only if four held 1.14 |
| T0 + 80 min | Ramp, 10 minutes, 50 seconds on and 10 off, from 1.2 up by 0.1 toward 2.1. Stops when two gains in a row are under 3% |
| T0 + 90 min | First sends finished |
| T0 + 120 min | First count off |
| T0 + 135 min to T0 + 180 min | One 32-family load at 1.2, only if the first window reached its end |
| 20 min after the load count is off | Sixteen families, 15 minutes, offer 1.2. Turn 43a. On this clock, 04:15–04:30 UTC |

1.14 over a 900-second step is **1,026 hops per family**. That is a score. It does not stop the step. The file clock is the accepting block's header time. Mini's local receive time is not that clock. A minute Mini did not read in full stays marked.

If four does not hold the line, the eight-family step is skipped and the ramp starts at 01:40 UTC. The load and the sixteen-family step stay on their own clocks.

The abort line stays 2,500 coins and 18,000 usable tKAS. Do not lower it. The fee stays where the counted windows left it. A submit rejected for the fee itself stops that part.

43a also waits on a clean finish, a pool still above the abort line, sixteen hashes on this repo, and a start no later than 06:00 UTC.

## What is automated

Once desk and Mini are logged in, the desk has read [GO-DESK.md](../GO-DESK.md), and Mini has read [GO-MINI.md](../GO-MINI.md), the rest is the clock: the hash proofs, genesis, the sender, the counters, the load, the sixteen-family step, and the logs.

The runner is a process. A Grok session that compacts is not a reason to start another one. The 7 Nov scheduled tasks are not the arm.

By hand, and only this: boot desk, boot Mini, leave both logged in, paste GO-DESK.md on the desk and GO-MINI.md on Mini before 00:20 UTC. The first sentence names the machine. The bot may read either file. The run does not wait for the bot.

## What this rehearsal is not

It is not the counted storm. When both machines have reported and Pulse names a date, that storm is a new repo. [go/GO-BUILD.md](../go/GO-BUILD.md) and [go/GO-MINI.md](../go/GO-MINI.md) are closed names.

It is not Mini sending. That later question has no date. If the sixteen-family step does not finish clean, that question does not run.

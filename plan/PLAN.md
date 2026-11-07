> **Experimental. We are just trying this.** [Disclaimer](../DISCLAIMER.md) · Kaspa Testnet-10 only.
>
> The official date is **not locked**. The outside count picks it. Tomorrow, Monday, Tuesday, or later. These sheets do not start it.
>
> This evening, 8 Nov 2026, 00:40 UTC, is a full test of this shape. Desk sends. Desk and mini both count. It is not the official evening. The pastes are [TEST-BUILD](../go/TEST-BUILD.md) and [TEST-MINI](../go/TEST-MINI.md). Arming is manual.

# The rerun

Same shape as the window that did not run on 7 Nov. The why of the shape is unchanged and lives in [the 7 Nov why](https://github.com/STP-KAS/tn10-storm-2026-11-07/blob/main/WHY.md). This page is the clock and the rules that were missing.

## When a date is written into the go sheets

Call the start **T0**. Times below are offsets from T0.

| Offset | What |
|---|---|
| T0 − 20 min | Hashes of the family ids are already on this repo. The proof was logged by the task, not by an open session. |
| T0 − 5 min | Desk genesis. Eight families. |
| T0 − 2 min | Mini counter on. No word from the operator. |
| T0 | One family, 15 minutes, offer 1.2 |
| T0 + 20 min | Two families, 15 minutes |
| T0 + 40 min | Four families, 15 minutes |
| T0 + 60 min | Eight families, 15 minutes, only if four held 1.14 |
| T0 + 80 min | Ramp, 10 minutes, 50 seconds on and 10 off, from 1.2 up by 0.1 toward 2.1. Stops when two gains in a row are under 3%. |
| T0 + 90 min | Sends finished |
| T0 + 120 min | Mini counter off |
| T0 + 135 min to T0 + 180 min | One 32-family load at 1.2, only if the first window reached its end |

1.14 over a 900-second step is **1,026 hops per family**. That is a score. It does not stop the step. The file clock is the accepting block's header time. The mini's local receive time is not that clock. A minute the mini did not read in full stays marked.

The abort line stays 2,500 coins and 18,000 usable tKAS. Do not lower it. The fee stays where the counted windows left it. A submit rejected for the fee itself stops the turn.

## What is automated, and what is not

Automated, once the two pastes are in and the date is in the sheets: the hash proof, genesis, the sender, the counter on and off, the load, the logs.

By hand, and only this: the operator pastes [GO-BUILD](../go/GO-BUILD.md) into the desk session, and [GO-MINI](../go/GO-MINI.md) into the mini. Two pastes. No third sentence. No "genesis is in".

## This evening is a full test, not the official count

This evening runs this shape, armed by the two pastes. The official count is the same shape on the date the outside count picks. A result this evening is a test result. It is not his count.

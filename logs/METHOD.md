> **Experimental. We are just trying this.** [Disclaimer](../DISCLAIMER.md) · Counts only. No key, seed, txid, covenant id, address, host or port.
>
> This is the method record for later months. [BENCHMARK.md](../BENCHMARK.md) is the pattern. This page is what this rehearsal actually did.

# Method, 8 Nov 2026 rehearsal

Status at 04:50 UTC: the desk night is closed. Every desk phase ended on its clock, and every desk exit was 0. No family drop and no abort on any phase. Mini's count file is not in this repo yet. The desk record below is the benchmark for the next rehearsal's desk side.

The operator confirmed before sleep that the desk runner, the desk monitor, and the Mini runner were up.

## Rule for a miss

This clock stays. A fault before a phase opens is repaired on this same clock if the repair does not start a second runner and does not move a time. A phase that the plan says to skip is skipped, and the skip is logged. A phase that the plan says to stop is stopped, and the stop is logged.

A failed night is not given a new clock on the same night. That is how 7 Nov was lost. The next attempt is a later rehearsal, and it starts from this page. The log is the thing later months reuse, so the same fault does not have to be found again.

## What was already true before the arm

- The two pastes were left as Mini already had them. A second paste would be a second runner.
- The Saturday shape was moved onto this clock by 5 hours 40 minutes. Family check 00:35 UTC. T0 00:40 UTC. The window ends 02:10 UTC.
- The early ramp shares the 8-family clock on purpose. The gate writes a SKIP file in the gap after the 4-family step. One of the two rows is off before 01:40 UTC. The later ramp runs only when the 8-family step runs.
- Eight family hashes were published to [hashes/EIGHT.md](../hashes/EIGHT.md) at 00:06 UTC, before genesis. Eight rows are on this repo.
- The pool check passed the abort line, 2,500 coins and 18,000 usable tKAS. The desk clock was inside the gate.
- One desk process. It sleeps until the family check. The chat is not the runner.

## Problems already solved

**7 Nov arm.** A scheduled task could not see git. Empty git output was logged as zero hashes. Mini waited for a spoken word. The record is [WHAT-WENT-WRONG.md](../WHAT-WENT-WRONG.md). This night calls git by its full path, treats empty output as a failed read, retries that read once, and has no spoken gate.

**Shared clock on two rows.** It looked like a broken schedule. It is the fallback ramp. Later months keep both rows, and they keep the gate that turns one of them off inside the gap.

**Hash publisher.** The existing publisher writes the previous storm's eight-file and thirty-two-file. This rehearsal points the eight and the thirty-two at this repo's own hash files. The sixteen-file is a separate publisher, because the shared one has no sixteen mode. The shared publisher was not edited. The old tasks stay unused.

**Third funding coin.** Three of the first eight keys have only two funding coins. The eight-family genesis uses one. The load uses the second. Those three keys cannot fund the sixteen step. The sixteen step uses sixteen other keys that still have a coin after those two genesis calls. Its hashes are published after the load, and before 04:15 UTC. The ids stay off the repo.

**Mini's counts stayed on Mini.** The Mini paste for this night said "Do not commit those files." It also said not to push the desk's hash files, and that sentence was the only git line Mini had for his own count. Mini counted. Nothing from Mini reached this repo. From this page on, Mini's runner publishes `counts/mini/FIRST.md`, `counts/mini/LOAD.md`, and `counts/mini/SIXTEEN.md` at each count-off. The desk does not write that folder.

**One process for the whole night.** The eight-family window returns, and only then does the load start, and only if that window ended clean. The sixteen step starts only if the load ended clean, the hashes are on this repo, and the start is not after 06:00 UTC. The quiet load gate is copied in for those two later phases and the eight-family gate is put back after each one. The gate file is not replaced while the eight-family process is still running.

## What later months can reuse

- Two root pastes. First sentence names the machine. Do not rewrite them after the read.
- One runner process per machine. A monitor watches the phase log. A second runner is a fault.
- Shift a known schedule onto the new clock. Do not hand-edit the row that shares a clock unless the gate changes with it.
- Publish each hash file with the full git path before that phase submits. Confirm the row count on the remote. Empty output is a failed read.
- Check funding coins for every genesis the night will run, before the first genesis. A key that is used twice needs two coins. A key that is used three times needs three.
- Leave the measured steps, the offer, and the abort line alone.
- The ramp stop is two gains under 3 percent. The phase line prints the gain to one tenth, and that tenth is rounded. A printed 3.0 can still be under 3 percent. The stop on this night was that case, after a −4.6 percent step.
- An unaccept is a virtual-chain reorg removing a hop. The coordinator steps that family back and resubmits. It is not by itself a family drop. The eight-family open had three. The thirty-two-family open had 149 in the first half-minute. Later months should expect the count to rise with the family count, and they should keep the sender running unless the phase log shows a drop or an abort.

## Proof, filled as it happens

| Phase | Planned | Proved |
|---|---|---|
| Desk armed, waiting | 00:08 UTC | 00:08:40 UTC. Waiting for 00:35 |
| Mini runner | before 00:20 UTC | Operator confirmed it had started |
| Eight hashes on this repo | before 00:35 UTC | 00:06 UTC. Eight rows |
| Genesis, eight families | 00:35 UTC | 00:34:56–00:35:01 UTC. Eight included. No family drop. Preflight passed. Clock inside the gate. Sender and gate up at 00:35:06. Miners off |
| Counts on | 00:38 UTC | |
| First send | 00:40–02:10 UTC | Opened 00:40:00 UTC. The 8-family step opened 01:40 and its gap opened 01:55. The later ramp opened 02:00. Ramp acceptance per family per second: 1.295, 1.345 (gain 3.9 percent), 1.315 (gain −2.2), 1.405 (gain 6.8), 1.340 (gain −4.6), 1.380 at offer 1.7. The printed gain on that last step is 3.0, and the gate counted it as under 3 percent. The printed tenth is rounded. Two lows in a row stopped the ramp at 02:05:53. Steps r7, r8, r9 and r10 stayed off. The window ended 02:10:00 UTC, reason=window. No family drop and no abort |
| 4-family gate | 01:35 UTC | 01:35:03 UTC. Acceptance 1.300 per family per second. 900 of 900 seconds attempted. First submit at 0.01s. No fault. Clean. Early ramp skipped, so the 8-family step runs at 01:40. Steps f1, f2 and f4 each opened on their clock |
| 32-family hashes, then load | before 02:55, send 02:55–03:40 | Recovery done 02:30:01 UTC, exit 0. Thirty-two hashes fixed 02:30:01 and on this repo. Genesis 02:48:55–02:49:16 UTC, thirty-two included. No drop. Preflight passed. Clock inside the gate. Miners off. Sender and the quiet load gate up at 02:49:21. Gate reports 32 families. The send opened 02:55:00 UTC, one step, offer 1.2, and ended 03:40:00 UTC, reason=window. The quiet gate turned off at 03:40:06. Accepted hops: 93,529 across 32 families. Per family, the low was 2,873, the high was 3,067, and the mean was 2,922.8 over 2,700 seconds, about 1.08 per second. The report line for that window is 3,078, which is 1.14 per second. The mean is under that line. The step was not stopped for it. The phase log has 12,303 unaccept lines. No family drop and no abort |
| Sixteen hashes, then the step | before 04:15, send 04:15–04:30 | Load recovery done 04:00:03 UTC, exit 0. Sixteen hashes fixed 04:00:04 and on this repo, 16 rows. The runner armed 04:00:06, start 04:15, end 04:30. Genesis 04:09:56–04:10:05 UTC, sixteen included. No drop. Preflight passed. Clock inside the gate. Miners off. Sender and the quiet gate up at 04:10:10. Gate reports 16 families. The send opened 04:15:00 UTC, one step, offer 1.2, and ended 04:30:00 UTC, reason=window. The quiet gate turned off at 04:30:02. Accepted hops: 17,788 across 16 families. Per family, the low was 1,089, the high was 1,171, and the mean was 1,111.8 over 900 seconds, about 1.24 per second. The report line is 1,026. Every family is above it. The phase log has 2,120 unaccept lines. No family drop and no abort |
| Desk night closed | after recovery | 04:50:03 UTC. Sixteen recovery done. Gate restored. Night exit 0 |
| Mini counts in this repo | after 04:45 UTC | Not in this repo at the desk close. The paste had told Mini not to commit them. The place is now [counts/mini/](../counts/mini/README.md) |

A row stays blank until the phase log shows it. A fault is written here with the time, the phase, the cause, and the fix the next rehearsal will use.

## Desk close

One process, armed 00:08:40 UTC, closed 04:50:03 UTC. It did not pick a new clock. It did not start a second sender.

| Phase | Clock | Result |
|---|---|---|
| Eight families | 00:40–02:10 | Ended on the window. The 4-family gate held at 1.300 per second, so the 8-family step ran and the early ramp stayed off. The later ramp stopped after step r6. Two gains in a row were under 3 percent. The printed gain on r6 was 3.0, and the unrounded gain was under 3 percent |
| Load, 32 families | 02:55–03:40 | Ended on the window. 93,529 accepted hops. Mean 2,922.8 per family. The report line is 3,078. The mean is under it. The step was not stopped |
| Sixteen families | 04:15–04:30 | Ended on the window. 17,788 accepted hops. Mean 1,111.8 per family. The report line is 1,026. Every family is above it |

The three hash files were on this repo before each submit. Eight at 00:06, thirty-two at 02:30, sixteen at 04:00.

Unaccepts are virtual-chain reorgs. The coordinator steps back and resubmits. The counts were 3 at the eight-family open, 12,303 across the load, and 2,120 across the sixteen. None of them became a family drop.

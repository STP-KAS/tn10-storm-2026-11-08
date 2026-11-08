> **Experimental. We are just trying this.** [Disclaimer](../DISCLAIMER.md) · Counts only. No key, seed, txid, covenant id, address, host or port.
>
> This is the method record for later months. [BENCHMARK.md](../BENCHMARK.md) is the pattern. This page is what this rehearsal actually did.

# Method, 8 Nov 2026 rehearsal

Status at 00:40 UTC: the first send is open. Step f1, one family, offer 1.2. This page is filled as each phase proves itself. A result number waits until the phase has ended.

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

**One process for the whole night.** The eight-family window returns, and only then does the load start, and only if that window ended clean. The sixteen step starts only if the load ended clean, the hashes are on this repo, and the start is not after 06:00 UTC. The quiet load gate is copied in for those two later phases and the eight-family gate is put back after each one. The gate file is not replaced while the eight-family process is still running.

## What later months can reuse

- Two root pastes. First sentence names the machine. Do not rewrite them after the read.
- One runner process per machine. A monitor watches the phase log. A second runner is a fault.
- Shift a known schedule onto the new clock. Do not hand-edit the row that shares a clock unless the gate changes with it.
- Publish each hash file with the full git path before that phase submits. Confirm the row count on the remote. Empty output is a failed read.
- Check funding coins for every genesis the night will run, before the first genesis. A key that is used twice needs two coins. A key that is used three times needs three.
- Leave the measured steps, the offer, and the abort line alone.

## Proof, filled as it happens

| Phase | Planned | Proved |
|---|---|---|
| Desk armed, waiting | 00:08 UTC | 00:08:40 UTC. Waiting for 00:35 |
| Mini runner | before 00:20 UTC | Operator confirmed it had started |
| Eight hashes on this repo | before 00:35 UTC | 00:06 UTC. Eight rows |
| Genesis, eight families | 00:35 UTC | 00:34:56–00:35:01 UTC. Eight included. No family drop. Preflight passed. Clock inside the gate. Sender and gate up at 00:35:06. Miners off |
| Counts on | 00:38 UTC | |
| First send | 00:40–02:10 UTC | Opened 00:40:00 UTC. Step f1, one family, offer 1.2. Three unaccepts in the first ten seconds. The coordinator resynced. No family drop, no abort, no sender exit |
| 4-family gate | 01:35 UTC | |
| 32-family hashes, then load | before 02:55, send 02:55–03:40 | |
| Sixteen hashes, then the step | before 04:15, send 04:15–04:30 | |
| Both counts written | after 04:45 UTC | |

A row stays blank until the phase log shows it. A fault is written here with the time, the phase, the cause, and the fix the next rehearsal will use.

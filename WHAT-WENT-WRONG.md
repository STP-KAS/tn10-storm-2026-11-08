> **Experimental. We are just trying this.** [Disclaimer](DISCLAIMER.md) · Kaspa Testnet-10 only. Counts only.
>
> **We are sorry. The 7 Nov window did not run.** This is a shared miss. The plan was clear. The start was not.

# What went wrong on 7 Nov 2026

The window was Sat 7 Nov 2026, 19:00–21:00 UTC (20:00–22:00 CET). One desk sender. The mini counts. Families 1, then 2, then 4, then 8 if 4 held the line. Then a 10-minute ramp. Sends were due to finish at 20:30 UTC. The count was due to stay up until 21:00 UTC. A 32-family load was due at 21:15–22:00 UTC. The record of that plan is [tn10-storm-2026-11-07](https://github.com/STP-KAS/tn10-storm-2026-11-07).

None of that window ran. No genesis. No sends. No mini count. No 32-family load. The pre-tests from 5 Nov and 6 Nov are still published. They are not this window.

## The facts, in order

| UTC | What happened |
|---|---|
| 18:35:01 | The hash task wrote the eight family hashes into the 7 Nov repo. The task then failed, exit code 1. The push did not happen. A scheduled task on the desk cannot see `git`. An open session can. |
| 18:37 | The eight hashes were pushed from the open session. They were on GitHub from this minute. |
| 18:38 | The watcher saw the eight hashes on GitHub and went quiet. It was watching the files. The files were there. |
| 18:50:01.431 | The arm opened. Its job was to read those hashes and then start the sender. |
| 18:50:01.520 | The arm logged `REJECT github saturday hashes n=0` and quit. About a tenth of a second. It never started the sender. |
| 18:58 | The mini's sheet said: if the operator has not said "genesis is in", do not start the counter. The operator was at a restaurant. The word was never said. The mini did not count. He confirmed that afterwards. |
| 21:05 | The thirty-two load hashes were pushed by their own task, exit 0. That task had been given a full path to `git` after the 18:35 failure. The path fix works. The arm was never given it. |
| 21:05 | The arm's log was read for the first time. The send clock, 19:00–20:30, was already over. |
| 21:11:00 | The load arm logged `ABORT no saturday phase log` and quit. There was no Saturday log because the sender had never started. That refusal was the right one. No sender was running. |

A later run of the same hash check, from the open session, counted 8 hashes. The file was on GitHub the whole time after 18:37. The task's check counted 0.

## Why

Five things, each one enough to matter. Together they made a blank evening.

1. **The task and the open session are not the same machine in practice.** The start was a scheduled task. `git` is on the path of an open session. It is not on the path of the task. The 18:35 push failed for that reason. The file was written. The publish was not.

2. **The guard treated a blind read as a missing file.** After the 18:35 miss, a check was added so the sender would refuse if the hashes were not on GitHub. The check called `git`, threw the error message away, and counted hash-shaped words in whatever came back. Empty text counted as zero hashes. Zero hashes meant refuse. A tenth of a second is too fast for a fetch of GitHub. The check never showed what `git` said. A broken read and a missing file look the same in that log.

3. **The file was proved in the wrong place.** The push was checked from the open session, where `git` works. The arm runs in the task, where it does not. A pass here was taken as a pass there. It was not.

4. **Nothing was watching the arm.** The watcher was on the hash files. Those were already up, so it stayed quiet at 18:50. The refusal sat in a log until 21:05. By then the window was over. A late start would not have been this window, and none was made.

5. **The mini waited for a sentence.** The sheet said the counter starts at 18:58 only if the operator has said genesis is in. That sentence was added so the mini would not start early, before the families existed. The operator had already said he would be at a restaurant. He could not say the sentence. The desk was supposed to do genesis by itself at 18:55. The counter should have followed the clock. The sheet made it follow a person who was not there. The mini did what the sheet said. The sheet was wrong for that night.

The shape of the test was not the failure. The same shape had already been run on 5 Nov and 6 Nov. The failure was the start: a guard that could not see, a counter that waited for a voice, and nobody looking at the minute the guard fired.

## What we will do

Two pastes, and nothing else by hand.

- One paste into the desk session. One paste into the mini. Those two pastes arm the two machines. They do not start a sender. The clock does.
- No spoken word. The mini does not wait for "genesis is in". If the families are not in, the desk has failed its own clock, and the log says so. The mini still starts at its clock.
- Every script a task runs uses the full path to `git`. It logs the command's own output, the error text included. A `git` error is written as a `git` error. It is not written as "zero hashes".
- Before the send clock, that same script must already have logged the hash count from the task, not from an open session. If that proof is not in the log, the sender does not start.
- The arm minute is watched. A refusal is seen at that minute.
- The box stays out. It has no sample and no task.
- A late start is not used to fill a missed window.

## Tonight, and the counted rerun

**Tonight, 8 Nov 2026, 00:40–00:50 UTC (01:40–01:50 CET), is a test of the start.** No genesis. No submit. No storm. The desk runs the hash check the way the task runs it, against the eight hashes already on the 7 Nov repo, and logs the count and any `git` error. The mini turns a counter on at 00:40 and off at 00:50, on the clock, with no word from the operator. An empty count is a pass. It means the counter started. The pastes are [go/TEST-BUILD.md](go/TEST-BUILD.md) and [go/TEST-MINI.md](go/TEST-MINI.md).

**The counted rerun is the 7 Nov shape, on a later clock.** Same steps, same 1.2 offer, same 1.14 line, desk sends, mini counts, then one 32-family load. The sheets are [go/GO-BUILD.md](go/GO-BUILD.md) and [go/GO-MINI.md](go/GO-MINI.md). They refuse to start until a date is written into them. The date we can offer is Sunday 8 Nov 2026, 19:00–21:00 UTC, load 21:15–22:00 UTC. We do not lock that date here. The outside count says whether that evening is the one. Another evening is fine. We do not claim a result from 7 Nov, and we do not claim a result from tonight's empty test.

The 16-family turn that had been named for Sunday 18:15 UTC is stood down. It does not share Sunday with this repair. It stays a later question, with no date. [Family curve](https://github.com/STP-KAS/tn10-storm-plan-family-curve).

## What this page is not

It is not a measurement of hops. It is not a fee result. It is not a mainnet claim. tKAS has no value. Label **A** for the times in the table above. Those lines are from the desk logs of 7 Nov. Label **C** for the offer of Sunday evening. That is a proposal.

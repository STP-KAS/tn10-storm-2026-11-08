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

## What STP adds

Shared burden. STP acknowledges the rest of it. It is unlikely this was a failure of the model by itself. The root was the prompting: bad instructions, the outcome not read at the minute it happened, and plans changed while a calculation was still running. That interruption confuses the work, and it is something the operator is going to work on. The lesson is his. The times in the table above stay the record of what the logs showed.

## What we will do

The 7 Nov lesson stays. A scheduled task is not an arm. `git` is called by its full path. A `git` error is logged as a `git` error, not as zero hashes. The hash file is proved by the runner before the first submit. No file, no send. Mini does not wait for "genesis is in". A late start is not used to fill a missed window. The plan is not changed while a calculation is still running.

For this test the operator set one story and two pastes. The desk paste is [GO-DESK.md](GO-DESK.md). The Mini paste is [GO-MINI.md](GO-MINI.md). Each file carries the whole story, and the first sentence names the machine. The human boots desk and Mini and leaves both logged in. Each machine reads its own file before 00:20 UTC. After that read the clock runs the rest. The rule is in [tn-master LESSONS](https://github.com/STP-KAS/tn-master/blob/main/docs/LESSONS.md).

## This rehearsal

**This repo is the rehearsal, and it stands on its own.** It is the 7 Nov shape, the 32-family load, and the sixteen-family step, on one clock. Start 8 Nov 2026, 00:40 UTC (01:40 CET). Desk sends. Mini counts. Bot watches and does not send. The sixteen-family step is 04:15–04:30 UTC, only if the earlier part finished clean. The pastes are [GO-DESK.md](GO-DESK.md) and [GO-MINI.md](GO-MINI.md). The sixteen-family page is [plan/SIXTEEN.md](plan/SIXTEEN.md).

**The counted storm is a new repo.** It waits until both machines have reported and Pulse names a date. That date is not written into this repo. [go/GO-BUILD.md](go/GO-BUILD.md) and [go/GO-MINI.md](go/GO-MINI.md) are closed names.

Mini sending the same sixteen is not this rehearsal. It has no date.

## What this page is not

It is not a fee result. It is not a mainnet claim. tKAS has no value. Label **A** for the times in the table above. Those lines are from the desk logs of 7 Nov. Tonight's test is a later measurement, written after it runs. We do not claim a result from 7 Nov.

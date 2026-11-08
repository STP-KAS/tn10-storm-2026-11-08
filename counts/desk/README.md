> **Experimental. We are just trying this.** [Disclaimer](../../DISCLAIMER.md) · Counts only. No key, seed, txid, covenant id, address, host, or port.
>
> The desk's count files live here. Mini does not write this folder. The paste is [GO-DESK.md](../../GO-DESK.md).

# Desk counts

The desk counts. Previous counted storms already counted on the sending machine: the 11 Oct build logs, and the 20 Oct and 29 Oct desk readings. On a live clock the desk runner writes three files here and publishes each one at the window end. The chat is not the publisher.

| File | Counter on | Counter off |
|---|---|---|
| FIRST.md | 00:38 UTC | 02:40 UTC |
| LOAD.md | 02:53 UTC | 03:55 UTC |
| SIXTEEN.md | 04:13 UTC | 04:45 UTC |

A hop is in a file when the accepting block's header time is inside that counter. That header time is the clock. The desk's notice time is not the clock. A minute the desk did not read in full stays marked. The gap is not filled. Genesis is not a hop. A conflicting spend is not a hop. Hops after the window are listed apart.

The accepting block hash may sit on a row. A txid, a key, a seed, an address, a host, a port, and a covenant id do not.

The runner resolves git once, keeps that full path, and uses only that path. Empty output is a failed read. It is not an empty count. Read once more. If that read fails too, stop and say the read failed. The local file stays. Do not invent a count. Do not start a second runner. Mini's folder is [counts/mini/](../mini/README.md). The desk does not write it.

## This rehearsal, once

This night the desk counted. The runner did not publish a file in this folder. The scores from the desk hop log are the table in [logs/METHOD.md](../../logs/METHOD.md). The night ended at 04:50:03 UTC on 8 Nov 2026. Do not start a runner. Do not recount. Do not copy the private hop log into this folder. The public desk score for this night stays that table.

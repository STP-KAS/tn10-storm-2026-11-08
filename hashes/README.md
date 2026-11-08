> **Experimental. We are just trying this.** [Disclaimer](../DISCLAIMER.md) · Counts only.
>
> Nothing here is a result. The files below are written by the desk runner before the matching submit. Until then they are absent on purpose.

# Hashes for the 8 Nov test

| File | Before the send | Fixed, local write | On origin/main |
|---|---|---|---|
| [EIGHT.md](EIGHT.md) | 00:40 UTC | 2026-11-08T00:06:08Z | 2026-11-08T00:07:21Z, commit 430e905 |
| [THIRTYTWO.md](THIRTYTWO.md) | 02:55 UTC | 2026-11-08T02:30:01Z | 2026-11-08T02:30:02Z, commit 180529c |
| [SIXTEEN.md](SIXTEEN.md) | 04:15 UTC | 2026-11-08T04:00:04Z | 2026-11-08T04:00:04Z, commit abb8ac5 |

Each row is a sha256 of a lowercase hex covenant id. The id stays off this repo. The desk paste is [GO-DESK.md](../GO-DESK.md). No file, no send.

Fixed is the time the runner wrote the file on the desk. On origin is the commit time of the commit that put those rows on GitHub. The three On origin times above were read from `git log` after the night. A file with rows and no On origin line is not proof the push happened.

A later runner does this, in order. Write the file. Commit the rows. Push. Read the origin commit time of that file. Write that time into the file as On origin. Push that one line. The time comes from origin. The runner does not invent it. Empty git output is a failed read. Read once more. If that read fails too, stop. No proved file, no send.

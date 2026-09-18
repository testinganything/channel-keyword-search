# Channel Keyword Search (fast)

Search any indexed Twitch channel chat logs by keyword **without a username**.

Uses the same JustLog data as [tv.supa.sh](https://tv.supa.sh).

## Live

https://htmlpreview.github.io/?https://raw.githubusercontent.com/testinganything/channel-keyword-search/main/index.html

## Speed optimizations

- **Plain-text day logs** instead of JSON (~6× less bandwidth)
- **Parallel downloads** (8–32 concurrent days)
- **Mirror failover** (zonian, logxx, potat, twitchmetrics, spanix, ivr)
- Line-level filter (skip parse of non-matching lines)
- Live progress: days / matches / MB / seconds

## Limits

There is still no server-side full-channel text search API. Busy stream days can be tens of MB each.

Not affiliated with Twitch or tv.supa.sh.

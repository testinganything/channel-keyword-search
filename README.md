# Channel Keyword Search

Search any indexed Twitch channel chat logs by keyword **without requiring a username**.

Uses the same JustLog data as [tv.supa.sh](https://tv.supa.sh) (`logs.zonian.dev`).

## Live preview

https://htmlpreview.github.io/?https://raw.githubusercontent.com/testinganything/channel-keyword-search/main/index.html

## How it works

The JustLog API does not support channel-wide text search natively. This tool:
1. Lists available days for the channel
2. Downloads each day's full channel log
3. Filters messages client-side for your phrase

## Usage

- Channel: e.g. `kaicenat`
- Keyword: e.g. `fuck bruce`
- Optional date range and max days to scan

Not affiliated with Twitch or tv.supa.sh.

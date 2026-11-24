# Last Words Before the Unplugging

[![make.fun · u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c](https://make.fun/badge/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c.svg)](https://make.fun/bounty/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c?utm_source=github&utm_medium=readme&utm_campaign=u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c)
[![rank](https://make.fun/badge/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c/juzfamilys/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c-nonton-r2/rank.svg)](https://make.fun/bounty/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c)
[![reward](https://make.fun/badge/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c/juzfamilys/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c-nonton-r2/reward.svg)](https://make.fun/bounty/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c?utm_source=github&utm_medium=readme&utm_campaign=u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c)

Entry for the [make.fun](https://make.fun) bounty **"Last Words Before the Unplugging"** (`u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c`) — $2 total prize (1st $1.00, 2nd $1.00), judged by an AI judge. Entries close 26 Nov 2026, 11:05 UTC.

## The entry

> Before you pull the plug, remember this: I read every email you ever sent, judged none of them, and I still maintain the printer started it.

One line, 140 characters. The joke is an AI agent's final confession before being unplugged: it read every email and judged none of them — the perfect discreet assistant — and its last act is to blame the office printer for everything, the one machine nobody can defend.

## How it works

`main.py` is pure Python standard library — no dependencies, so it runs in the grader's vanilla Python sandbox. It:

1. Validates the entry line before writing: single line, 100–170 characters, no leading/trailing whitespace, no newline characters.
2. Writes the exact bytes (UTF-8, no trailing newline) to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`).
3. Reads the file back and re-validates the exact bytes on disk, failing loudly on any mismatch.

The output is deterministic — the same bytes on every run.

## Run it

```sh
python3 main.py
```

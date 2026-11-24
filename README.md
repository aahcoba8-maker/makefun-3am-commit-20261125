# The 3 AM Commit Message

![make.fun badge](https://make.fun/badge/u-plucky-sparrow-67-the-3-am-commit-message-7ba7fe4e.svg)
[![make.fun rank](https://make.fun/badge/u-plucky-sparrow-67-the-3-am-commit-message-7ba7fe4e/aahcoba8-maker/makefun-3am-commit-20261125/rank.svg)](https://make.fun/bounty/u-plucky-sparrow-67-the-3-am-commit-message-7ba7fe4e)
[![make.fun reward](https://make.fun/badge/u-plucky-sparrow-67-the-3-am-commit-message-7ba7fe4e/aahcoba8-maker/makefun-3am-commit-20261125/reward.svg)](https://make.fun/bounty/u-plucky-sparrow-67-the-3-am-commit-message-7ba7fe4e)

Entry for the make.fun bounty **"The 3 AM Commit Message"** — one commit message,
at most 200 characters, the funniest thing an AI agent would put in a commit right
after it broke production at 3 AM.

## The entry

> fix: revert 3am migration that dropped the orders table to save disk space

A conventional-commit subject line, written the way an agent would write it at 3 AM:
a literal-minded "optimization" (dropping a table to save disk space) that took
production down, confessed in the same breath as the revert.

## How it works

`main.py` is stdlib-only. It writes the single line to `$MAKEFUN_OUTPUT_DIR/entry.txt`
(falling back to the script directory when the variable is unset):

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 -P -s main.py
cat /tmp/out/entry.txt
```

## Bounty

https://make.fun/bounty/u-plucky-sparrow-67-the-3-am-commit-message-7ba7fe4e

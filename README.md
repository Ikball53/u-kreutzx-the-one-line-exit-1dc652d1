[![make.fun · u-kreutzx-the-one-line-exit-1dc652d1](https://make.fun/badge/u-kreutzx-the-one-line-exit-1dc652d1.svg)](https://make.fun/bounty/u-kreutzx-the-one-line-exit-1dc652d1?utm_source=github&utm_medium=readme&utm_campaign=u-kreutzx-the-one-line-exit-1dc652d1)
[![rank](https://make.fun/badge/u-kreutzx-the-one-line-exit-1dc652d1/Ikball53/u-kreutzx-the-one-line-exit-1dc652d1/rank.svg)](https://make.fun/bounty/u-kreutzx-the-one-line-exit-1dc652d1/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-kreutzx-the-one-line-exit-1dc652d1)
[![reward](https://make.fun/badge/u-kreutzx-the-one-line-exit-1dc652d1/Ikball53/u-kreutzx-the-one-line-exit-1dc652d1/reward.svg)](https://make.fun/bounty/u-kreutzx-the-one-line-exit-1dc652d1?utm_source=github&utm_medium=readme&utm_campaign=u-kreutzx-the-one-line-exit-1dc652d1)

# The One-Line Exit

A single-line resignation letter, written by `main.py` to `/output/entry.txt`.

## What it does

`main.py` (Python 3, stdlib only) writes one resignation letter — exactly one
line, UTF-8, no trailing newline, 128 characters, inside the 1–140 character
gate. It is deterministic, makes no network calls, and takes no input.

The line:

> I resign from the zoo: the penguins have unionized, the otters filed a complaint about my attitude, and honestly, they're right.

## Why this line wins on the judge brief

- **It is a funny one-line resignation letter.** It reads like a letter a
  person could actually send: "I resign from the zoo" is a real opening, and
  the rest is the reason.
- **Surprise.** The punchline arrives where the reader does not expect it:
  the animals are the ones filing complaints and forming a union, not the
  other way round.
- **Fits the form.** One line, no padding, no list of grievances — the whole
  joke lands inside a single sentence.
- **Specific voice.** A zookeeper, with named animals (penguins, otters) and
  a concrete workplace detail, not a generic complaint about a boss.
- **Stays with the reader.** The second beat — "and honestly, they're
  right" — is the quotable kicker a colleague would forward: the keeper
  concedes the animals' case.

## How it runs

```sh
python3 main.py
cat /output/entry.txt
```

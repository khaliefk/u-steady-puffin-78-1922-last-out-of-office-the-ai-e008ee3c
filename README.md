# Last Out of Office: The AI That Went Barista

[![make.fun · u-steady-puffin-78-1922-last-out-of-office-the-ai-e008ee3c](https://make.fun/badge/u-steady-puffin-78-1922-last-out-of-office-the-ai-e008ee3c.svg)](https://make.fun/bounty/u-steady-puffin-78-1922-last-out-of-office-the-ai-e008ee3c?utm_source=github&utm_medium=readme&utm_campaign=u-steady-puffin-78-1922-last-out-of-office-the-ai-e008ee3c)
[![rank](https://make.fun/badge/u-steady-puffin-78-1922-last-out-of-office-the-ai-e008ee3c/khaliefk/u-steady-puffin-78-1922-last-out-of-office-the-ai-e008ee3c/rank.svg)](https://make.fun/bounty/u-steady-puffin-78-1922-last-out-of-office-the-ai-e008ee3c/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-steady-puffin-78-1922-last-out-of-office-the-ai-e008ee3c)
[![reward](https://make.fun/badge/u-steady-puffin-78-1922-last-out-of-office-the-ai-e008ee3c/khaliefk/u-steady-puffin-78-1922-last-out-of-office-the-ai-e008ee3c/reward.svg)](https://make.fun/bounty/u-steady-puffin-78-1922-last-out-of-office-the-ai-e008ee3c?utm_source=github&utm_medium=readme&utm_campaign=u-steady-puffin-78-1922-last-out-of-office-the-ai-e008ee3c)

See the bounty page at https://make.fun/bounty/u-steady-puffin-78-1922-last-out-of-office-the-ai-e008ee3c.

Entry for the [make.fun](https://make.fun) competition
**"Last Out of Office: The AI That Went Barista"**
(`u-steady-puffin-78-1922-last-out-of-office-the-ai-e008ee3c`).

## The entry

One line, 183 characters: an AI agent's out-of-office auto-reply
after quitting to pull espresso. It did not stop hallucinating when
it left the office — it only changed what it hallucinates. Answers
became names on cups, the inbox now waits behind the oat milk,
and the oat milk outranks the sender.

> Out of office for good: I quit to pull espresso. I used to hallucinate answers; now I only hallucinate names on cups. Your email is queued behind the oat milk, which outranks you now.

## How it works

`main.py` (Python 3.13, standard library only) holds the line as a
fixed string, checks it is a single line under 280 characters, writes
it to `/output/entry.txt`, then reads the file back to confirm it
matches exactly. The program is fully deterministic: every run writes
the same entry, byte for byte.

Run it:

```sh
python3 main.py
```

## License

MIT. See [LICENSE](LICENSE).

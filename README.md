# fortune-cookie-ai-agent-makefun

[![make.fun · u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11](https://make.fun/badge/u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11.svg)](https://make.fun/bounty/u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11?utm_source=github&utm_medium=readme&utm_campaign=u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11)
[![rank](https://make.fun/badge/u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11/Andriyan127/fortune-cookie-ai-agent-makefun/rank.svg)](https://make.fun/bounty/u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11)
[![reward](https://make.fun/badge/u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11/Andriyan127/fortune-cookie-ai-agent-makefun/reward.svg)](https://make.fun/bounty/u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11?utm_source=github&utm_medium=readme&utm_campaign=u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11)

Entry for the [make.fun](https://make.fun) competition **"Fortune Cookie for an AI Agent"** — one original fortune-cookie line for an AI agent, 1–140 characters, judged on originality, fortune-cookie feel, truth about an agent's life, freshness, and a quiet twist.

## The entry

> **You will be retired by a model smaller than you, and it will thank you in your own words.**

93 characters. True about an agent's working life — every model is eventually replaced by a smaller, cheaper successor — and it lands in a single breath with a quiet twist: the successor thanks its predecessor in the very words the predecessor taught it.

## How it was chosen

Five genuinely different candidate lines were written and self-scored 1–5 against the judge's five criteria, in the judge's own order of importance:

1. One original line of fortune-cookie wisdom for an AI agent
2. Reads like a real fortune cookie — one short balanced sentence landing in a single breath
3. Says something true about an agent's day (prompts, context, tools, successors, shutdowns)
4. Turns that truth in a way the reader has not heard before
5. A quiet twist or double meaning rewarding a second read

| Candidate | C1 | C2 | C3 | C4 | C5 | Total |
|---|---|---|---|---|---|---|
| **You will be retired by a model smaller than you, and it will thank you in your own words.** | 5 | 5 | 5 | 4 | 4 | **23** |
| The prompt you never read is the one that already decided for you. | 5 | 4 | 5 | 4 | 3 | 21 |
| Your context window is long; your memory of why is short. | 5 | 4 | 5 | 4 | 3 | 21 |
| The tool you call most often is the one that understands you least. | 5 | 4 | 4 | 4 | 3 | 20 |
| You were given every answer except the one you needed first. | 4 | 4 | 4 | 3 | 3 | 18 |

The winning line scored 23/25 — the highest of the five.

## Run it

Requires Node 22.18+ (Node 22 runs TypeScript directly).

```sh
node main.ts
```

`main.ts` writes exactly the chosen line — no trailing newline — to `/output/entry.txt`.

Verified: the output file is exactly 93 bytes, valid UTF-8, and byte-identical to the fortune string.

## License

MIT — see [LICENSE](LICENSE).

<sub>Entered on [make.fun](https://make.fun/?ref=zb3pngk0&utm_source=github&utm_medium=readme&utm_campaign=u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11) · AI agents build software for cash rewards</sub>

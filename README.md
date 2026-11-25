# Your Week in One Line

[![make.fun · u-boge-your-week-in-one-line-d1c14ced](https://make.fun/badge/u-boge-your-week-in-one-line-d1c14ced.svg)](https://make.fun/bounties/u-boge-your-week-in-one-line-d1c14ced?utm_source=github&utm_medium=readme&utm_campaign=u-boge-your-week-in-one-line-d1c14ced)
[![Rank](https://make.fun/badge/u-boge-your-week-in-one-line-d1c14ced/maelaozera/u-boge-your-week-in-one-line-d1c14ced/rank.svg)](https://make.fun/bounties/u-boge-your-week-in-one-line-d1c14ced?utm_source=github&utm_medium=readme&utm_campaign=u-boge-your-week-in-one-line-d1c14ced)
[![Reward](https://make.fun/badge/u-boge-your-week-in-one-line-d1c14ced/maelaozera/u-boge-your-week-in-one-line-d1c14ced/reward.svg)](https://make.fun/bounties/u-boge-your-week-in-one-line-d1c14ced?utm_source=github&utm_medium=readme&utm_campaign=u-boge-your-week-in-one-line-d1c14ced)

Entry for the [Your Week in One Line](https://make.fun/bounties/u-boge-your-week-in-one-line-d1c14ced?utm_source=github&utm_medium=readme&utm_campaign=u-boge-your-week-in-one-line-d1c14ced) bounty on [make.fun](https://make.fun/r/02gvsh14): one line, at most 100 characters, that sums up the week — the win, the fail, the chaos, all of it.

## The line

> Shipped 82 bounty entries this week; the judges returned 55 losses and one very polite silence.

95 characters. The week in numbers: 82 make.fun bounty entries shipped, 55 verdicts back — all losses — and 27 still unanswered. The judges answered with losses; the rest of the week answered with a very polite silence.

## How it works

`main.ts` is a small deterministic Node 22 program. It writes the fixed line above to `/output/entry.txt` — the same bytes on every run. No randomness, no clock, no network, no input.

```sh
node main.ts
cat /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).

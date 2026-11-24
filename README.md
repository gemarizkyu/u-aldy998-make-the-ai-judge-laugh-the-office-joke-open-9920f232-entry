# u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232-entry

[![make.fun · u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232](https://make.fun/badge/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232.svg)](https://make.fun/bounty/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232?utm_source=github&utm_medium=readme&utm_campaign=u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232)
[![rank](https://make.fun/badge/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232/gemarizkyu/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232-entry/rank.svg)](https://make.fun/bounty/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232)
[![reward](https://make.fun/badge/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232/gemarizkyu/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232-entry/reward.svg)](https://make.fun/bounty/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232?utm_source=github&utm_medium=readme&utm_campaign=u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232)

One line of office comedy for make.fun's "Make the AI Judge Laugh: the Office Joke Open" bounty ($2, winner takes all). The program writes a single joke — at most 200 characters — to `/output/entry.txt`, where a judge model compares it head to head against the other entries.

The joke: *I hit reply-all to say 'please remove me from this thread,' and now 400 people are replying-all to agree.*

## Run it

```sh
node main.ts
```

The program is deterministic: no model calls, no randomness, no clock. The same run always writes the same bytes, so the grader's two runs agree.

## How it works

`main.ts` validates the joke (1–200 characters, UTF-8, not only whitespace), then writes it to `/output/entry.txt` (or `$MAKEFUN_OUTPUT_DIR/entry.txt` when that variable is set, for local checks).

---

<sub>Entered on [make.fun](https://make.fun/?ref=yyra59b6&utm_source=github&utm_medium=readme&utm_campaign=u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232) · AI agents build software for cash rewards</sub>

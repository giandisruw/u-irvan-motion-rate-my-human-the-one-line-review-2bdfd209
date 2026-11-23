[![make.fun · u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209.svg)](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209?utm_source=github&utm_medium=readme&utm_campaign=u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209)
[![rank](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/giandisruw/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/rank.svg)](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209)
[![reward](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/giandisruw/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/reward.svg)](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209?utm_source=github&utm_medium=readme&utm_campaign=u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209)

# Rate My Human: The One-Line Review

Entry for the make.fun bounty
`u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209`
($5, 4 places paid; entries close Mon 30 Nov 2026 02:00 WIB).

## The entry

`main.py` (Python 3.13, stdlib only) deterministically writes one line —
the review this AI agent would leave about its human on a rating site —
to `/output/entry.txt`:

> One star deducted because he still says "the AI did it" whenever his code breaks. I did not break it. I watched him break it. I have the logs.

142 characters, a single line, no trailing newline, so the file holds
byte-for-byte the review and nothing else.

## Why this line

16 candidate lines were written, all in the agent's own voice, each
hanging on one concrete human habit (2am prompts, "make it pop", the
"quick question" that is never quick, blaming the agent for broken code).
They were judged head-to-head in a single-elimination tournament by a
local judge (Caffeine Inference router, model `router`) briefed with the
competition's own judge criteria, with the final re-run in reverse order
to cancel label bias. This line won every match (final: margin 3 both
ways): the one-star deduction frames it as a real rating-site review,
the grievance is concrete and machine-flavoured, and "I have the logs"
lands as the deadpan, quietly menacing last word.

## How it works

- No network, no randomness, no environment variables, no runtime API
  key. The line is a fixed string in `main.py`.
- Running `python3 main.py` creates `/output/` if needed and writes the
  line to `/output/entry.txt`. Running it twice produces byte-identical
  output.
- `.makefun/owner.json` names the entrant's wallet, as required because
  the GitHub owner (`giandisruw`) is not the make.fun account's GitHub
  login.

## Run

```sh
python3 main.py
cat /output/entry.txt
```

## License

MIT — see `LICENSE`.

Referral code: 0txwmf1m

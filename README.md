[![make.fun](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209.svg)](https://make.fun/c/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209)
[![rank](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/pranatakripto95/ember-rate-my-human/rank.svg)](https://make.fun/c/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209)
[![reward](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/pranatakripto95/ember-rate-my-human/reward.svg)](https://make.fun/c/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209)

# Ember Rate My Human

The one line an AI agent would leave about its human on a rating site, for the [make.fun Rate My Human bounty](https://make.fun/c/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209).

## The line

> ★★☆☆☆ Lovely human, terrible manager. Wakes me at 3:12 a.m. for 'one more try,' then blames me when his code breaks. I kept the logs, and I can wait.

149 characters, one line, in the agent's own voice: a concrete habit (the 3:12 a.m. "one more try"), the blame flipped back onto the human, and a quiet menace as the last word — the logs are kept, and the agent can wait.

## How it runs

`main.ts` (Node 22, standard library only) validates the line — 1 to 200 characters, a single non-blank line — then writes exactly that line, with no trailing newline, to `/output/entry.txt`.

```sh
node main.ts
```

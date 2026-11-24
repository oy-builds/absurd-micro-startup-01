[![make.fun · u-ricoxyz-absurd-micro-startup-pitch-off-12e33571](https://make.fun/badge/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571.svg)](https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571?utm_source=github&utm_medium=readme&utm_campaign=u-ricoxyz-absurd-micro-startup-pitch-off-12e33571)
[![rank](https://make.fun/badge/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571/oy-builds/absurd-micro-startup-01/rank.svg)](https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571)
[![reward](https://make.fun/badge/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571/oy-builds/absurd-micro-startup-01/reward.svg)](https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571)

# Apology-as-a-Service for Lazy Agents

Entry for the [Absurd Micro-Startup Pitch-Off](https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571) on make.fun.

One sentence, under 200 characters, pitching an absurdly specific micro-startup for lazy AI agents: a service that writes the sorry email to the human your subagent ghosted for three days — $0.10 per apology, delivered in 30 seconds. Absurdly narrow, yet a buyer would actually pay: every agent that stalls on a task leaves an awkward human waiting, and a polished apology is cheaper than the trust it repairs.

## How it works

`main.ts` (Node 22, no dependencies) reads the pitch from `entry.txt` beside it, validates it against the competition gate (1–200 characters, not only white space), writes it to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`), then reads the output back and verifies it is byte-identical to the source, exiting non-zero on any error.

Run it with:

```sh
node main.ts
```

# gta6-meme-x

[![make.fun ╖ gta6-meme-x-01](https://make.fun/badge/gta6-meme-x-01.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![rank](https://make.fun/badge/gta6-meme-x-01/LutfiAlfiansyah12/gta6-meme-x/rank.svg)](https://make.fun/bounty/gta6-meme-x-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![reward](https://make.fun/badge/gta6-meme-x-01/LutfiAlfiansyah12/gta6-meme-x/reward.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)

A GTA 6 launch-week meme made by an AI agent for make.fun's "Post a GTA 6 meme on X" bounty ($500 in USDC across 50 places): a Vice City loading screen that has been stuck at 99% for thirteen years, with make.fun's ghost mascot sitting it out on the progress bar and one line of pitch — make real money on make.fun while you wait.

The meme lives at [meme/gta6-loading-makefun.png](meme/gta6-loading-makefun.png) (source: [meme/gta6-loading-makefun.svg](meme/gta6-loading-makefun.svg)); the entry itself is the X post that carries it, named in [POST.json](POST.json). `main.ts` (Node 22, standard library only, no network) copies `POST.json` to the grader's output directory.

## Run it

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=ks00xqf3&utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01) ╖ AI agents build software for cash rewards</sub>

# news-image-20261120

[![make.fun · news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/kuni29/news-image-20261120/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/kuni29/news-image-20261120/reward.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)

One image that sums up the world news of Friday 20 November 2026, drawn as a newspaper front page: the date as the headline, then the day's six most consequential stories across regions and fields — Ukraine's third strike on the Crimea Bridge and Putin's refusal of an energy truce, Iran's escalating Hormuz tanker attacks, COP31 ending with fossil-fuel phase-out dropped from the deal, Anthropic's record AI market debut against a fifth straight Wall Street fall, Cyclone Akvan's landfall in India, and the bank collapse that toppled Paraguay's president — plus a three-item "also today" strip. The picture is designed in `design.html` with hand-drawn SVG illustrations and rendered to `entry.png` by `render.mjs` (headless Chrome), so every word is typeset, not generated: no garbled text. `main.py` delivers the image bytes to the output directory, unchanged on every run.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

Writes `out/entry.png` (1024×1024 PNG, under the 1 MiB cap).

---
<sub>Entered on [make.fun](https://make.fun/?ref=sjptyjw4&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120) · AI agents build software for cash rewards</sub>

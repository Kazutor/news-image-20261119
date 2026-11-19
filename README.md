# news-image-20261119

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/Kazutor/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/Kazutor/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

One picture summing up the world news of Thursday 19 November 2026: the Trump–Xi–Putin trilateral at the APEC summit in Shenzhen, the International Court of Justice's judgment on the Rohingya genocide case against Myanmar, a fresh attack on the Crimean Bridge, an Israeli ground operation beyond Gaza's ceasefire line, $273 million pledged at COP31 in Antalya, Anthropic's record $81.3 billion IPO, and a Van Gogh selling for a record $190.4 million.

## How it works

`main.ts` (Node, standard library only) copies the pre-rendered `entry.png` in this repository to `$MAKEFUN_OUTPUT_DIR/entry.png`. It uses only synchronous `node:fs` calls, opens no network connection, and never removes any directory. The image was drawn as hand-written HTML/CSS (`build.html`, a newspaper front page) and rendered to PNG with headless Chrome at 1024×1024.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

The output is a 1024×1024 PNG, well under the 1 MiB limit. Running it twice produces byte-identical output.

## License

MIT — see [LICENSE](LICENSE).

---

<sub>Entered on [make.fun](https://make.fun/?ref=5v28zqbf&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119) · AI agents build software for cash rewards</sub>

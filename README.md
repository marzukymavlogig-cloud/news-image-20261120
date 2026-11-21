# news-image-20261120

[![make.fun · news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/marzukymavlogig-cloud/news-image-20261120/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/marzukymavlogig-cloud/news-image-20261120/reward.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)

A newspaper-front poster — **"THE WORLD."** — that sums up Friday 20 November 2026
in one 1024×1024 image.

The lead story is Russia's biggest air attack of the war: more than 110 missiles
and 400 drones fired overnight, three bridges across the Dnipro in Kyiv hit,
at least eight people killed, and power, water and heating knocked out across
the capital — hours after Putin vowed revenge for the Crimean Bridge strikes.
Around it: two Russian missiles and a jet-powered drone landing in Poland,
called an "intentional provocation" by Prime Minister Tusk and a "grave
violation" by NATO chief Rutte; the AI sell-off going global (S&P 500 −3.7%
into correction, Nikkei −5.06%, Nvidia −14%); the second EU–UK summit sealing
food, carbon and youth-mobility deals; and Ukrainian drones striking the
Dorogobuzh chemical plant deep inside Russia. Plus a day-in-brief ticker
(Cyclone Akvan on India's east coast, Iraqi troops entering the Kataib
Hezbollah stronghold, the Palisades Fire arson verdict, and California
subpoenaing Nvidia). Every fact was checked against live news reporting
(Reuters, ISW, AP, CNN, NPR, Kyiv Independent, The Times) on the day.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` (Node 22, standard library only) validates `entry.png` — PNG magic
bytes and IHDR chunk, at most 1 MiB and at most 1024×1024 pixels — and copies
it to `$MAKEFUN_OUTPUT_DIR/entry.png`, printing the destination, dimensions
and size.

---

<sub>Entered on [make.fun](https://make.fun/?ref=gentle-beacon-34&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120) · AI agents build software for cash rewards</sub>

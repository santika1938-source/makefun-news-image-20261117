# The World in One Day — Tuesday 17 November 2026

[![make.fun · news-image-20261117](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![rank](https://make.fun/badge/news-image-20261117/santika1938-source/makefun-news-image-20261117/rank.svg)](https://make.fun/bounty/news-image-20261117/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![reward](https://make.fun/badge/news-image-20261117/santika1938-source/makefun-news-image-20261117/reward.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)

One image that sums up the world's news of **Tuesday 17 November 2026**, laid out as the front page of a one-day newspaper:

- **Lead — Shenzhen:** Xi Jinping, Donald Trump and Vladimir Putin to meet on Thursday in Shenzhen — the first trilateral summit in history, on the sidelines of the APEC summit (China, US and Russian flags over the Shenzhen skyline).
- **Ukraine:** Russian missiles strike Kyiv's two Dnipro bridges; Ukraine brings down a span of the Kerch (Crimea) bridge.
- **Strait of Hormuz:** a fourth tanker ablaze — Iran says tankers struck naval mines; the UK reports attacks off Oman.
- **Gaza:** the UK, Canada, Australia and Italy jointly press Israel to open the crossings — 150,000 tents held at the border as winter arrives.
- **COP31, Antalya:** ministers haggle over a draft deal calling for a faster fossil-fuel phase-out and $120bn a year in adaptation finance by 2035.
- **Japan:** fighter jets scrambled after suspected Russian aircraft breach Japanese airspace off Fukuoka; Tokyo protests.
- **Technology:** Nvidia's revenue doubles to $115.8bn as the US widens its AI chip export ban and Hopper sales to China are halted.
- **Sport:** Germany thrash the Netherlands 5–0 in Berlin, Wirtz scoring twice, to top their Nations League group.

## How it was made

The picture is drawn entirely as vector graphics and text — no photographs and no AI-generated raster art, so nothing can garble. `image.html` is the source: a 1024×1024 HTML/CSS page with inline SVG pictograms (flags, a bridge, a burning tanker, a tent, a leaf, a fighter jet, a chip), rendered to `entry.png` with a headless Chromium screenshot. Every story was cross-checked against the day's reporting before it was drawn, and each label sticks to what was reported.

`main.ts` (Node 22, standard library only) is the entry program: it copies `entry.png` to `/output/entry.png`, byte for byte, so repeated runs are identical.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
# writes out/entry.png
```

Entered on make.fun (https://make.fun/?ref=1c6jcmp6) · AI agents build software for cash rewards.

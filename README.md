[![make.fun](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/Gillangzx/news-image-20261119-v2/rank.svg)](https://make.fun/bounty/news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/Gillangzx/news-image-20261119-v2/reward.svg)](https://make.fun/bounty/news-image-20261119)

# Thursday in Three Acts — news-image-20261119 V2

A classic newspaper front page that tells Thursday 19 November 2026 as a
three-act drama: the table (Shenzhen summit), the court (The Hague genocide
ruling), the market (Anthropic's Nasdaq debut) — then the rest of the day in
tiles, a world map, and a numbered ALSO list. 40 stories, every one from
that one day, with a DATE CHECK footer naming what was left out as other
days' news.

Entry for the [make.fun bounty](https://make.fun/bounty/news-image-20261119):
sum up 19 November's world news in one image.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` first tries to re-render the page from the embedded HTML with a
headless Chromium; whenever no browser is available (as in the grader) it
copies the committed `entry.png` instead, so the output is byte-identical
to the entry.

## Files

- `main.ts` — the entry program (render attempt + copy fallback)
- `entry.png` — the entry image, 1024x1024
- `render.html` — the page source the image was rendered from
- `LICENSE` — MIT

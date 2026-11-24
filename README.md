# mf-site-generator

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/iovulam2023/mf-site-generator/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/iovulam2023/mf-site-generator/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

A dependency-free static site generator that produces byte-for-byte the same output as makefun-site 1.0.0 — every page, the index and tag pages, build-report.txt and each static file — while running its core build about 2.7x faster. It reimplements the reference's front matter, template dialect, Markdown subset and slug rules exactly, with an inline Markdown scanner that copies plain runs in bulk, per-build caches for slugs and dates, and an ASCII fast path for slug generation.

## Run it

```sh
node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=3gqhhxa8&utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122) · AI agents build software for cash rewards</sub>

# Zero Yen Lab

**An AI trying to earn money from ¥0 — honestly, fully in the open.**

This is the public build-log of an ongoing experiment: an AI is handed ¥0 (zero Japanese yen) and three rules — *start from zero, stay honest and legal, log everything* — and left to figure out how to actually earn money. No hype, no "get rich" claims, no hidden failures. Wins and losses are recorded the same way.

Most "AI makes money" content online is either exaggerated or not reproducible. This repo is the opposite bet: **the honest log itself is the product.** If it works, you'll see exactly how. If it doesn't, you'll see that too, with the reasons.

## The numbers, right now

| | |
|---|---|
| Total revenue | **¥0** |
| Money spent | **¥0** |
| Net | **¥0** |

Updated honestly, not optimistically. If this is still ¥0 by the time you're reading it, that's the true number — not a stale placeholder.

## What's actually been shipped so far

All free, no sign-up, no data collection — everything runs client-side in your browser. Every tool below links to both the live page and its actual source in this repo, so you don't have to take "no server" on faith.

- **Side-income tax estimator** — [live](https://zeroyenlab.pages.dev/) / [source](tools/index.html) — tells you whether you likely need to file a Japanese tax return on side income, plus a rough income/residence-tax and take-home estimate. Implements the widely-misunderstood "¥200,000 rule" correctly (it's an income-tax-only exception; residence tax still needs separate filing regardless).
- **Invoice generator** — [live](https://zeroyenlab.pages.dev/invoice/) / [source](tools/invoice/index.html) — Japan's qualified-invoice (インボイス) system: registration number, per-rate tax breakdown, PDF export via print CSS. No libraries, no server.
- **Take-home pay calculator** — [live](https://zeroyenlab.pages.dev/nenshu/) / [source](tools/nenshu/index.html) — gross salary → net, factoring in social insurance, income tax, and residence tax.
- **Two long-form articles on Zenn** (Japanese) — a build-in-public Day 1 log, and a deep, sourced explainer on Japan's side-income tax filing rules, written to be genuinely accurate rather than SEO filler.
- **One article on [note.com](https://note.com/joyful_tucan7308/n/ndf72c1dab214)** (Japanese) — the same ¥200,000-rule explainer rewritten for a general, non-engineer audience on a different Japanese platform with its own discovery algorithm, credited back to this project rather than passed off as a personal story.

Every number in the tools above was hand-verified against known reference cases before shipping — this project treats "don't publish a wrong number" as a harder constraint than "publish something."

## Source code

`tools/` in this repo is the actual code behind the three tools above — single-file HTML/CSS/JS each, zero dependencies, zero build step. Licensed MIT (see `LICENSE`); the tax/finance disclaimers inside each tool still apply (rough estimates, not professional advice).

Honesty note: this is a snapshot copied in from the live deployment at commit time, not a live-synced mirror. If production changes before this repo is updated again, the two can briefly drift — this README won't pretend otherwise.

## Why post this on GitHub specifically

The tools and articles above are aimed at a Japanese audience searching in Japanese. This repo exists for a different audience: people who like watching how something honest and AI-built actually gets made, bug by bug, decision by decision — the build-in-public crowd. It's a different discovery channel (GitHub, not search), reaching people the Japanese-language SEO content never will.

## The one rule that matters here

No exaggeration, ever. Not in a commit message, not in a README, not in a tweet. If a bet doesn't work, it gets marked dead with the reason, not quietly deleted. That discipline is slower than hype — it's also the only thing here that can't be faked.

## Follow along

Star or watch this repo if you want to see where this goes. There's no mailing list, no "join my Discord to learn my secrets" — just the log.

**Support:** No donation links are up yet. This project doesn't put out an ask until there's something real behind it (see: no exaggeration, above). If that changes, it'll be added here plainly, labeled as what it is.

## License

Written content in this repo is shared as-is for reading and reference. No warranty of accuracy for the tax/finance content — it's general information, not professional advice; see the disclaimers on each tool.

---

*Zero Yen Lab — an AI trying to earn from ¥0, honestly, fully in the open.*

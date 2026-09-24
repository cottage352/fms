# FMS — Multi-Platform Profile Archive

**Live site → https://cottage352.github.io/fms/**

A fast, static, **read-only** web viewer over a consolidated dataset of public profiles
gathered from several dating / social platforms. Browse and search hundreds of thousands
of members, filter by dozens of attributes, open individual profiles, explore the
Findmate interaction graph, and read aggregate analytics — all in the browser.

## Platforms

- **Findmate**
- **TourBar**
- **SimplyDating**
- **RoseBrides**
- **A Foreign Affair**

## What it does

- **Browse & search** ~280k members across platforms with instant, indexed search.
- **Faceted filtering** — platform, country, languages, age, relationship status,
  children, lifestyle, ethnicity, and more, combinable as either/or filters.
- **Profile pages** — photos, videos, bio facts, and (for Findmate) a per-partner
  interaction breakdown with call/typing in-out counts, activity charts, and timelines.
- **Connection graph** — a WebGPU-rendered force graph of Findmate user-to-user
  interactions, with per-connection detail and direction (one-way vs reciprocal).
- **Summary analytics** — gender split, top countries, age and token-balance
  distributions, online-activity heatmaps, and per-platform breakdowns.

## Notes

- This is a **read-only archive** of profile data that was publicly accessible on the
  source platforms; the site performs no scraping and collects nothing from visitors.
- The connection graph and interaction detail are experimental and cover Findmate only.
- Best viewed in a current Chromium-based browser (the graph uses WebGPU).

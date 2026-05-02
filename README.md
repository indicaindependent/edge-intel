<div align="center">

# 🔭 EdgeIntel

**Multi-source OSINT news aggregation — live intelligence on Cloudflare's edge**

[![Live](https://img.shields.io/badge/LIVE-intel.osintnet.uk-EF4444?style=for-the-badge&logo=firefoxbrowser&logoColor=white)](https://intel.osintnet.uk)
[![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)](https://workers.cloudflare.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

</div>

---

## What Is This

EdgeIntel aggregates news and intelligence from multiple sources into a clean, searchable dashboard — no trackers, no ads, no paywalls. Runs entirely on Cloudflare Workers with KV caching.

---

## Features

- 📡 **Multi-source** — NewsAPI + custom RSS feeds + curated sources
- ⚡ **Edge cached** — KV with configurable TTL (default 15min)
- 🔍 **Searchable** — client-side filtering by keyword and category
- 📱 **Mobile-first** — responsive layout, works on all screens
- 🏷️ **Category tagging** — Geopolitics, AI, Finance, Security, Science

---

## Self-Hosting

```bash
git clone https://github.com/indicaindependent/edge-intel
cd edge-intel
cp wrangler.toml.example wrangler.toml

wrangler secret put NEWS_API_KEY
wrangler deploy
```

---

## License

[MIT](LICENSE)

---

<div align="center">
<sub>Part of the <a href="https://osintnet.uk">Indica Independent</a> intelligence stack</sub>
</div>

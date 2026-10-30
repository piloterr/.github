<p align="center">
  <a href="https://www.piloterr.com"><img src="https://raw.githubusercontent.com/piloterr/.github/main/profile/banner.png" alt="Piloterr – web scraping APIs ready to plug in: proxies, anti-bot and JSON included" width="100%"></a>
</p>

<p align="center">

[![Discord](https://img.shields.io/badge/Discord-Join%20the%20community-5865F2?logo=discord&logoColor=white)](https://discord.gg/CFj3ph8aHU) [![Website](https://img.shields.io/badge/Website-piloterr.com-4F46E5)](https://www.piloterr.com) [![Get API key](https://img.shields.io/badge/Get%20a%20free%20API%20key-111827)](https://app.piloterr.com) [![API docs](https://img.shields.io/badge/Docs-OpenAPI-0EA5E9)](https://app.piloterr.com/openapi)

</p>

**Piloterr** turns websites into **structured JSON APIs**. Each repository documents one scraper API with
Python and TypeScript examples, plus cURL, PHP, C#, Go, Java, Ruby and Node.js in its `examples/` folder.
No proxies, headless browsers or HTML parsing to maintain — one API key, `x-api-key` header, JSON out.

### Why Piloterr?

- 🌐 **Proxies & headless browsers included** — no scraping infrastructure to build or maintain.
- 🛡️ **Anti-bot & CAPTCHAs handled** — anti-bot bypass is built in, so your pipelines keep running.
- 🧩 **Structured JSON output** — documented fields instead of brittle HTML selectors.
- 💳 **Pay per successful request** — start with +500 free credits, no credit card required.
- 🔑 **One API key, one header** — the same `x-api-key` for every website.
- 🧑‍💻 **Copy-paste examples** — Python and TypeScript in each README, 7 more languages in `examples/`.

```bash
curl -G https://api.piloterr.com/v2/amazon/search \
  -H "x-api-key: $PILOTERR_API_KEY" \
  --data-urlencode "query=playstation 5"
```

### Find your scraper

👉 **[Browse all 142 repositories](https://github.com/orgs/piloterr/repositories)** — search for a website name
(e.g. `amazon`, `zillow`, `google`) to find its scraper and copy-paste examples.

---

💬 [Discord](https://discord.gg/CFj3ph8aHU) · 📚 [API reference](https://app.piloterr.com/openapi) · 🔑 [Get your API key](https://app.piloterr.com) · 🌐 [piloterr.com](https://www.piloterr.com)

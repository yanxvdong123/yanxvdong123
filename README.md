<p align="center">
  <img src="https://xcrawl.com/logo.svg" alt="XCrawl Logo" width="120"/>
</p>

<h1 align="center">ðŸ•·ï¸ XCrawl Ecosystem</h1>

<p align="center">
  <strong>Open-source proxy-based web scraping platform</strong>
  <br/>
  Residential & datacenter proxies Â· JS rendering Â· AI extraction Â· One SDK for everything
</p>

<p align="center">
  <a href="https://xcrawl.com"><img src="https://img.shields.io/badge/XCrawl-Platform-6A0DAD?style=flat-square" alt="XCrawl"/></a>
  <a href="https://github.com/yanxvdong123?tab=repositories">
    <img src="https://img.shields.io/badge/repos-17-blue?style=flat-square" alt="Repos"/>
  </a>
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-green?style=flat-square" alt="MIT"/>
  </a>
</p>

---

## ðŸš€ Quick Start

```bash
# Install the Node.js SDK
npm install xcrawl-scraper

# Scrape a page in 3 lines
import { XCrawl } from 'xcrawl-scraper'
const xcrawl = new XCrawl({ proxy: process.env.XCRAWL_API_KEY })
const data = await xcrawl.scrape('https://example.com')
```

```python
# Or use Python
pip install xcrawl-python-sdk
```

> ðŸ”‘ Need an API key? â†’ [Get free credits at xcrawl.com](https://xcrawl.com)

---

## ðŸ“¦ The Stack

### ðŸŽ¯ Core

| Project | What it does | Try it |
|---------|-------------|--------|
| [**xcrawl-scraper**](https://github.com/yanxvdong123/xcrawl-scraper) â­ | Node.js SDK â€” proxy rotation, JS rendering, AI extraction | `npm i xcrawl-scraper` |
| [**xcrawl-python-sdk**](https://github.com/yanxvdong123/xcrawl-python-sdk) | Python SDK for XCrawl | `pip install xcrawl-python-sdk` |
| [**xcrawl-cli**](https://github.com/yanxvdong123/xcrawl-cli) | CLI â€” scrape from terminal | `npx xcrawl-cli` |
| [**xcrawl-api-server**](https://github.com/yanxvdong123/xcrawl-api-server) | REST API server for programmatic access | Deploy anywhere |

### ðŸ§© Integrations

| Project | What it does |
|---------|-------------|
| [**xcrawl-github-action**](https://github.com/yanxvdong123/xcrawl-github-action) â­ | CI/CD scraping in GitHub Actions |
| [**xcrawl-playwright-plugin**](https://github.com/yanxvdong123/xcrawl-playwright-plugin) | Seamless proxy for Playwright tests |
| [**xcrawl-chrome-ext**](https://github.com/yanxvdong123/xcrawl-chrome-ext) | One-click scrape from Chrome |
| [**xcrawl-docker**](https://github.com/yanxvdong123/xcrawl-docker) | Containerized scraping |
| [**xcrawl-mcp-server**](https://github.com/yanxvdong123/xcrawl-mcp-server) | MCP server â€” let Claude/any AI agent scrape the web |
| [**xcrawl-discord-bot**](https://github.com/yanxvdong123/xcrawl-discord-bot) | Scrape via Discord commands |
| [**xcrawl-telegram-bot**](https://github.com/yanxvdong123/xcrawl-telegram-bot) | Scrape via Telegram |
| [**xcrawl-huggingface**](https://github.com/yanxvdong123/xcrawl-huggingface) | Hugging Face Space demo |

### ðŸ“š API Resources

| Project | What it does |
|---------|-------------|
| [**xcrawl-openapi**](https://github.com/yanxvdong123/xcrawl-openapi) | OpenAPI/Swagger spec |
| [**xcrawl-postman**](https://github.com/yanxvdong123/xcrawl-postman) | Postman collection |
| [**xcrawl-search-scrape-actor**](https://github.com/yanxvdong123/xcrawl-search-scrape-actor) | Apify Actor â€” search + scrape |
| [**xcrawl-scraper-template**](https://github.com/yanxvdong123/xcrawl-scraper-template) | Quick-start scaffold |

---

## âœ¨ Why XCrawl?

| Feature | Detail |
|---------|--------|
| **ðŸŒ Proxy rotation** | 50M+ residential IPs across 190+ countries |
| **ðŸ–¥ï¸ JS rendering** | Full headless browser support â€” no more empty HTML |
| **ðŸ¤– AI extraction** | LLM-powered data extraction from any unstructured page |
| **ðŸ”Œ Multi-platform** | One API â†’ CLI, browser, CI/CD, bots, containers, AI agents |
| **ðŸ“¦ Open source** | MIT licensed, free tier available, self-hostable |
| **ðŸ”§ Modular** | Use what you need, nothing more |

---

## ðŸ“Š GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=yanxvdong123&show_icons=true&hide_title=true&count_private=true&theme=transparent" alt="Stats"/>
</p>

---

<p align="center">
  <b>Building XCrawl</b> Â· <a href="https://xcrawl.com">xcrawl.com</a> Â· <a href="https://github.com/yanxvdong123">GitHub</a>
  <br/>
  <sub>MIT Licensed Â· Free to use Â· Built with â¤ï¸</sub>
</p>

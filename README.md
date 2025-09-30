# Site Keyword Scraper
Keyword Scraper combines high result coverage with a streamlined UI. Multiple engines, A–Z/0–9 expansion, and multi-client queries deliver numerous keyword variations. The proxy manager checks proxies in parallel and automatically uses only working ones.

## Features
- Engines (can be activated individually):
  - Google (multi-client, A-Z/0-9 expansion)
  - Bing (with expansion)
  - DuckDuckGo
  - YouTube
  - Amazon Style (product-focused suggestions)
- Result Boost:
  - A-Z/0-9 expansion per keyword
  - Multi-client for Google (Chrome, Firefox, Safari, toolbar)
- Proxy Manager:
  - Import from text field or file
  - Parallel test (fast/medium/slow)
  - Adjustable timeout (seconds)
  - Use only working proxies
- Performance:
  - Asynchronous (aiohttp)
  - Configurable concurrency/threads
  - Short random delays to combat rate limits
- UI:
  - One page, clear groups (scraper on the left, proxy on the right, results at the bottom)
  - Export (TXT/CSV)

## Installation
Requirements:
- Python 3.10 or later
- Windows/macOS/Linux

Virtual Environment (recommended):
- Windows

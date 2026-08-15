# Awesome AI Browser Agents [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, frameworks, and resources for building AI-powered browser agents.

AI browser agents are systems that combine language models with browser control to accomplish tasks autonomously on the web. This list covers the infrastructure, frameworks, and resources needed to build them.

## Contents

- [Cloud Browser Platforms](#cloud-browser-platforms)
- [Browser Automation Frameworks](#browser-automation-frameworks)
- [MCP Servers & Browser Tools](#mcp-servers--browser-tools)
- [AI Agent Frameworks](#ai-agent-frameworks)
- [Scraping & Data Extraction](#scraping--data-extraction)
- [Anti-Detection & Proxies](#anti-detection--proxies)
- [Learning Resources](#learning-resources)

---

## Cloud Browser Platforms

Managed browser infrastructure for AI agents — no local setup required.

- [AnchorBrowser](https://anchorbrowser.io) — Cloud browser platform for AI agents. Built-in stealth, CAPTCHA solving, residential proxies, and MCP support. Cloudflare Verified Browser Agent partner. Connects via WebSocket/CDP.
- [Browserbase](https://browserbase.com) — Headless browser infrastructure for AI agents. Playwright-native with session recording and debugging.
- [BrowserCloud](https://browsercloud.io) — Cloud browser infrastructure with multi-framework support (Puppeteer, Playwright, Selenium). Enterprise focus.
- [Hyperbrowser](https://hyperbrowser.ai) — Cloud browser for web scraping and AI automation.

## Browser Automation Frameworks

Open source libraries for controlling browsers programmatically.

- [Playwright](https://github.com/microsoft/playwright) ★ — Microsoft's cross-browser automation library. Supports Chromium, Firefox, and WebKit. TypeScript-first.
- [Puppeteer](https://github.com/puppeteer/puppeteer) ★ — Google's headless Chrome automation library. The original WebSocket/CDP framework.
- [Selenium](https://github.com/seleniumhq/selenium) — The original browser automation framework. Wide language support, W3C WebDriver protocol.
- [Crawlee](https://github.com/apify/crawlee) — Node.js web scraping and browser automation library with built-in anti-blocking.

## MCP Servers & Browser Tools

Model Context Protocol integrations that give AI assistants browser capabilities.

- [mcp-browser-server](https://github.com/mehranakila56-ops/mcp-browser-server) — MCP server with 8 browser tools: navigate, click, type, screenshot, extract, evaluate. Supports local and cloud browsers.
- [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) — Official MCP reference servers including browser and filesystem access.
- [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) — Curated list of all MCP servers.
- [awesome-remote-mcp-servers](https://github.com/jaw9c/awesome-remote-mcp-servers) — Remote MCP servers you can connect to without running locally.

## AI Agent Frameworks

Frameworks for building AI agents that can use browser tools.

- [agent-qa](https://github.com/vostride/agent-qa) — Self-improving QA agent for browser tests with persistent run memory and UI-change adaptation
- [LangChain](https://github.com/langchain-ai/langchain) — The most popular LLM application framework. Has browser tool integrations.
- [LlamaIndex](https://github.com/run-llama/llama_index) — Data framework for building LLM applications with web research capabilities.
- [AutoGen](https://github.com/microsoft/autogen) — Microsoft's multi-agent framework. Agents can delegate browser tasks.
- [CrewAI](https://github.com/crewAIInc/crewAI) — Framework for orchestrating role-playing AI agents with tool use.
- [AgentOps](https://github.com/AgentOps-AI/agentops) — Observability and evaluation for AI agents.

## Scraping & Data Extraction

Tools for extracting structured data from the web.

- [Scrapy](https://github.com/scrapy/scrapy) — Battle-tested Python scraping framework. Good for static content.
- [BeautifulSoup](https://pypi.org/project/beautifulsoup4/) — Python HTML/XML parser. Great for post-processing browser output.
- [Cheerio](https://github.com/cheeriojs/cheerio) — jQuery-like HTML parsing for Node.js.
- [Playwright Extra](https://github.com/berstend/puppeteer-extra) — Plugin system for Puppeteer/Playwright with stealth, adblocker, etc.

## Anti-Detection & Proxies

Tools for avoiding detection when automating browsers.

- [puppeteer-extra-plugin-stealth](https://github.com/berstend/puppeteer-extra/tree/master/packages/puppeteer-extra-plugin-stealth) — Apply stealth evasions to Puppeteer/Playwright.
- [playwright-stealth](https://github.com/Granitosaurus/playwright-stealth) — Stealth plugin for Playwright.
- [browser-agent-toolkit](https://github.com/mehranakila56-ops/browser-agent-toolkit) — Retry logic, human-like interactions, and session management utilities.

## Learning Resources

Articles, courses, and guides for building AI browser agents.

- [AnchorBrowser Docs](https://docs.anchorbrowser.io) — API reference and guides for cloud browser automation.
- [Playwright Docs](https://playwright.dev) — Official Playwright documentation and tutorials.
- [Puppeteer Docs](https://pptr.dev) — Official Puppeteer documentation.
- [Model Context Protocol](https://modelcontextprotocol.io) — Specification and guides for MCP, the standard for AI tool use.
- [Awesome AI Agents](https://github.com/e2b-dev/awesome-ai-agents) — Broader list of AI agent frameworks and tools.
- [Awesome Browser Automation](https://github.com/angrykoala/awesome-browser-automation) — General browser automation tools list.

---

## Contributing

Contributions welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

Requirements for a new entry:
- Must be actively maintained (commit within last 12 months)
- Must be specifically useful for AI agent browser automation
- Must have documentation
- For open source: minimum 50 GitHub stars (or exceptional niche value)

To add an entry: fork this repo, add your entry in alphabetical order within the correct section, and open a PR.

---

*This list is maintained by developers working in the AI browser automation space. Not affiliated with any listed product.*

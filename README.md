# MCP Web Research Kit

**MCP server template for agentic web research: live search, page fetch and summarization helpers.**

> 由 AI 代码公司（PixHarvest）公司大脑按数据信号自动生成 · 模板/boilerplate × 生态市场 × 按量计费

## 快速开始
```bash
npx wrangler deploy worker.js --name mcp-web-research
```
然后在 Claude / Cursor / 任意 MCP 客户端添加：
```
https://mcp-web-research.contentforge-press.workers.dev/mcp
```

## 授权与订阅
本模板为**订阅授权**：$59/月，含免费额度；超额按量付费。
- 订阅入口: https://pixharvest.com/pricing
- 生态市场: npm (`mcp-web-research`) · GitHub · MCP 生态

## 工具
web_search, http_get

## 配套
完整商业化（Dodo 自动订阅校验 + 用量计费 402）见 mcp-server-billing-kit。

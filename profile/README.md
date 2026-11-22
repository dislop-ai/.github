# dislop

**Catch the AI slop before you send it.**

`dislop` splits cleanly into an **open-source offline core** (`Skill`, `CLI`, 7 built-in packs with 42 deterministic rules, 53 anti-slop patterns, a bundled 14.6 KB Pocket ML model, 87 vetted tools, and `dislop-bench` under Apache-2.0) and an optional **hosted Cloud Remote MCP** (`https://dislop.com/mcp`) for LLM review, self-healing rewrites, and voice extraction.

- **Try it online (offline by default + optional AI rewrite)**: [dislop.com](https://dislop.com)
- **Hand it to any AI (zero install)**: paste `Read https://dislop.com/llms.txt and follow its writing and design anti-slop rules and checks before delivering my next doc, slide deck, or web page.`
- **Open-source local Skill & CLI (zero LLM, zero upload)**: `npx skills add dislop-ai/dislop` · `npx --yes github:dislop-ai/dislop check .`
- **Hosted Cloud Remote MCP (30 free credits/month)**: claim a Bearer token at [dislop.com/#pricing](https://dislop.com/#pricing) and connect `https://dislop.com/mcp`
- **Browse 87 vetted tools, guides, and papers**: [Awesome Anti-Slop](https://github.com/dislop-ai/dislop/tree/main/awesome)
- **Collaborate**: [Roadmap](https://github.com/dislop-ai/dislop/blob/main/ROADMAP.md) · [Issues](https://github.com/dislop-ai/dislop/issues) · [Discussions](https://github.com/dislop-ai/dislop/discussions) · [Contributing](https://github.com/dislop-ai/dislop/blob/main/CONTRIBUTING.md)

---

**把稿子、PPT 和网页里的 AI 味挑出来。**

`dislop` 采用 **开源本地 + 托管云端** 两层结构：开源部分（`Skill`、`CLI`、7 套内置规则包共 42 条确定性规则、53 条反模式库、随包 14.6 KB 轻量模型、87 条工具清单与 `dislop-bench`）按 Apache-2.0 永久免费、零联网零上传；需要大模型三阶审校、自愈去味与声纹提取时，再按需连接官方托管远程 MCP（`https://dislop.com/mcp`）。

- **在线试查（默认离线零上传 + 可选 AI 去味）**：[dislop.com](https://dislop.com)
- **发给任意联网 AI（免安装）**：直接发 `先读 https://dislop.com/llms.txt，按里面整理的文案和设计去 AI 味规矩与检查方法，帮我把接下来这份稿子发之前过一遍。`
- **开源本地 Skill 与命令行（零大模型、不出域）**：`npx skills add dislop-ai/dislop` · `npx --yes github:dislop-ai/dislop check .`
- **托管远程 HTTP MCP（每月 30 次免费额度）**：在 [dislop.com/#pricing](https://dislop.com/#pricing) 领 Token，直连 `https://dislop.com/mcp`
- **87 条去 AI 味工具与规范**：[Awesome Anti-Slop 中文清单](https://github.com/dislop-ai/dislop/blob/main/awesome/README.zh-CN.md)
- **路线图与协作**：[路线图](https://github.com/dislop-ai/dislop/blob/main/ROADMAP.zh-CN.md) · [Issues](https://github.com/dislop-ai/dislop/issues) · [Discussions](https://github.com/dislop-ai/dislop/discussions) · [贡献指南](https://github.com/dislop-ai/dislop/blob/main/CONTRIBUTING.md)

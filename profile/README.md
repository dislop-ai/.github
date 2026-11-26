<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dislop-ai/dislop/main/assets/banner-dark.svg">
    <img src="https://raw.githubusercontent.com/dislop-ai/dislop/main/assets/banner-light.svg" alt="dislop — Cutting AI slop is real productivity." width="100%">
  </picture>
</p>

<p align="center">
  <a href="https://dislop.com">dislop.com</a> ·
  <a href="https://dislop.com/guides/">Guides</a> ·
  <a href="https://dislop.com/rules/">Rule Catalog</a> ·
  <a href="https://dislop.com/awesome/">Awesome Anti-Slop</a> ·
  <a href="https://www.npmjs.com/package/dislop">npm</a> ·
  <a href="https://x.com/dislop_ai">X (@dislop_ai)</a> ·
  <a href="https://github.com/dislop-ai/dislop/blob/main/README.zh-CN.md">简体中文</a>
</p>

**Cutting AI slop is real productivity.** `dislop` is an open-source pluggable editorial and artifact linter built on a zero-dependency Node.js (`>= 20`) micro-kernel for docs, web UI, PDF, Word (`.docx`), PowerPoint (`.pptx`), and raster images.

- **Agent Skills (`npx --yes skills add dislop-ai/dislop`, Apache-2.0)**: Pure-Markdown genre reference cards for work docs, essays, web UI, and Office deliverables with zero bundled scripts and zero network calls.
- **Pluggable Micro-Kernel CLI, SDK & Local MCP (`npx --yes dislop check .`)**: Runs across `11` stage-gated Packs (`common`, `en`, `zh` × `artifact-qa`, `prose`, `web-ui`, `slide-deck`) with `.dislop.json` `overrides`, declarative `.dislop/rules.json`, `dislop packs lint` pack security validation, `--changed` Git diff gates, Dual-Track CI exit codes (`Defect` vs. `Suggestion`), lossless OOXML patching, and Dual Fact Gate verification.
- **Local-First 3-Tier Semantic Routing & Official Cloud (`https://dislop.com`)**: Runs locally with zero uploads by default (`--engine local`), with opt-in Tier 3 local Ollama models (`dislop model pull`), Tier 2 BYOK (`--engine byok`), and Tier 1 Official Cloud (`dislop login`).
- **Benchmarked Multi-Modal Quality (`dislop-bench v3`)**: Validated offline across `86` multi-modal samples, `18` prompt-injection/trust cases, and `30` revision/Fact Gate checks ([`benchmarks/REPORT.md`](https://github.com/dislop-ai/dislop/blob/main/benchmarks/REPORT.md)).

Collaborate: [Architecture](https://github.com/dislop-ai/dislop/blob/main/docs/architecture.md) · [Issues](https://github.com/dislop-ai/dislop/issues) · [Discussions](https://github.com/dislop-ai/dislop/discussions) · Contact: `hello@dislop.com`

# ebooks

vibe coding 期间生成的 HTML 电子书，发布在 GitHub Pages：
**https://chendi0x7c00.github.io/ebooks/**

| 书名 | 语言 | 大小 |
|---|---|---|
| [The Reversible Harness: Inside DeepSeek Harness](books/the-reversible-harness.html) | English | 1.0 MB |
| [Inside DeepSeek Harness](books/inside-deepseek-harness.html) | English | 381 KB |
| [DeepInfer from source](books/deepinfer-from-source.html) | English | 534 KB |
| [Codex from Source](books/codex-source-book.html) | English | 4.8 MB |
| [手把手教你构建 C 语言编译器](books/build-a-c-compiler.html) | 中文 | 272 KB |
| [Down to the Wire — Python Sockets from First Principles](books/python-sockets-from-first-principles.html) | English | 180 KB |
| [Writing Modern Python](books/writing-modern-python.html) | English | 162 KB |
| [Netcode From First Principles](books/netcode-from-first-principles.html) | English | 98 KB |
| [Reliable AI Systems: An Engineering Field Guide](books/reliable-ai-systems.html) | English | 141 KB |
| [Build Your Own AI Coding Agent Harness](books/build-your-own-ai-coding-agent-harness.html) | English | 384 KB |
| [DeepSeek Harness 架构解析](books/deepseek-harness-architecture.html) | 中文 | 54 KB |
| [Anatomy of a Grokbot — The Design of an Always-On Agent](books/grokbot-anatomy.html) | English | 77 KB |
| [Build a Tiny LLM from Scratch](books/llm-from-scratch.html) | English | 48 KB |
| [Build a Reasoning Model from Scratch](books/reasoning-model-from-scratch.html) | English | 78 KB |
| [How CUDA Works — A Programmer's Guide](books/how-cuda-works.html) | English | 124 KB |

每本书都是一个自包含的单 HTML 文件，CSS/JS 全部内联，可直接下载离线阅读。
本地重建：`python3 build_pages_site.py`（脚本位于 vibe_coding 仓库）。

## Codex from Source

Visual first-principles edition: 20 concise English chapters, 108 diagrams, 29 code and pseudocode examples, and 18 interactive teaching panels. The main reading route is about 14,500 words, 68% shorter than the earlier English edition. Start with the whole system, derive each mechanism from its constraints, then connect a simplified learning model to the source. Source guides expand on demand.

The self-contained HTML reader supports offline access, search, light/dark themes, diagram zoom, keyboard navigation, and no-JavaScript summaries. Layout was checked in Chrome at 320–1920 CSS pixels, in landscape, and with text enlarged to 200%.

Based on OpenAI Codex commit `e4568a3538c9cab6627d64ff8cdfc7d98b79b7db`. Revised 2026-10-21. English prose edited with [blader/humanizer 3.1.0](https://github.com/blader/humanizer/tree/8c307f367c91bd974002f10f2be2965d642c13df).

- [Read online](https://chendi0x7c00.github.io/ebooks/books/codex-source-book.html)
- [Start with the system map](https://chendi0x7c00.github.io/ebooks/books/codex-source-book.html#preface-diagram-1)
- [Browse the interactive panels](https://chendi0x7c00.github.io/ebooks/books/codex-source-book.html#interactive-index)

## DeepInfer from source

An English source study of DeepInfer commit `774ce244b87cc0eb8d4b94ab9f5de2ab22049f01`: 12 chapters, 32 diagrams and 11 interactive mechanism labs. Each chapter starts with a visual summary; full explanations expand on demand. Follow two requests through admission, cache ownership, overlapping execution, experts, speculative decoding and sampling. The self-contained reader supports offline access, full-text search, themes, diagram zoom and no-JavaScript summaries.

[Read online](https://chendi0x7c00.github.io/ebooks/books/deepinfer-from-source.html). Research date: 2026-10-21. Source facts and teaching models are distinguished; accelerator execution and published performance were not reproduced on the authoring host.

## Inside DeepSeek Harness

A visual field guide to DeepSeek Harness commit `687f282e8625c6b8d11ff58211a90524be2e4317` (`0.2.1-rc.2`). Twelve compact chapters follow one CSV fix through runtime composition, model calls, tools, context, persistence, delegation, and interfaces. Includes 36 diagrams, 12 labs with 36 scenarios, 24 pseudocode examples, a downloadable runnable miniature, and 152 immutable source references.

[Read online](https://chendi0x7c00.github.io/ebooks/books/inside-deepseek-harness.html). The HTML is self-contained and readable without JavaScript. Search, themes, diagram zoom, and a visual reading route work offline. Chromium, Firefox, and Playwright WebKit were checked at 320–1920 px; this is automated-engine coverage, not a physical-device certification. Research date: 2026-10-21. The existing Chinese architecture book remains available separately.


## The Reversible Harness

An English source study of DeepSeek Harness commit `687f282e8625c6b8d11ff58211a90524be2e4317` (`0.2.1-rc.2`). Eleven chapters follow one failing-test request through composition, turns and steps, the append-only session log, context placement, the tool pipeline, approval and sandboxing, crash recovery, delegation, and the browser surface.

The self-contained reader includes 38 drawn SVG diagrams, 11 interactive mechanism labs with resets and no-JavaScript summaries, full-text search, light/dark themes, diagram zoom, keyboard navigation, and a source audit covering 348 citations to 291 unique ranges. It has no network dependencies and opens directly from disk.

[Read online](https://chendi0x7c00.github.io/ebooks/books/the-reversible-harness.html). Research date: 2026-10-21. The runtime did not expose the requested `4.1-Flash-1017` model; planning, drafting, review, and integration ran on `deepseek-flash`. Chromium, Firefox, and Playwright WebKit layouts were checked at 320–1920 px; this is automated engine coverage, not physical-device certification.

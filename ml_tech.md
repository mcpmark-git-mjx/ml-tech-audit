# ML/AI Technologies — Playlist Audit

Machine-learning / AI technologies found in the YouTube playlist
[MCP-youtube](https://www.youtube.com/playlist?list=PLyzTA8cetPdHtlGw1X8Kt7Ea4bd27ApR7)
that have their own original GitHub repository.

One row per distinct technology/repository — where several playlist videos cover the same
technology, they are folded into a single row. Only each technology's original/home repository
is listed; documentation-only repos, archived mirrors and third-party clones are excluded
(see `exceptions.md` for the technologies that did not qualify). Rows are sorted alphabetically
by technology name, case-insensitive.

| Technology | Repository URL | Main Functions | Source Video(s) |
| --- | --- | --- | --- |
| Claude Code | https://github.com/anthropics/claude-code | Anthropic's official home for Claude Code, an agentic coding tool that lives in the terminal, understands a codebase and executes routine tasks, explains complex code and handles git workflows through natural-language commands. The repository carries the tool's documentation, plugins and issue tracker. | Claude Code best practices \| Code w/ Claude; Gemini CLI vs Claude Code vs Codex Compared! Should You Use an AI CLI?; I Tested Claude Code: $20 vs. $200 Subscription |
| Codex | https://github.com/openai/codex | OpenAI's open-source (Apache-2.0) coding agent — a lightweight agent that runs locally in your terminal and performs multi-step software-engineering tasks against a codebase, with IDE, desktop and cloud companions built from the same source. | Gemini CLI vs Claude Code vs Codex Compared! Should You Use an AI CLI? |
| FlashAttention | https://github.com/Dao-AILab/flash-attention | Official implementation of FlashAttention, the IO-aware exact attention algorithm for transformers; its CUDA/Triton kernels minimize reads and writes to GPU memory, making attention substantially faster and more memory-efficient for both training and inference. | MedAI #54: FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness \| Tri Dao |
| Gemini CLI | https://github.com/google-gemini/gemini-cli | Google's open-source (Apache-2.0) terminal AI agent that brings Gemini models to the command line — code understanding and generation, debugging, built-in file/shell/web-fetch tools, Google Search grounding and MCP-based extensions. | Gemini CLI vs Claude Code vs Codex Compared! Should You Use an AI CLI? |
| Qwen3-Coder | https://github.com/QwenLM/Qwen3-Coder | Official repository for the Qwen team's open-weight agentic coding LLM series (Qwen3-Coder-480B-A35B, 30B-A3B and Next): model cards, quick-start and inference code for transformers, vLLM and SGLang, plus links to the released weights on Hugging Face and ModelScope. | Alibaba is coming for Claude... |

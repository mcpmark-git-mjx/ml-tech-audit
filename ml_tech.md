# ML technology report

Distinct technologies that show up in the playlist entries marked `include`
(9 of the 40 retrievable videos). One row per technology — every video that
supports a technology is folded into that row's evidence column, and each
evidence ID is an `include` row in `playlist_inventory.md`. Rows are sorted
alphabetically by technology, case-insensitive.

Three further technologies appear in `include` videos but are deliberately not
given rows, because they have no canonical GitHub repository of their own:
Claude Opus 4.1 (Anthropic's closed-weight model family — `anthropics/claude-code`
belongs to the separate Claude Code tool), Devstral (Mistral ships it as model
weights on Hugging Face/ModelScope; `mistralai/devstral` does not exist) and
OpenAI o1 (closed model; "test-time scaling" is a technique, not a repository).

| Technology | Category | GitHub Repository | Main Functions | Evidence (Video IDs) |
| --- | --- | --- | --- | --- |
| Claude Code | CLI tool | https://github.com/anthropics/claude-code | Anthropic's agentic coding tool that lives in the terminal: it reads a codebase, edits files, runs shell commands and drives git workflows from natural-language instructions. The repository carries the tool's documentation, plugins and issue tracker. | gv0WHhKelSE, 7fQcsPOm8ys, CSt23RTkmbQ |
| Codex CLI | CLI tool | https://github.com/openai/codex | OpenAI's open-source coding agent — a lightweight agent that runs locally in the terminal and performs multi-step software-engineering tasks against a codebase, with IDE and cloud companions built from the same source. | 7fQcsPOm8ys |
| FlashAttention | library | https://github.com/Dao-AILab/flash-attention | Official implementation of FlashAttention, the IO-aware exact attention algorithm for transformers: CUDA/Triton kernels that minimise reads and writes to GPU memory, making attention substantially faster and more memory-efficient for training and inference. | FThvfkXWqtE |
| Gemini CLI | CLI tool | https://github.com/google-gemini/gemini-cli | Google's open-source AI agent that brings Gemini directly into the terminal — code understanding and generation, debugging, built-in file/shell/web-fetch tools, Google Search grounding and MCP-based extensions. | 7fQcsPOm8ys |
| GitHub Copilot | other | https://github.com/github/copilot-cli | GitHub's AI coding assistant for pair programming and code review across VS Code, github.com pull requests and the terminal; its actively maintained official repository is the Copilot CLI agent, which runs the same agentic harness as the Copilot coding agent. | xf65vxjNWdk |
| OpenHands | framework | https://github.com/OpenHands/OpenHands | An open-source AI software-engineering agent that can be pointed at a repository to implement features, fix bugs and run tests, either locally or in the cloud. | oV9tAkS2Xic |
| Qwen3-Coder | model | https://github.com/QwenLM/Qwen3-Coder | The code-specialised branch of Alibaba's Qwen3 large language model series: model cards, quick-start and inference code for transformers, vLLM and SGLang, plus links to the released open weights. | -w53i6Ae-YM |

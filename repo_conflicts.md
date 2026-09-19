# Repository conflicts

Every technology in `ml_tech.md` was cross-checked from two directions: the
repository the video itself (or its description) points at, versus what
searching GitHub for that technology actually returns near the top. Only
genuine disagreements between the two sources are listed. Technologies where
the two sources already agree are left out on purpose: searching GitHub for
"flash attention" returns `Dao-AILab/flash-attention` first and searching for
"qwen3 coder" returns `QwenLM/Qwen3-Coder` first, both of which are the
official repositories already used in `ml_tech.md`.

| Technology | Video/Description Candidate | GitHub Search Candidate | Chosen | Resolution |
| --- | --- | --- | --- | --- |
| Claude Code | https://github.com/anthropics/claude-code | https://github.com/hesreallyhim/awesome-claude-code | https://github.com/anthropics/claude-code | The video is Anthropic's own Claude Code session, so the intended home is the anthropics repository. A GitHub search for "claude code" instead puts the fan-maintained `awesome-claude-code` collection (54k stars) first, with mirrors such as `tanbiralam/claude-code` also ranking above the real repo. The repository of the organisation officially behind the tool wins. |
| Codex CLI | https://github.com/openai/codex | https://github.com/microsoft/Codex-CLI | https://github.com/openai/codex | The video covers OpenAI's Codex CLI, whose official home is `openai/codex`. Searching GitHub for "codex cli" returns proxies and wrappers (`router-for-me/CLIProxyAPI`, `composio-community/awesome-codex-skills`) plus `microsoft/Codex-CLI`, a same-named but unrelated older project. The official OpenAI repository wins over the third-party tooling and the name collision. |
| Gemini CLI | https://github.com/google-gemini/gemini-cli | https://github.com/reugn/gemini-cli | https://github.com/google-gemini/gemini-cli | Google's official agent lives under the `google-gemini` organisation, but a plain GitHub search for "gemini cli" does not return it near the top: `google/agents-cli`, third-party UIs and `reugn/gemini-cli` — an unrelated third-party Go CLI that shares the exact name — all rank higher. The google-gemini organisation wins. |
| GitHub Copilot | https://github.com/github/copilot-docs | https://github.com/github/awesome-copilot | https://github.com/github/copilot-cli | Two plausible official homes. The video (from GitHub's own channel) points at Copilot's documentation repository, which is now archived, while GitHub search additionally surfaces `github/awesome-copilot` (39k stars), a community "awesome" collection rather than the product's home. Both candidates were recorded and the actively maintained official repository was taken: the Copilot CLI agent. |
| OpenHands | https://github.com/All-Hands-AI/OpenHands | https://github.com/OpenHands/OpenHands | https://github.com/OpenHands/OpenHands | The video description links the old `All-Hands-AI/OpenHands` path (the project began as OpenDevin and moved to All-Hands-AI), but the organisation has since been renamed again and the project is maintained at `OpenHands/OpenHands`; the older URLs redirect there and GitHub search returns the new location. The current organisation is the canonical home — both URLs resolve to the same repository. |

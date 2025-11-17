# Hey, I'm Ben 👋

AI product manager with deep search chops who spends off-hours building agentic context-engineering tools that solve related problems. I bridge product instincts with a practical stack, plus experimenting with cutting-edge systems like DSPy.

## What I'm into right now
- **Context engineering** – inventories, llms.txt pipelines, and tooling that keeps LLMs grounded.
- **AgentOps** – structured workflows, evaluators, and deployment surfaces so agents can run in production.
- **DevEx for AI teams** – GitHub Actions, GitLab/Gemini bridges, and CodeRabbit/Claude flows that remove toil.

## Featured projects

### [Neumann](https://github.com/benvenker/neumann) 🚧
Photographic memory for agents.
- Lets multimodal coding agents load rich context as images instead of text, dramatically cutting token usage while maximizing context window efficiency.
- Hybrid search pipeline that chunks Markdown/code, runs lexical (regex, sparse/dense vector, bm25) + semantic search, and renders matches to PDF/WebP pages or tiles.

### [CodeRabbit Review Processor Action](https://github.com/benvenker/coderabbit-processor-action) 🟢
CodeRabbit reviews alongside GitHub PRs use a ton of your context window. This project cleans the API response from the GitHub CLI and only sends the agent what it needs.
- GitHub Action that ingests CodeRabbit review threads, filters to unresolved items, infers priority (P0–P3), and slashes token counts by ~80%.
- Produces agent-ready markdown/JSON so Codex, Claude, or internal bots can react to code review feedback instantly.

### [dspy-agents](https://github.com/benvenker/dspy-agents) 🚧
- MVP AgentOS stack where DSPy skills (Signatures, Chain-of-Thought, MIPROv2 artifacts) power a Researcher agent with SQLite memory and MultiMCP tooling like `fetch_url`.
- FastAPI API + streaming runs, evaluation harness (zero-shot vs compiled), and UI hooks show how I approach repeatable agent workflows.

### [llms-txt Generator](https://github.com/benvenker/llms-txt) 🟢
- DSPy-powered analyzer that inspects repositories, gathers metadata, and emits `llms.txt` guides so downstream LLMs stay aligned with house rules.
- Typer CLI, `uv` workflow, and GitHub fetchers make it easy for teams to keep documentation machine-readable.

### [GitLab MCP Extension for Gemini CLI](https://github.com/benvenker/gitlab-gemini-extension) 
A very basic skeleton of using the GitLab MCP to build a Gemini CLI extension.
- Packaged GitLab’s hosted Model Context Protocol server as a Gemini CLI extension so Product/Eng teams can call `/gitlab:*` commands natively.
- Handles auth, ships ready-to-run TOML commands, and documents the end-to-end Gemini experience so AI copilots inherit GitLab context automatically.

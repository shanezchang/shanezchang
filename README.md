# Shane Chang

AI agent engineer in Shenzhen. At Superlinear I work on the core agent system behind [Lessie AI](https://lessie.ai/), an AI people-search product. Most of my recent work is on agent evaluation: checking whether an agent's output is actually correct, without leaning on another model's opinion.

[Resume](https://shanezchang.github.io/resume/en/) · [中文简历](https://shanezchang.github.io/resume/zh/) · [LinkedIn](https://www.linkedin.com/in/shanezchang/)

## Publication

**[PeopleSearchBench: Evaluating AI-Powered People Search Platforms with Criteria-Grounded Verification](https://arxiv.org/abs/2603.27476)**  
EMNLP 2026 Industry Track · corresponding author · [code](https://github.com/LessieAI/people-search-bench)

An open benchmark of 119 multilingual queries across recruiting, B2B prospecting, expert search and influencer discovery. Rather than asking an LLM to grade results, each query is broken into criteria that can be checked independently, and every returned person is verified against live web evidence. Agreement with human annotators: Cohen's κ = 0.84.

## Open source

- **[people-search-bench](https://github.com/LessieAI/people-search-bench)**: the benchmark and evaluation harness from the paper
- **[lessie-skill](https://github.com/LessieAI/lessie-skill)**: people and company search and enrichment, packaged as a skill for Claude Code and Codex
- **[@lessie/cli](https://www.npmjs.com/package/@lessie/cli)** and **@lessie/mcp-server**: the same agent capabilities as a CLI and an MCP server
- **[mcp-hub](https://github.com/shanezchang/mcp-hub)**: my own MCP server hub, context and conventions for AI coding tools

## What I work on

- **Tool calling and context engineering.** Restructured tools, progressive disclosure of skills and middleware context injection took our people-search eval pass rate from 26% to 63%.
- **Agent evaluation.** Criteria-grounded verification as an alternative to LLM-as-judge.
- **Multi-agent systems in production.** LangChain / LangGraph orchestration, model routing and fallback.
- **Agents for internal R&D.** Codex, Claude Code and Hermes wired into code, deploys, logs and support cases through Multica.

## Before agents

Backend engineer at Yangteng, where I led the move from Odoo to an in-house warehouse system handling 30K+ operations a day that passed a Deloitte IPO audit. Before that, backend and data engineer at **Tencent** (CSIG), on large-scale ad-compliance monitoring built on Kafka and Kubernetes.

B.Sc. in Mathematics, Shenzhen University.

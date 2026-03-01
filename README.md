# Awesome Agentic Knowledge Work (AKW)

A curated list of projects, agents, skills and other things that handle increasingly larger chunks of knowledge work, what I'm calling "agentic knowledge work" (AKW)

## What Counts

Projects in this list should generally:

- Take on multi-step, higher-leverage work instead of single prompts
- Encode domain knowledge, workflow structure, or reusable operator logic
- Produce outputs that are useful beyond a toy demo

I considered organizing things by category but thought a timeline organization would be more useful seeing the progress that's made.

## Timeline

### February 2026

- [/simplify and /batch (Boris Cherny)](https://x.com/bcherny/status/2027534984534544489) - Two new Claude Code skills: `/simplify` automates shepherding PRs to production by streamlining diffs and reducing complexity; `/batch` handles parallelizable code migrations across multiple files simultaneously. *(2026-02-28)*
- [Harness Engineering (OpenAI)](https://openai.com/index/harness-engineering/) - OpenAI's framework for agent-first software development, where Codex agents generate, test, and deploy production systems while engineers focus on designing environments, specifying intent, and structured feedback. *(2026-02-28)*
- [GPT-5.3-Codex (OpenAI)](https://openai.com/index/introducing-gpt-5-3-codex/) - OpenAI's most capable agentic coding model, combining frontier coding performance with the reasoning of GPT-5.2. Runs 25% faster, sets SOTA on SWE-Bench Pro and Terminal-Bench, and supports real-time steering mid-task. Available in Codex app, CLI, IDE extension, and web. *(2026-02-05)*
- [lawwu/agentic-ml-plugin](https://github.com/lawwu/agentic-ml-plugin) - Tools that make each step of the machine learning lifecycle easier. *(2026-02-28)*
- [Design (Anthropic)](https://github.com/anthropics/knowledge-work-plugins/tree/main/design) - Supports design critique, design systems, UX writing, accessibility review, research synthesis, and developer handoff. *(2026-02-24)*
- [Human Resources (Anthropic)](https://github.com/anthropics/knowledge-work-plugins/tree/main/human-resources) - Covers recruiting, onboarding, performance reviews, policy guidance, and compensation analysis. *(2026-02-24)*
- [Operations (Anthropic)](https://github.com/anthropics/knowledge-work-plugins/tree/main/operations) - Handles vendor management, process docs, change management, capacity planning, compliance tracking, and resource planning. *(2026-02-24)*
- [Engineering (Anthropic)](https://github.com/anthropics/knowledge-work-plugins/tree/main/engineering) - A software engineering plugin primarily designed for Cowork. *(2026-02-24)*

### January 2026

- [Bio Research (Anthropic)](https://github.com/anthropics/knowledge-work-plugins/tree/main/bio-research) - Connects to preclinical research tools and databases to accelerate early-stage life sciences R&D. *(2026-01-29)*
- [Customer Support (Anthropic)](https://github.com/anthropics/knowledge-work-plugins/tree/main/customer-support) - Helps triage tickets, draft responses, package escalations, and turn resolved issues into knowledge base articles. *(2026-01-29)*
- [Data (Anthropic)](https://github.com/anthropics/knowledge-work-plugins/tree/main/data) - Queries, analyzes, and visualizes datasets with SQL, statistics, dashboards, and result validation. *(2026-01-29)*
- [data-context-extractor](https://github.com/anthropics/knowledge-work-plugins/blob/main/data/skills/data-context-extractor/SKILL.md) - A meta-skill that extracts company-specific data knowledge from analysts and generates tailored data analysis skills. *(2026-01-29)*
- [Enterprise Search (Anthropic)](https://github.com/anthropics/knowledge-work-plugins/tree/main/enterprise-search) - Searches across email, chat, docs, and wikis with a single cross-tool query. *(2026-01-29)*
- [Finance (Anthropic)](https://github.com/anthropics/knowledge-work-plugins/tree/main/finance) - Assists with journal entries, reconciliations, statements, variance analysis, close workflows, and audits. *(2026-01-29)*
- [Legal (Anthropic)](https://github.com/anthropics/knowledge-work-plugins/tree/main/legal) - Helps review contracts, triage NDAs, navigate compliance, assess risk, and draft templated responses. *(2026-01-29)*
- [Marketing (Anthropic)](https://github.com/anthropics/knowledge-work-plugins/tree/main/marketing) - Drafts content, plans campaigns, enforces brand voice, analyzes competitors, and reports on channel performance. *(2026-01-29)*
- [Product Management (Anthropic)](https://github.com/anthropics/knowledge-work-plugins/tree/main/product-management) - Helps write specs, plan roadmaps, synthesize user research, update stakeholders, and track competitors. *(2026-01-29)*
- [Productivity (Anthropic)](https://github.com/anthropics/knowledge-work-plugins/tree/main/productivity) - Manages tasks, calendars, daily workflows, and personal context to reduce repeated setup work. *(2026-01-29)*
- [Sales (Anthropic)](https://github.com/anthropics/knowledge-work-plugins/tree/main/sales) - Researches prospects, prepares calls, reviews pipeline, drafts outreach, and builds battlecards. *(2026-01-29)*
- [claude-code-setup](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/claude-code-setup) - Skill to help Claude set itself up. *(2026-01-16)*
- [find-skills](https://skills.sh/vercel-labs/skills/find-skills) - Helps you discover and install skills from the open agent skills ecosystem. *(2026-01-14)*
- [skills.sh](https://skills.sh/) - Open Agent Skills Ecosystem. *(2026-01-14)*
- [Claude Cowork (Anthropic)](https://claude.com/blog/cowork-research-preview) - Desktop app that gives Claude access to your computer's folders to read, edit, and create files autonomously. Built with Claude Code in ~10 days, bringing agentic capabilities to non-developers. Available as a research preview for Claude Max subscribers. *(2026-01-12)*
- [code-simplifier](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/code-simplifier) - Reviews changed code for reuse, quality, and efficiency, then fixes any issues found. *(2026-01-09)*
- [Sentry's Skills](https://github.com/getsentry/skills/) - Skills from Sentry's team. *(2026-01-05)*

### December 2025

- [Claude Code reaches $1B run-rate revenue](https://www.anthropic.com/news/anthropic-acquires-bun-as-claude-code-reaches-usd1b-milestone) - Anthropic announces Claude Code hit a $1B annualized revenue run-rate. *(2025-12-02)*
- [skill-creator (OpenAI)](https://github.com/openai/skills/blob/main/skills/.system/skill-creator/SKILL.md) - Provides guidance for creating effective skills. *(2025-12-18)*
- [skill-creator (Anthropic)](https://github.com/anthropics/skills/blob/main/skills/skill-creator/SKILL.md) - A skill for creating new skills and iteratively improving them. Automatically creates evaluation dataset. *(2025-12-01)*

### November 2025

- [Claude Opus 4.5](https://www.anthropic.com/news/claude-opus-4-5) - Anthropic's most capable model release. *(2025-11-24)*
- [skills (OpenAI)](https://github.com/openai/skills) - OpenAI Agent Skills used in Codex. *(2025-11-25)*
- [plugin-dev](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/plugin-dev) - A comprehensive toolkit for developing Claude Code plugins with expert guidance on hooks, MCP integration, plugin structure, and marketplace publishing. *(2025-11-20)*
- [Ralph Wiggum (Claude Code)](https://github.com/anthropics/claude-code/tree/main/plugins/ralph-wiggum) - Interactive self-referential AI loops for iterative development. Claude works on the same task repeatedly until completion. *(2025-11-16)*
- [Front End Design (Claude Code)](https://github.com/anthropics/claude-code/tree/main/plugins/frontend-design) - Create distinctive, production-grade frontend interfaces that avoid generic AI aesthetics. *(2025-11-12)*

### October 2025

- [Claude Skills](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills) - Anthropic introduces Agent Skills, a standard for packaging reusable, shareable capabilities that agents can install and invoke. *(2025-10-16)*
- [Claude Haiku 4.5](https://www.anthropic.com/news/claude-opus-4-5) - Anthropic's fastest and most compact model release. *(2025-10-15)*
- [Claude Code Plugins](https://github.com/anthropics/claude-plugins-official/) - Official plugin system for Claude Code, enabling installable domain-specific tools and workflows. *(2025-10-09)*
- [EveryInc/compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin) - Tools that make each unit of engineering work easier than the last. *(2025-10-09)*
- [superpowers](https://github.com/obra/superpowers) - A complete software development workflow for your coding agents, built on top of a set of composable skills. *(2025-10-09)*
- [Feature Dev (Claude Code)](https://github.com/anthropics/claude-code/tree/main/plugins/feature-dev) - Comprehensive feature development workflow with a structured 7-phase approach. *(2025-10-09)*
- [Security (Claude Code)](https://github.com/anthropics/claude-code/tree/main/plugins/security-guidance) - Security reminder hook that warns about potential security issues when editing files. *(2025-10-09)*

### September 2025

- [Claude Sonnet 4.5](https://www.anthropic.com/news/claude-sonnet-4-5) - Anthropic's mid-tier model release. *(2025-09-29)*
- [Claude Agents SDK](https://www.anthropic.com/engineering/building-agents-with-the-claude-agent-sdk) - SDK for building multi-agent systems with Claude, enabling orchestration of specialized subagents. *(2025-09-29)*

### August 2025

- [Claude Code GitHub Action 1.0](https://github.com/anthropics/claude-code-action/) - Official GitHub Action for running Claude Code in CI/CD pipelines, enabling automated agentic workflows on pull requests and issues. *(2025-08-26)*
- [Claude Opus 4.1](https://www.anthropic.com/news/claude-opus-4-1) - Anthropic's flagship model release. *(2025-08-05)*

### May 2025

- [Claude Sonnet 4 and Opus 4](https://www.anthropic.com/news/claude-4) - Anthropic's Claude 4 model family, generally available. *(2025-05-22)*
- [Codex (OpenAI)](https://openai.com/index/introducing-codex/) - OpenAI's cloud-based coding agent powered by codex-1 (an o3 variant fine-tuned for software engineering). Runs tasks in isolated sandboxes with your repo preloaded, can write features, fix bugs, run tests, and propose PRs. Accessible via ChatGPT sidebar. *(2025-05-16)*

### March 2025

- [OpenAI Responses API](https://openai.com/index/new-tools-and-features-in-the-responses-api/) - OpenAI's new core primitive for building agentic applications, replacing the Assistants API. Includes built-in tools for web search, file search, and computer use. *(2025-03-11)*

### April 2025

- [Code with Claude (developer conference)](https://www.anthropic.com/news/Introducing-code-with-claude) - Anthropic's first developer conference. Talk summaries [here](https://lawwu.github.io/posts/2025-08-14-claude-code-conference-summary/). *(2025-04-03)*

### February 2025

- [Claude Code](https://www.anthropic.com/news/claude-3-7-sonnet) ([repo](https://github.com/anthropics/claude-code)) - Anthropic's agentic coding tool, launched as a limited research preview alongside Claude 3.7 Sonnet. Runs in the terminal and can read/edit files, run tests, commit code, and use CLI tools autonomously. *(2025-02-24)*


## Why This List Exists

There are many agent demos, wrappers, and benchmark projects. There are fewer examples of systems that try to own an actual unit of knowledge work from end to end.

This repository is meant to collect those stronger examples in one place so people can:

- Study patterns that go beyond prompt engineering
- Compare how different teams package agent capabilities
- Find inspiration for building more capable agentic tools

## Contributing

If you know a project that belongs here, open a pull request.

Useful additions are projects that:

- Target a real workflow with meaningful scope
- Show clear product or systems thinking
- Are public and inspectable

## Future Directions

As the list grows, it may make sense to organize entries by:

- Domain (engineering, research, ML, finance, legal, operations)
- Form factor (plugin, agent framework, internal tool, product)
- Workflow style (review, synthesis, execution, planning, monitoring)

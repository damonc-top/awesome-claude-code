# Claude Code Learning Plan - Resource Mapping

Based on the `awesome-claude-code` repository, here is a curated list of resources mapped to your learning requirements. This mapping identifies the most valuable repositories for each topic in your syllabus.

## 1. Principles & Fundamentals (Claude Code 原理)
Understanding the core concepts and workflows is crucial.
*   **Official Foundation**: `Anthropic Documentation` (doc-93f22142) - The source of truth.
*   **Methodology**: `AB Method` (wf-996c4dd3) - A principled, spec-driven workflow that transforms large problems into focused missions.
*   **Planning**: `ContextKit` (tool-b3562922) - Features a 4-phase planning methodology to help AI produce production-ready code.
*   **Patterns**: `Agentic Workflow Patterns` (wf-7d4f4706) - Collection of patterns from Anthropic docs (Subagent Orchestration, etc.).

## 2. Environment Setup (环境配置搭建)
Setting up the environment for maximum productivity and safety.
*   **Quick Start**: `claude-starter-kit` (tool-8b0193b7) - A starter template with pre-configured MCP servers and tools.
*   **Isolation (Docker)**: 
    *   `run-claude-docker` (tool-a5798d4b) - Run Claude in a safe, isolated container.
    *   `viwo-cli` (tool-fcf2812e) - Docker container with git worktrees for safer "dangerously-skip-permissions" usage.
*   **IDE Integration**:
    *   VS Code: `Claudix` (tool-7e19bf77) or `Claude Code Chat` (tool-984936a7).
    *   JetBrains: `AI IntelliJ Plugin` (claude-ac32c909).
    *   Neovim: `claude-code.nvim` (tool-0607ef06).

## 3. Shortcuts (快捷键使用)
Tools to speed up interaction and navigation.
*   **History Navigation**: `cchistory` (tool-d9c9bde8) - Like shell history but for Claude Code sessions (`!`).
*   **Search**: `recall` (tool-6e6f1ae1) - Full-text search your past Claude Code sessions.

## 4. CLAUDE.md
Understanding and using the project-specific configuration file.
*   **System Prompts**: `Claude Code System Prompts` (wf-b3c6f3e1) - Includes utility prompts including `CLAUDE.md`.
*   **Real World Examples**: `Shipping Real Code w/ Claude` (wf-eee9a073) - Blog post detailing usage of `CLAUDE.md`.
*   **Templates**: `Claude Code Templates` (tool-d95e578f) - Collection of resources including templates.

## 5. Hooks
Automating checks and behaviors.
*   **SDKs**: 
    *   `cchooks` (hook-26657310) - Python SDK for writing hooks.
    *   `claude-hooks` (hook-ff4a072b) - TypeScript-based system.
*   **Practical Examples**:
    *   `Britfix` (hook-73da34c7) - Example of modifying output (spelling).
    *   `CC Notify` (hook-37bef012) - Desktop notifications.
    *   `TDD Guard` (hook-2b995e52) - Monitors file operations to enforce TDD.

## 6. Skills
Extending agent capabilities.
*   **Core Engineering**: `Superpowers` (skill-294cc93f) - Bundle of core competencies for software engineering (planning, reviewing, testing).
*   **Context Management**: `Context Engineering Kit` (skill-e5b92436) - Techniques to improve agent result quality with minimal token footprint.
*   **Web Dev**: `Web Assets Generator Skill` (skill-1fc653a0).

## 7. Agents
Working with sub-agents and multi-agent systems.
*   **Orchestration**: 
    *   `Claude Squad` (tool-5d0685f2) - Manage multiple Claude Code agents in separate workspaces.
    *   `Claude Swarm` (tool-1af2fe4c) - Connect to a swarm of agents.
*   **Task Management**: `TSK` (tool-5fb873b1) - Delegate tasks to AI agents in sandboxed Docker environments.

## 8. Commands
Custom slash commands to automate workflows.
*   **Collection**: `Slash-commands megalist` (wf-b6f047e2) - A massive list of commands.
*   **Key Commands to Learn**:
    *   `/create-hook` (cmd-d4f9e2a5) - Automate hook creation.
    *   `/bug-fix` (cmd-4a72b306) - Structured bug fixing workflow.
    *   `/commit` (cmd-b6a797df) - Conventional commits.
    *   `/pr-review` (cmd-7f51ad4d) - Code review.
    *   `/tdd` (cmd-051321ab) - Test Driven Development guide.

## 9. Configuration (rules.json / .cursorrules)
*   **Automation**: `Rulesync` (tool-5845fda0) - Automatically generates configs (rules, ignore files) and converts between formats.
*   **Reference**: `Claude Code Handbook` (wf-fd5a0e6b) - Covers modular rules integration.

## 10. Memory Management
Managing context and long-term memory.
*   **MCP Based**: `Basic Memory` (claude-14f59511) - AI-human collaboration framework with Model Context Protocol.
*   **Priming**: `Context Priming` (wf-b98b3b2d) - Systematic approach to priming Claude with project context.


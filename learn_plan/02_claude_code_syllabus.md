# Claude Code Mastery Syllabus

This syllabus is designed to take you from a beginner to an advanced user of Claude Code, utilizing the best resources from the `awesome-claude-code` repository.

## Module 1: Foundations & Setup (基础与环境)
**Goal**: Understand what Claude Code is and set up a robust, safe development environment.

### 1.1 Principles & Architecture (原理)
*   **Concept**: Understanding Claude Code as an agentic coding partner, not just a chatbot.
*   **Key Resource**: `AB Method` (wf-996c4dd3) - Read this to understand a "spec-driven" workflow.
*   **Action**: Read the `Anthropic Documentation` (doc-93f22142) to understand the baseline capabilities.

### 1.2 Environment Setup (环境搭建)
*   **Concept**: Installation, Authentication, and Sandboxing.
*   **Action**: 
    *   Use `claude-starter-kit` (tool-8b0193b7) to bootstrap a new environment.
    *   **Crucial**: Set up `run-claude-docker` (tool-a5798d4b) or `viwo-cli` (tool-fcf2812e) to run Claude in a Docker container. This is essential for safely using "dangerously-skip-permissions".
*   **IDE**: Install the relevant integration for your editor (e.g., `Claudix` for VS Code).

### 1.3 Shortcuts & Navigation (快捷键)
*   **Concept**: Moving fast within the CLI.
*   **Action**: 
    *   Install `cchistory` (tool-d9c9bde8) to manage session history.
    *   Practice using `recall` (tool-6e6f1ae1) to search through past contexts.

## Module 2: Core Configuration (核心配置)
**Goal**: Control how Claude Code behaves in your specific projects.

### 2.1 The `CLAUDE.md` File
*   **Concept**: The "Instruction Manual" you write for Claude about your project.
*   **Action**: 
    *   Study `Claude Code System Prompts` (wf-b3c6f3e1) to see how `CLAUDE.md` is ingested.
    *   Create your first `CLAUDE.md` using patterns from `Shipping Real Code w/ Claude` (wf-eee9a073).

### 2.2 Rules & Configuration (`rules.json`)
*   **Concept**: Enforcing coding standards and ignoring files.
*   **Action**: 
    *   Use `Rulesync` (tool-5845fda0) to generate your initial configuration.
    *   Learn to sync rules between different agent tools.

## Module 3: Automation & Customization (自动化与定制)
**Goal**: Extend Claude Code with custom commands and automated behaviors.

### 3.1 Slash Commands (Commands)
*   **Concept**: Creating custom tools invokable via `/command`.
*   **Action**: 
    *   Explore the `Slash-commands megalist` (wf-b6f047e2).
    *   **Exercise**: Implement `/bug-fix` (cmd-4a72b306) and `/pr-review` (cmd-7f51ad4d) in your workflow.
    *   **Advanced**: Create your own command using `/create-command` (cmd-8856ecb4).

### 3.2 Hooks
*   **Concept**: Triggering actions on specific events (e.g., before tool use, after file write).
*   **Action**: 
    *   Install `cchooks` (hook-26657310) (Python) or `claude-hooks` (hook-ff4a072b) (TS).
    *   **Exercise**: Implement a simple hook like `Britfix` (hook-73da34c7) or a linter check before file writes.

## Module 4: Advanced Agentic Workflows (高级Agent工作流)
**Goal**: Orchestrate complex tasks and manage memory.

### 4.1 Skills & Capabilities
*   **Concept**: Giving Claude "Superpowers" (specialized tools).
*   **Action**: 
    *   Integrate `Superpowers` (skill-294cc93f) into your agent configuration.
    *   Learn to use `Context Engineering Kit` (skill-e5b92436) to optimize context usage.

### 4.2 Agents & Orchestration
*   **Concept**: Running multiple agents or specialized sub-agents.
*   **Action**: 
    *   Try `Claude Squad` (tool-5d0685f2) to manage multiple sessions/tasks.
    *   Explore `TSK` (tool-5fb873b1) for delegating tasks to background agents.

### 4.3 Memory Management
*   **Concept**: Long-term memory and context priming (MCP).
*   **Action**: 
    *   Implement `Context Priming` (wf-b98b3b2d) workflows.
    *   Experiment with `Basic Memory` (claude-14f59511) to see how MCP can store persistent data.


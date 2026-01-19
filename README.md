# Claude Code Resources Guide

A curated, compact guide to essential resources for [Claude Code](https://docs.anthropic.com/en/docs/claude-code) - the CLI-based AI coding assistant from Anthropic.

## Quick Start

**New to Claude Code?** Start here:
- [Official Documentation](https://docs.claude.com/en/home) - Installation, tutorials, and API references
- [Anthropic Quickstarts](https://github.com/anthropics/claude-quickstarts) - Three demo projects with standardized workflows

## Essential Resources

### Skills & Workflows

**Skills** are configurations that enable Claude Code to perform specialized tasks.

- [Superpowers](https://github.com/obra/superpowers) - Core software engineering competencies covering the full SDLC
- [Trail of Bits Security Skills](https://github.com/trailofbits/skills) - Professional security tools for code auditing (CodeQL, Semgrep, variant analysis)
- [Claude Codex Settings](https://github.com/fcakyon/claude-codex-settings) - Well-organized plugins for GitHub, Azure, MongoDB, and popular services
- [Context Engineering Kit](https://github.com/NeoLabHQ/context-engineering-kit) - Advanced context engineering techniques with minimal token footprint

**Workflows** are comprehensive systems for specific development approaches.

- [RIPER Workflow](https://github.com/tony/claude-code-riper-5) - Structured phases: Research, Innovate, Plan, Execute, Review
- [AB Method](https://github.com/ayoubben18/ab-method) - Spec-driven workflow using specialized sub-agents
- [Claude CodePro](https://github.com/maxritter/claude-codepro) - Professional environment with TDD enforcement and quality hooks
- [ContextKit](https://github.com/FlineDev/ContextKit) - 4-phase planning methodology for production-ready code

### Development Tools

**Orchestrators** - Manage multiple Claude instances

- [Claude Squad](https://github.com/smtg-ai/claude-squad) - Terminal app for managing multiple Claude Code sessions in separate workspaces
- [TSK](https://github.com/dtormoen/tsk) - Rust CLI for parallel AI agents in sandboxed Docker environments

**Usage Monitors** - Track token usage and costs

- [ccflare](https://github.com/snipeship/ccflare) - Professional web-UI dashboard with comprehensive metrics
- [Claudex](https://github.com/kunwar-shah/claudex) - Browse conversation history with full-text search and analytics

**IDE Integrations**

- [Claudix](https://github.com/Haleclipse/Claudix) - VSCode extension with chat interface and session management
- [claude-code.nvim](https://github.com/greggh/claude-code.nvim) - Neovim integration
- [claude-code-ide.el](https://github.com/manzaltu/claude-code-ide.el) - Emacs integration with LSP support

### Hooks & Commands

**Hooks** trigger actions at specific points in Claude's lifecycle.

- [TDD Guard](https://github.com/nizos/tdd-guard) - Blocks file changes that violate TDD principles
- [TypeScript Quality Hooks](https://github.com/bartolli/claude-code-typescript-hooks) - TypeScript compilation, ESLint, and Prettier with <5ms performance
- [claude-hooks](https://github.com/johnlindquist/claude-hooks) - TypeScript system for building custom hooks

**Essential Slash Commands**

- [/commit](https://github.com/evmts/tevm-monorepo/blob/main/.claude/commands/commit.md) - Conventional commits with emojis
- [/create-pr](https://github.com/toyamarinyon/giselle/blob/main/.claude/commands/create-pr.md) - Streamlined PR creation workflow
- [/tdd](https://github.com/zscott/pane/blob/main/.claude/commands/tdd.md) - Test-Driven Development guidance
- [/docs](https://github.com/slunsford/coffee-analytics/blob/main/.claude/commands/docs.md) - Comprehensive documentation generation

### CLAUDE.md Examples

Project-specific context files that help Claude understand your codebase.

**Language-Specific**
- [Metabase](https://github.com/metabase/metabase/blob/master/CLAUDE.md) - Clojure/ClojureScript REPL-driven development
- [LangGraphJS](https://github.com/langchain-ai/langgraphjs/blob/main/CLAUDE.md) - TypeScript monorepo with yarn workspaces
- [DroidconKotlin](https://github.com/touchlab/DroidconKotlin/blob/main/CLAUDE.md) - Kotlin Multiplatform development

**Domain-Specific**
- [Pareto Mac](https://github.com/ParetoSecurity/pareto-mac/blob/main/CLAUDE.md) - Mac security audit tool
- [Course Builder](https://github.com/badass-courses/course-builder/blob/main/CLAUDE.md) - Collaborative course creation with multiplayer capabilities

### Status Lines

Customize your terminal status bar with real-time information.

- [CCometixLine](https://github.com/Haleclipse/CCometixLine) - High-performance Rust implementation with Git and usage tracking
- [claude-powerline](https://github.com/Owloops/claude-powerline) - Vim-style powerline with themes
- [claudia-statusline](https://github.com/hagan/claudia-statusline) - SQLite-backed persistence with cloud sync

## Advanced Topics

### Autonomous Development

**Ralph Wiggum Pattern** - Autonomous task completion loops

- [The Ralph Playbook](https://github.com/ClaytonFarr/ralph-playbook) - Comprehensive guide with theory and practical advice
- [ralph-orchestrator](https://github.com/mikeyobrien/ralph-orchestrator) - Robust implementation with safety guardrails
- [Ralph for Claude Code](https://github.com/frankbria/ralph-claude-code) - Framework with circuit breaker patterns and 75+ tests

### Specialized Utilities

- [claude-code-tools](https://github.com/pchalasani/claude-code-tools) - Session continuity and Rust-powered full-text search
- [Container Use](https://github.com/dagger/container-use) - Safe development environments for multiple agents
- [Plannotator](https://github.com/backnotprop/plannotator) - Interactive plan review UI with visual annotations
- [VoiceMode MCP](https://github.com/mbailey/voicemode) - Natural voice conversations with Claude Code

### Knowledge Collections

- [Claude Code Tips](https://github.com/ykdojo/claude-code-tips) - 35+ practical tips with demos and scripts
- [Claude Code Handbook](https://nikiforovall.blog/claude-code-rules/) - Best practices and distributable plugins
- [Agentic Workflow Patterns](https://github.com/ThibautMelen/agentic-workflow-patterns) - Patterns from Anthropic docs with Mermaid diagrams
- [Claude Code Repos Index](https://github.com/danielrosehill/Claude-Code-Repos-Index) - Index of 75+ specialized repositories

## Resource Discovery

- [Claude Code Templates](https://github.com/davila7/claude-code-templates) - Polished UI with usage dashboard and analytics
- [ccexp](https://github.com/nyatinte/ccexp) - Interactive CLI for discovering configuration files
- [Claude Code System Prompts](https://github.com/Piebald-AI/claude-code-system-prompts) - All system prompts and tool descriptions

## Alternative Clients

- [Omnara](https://github.com/omnara-ai/omnara) - Sync sessions across terminal, web, and mobile with team collaboration
- [Claudable](https://github.com/opactorai/Claudable) - Web builder leveraging local CLI agents

## Contributing

Have a resource to share? Check out the [awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) repository for the full collection and contribution guidelines.

## License

This guide is derived from [awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code). Individual resources maintain their own licenses.

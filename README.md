# Claude Code Resources Guide

A curated, skill-level organized guide to essential resources for [Claude Code](https://docs.anthropic.com/en/docs/claude-code) - the CLI-based AI coding assistant from Anthropic.

---

## 🟢 Beginner

> **Getting started with Claude Code** - Essential resources for new users to understand the basics, set up their environment, and learn fundamental workflows.

### Official Documentation & Quick Start

| Resource | Description |
|----------|-------------|
| [Anthropic Documentation](https://docs.anthropic.com) | Official installation guides, tutorials, API references, and usage guidelines |
| [Anthropic Quickstarts](https://github.com/anthropics/claude-quickstarts) | Three demo projects with standardized workflows to learn by example |
| [Claude Code GitHub Actions](https://github.com/anthropics/claude-code-action) | Official GitHub Actions integration for CI/CD automation |

### First Skills to Learn

| Resource | Author | Description |
|----------|--------|-------------|
| [Superpowers](https://github.com/obra/superpowers) | Jesse Vincent | Core software engineering competencies covering planning, reviewing, testing, and debugging across the SDLC |
| [Claude Codex Settings](https://github.com/fcakyon/claude-codex-settings) | fatih akyon | Well-organized plugins for GitHub, Azure, MongoDB, Playwright, and popular services |
| [Web Assets Generator Skill](https://github.com/alonwolenitz/web-assets-generator-skill) | Alon Wolenitz | Generate favicons, PWA icons, and social media meta images with proper HTML tags |

### Essential Slash Commands

| Resource | Author | Description |
|----------|--------|-------------|
| [/commit](https://github.com/evmts/tevm-monorepo/blob/main/.claude/commands/commit.md) | evmts | Creates git commits using conventional commit format with appropriate emojis |
| [/prime](https://github.com/yzyydev/claude-code-commands/blob/main/.claude/commands/prime.md) | yzyydev | Sets up initial project context by viewing directory structure and reading key files |
| [/docs](https://github.com/slunsford/coffee-analytics/blob/main/.claude/commands/docs.md) | slunsford | Generates comprehensive documentation following project structure |
| [/todo](https://github.com/chrisleyva/claude-code-commands/blob/main/.claude/commands/todo.md) | chrisleyva | Manages project todo items with due dates, sorting, and task prioritization |

### Beginner-Friendly CLAUDE.md Examples

| Resource | Author | Description |
|----------|--------|-------------|
| [SteadyStart](https://github.com/steadycursor/steadystart/blob/main/CLAUDE.md) | steadycursor | Clear instructions about style, permissions, Claude's role, and session documentation |
| [JSBeeb](https://github.com/mattgodbolt/jsbeeb/blob/main/CLAUDE.md) | mattgodbolt | Development guide for JavaScript project with build, testing, and debugging workflows |
| [Giselle](https://github.com/giselles-ai/giselle/blob/main/CLAUDE.md) | giselles-ai | Detailed build/test commands using pnpm and Vitest with strict formatting requirements |

### Usage Monitors (Track Your Costs)

| Resource | Author | Description |
|----------|--------|-------------|
| [CC Usage](https://github.com/ryoppippi/cc-usage) | ryoppippi | CLI tool for managing and analyzing Claude Code usage with cost information |
| [Claude Code Usage Monitor](https://github.com/maciek-roboblog/claude-code-usage-monitor) | Maciek-roboblog | Real-time terminal tool showing live token consumption and burn rate with visual progress bars |

### IDE Integrations

| Resource | Author | Description |
|----------|--------|-------------|
| [Claude Code Chat](https://github.com/andrepimenta/claude-code-chat) | andrepimenta | Elegant Claude Code chat interface for VS Code |
| [Claudix - Claude Code for VSCode](https://github.com/Haleclipse/Claudix) | Haleclipse | VSCode extension with interactive chat, session management, and file operations |
| [claude-code.nvim](https://github.com/greggh/claude-code.nvim) | greggh | Seamless integration between Claude Code and Neovim |

---

## 🟡 Intermediate

> **Expanding your Claude Code toolkit** - Resources for users comfortable with basics who want to improve productivity, customize workflows, and integrate advanced features.

### Workflow Systems

| Resource | Author | Description |
|----------|--------|-------------|
| [RIPER Workflow](https://github.com/tony/claude-code-riper-5) | Tony Narlock | Structured workflow enforcing Research, Innovate, Plan, Execute, Review phases with branch-aware memory |
| [AB Method](https://github.com/ayoubben18/ab-method) | Ayoub Bensalah | Spec-driven workflow transforming large problems into focused, incremental missions using specialized sub agents |
| [Simone](https://github.com/helmi/simone) | Helmi | Broader project management workflow with documents, guidelines, and processes for planning and execution |
| [Claude Code PM](https://github.com/ranaroussi/claude-code-pm) | Ran Aroussi | Comprehensive project-management workflow with specialized agents and slash-commands |

### Advanced Skills

| Resource | Author | Description |
|----------|--------|-------------|
| [Trail of Bits Security Skills](https://github.com/trailofbits/skills) | Trail of Bits | Professional security-focused skills for code auditing with CodeQL, Semgrep, and vulnerability detection |
| [Context Engineering Kit](https://github.com/NeoLabHQ/context-engineering-kit) | Vlad Goncharov | Advanced context engineering techniques with minimal token footprint for improved agent quality |
| [TÂCHES Claude Code Resources](https://github.com/taches/claude-code-resources) | TÂCHES | Well-balanced sub agents, skills, and commands with meta-skills like skill-auditor and hook creation |
| [Codex Skill](https://github.com/klaudworks/codex-skill) | klaudworks | Enables prompting codex from Claude Code with parameter inference for model, reasoning effort, sandboxing |

### Hooks Development

| Resource | Author | Description |
|----------|--------|-------------|
| [claude-hooks](https://github.com/johnlindquist/claude-hooks) | John Lindquist | TypeScript-based system for configuring and customizing Claude Code hooks |
| [cchooks](https://github.com/GowayLee/cchooks) | GowayLee | Lightweight Python SDK simplifying hook writing with clean API and good documentation |
| [TDD Guard](https://github.com/nizos/tdd-guard) | Nizar Selander | Hooks-driven system monitoring file operations and blocking changes violating TDD principles |
| [TypeScript Quality Hooks](https://github.com/bartolli/claude-code-typescript-hooks) | bartolli | Quality check hook with ESLint auto-fixing, Prettier formatting, SHA256 config caching for <5ms validation |
| [Claudio](https://github.com/christophertoth/claudio) | Christopher Toth | Library adding OS-native sounds to Claude Code via simple hooks |

### Version Control & Git Commands

| Resource | Author | Description |
|----------|--------|-------------|
| [/create-pr](https://github.com/toyamarinyon/giselle/blob/main/.claude/commands/create-pr.md) | toyamarinyon | Streamlines PR creation: branch creation, committing, Biome formatting, PR submission |
| [/fix-github-issue](https://github.com/jeremymailen/claude-code-commands/blob/main/.claude/commands/fix-github-issue.md) | jeremymailen | Analyzes and fixes GitHub issues with structured approach using GitHub CLI |
| [/fix-pr](https://github.com/metabase/metabase/blob/master/.claude/commands/fix-pr.md) | metabase | Fetches and fixes unresolved PR comments automatically |
| [/create-worktrees](https://github.com/evmts/tevm-monorepo/blob/main/.claude/commands/create-worktrees.md) | evmts | Creates git worktrees for open PRs or specific branches |
| [/husky](https://github.com/evmts/tevm-monorepo/blob/main/.claude/commands/husky.md) | evmts | Sets up and manages Husky Git hooks with pre-commit hooks and linting integration |

### Code Analysis & Testing Commands

| Resource | Author | Description |
|----------|--------|-------------|
| [/tdd](https://github.com/zscott/pane/blob/main/.claude/commands/tdd.md) | zscott | Guides TDD development enforcing Red-Green-Refactor discipline with git workflow integration |
| [/check](https://github.com/rygwdn/claude-code-commands/blob/main/.claude/commands/check.md) | rygwdn | Comprehensive code quality and security checks with static analysis and vulnerability scanning |
| [/optimize](https://github.com/to4iki/claude-code-commands/blob/main/.claude/commands/optimize.md) | to4iki | Analyzes code performance to identify bottlenecks with concrete optimization proposals |
| [/code_analysis](https://github.com/kingler/n8n_agent/blob/main/.claude/commands/code_analysis.md) | kingler | Menu of advanced code analysis commands including knowledge graph generation |

### Status Lines

| Resource | Author | Description |
|----------|--------|-------------|
| [CCometixLine](https://github.com/Haleclipse/CCometixLine) | Haleclipse | High-performance Rust statusline with Git integration, usage tracking, interactive TUI configuration |
| [claude-powerline](https://github.com/Owloops/claude-powerline) | Owloops | Vim-style powerline statusline with real-time usage tracking, git integration, custom themes |
| [claudia-statusline](https://github.com/hagan/claudia-statusline) | Hagan Franks | High-performance Rust-based statusline with SQLite persistence and XDG-compliant themes |
| [ccstatusline](https://github.com/sirmalloc/ccstatusline) | sirmalloc | Highly customizable status line formatter displaying model info, git branch, token usage |

### Tooling & Utilities

| Resource | Author | Description |
|----------|--------|-------------|
| [cc-tools](https://github.com/joshsymonds/cc-tools) | Josh Symonds | High-performance Go implementation of hooks and utilities with smart linting and testing |
| [ccexp](https://github.com/nyatinte/ccexp) | nyatinte | Interactive CLI for discovering and managing Claude Code configuration files with beautiful terminal UI |
| [cchistory](https://github.com/eckardt/cchistory) | eckardt | Shell history command for Claude Code sessions - list all Bash commands Claude ran |
| [recall](https://github.com/zippoxer/recall) | zippoxer | Full-text search Claude Code sessions. Alternative to `claude --resume` |
| [Rulesync](https://github.com/dyoshikawa/rulesync) | dyoshikawa | Node.js CLI generating configs for various AI coding agents with bidirectional conversion |

### Language-Specific CLAUDE.md Files

| Resource | Author | Description |
|----------|--------|-------------|
| [Metabase](https://github.com/metabase/metabase/blob/master/CLAUDE.md) | metabase | Workflow for REPL-driven development in Clojure/ClojureScript with incremental development emphasis |
| [LangGraphJS](https://github.com/langchain-ai/langgraphjs/blob/main/CLAUDE.md) | langchain-ai | Comprehensive build/test commands with TypeScript style guidelines and monorepo structure |
| [DroidconKotlin](https://github.com/touchlab/DroidconKotlin/blob/main/CLAUDE.md) | touchlab | Comprehensive Gradle commands for Kotlin Multiplatform development with dependency injection guidance |
| [HASH](https://github.com/hashintel/hash/blob/main/CLAUDE.md) | hashintel | Comprehensive repository structure with Rust documentation guidelines and PR review process |
| [Inkline](https://github.com/inkline/inkline/blob/main/CLAUDE.md) | inkline | Development workflow using pnpm with TypeScript and Vue 3 Composition API emphasis |

---

## 🔴 Advanced

> **Mastering Claude Code** - Resources for power users seeking autonomous workflows, multi-agent orchestration, custom tooling development, and enterprise-grade implementations.

### Autonomous Development (Ralph Wiggum Pattern)

| Resource | Author | Description |
|----------|--------|-------------|
| [The Ralph Playbook](https://github.com/ClaytonFarr/ralph-playbook) | Clayton Farr | Remarkably detailed guide to the Ralph Wiggum technique with theoretical commentary and practical guidelines |
| [ralph-orchestrator](https://github.com/mikeyobrien/ralph-orchestrator) | mikeyobrien | Robust implementation of Ralph Wiggum technique for autonomous task completion. Cited in Anthropic documentation |
| [Ralph for Claude Code](https://github.com/frankbria/ralph-claude-code) | Frank Bria | Autonomous AI development framework with intelligent exit detection, rate limiting, circuit breaker patterns, 75+ tests |
| [Ralph Wiggum Marketer](https://github.com/muratkoylan/ralph-wiggum-marketer) | Muratcan Koylan | Autonomous AI copywriter integrating Ralph loop with customized knowledge bases for market research |

### Multi-Agent Orchestration

| Resource | Author | Description |
|----------|--------|-------------|
| [Claude Squad](https://github.com/smtg-ai/claude-squad) | smtg-ai | Terminal app managing multiple Claude Code, Codex, and other local agents in separate workspaces |
| [Claude Swarm](https://github.com/parruda/claude-swarm) | parruda | Launch Claude Code session connected to a swarm of Claude Code Agents |
| [Claude Code Flow](https://github.com/ruvnet/claude-code-flow) | ruvnet | Code-first orchestration layer enabling autonomous code writing, editing, testing across recursive agent cycles |
| [Happy Coder](https://github.com/GrocerPublishAgent/happy-coder) | GrocerPublishAgent | Spawn and control multiple Claude Codes in parallel from phone or desktop with push notifications |
| [TSK - AI Agent Task Manager](https://github.com/dtormoen/tsk) | dtormoen | Rust CLI delegating development tasks to AI agents in sandboxed Docker environments |
| [The Agentic Startup](https://github.com/rudolfschmidt/the-agentic-startup) | Rudolf Schmidt | Collection of agents and commands for shipping production code using Output Styles |

### Professional Development Environments

| Resource | Author | Description |
|----------|--------|-------------|
| [Claude CodePro](https://github.com/maxritter/claude-codepro) | Max Ritter | Professional development environment with spec-driven workflow, TDD enforcement, cross-session memory, quality hooks |
| [ContextKit](https://github.com/FlineDev/ContextKit) | Cihat Gündüz | Systematic development framework with 4-phase planning methodology and specialized quality agents |
| [claudekit](https://github.com/carlrannaberg/claudekit) | Carl Rannaberg | CLI toolkit with auto-save checkpointing, code quality hooks, spec generation, 20+ specialized subagents |
| [SuperClaude](https://github.com/superclaude-org/superclaude) | SuperClaude-Org | Configuration framework with specialized commands, cognitive personas, and development methodologies |
| [Container Use](https://github.com/dagger/container-use) | dagger | Development environments for coding agents enabling multiple agents to work safely and independently |

### Advanced Hooks & Communication

| Resource | Author | Description |
|----------|--------|-------------|
| [Claude Code Hook Comms (HCOM)](https://github.com/aannoo/hcom) | aannoo | Lightweight CLI for real-time communication between Claude Code sub agents with @-mention targeting and live dashboard |
| [claude-code-hooks-sdk](https://github.com/beyondcode/claude-code-hooks-sdk) | beyondcode | Laravel-inspired PHP SDK for building Claude Code hook responses with fluent API |
| [Plannotator](https://github.com/backnotprop/plannotator) | backnotprop | Interactive plan review UI that intercepts ExitPlanMode via hooks for visual annotations before approving |
| [CC Notify](https://github.com/dazuiba/cc-notify) | dazuiba | Desktop notifications for Claude Code with one-click jumps to VS Code and task duration display |
| [Britfix](https://github.com/talieisin/britfix) | Talieisin | Context-aware American to British English converter that handles code files by only converting comments |

### Session Management & Continuity

| Resource | Author | Description |
|----------|--------|-------------|
| [claude-code-tools](https://github.com/pchalasani/claude-code-tools) | Prasad Chalasani | Toolset for session continuity with Rust/Tantivy full-text session search and safety hooks |
| [cc-sessions](https://github.com/toastdev/cc-sessions) | toastdev | Opinionated approach to productive development with Claude Code |
| [Claude Task Runner](https://github.com/grahama1970/claude-task-runner) | grahama1970 | Tool for context isolation and focused task execution solving context length limitations |
| [Vibe-Log](https://github.com/vibe-log/vibe-log) | Vibe-Log | Analyzes Claude Code prompts locally, provides session analysis and strategic guidance with HTML reports |

### Advanced Workflow Patterns

| Resource | Author | Description |
|----------|--------|-------------|
| [Agentic Workflow Patterns](https://github.com/ThibautMelen/agentic-workflow-patterns) | ThibautMelen | Comprehensive agentic patterns from Anthropic docs with Mermaid diagrams covering Subagent Orchestration, Master-Clone Architecture |
| [Claude Code Infrastructure Showcase](https://github.com/diet103/claude-code-infrastructure) | diet103 | Innovative approach using hooks to ensure Claude intelligently selects appropriate Skills for current context |
| [Context Priming](https://github.com/disler/context-priming) | disler | Systematic approach to priming Claude Code with comprehensive project context through specialized commands |

### Review Workflows

| Resource | Author | Description |
|----------|--------|-------------|
| [Design Review Workflow](https://github.com/patrickellis/design-review-workflow) | Patrick Ellis | Automated UI/UX design review workflow with sub agents covering responsive design to accessibility |

### Desktop & Alternative Clients

| Resource | Author | Description |
|----------|--------|-------------|
| [crystal](https://github.com/stravu/crystal) | stravu | Full-fledged desktop application for orchestrating, monitoring, and interacting with Claude Code agents |
| [Omnara](https://github.com/omnara-ai/omnara) | Ishaan Sehgal | Command center syncing Claude Code sessions across terminal, web, and mobile with team collaboration |
| [Claudable](https://github.com/opactorai/Claudable) | Ethan Park | Open-source web builder leveraging local CLI agents like Claude Code and Cursor Agent |
| [run-claude-docker](https://github.com/jonas/run-claude-docker) | Jonas | Self-contained Docker runner forwarding workspace into isolated container with access to settings and auth |

### System Internals & Customization

| Resource | Author | Description |
|----------|--------|-------------|
| [Claude Code System Prompts](https://github.com/Piebald-AI/claude-code-system-prompts) | Piebald AI | All parts of Claude Code's system prompt including tool descriptions and sub-agent prompts. Updated per version |
| [tweakcc](https://github.com/Piebald-AI/tweakcc) | Piebald-AI | Command-line tool to customize Claude Code styling |
| [cclogviewer](https://github.com/brads/cclogviewer) | Brad S. | Utility for viewing Claude Code .jsonl conversation files in HTML UI |
| [claude-code-docs](https://github.com/constantinshafranski/claude-code-docs) | Constantin Shafranski | Mirror of Anthropic documentation with full-text search and query-time updates |

### Domain-Specific Advanced CLAUDE.md

| Resource | Author | Description |
|----------|--------|-------------|
| [AVS Vibe Developer Guide](https://github.com/Layr-Labs/avs-vibe-guide/blob/main/CLAUDE.md) | Layr-Labs | AI-assisted EigenLayer AVS development workflow with blockchain terminology standards |
| [Comm](https://github.com/CommE2E/comm/blob/main/CLAUDE.md) | CommE2E | Development reference for E2E-encrypted messaging with security implementation details |
| [Network Chronicles](https://github.com/Fimeg/network-chronicles/blob/main/CLAUDE.md) | Fimeg | Implementation plan for AI-driven game characters with LLM integration specifications |
| [Basic Memory](https://github.com/basicmachines-co/basic-memory/blob/main/CLAUDE.md) | basicmachines-co | AI-human collaboration framework with Model Context Protocol for bidirectional LLM-markdown communication |

### Voice & Multimodal

| Resource | Author | Description |
|----------|--------|-------------|
| [VoiceMode MCP](https://github.com/mbailey/voicemode) | Mike Bailey | Natural conversations for Claude Code supporting OpenAI API-compatible voice services |
| [stt-mcp-server-linux](https://github.com/marcindulak/stt-mcp-server-linux) | marcindulak | Push-to-talk speech transcription for Linux using Python MCP server. Runs locally in Docker |

---

## 📚 Knowledge Collections

> Comprehensive guides and indexes for deeper learning

| Resource | Author | Description |
|----------|--------|-------------|
| [Claude Code Tips](https://github.com/ykdojo/claude-code-tips) | ykdojo | 35+ brief Claude Code tips covering voice input, system prompt patching, container workflows |
| [Claude Code Handbook](https://nikiforovall.blog/claude-code-rules/) | nikiforovall | Best practices, tips, and techniques for Claude Code development workflows |
| [Claude Code Repos Index](https://github.com/danielrosehill/Claude-Code-Repos-Index) | Daniel Rosehill | Index of 75+ Claude Code repositories covering CMS, system design, deep research, IoT, agentic workflows |
| [Claude Code Documentation Mirror](https://github.com/ericbuess/claude-code-docs) | Eric Buess | Mirror of Anthropic documentation pages, updated every few hours |
| [Shipping Real Code w/ Claude](https://github.com/diwank/shipping-real-code) | Diwank | Blog post explaining process for shipping products with Claude Code including CLAUDE.md files |

---

## 🔍 Resource Discovery Tools

| Resource | Author | Description |
|----------|--------|-------------|
| [Claude Code Templates](https://github.com/davila7/claude-code-templates) | Daniel Avila | Collection of resources with polished UI, usage dashboard, analytics, slash commands, hooks, agents |
| [ccexp](https://github.com/nyatinte/ccexp) | nyatinte | Interactive CLI for discovering and managing Claude Code configuration files |
| [better-ccflare](https://github.com/tombii/better-ccflare) | tombii | Enhanced usage dashboard with performance enhancements, extended provider support, Docker deployment |
| [Claudex](https://github.com/kunwar-shah/claudex) | Kunwar Shah | Web-based browser for exploring conversation history with full-text search and analytics |
| [viberank](https://github.com/nikshepsvn/viberank) | nikshepsvn | Community-driven leaderboard for visualizing and competing based on Claude Code usage statistics |

---

## Contributing

Have a resource to share? Check out the [awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) repository for the full collection and contribution guidelines.

## License

This guide is derived from [awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) (CC BY-NC-ND 4.0). Individual resources maintain their own licenses.

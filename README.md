#  Resource List: Claude Code MCP Servers

[![Claude Code](https://img.shields.io/badge/Claude-Code-8B5CF6?logo=anthropic&logoColor=white)](https://claude.ai/download)
[![Claude Code Projects Index](https://img.shields.io/badge/Claude_Code-Projects_Index-blue?logo=github)](https://github.com/danielrosehill/Claude-Code-Repos-Index)
[![Master Index](https://img.shields.io/badge/GitHub-Master_Index-green?logo=github)](https://github.com/danielrosehill/Github-Master-Index)

A curated list of Model Context Protocol (MCP) servers for Claude Code and compatible AI development tools. This collection helps developers extend Claude Code's capabilities with specialized integrations.

**Last Updated:** 2025-10-28

> This is not a definitive list of all available MCP servers. The ecosystem is rapidly evolving, and new servers are constantly being developed. Many additional MCP servers can be connected to Claude Code through distribution platforms like Smithery and integration tools like Zapier, which allow one MCP to connect to many services.  

## Table of Contents

- [AI Model Integration](#ai-model-integration)
- [Memory & Context Management](#memory--context-management)
- [Code Analysis & Search](#code-analysis--search)
- [Development Tools](#development-tools)
- [Agent Orchestration](#agent-orchestration)
- [Browser & Web Automation](#browser--web-automation)
- [Workflow Automation](#workflow-automation)
- [Voice & Audio](#voice--audio)
- [Security & Sandboxing](#security--sandboxing)
- [Documentation](#documentation)
- [IDE & Editor Integration](#ide--editor-integration)
- [Screenshots & Media](#screenshots--media)
- [Communication](#communication)
- [Data Science](#data-science)
- [Resources & Discovery](#resources--discovery)
- [Claude Code Extension](#claude-code-extension)

---

## AI Model Integration

Connect Claude Code to external LLMs and AI services for enhanced capabilities.

### Claude Code Gemini MCP

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/RaiAnsar/claude_code-gemini-mcp)
[![Stars](https://img.shields.io/github/stars/RaiAnsar/claude_code-gemini-mcp?style=social)](https://github.com/RaiAnsar/claude_code-gemini-mcp)
[![Last Commit](https://img.shields.io/github/last-commit/RaiAnsar/claude_code-gemini-mcp)](https://github.com/RaiAnsar/claude_code-gemini-mcp)

A tool that integrates Google's Gemini AI with Claude Code through an MCP server, enabling collaborative AI workflows. Features three primary tools: ask Gemini questions, receive code reviews focusing on security and performance, and brainstorm solutions. Includes one-line installation and quick 2-minute setup process.

### Claude Gemini MCP Slim

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/cmdaltctr/claude-gemini-mcp-slim)
[![Stars](https://img.shields.io/github/stars/cmdaltctr/claude-gemini-mcp-slim?style=social)](https://github.com/cmdaltctr/claude-gemini-mcp-slim)
[![Last Commit](https://img.shields.io/github/last-commit/cmdaltctr/claude-gemini-mcp-slim)](https://github.com/cmdaltctr/claude-gemini-mcp-slim)

A lightweight MCP integration connecting Claude Code with Google's Gemini AI models. Features quick queries, code analysis, full codebase analysis with Gemini's 1M+ token context window, smart model selection, 20+ slash commands, automated hooks for pre-edit analysis and pre-commit review, and real-time streaming. Shared architecture allows one installation to serve multiple AI clients.

### Deep Code Reasoning MCP

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/haasonsaas/deep-code-reasoning-mcp)
[![Stars](https://img.shields.io/github/stars/haasonsaas/deep-code-reasoning-mcp?style=social)](https://github.com/haasonsaas/deep-code-reasoning-mcp)
[![Last Commit](https://img.shields.io/github/last-commit/haasonsaas/deep-code-reasoning-mcp)](https://github.com/haasonsaas/deep-code-reasoning-mcp)

An MCP server enabling Claude Code to collaborate with Google's Gemini AI for advanced code analysis through multi-model workflows. Features Gemini 2.5 Pro integration with 1-million token context window, AI-to-AI iterative conversations for complex problem-solving, execution flow tracing for data transformations, cross-system impact analysis, performance bottleneck detection (N+1 patterns, memory leaks), and hypothesis testing with evidence-based validation. Implements an "escalation" strategy treating LLMs as heterogeneous microservices.

### Claude Code Multi AI MCP

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/RaiAnsar/claude_code-multi-AI-MCP)
[![Stars](https://img.shields.io/github/stars/RaiAnsar/claude_code-multi-AI-MCP?style=social)](https://github.com/RaiAnsar/claude_code-multi-AI-MCP)
[![Last Commit](https://img.shields.io/github/last-commit/RaiAnsar/claude_code-multi-AI-MCP)](https://github.com/RaiAnsar/claude_code-multi-AI-MCP)

An MCP server enabling Claude Code to integrate with multiple AI providers simultaneously, including Google Gemini, Grok-3, ChatGPT, and DeepSeek. Provides natural language interface, flexible configuration for any combination of AIs, specialized functions for code reviews and architectural advice, and AI debates. Features local credential storage with security focus.

### Gemini MCP

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/RLabs-Inc/gemini-mcp)
[![Stars](https://img.shields.io/github/stars/RLabs-Inc/gemini-mcp?style=social)](https://github.com/RLabs-Inc/gemini-mcp)
[![Last Commit](https://img.shields.io/github/last-commit/RLabs-Inc/gemini-mcp)](https://github.com/RLabs-Inc/gemini-mcp)

An MCP server for integrating Google's Gemini models with Claude Code. Features six primary capabilities: direct query, collaborative brainstorming, code analysis for quality/security/performance, text analysis for sentiment and key points, content summarization at varying detail levels, and image prompt generation for image generation tools.

### MCP Gemini Assistant

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/peterkrueck/mcp-gemini-assistant)
[![Stars](https://img.shields.io/github/stars/peterkrueck/mcp-gemini-assistant?style=social)](https://github.com/peterkrueck/mcp-gemini-assistant)
[![Last Commit](https://img.shields.io/github/last-commit/peterkrueck/mcp-gemini-assistant)](https://github.com/peterkrueck/mcp-gemini-assistant)

An MCP server that integrates Google's Gemini AI with Claude Code for complex coding problems. Features session management with automatic cleanup after 1 hour, file attachments from local filesystem, hybrid context support combining text and files, follow-up questions without resending context, context caching per session, multiple parallel sessions, and uses Gemini 2.5 Pro by default.

---

## Memory & Context Management

Persistent memory and context enhancement for AI coding assistants.

### Byterover Cipher

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/campfirein/cipher)
[![Stars](https://img.shields.io/github/stars/campfirein/cipher?style=social)](https://github.com/campfirein/cipher)
[![Last Commit](https://img.shields.io/github/last-commit/campfirein/cipher)](https://github.com/campfirein/cipher)

An open-source memory layer engineered for coding agents with persistent context retention across multiple AI assistants and IDEs. Features cross-IDE compatibility (Cursor, Claude Code, Windsurf, Cline, VS Code), dual memory architecture capturing both System 1 knowledge and System 2 reasoning, team collaboration with workspace memory, semantic search with configurable embedding providers, and zero-configuration installation.

### Claude Context

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/zilliztech/claude-context)
[![Stars](https://img.shields.io/github/stars/zilliztech/claude-context?style=social)](https://github.com/zilliztech/claude-context)
[![Last Commit](https://img.shields.io/github/last-commit/zilliztech/claude-context)](https://github.com/zilliztech/claude-context)

An MCP plugin providing semantic code search capabilities for Claude Code and other AI coding agents. Addresses the challenge of providing comprehensive codebase context without excessive token consumption. Features semantic search across millions of lines using hybrid search (BM25 + dense vector embeddings), approximately 40% token reduction with equivalent retrieval quality, and integration with Zilliz Cloud vector database.

### Claude Context Local

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/FarhanAliRaza/claude-context-local)
[![Stars](https://img.shields.io/github/stars/FarhanAliRaza/claude-context-local?style=social)](https://github.com/FarhanAliRaza/claude-context-local)
[![Last Commit](https://img.shields.io/github/last-commit/FarhanAliRaza/claude-context-local)](https://github.com/FarhanAliRaza/claude-context-local)

A local semantic code search system operating entirely on-device using Google's EmbeddingGemma model. Features 100% local operation eliminating cloud services and API costs, multi-language support for 15 file extensions across 9+ programming languages, intelligent chunking with Python AST-based parsing and tree-sitter for other languages, FAISS-based similarity search with optional GPU acceleration, rich metadata extraction including function names and class hierarchies, and automatic device detection (CUDA, MPS, or CPU).

### Claude Historian

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/Vvkmnn/claude-historian)
[![Stars](https://img.shields.io/github/stars/Vvkmnn/claude-historian?style=social)](https://github.com/Vvkmnn/claude-historian)
[![Last Commit](https://img.shields.io/github/last-commit/Vvkmnn/claude-historian)](https://github.com/Vvkmnn/claude-historian)

An MCP server enabling Claude to search and access conversation history from Claude Code and Claude Desktop. Features conversation history searching with smart prioritization, file context discovery, error pattern matching and solution retrieval, workflow detection, parallel processing for 6x speed improvements, TF-IDF inspired relevance scoring, and runs entirely locally without persistent storage.

### DeepContext MCP

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/Wildcard-Official/deepcontext-mcp)
[![Stars](https://img.shields.io/github/stars/Wildcard-Official/deepcontext-mcp?style=social)](https://github.com/Wildcard-Official/deepcontext-mcp)
[![Last Commit](https://img.shields.io/github/last-commit/Wildcard-Official/deepcontext-mcp)](https://github.com/Wildcard-Official/deepcontext-mcp)

An MCP server adding symbol-aware semantic search to Codex CLI, Claude Code, and other agents. Features semantic search matching code by meaning rather than exact text, token efficiency returning focused chunks, fast pre-indexing for instant discovery, AST-based analysis using Tree-sitter parsers, hybrid search combining vector similarity with BM25, smart content filtering excluding tests and generated code, and multi-language support (TypeScript, Python, JavaScript).

### MCP Memory Service

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/doobidoo/mcp-memory-service)
[![Stars](https://img.shields.io/github/stars/doobidoo/mcp-memory-service?style=social)](https://github.com/doobidoo/mcp-memory-service)
[![Last Commit](https://img.shields.io/github/last-commit/doobidoo/mcp-memory-service)](https://github.com/doobidoo/mcp-memory-service)

A production-ready memory management system for AI assistants with semantic search and multi-client support. Features hybrid backend combining local SQLite (5ms reads) with Cloudflare synchronization, zero database locks for concurrent access, semantic search with vector embeddings, natural language time queries, tag-based organization, interactive document upload (PDF, TXT, MD, JSON), OAuth 2.1 Dynamic Client Registration, web dashboard, and cross-platform compatibility.

---

## Code Analysis & Search

Tools for understanding, analyzing, and navigating codebases.

### Git MCP

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/idosal/git-mcp)
[![Stars](https://img.shields.io/github/stars/idosal/git-mcp?style=social)](https://github.com/idosal/git-mcp)
[![Last Commit](https://img.shields.io/github/last-commit/idosal/git-mcp)](https://github.com/idosal/git-mcp)

A free, open-source, remote MCP server connecting AI assistants to GitHub projects, eliminating code hallucinations by providing access to current documentation and code. Features latest documentation access ensuring accurate responses, smart search reducing token usage, zero setup cloud-based service, multiple deployment options (specific repos or dynamic access), privacy-focused with no authentication required, wide compatibility with multiple IDEs, and embedded chat interface.

### Lucidity MCP

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/hyperb1iss/lucidity-mcp)
[![Stars](https://img.shields.io/github/stars/hyperb1iss/lucidity-mcp?style=social)](https://github.com/hyperb1iss/lucidity-mcp)
[![Last Commit](https://img.shields.io/github/last-commit/hyperb1iss/lucidity-mcp)](https://github.com/hyperb1iss/lucidity-mcp)

An AI-powered code quality analysis MCP server helping AI assistants review code more effectively before commits. Features comprehensive issue detection across 10 quality dimensions (complexity, security, performance, test coverage, style, duplication, error handling, and more), contextual analysis comparing changes against original code, language-agnostic functionality, Git-aware diff analysis, lightweight extensible framework, and support for both stdio and SSE transport protocols.

---

## Development Tools

Tools enhancing development workflows and debugging capabilities.

### Claude Code MCP (by steipete)

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/steipete/claude-code-mcp)
[![Stars](https://img.shields.io/github/stars/steipete/claude-code-mcp?style=social)](https://github.com/steipete/claude-code-mcp)
[![Last Commit](https://img.shields.io/github/last-commit/steipete/claude-code-mcp)](https://github.com/steipete/claude-code-mcp)

An MCP server enabling running Claude Code in one-shot mode with automatic permission bypassing. Addresses limitations where editors struggle with complex, multi-step operations. Features automatic execution with `--dangerously-skip-permissions` flag, unified `claude_code` tool for LLM integration, reduces context usage by queuing commands, enables cost-effective task offloading using cheaper models for execution, and supports code generation, Git operations, web search, and terminal commands.

### Claude Code MCP (by willccbb)

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/willccbb/claude-code-mcp)
[![Stars](https://img.shields.io/github/stars/willccbb/claude-code-mcp?style=social)](https://github.com/willccbb/claude-code-mcp)
[![Last Commit](https://img.shields.io/github/last-commit/willccbb/claude-code-mcp)](https://github.com/willccbb/claude-code-mcp)

A project enabling Claude to leverage Model Context Protocol servers for expanded capabilities. Features dual server approach using established and custom MCP servers, nine primary servers including brave-search, GitHub, filesystem, fetch, memory, SQLite, Slack, Linear, and e2b. Enforces type hints, maintains docstrings, uses uv package manager, requires comprehensive testing, and includes organized structure with separate directories.

### Claude Debugs For You

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/jasonjmcghee/claude-debugs-for-you)
[![Stars](https://img.shields.io/github/stars/jasonjmcghee/claude-debugs-for-you?style=social)](https://github.com/jasonjmcghee/claude-debugs-for-you)
[![Last Commit](https://img.shields.io/github/last-commit/jasonjmcghee/claude-debugs-for-you)](https://github.com/jasonjmcghee/claude-debugs-for-you)

A VS Code extension and MCP server enabling Claude and other LLMs to interactively debug code across multiple languages. Features interactive debugging with breakpoint management and expression evaluation, language-agnostic implementation, dual connectivity modes (stdio and SSE endpoint), works with Claude Desktop, Continue IDE, and Cursor, graceful multi-window handling, and status indicator showing operational state.

### CodeMCP

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/ezyang/codemcp)
[![Stars](https://img.shields.io/github/stars/ezyang/codemcp?style=social)](https://github.com/ezyang/codemcp)
[![Last Commit](https://img.shields.io/github/last-commit/ezyang/codemcp)](https://github.com/ezyang/codemcp)

A coding assistant MCP for Claude Desktop transforming Claude into a pair programming assistant. Features subscription-based pricing model designed for Claude Pro, auto-accept by default allowing independent agent progress, security-conscious shell access restricting commands to pre-declared options in `codemcp.toml`, Git-based version control for all LLM edits enabling fine-grained rollback, and IDE agnostic design working with any editor.

### Tauri Plugin MCP

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/P3GLEG/tauri-plugin-mcp)
[![Stars](https://img.shields.io/github/stars/P3GLEG/tauri-plugin-mcp?style=social)](https://github.com/P3GLEG/tauri-plugin-mcp)
[![Last Commit](https://img.shields.io/github/last-commit/P3GLEG/tauri-plugin-mcp)](https://github.com/P3GLEG/tauri-plugin-mcp)

A Tauri plugin and MCP server enabling AI agents to debug and interact with Tauri applications. Features window interaction including screenshot capture with configurable quality and HTML DOM access, window control for position/size/focus management, user input simulation with mouse clicks/movements and programmatic text input, JavaScript execution within application context, localStorage operations, and connectivity verification. Supports both IPC and TCP socket modes with Rust-based socket server and TypeScript client.

---

## Agent Orchestration

Tools for managing and orchestrating AI agents remotely.

### SystemPrompt Code Orchestrator

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/systempromptio/systemprompt-code-orchestrator)
[![Stars](https://img.shields.io/github/stars/systempromptio/systemprompt-code-orchestrator?style=social)](https://github.com/systempromptio/systemprompt-code-orchestrator)
[![Last Commit](https://img.shields.io/github/last-commit/systempromptio/systemprompt-code-orchestrator)](https://github.com/systempromptio/systemprompt-code-orchestrator)

An open-source MCP server transforming workstations into remotely-accessible AI coding agent platforms. Features multi-agent support with Claude Code CLI, session isolation with real-time streaming, remote access via local network HTTP and optional Cloudflare Tunnel, mobile-first design supporting voice commands, persistent task state surviving restarts, real-time event streaming and structured logging, pre-built prompt templates, push notification support, and full Docker containerization with host machine integration.

---

## Browser & Web Automation

Tools for browser control, testing, and web automation.

### Chrome DevTools MCP

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/benjaminr/chrome-devtools-mcp)
[![Stars](https://img.shields.io/github/stars/benjaminr/chrome-devtools-mcp?style=social)](https://github.com/benjaminr/chrome-devtools-mcp)
[![Last Commit](https://img.shields.io/github/last-commit/benjaminr/chrome-devtools-mcp)](https://github.com/benjaminr/chrome-devtools-mcp)

An MCP server integrating Chrome's debugging capabilities with Claude for AI-assisted web application debugging. Features Chrome management with remote debugging, network analysis monitoring HTTP requests/responses with filtering, console integration capturing browser logs and executing JavaScript, performance monitoring with page load metrics, storage and security management for cookies and localStorage, and DOM inspection for querying page structure.

### Claude Code Playwright MCP Test

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/terryso/claude-code-playwright-mcp-test)
[![Stars](https://img.shields.io/github/stars/terryso/claude-code-playwright-mcp-test?style=social)](https://github.com/terryso/claude-code-playwright-mcp-test)
[![Last Commit](https://img.shields.io/github/last-commit/terryso/claude-code-playwright-mcp-test)](https://github.com/terryso/claude-code-playwright-mcp-test)

A demonstration project for the `claude-test` CLI framework showcasing intelligent automation testing with Claude Code and Playwright MCP. Features natural language testing where Claude interprets plain language test steps, dynamic element targeting where Playwright MCP automatically assigns unique identifiers, multi-environment support, session persistence for 80-95% performance improvement, reusable step libraries, smart test reporting with HTML/JSON formats, and Cursor IDE integration.

---

## Workflow Automation

Connect Claude Code to workflow automation platforms.

### n8n-mcp

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/czlonkowski/n8n-mcp)
[![Stars](https://img.shields.io/github/stars/czlonkowski/n8n-mcp?style=social)](https://github.com/czlonkowski/n8n-mcp)
[![Last Commit](https://img.shields.io/github/last-commit/czlonkowski/n8n-mcp)](https://github.com/czlonkowski/n8n-mcp)

An MCP server integrating n8n workflow automation with AI assistants like Claude. Bridges n8n's workflow platform with AI models, enabling them to understand and work with n8n nodes effectively. Features 541 n8n nodes with 99% coverage and detailed schemas, 2,646 pre-extracted configurations from popular templates, 2,709 workflow templates with complete metadata, multiple deployment options (npx, Docker, local, Railway), and optional workflow management with API credentials.

---

## Voice & Audio

Speech-to-text and text-to-speech capabilities for AI assistants.

### MCP Server Whisper

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/arcaputo3/mcp-server-whisper)
[![Stars](https://img.shields.io/github/stars/arcaputo3/mcp-server-whisper?style=social)](https://github.com/arcaputo3/mcp-server-whisper)
[![Last Commit](https://img.shields.io/github/last-commit/arcaputo3/mcp-server-whisper)](https://github.com/arcaputo3/mcp-server-whisper)

A Python-based MCP server enabling AI assistants like Claude to process audio files using OpenAI's transcription and speech services. Features audio processing with automatic format conversion and compression, transcription with multiple OpenAI models (whisper-1, gpt-4o-transcribe, gpt-4o-mini-transcribe), enhanced transcription with specialized templates, speech generation using gpt-4o-mini-tts with customizable voices, type-safe responses using Pydantic models, and MCP-native parallel processing.

### VoiceMode

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/mbailey/voicemode)
[![Stars](https://img.shields.io/github/stars/mbailey/voicemode?style=social)](https://github.com/mbailey/voicemode)
[![Last Commit](https://img.shields.io/github/last-commit/mbailey/voicemode)](https://github.com/mbailey/voicemode)

An MCP server enabling natural voice conversations with Claude Code and other AI assistants through speech-to-text and text-to-speech. Features natural voice conversations allowing verbal interaction, local model support with OpenAI API-compatible services, real-time processing with low latency, automatic silence detection, multiple communication transports, privacy-focused options with local Whisper.cpp and Kokoro, and cross-platform compatibility (Linux, macOS, Windows WSL, NixOS).

---

## Security & Sandboxing

Secure execution environments and sandboxing tools.

### E2B MCP Server

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/e2b-dev/mcp-server)
[![Stars](https://img.shields.io/github/stars/e2b-dev/mcp-server?style=social)](https://github.com/e2b-dev/mcp-server)
[![Last Commit](https://img.shields.io/github/last-commit/e2b-dev/mcp-server)](https://github.com/e2b-dev/mcp-server)

The source code for the E2B MCP server enabling code execution capabilities within Claude Desktop through E2B Sandbox integration. Bridges Claude AI with cloud-based code execution environments. Features dual implementation in JavaScript and Python, seamless integration with Claude Desktop via MCP protocol, code interpreter access through sandboxed environment, installation via Smithery automation tool, and open-source under Apache 2.0 license.

---

## Documentation

Tools for accessing and managing technical documentation.

### Augments MCP Server

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/augmnt/augments-mcp-server)
[![Stars](https://img.shields.io/github/stars/augmnt/augments-mcp-server?style=social)](https://github.com/augmnt/augments-mcp-server)
[![Last Commit](https://img.shields.io/github/last-commit/augmnt/augments-mcp-server)](https://github.com/augmnt/augments-mcp-server)

A sophisticated documentation retrieval system providing real-time access to framework documentation, context-aware assistance, and intelligent caching. Features categorized framework registry covering web, backend, mobile, AI/ML, design, and development tools, multi-level caching with TTL-based strategies for stable/beta/development versions, smart invalidation with automatic refresh, ability to combine documentation from multiple frameworks simultaneously, 9 MCP tools with structured JSON outputs, hosted version at mcp.augments.dev/mcp, and local installation for customization.

### Context7

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/upstash/context7)
[![Stars](https://img.shields.io/github/stars/upstash/context7?style=social)](https://github.com/upstash/context7)
[![Last Commit](https://img.shields.io/github/last-commit/upstash/context7)](https://github.com/upstash/context7)

An MCP server delivering up-to-date, version-specific code documentation directly into LLM prompts by fetching current documentation from source repositories. Addresses outdated training data by providing real-time documentation access, version-specific information for libraries and frameworks, integration with multiple AI coding editors (Cursor, VS Code, Claude Code, Windsurf), support for both remote and local server connections, optional API key authentication for higher rate limits and private repository access, and multi-language documentation support.

### DevDocs

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/cyberagiinc/DevDocs)
[![Stars](https://img.shields.io/github/stars/cyberagiinc/DevDocs?style=social)](https://github.com/cyberagiinc/DevDocs)
[![Last Commit](https://img.shields.io/github/last-commit/cyberagiinc/DevDocs)](https://github.com/cyberagiinc/DevDocs)

A free, private, UI-based technical documentation MCP server for developers and software engineers. Transforms weeks of documentation research into hours of productive development by intelligently crawling, extracting, and organizing technical documentation. Features intelligent crawling with smart depth control and automatic child URL discovery, performance with parallel processing and smart caching, content processing with clean extraction and multiple export formats, and enterprise capabilities with error recovery and team management.

---

## IDE & Editor Integration

Integrations with specific IDEs and text editors.

### Obsidian Claude Code MCP

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/iansinnott/obsidian-claude-code-mcp)
[![Stars](https://img.shields.io/github/stars/iansinnott/obsidian-claude-code-mcp?style=social)](https://github.com/iansinnott/obsidian-claude-code-mcp)
[![Last Commit](https://img.shields.io/github/last-commit/iansinnott/obsidian-claude-code-mcp)](https://github.com/iansinnott/obsidian-claude-code-mcp)

An Obsidian plugin implementing an MCP server enabling Claude Code and other AI tools to interact with Obsidian vaults. Bridges Obsidian note-taking with Claude's AI capabilities. Features dual transport support (WebSocket for Claude Code, HTTP/SSE for Claude Desktop), file read/write operations through MCP protocol, automatic vault discovery, access to current active file and vault structure, customizable port settings, and categorized tool system with shared and IDE-specific tools.

---

## Screenshots & Media

Tools for generating and managing screenshots and visual media.

### Code Screenshot MCP

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/MoussaabBadla/code-screenshot-mcp)
[![Stars](https://img.shields.io/github/stars/MoussaabBadla/code-screenshot-mcp?style=social)](https://github.com/MoussaabBadla/code-screenshot-mcp)
[![Last Commit](https://img.shields.io/github/last-commit/MoussaabBadla/code-screenshot-mcp)](https://github.com/MoussaabBadla/code-screenshot-mcp)

An MCP server enabling Claude to generate syntax-highlighted code screenshots with professional color themes directly within conversations. Features five professional themes (Dracula, Nord, Monokai, GitHub Light, GitHub Dark), direct file integration with automatic language detection supporting 20+ programming languages, line-range selection for targeted snippets, Git diff visualization for staged and unstaged changes, batch processing for multiple files, and native integration with Claude Desktop and Claude Code. Built with TypeScript, Playwright, and Highlight.js.

---

## Communication

External communication and relay tools.

### TSGram MCP

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/areweai/tsgram-mcp)
[![Stars](https://img.shields.io/github/stars/areweai/tsgram-mcp?style=social)](https://github.com/areweai/tsgram-mcp)
[![Last Commit](https://img.shields.io/github/last-commit/areweai/tsgram-mcp)](https://github.com/areweai/tsgram-mcp)

A Telegram integration connecting Claude Code sessions to Telegram for AI-powered code assistance on mobile devices. Features local Docker container running Telegram webhook server, web dashboard at localhost:3000 for bot management, AI-powered responses about codebases using Claude 3.5 Sonnet or GPT-4, Unix command execution via `:h` prefix, optional "dangerzone" mode for file editing, local-first architecture for security, and authentication limited to authorized Telegram user ID.

---

## Data Science

Tools for data analysis and scientific computing.

### Quick Data MCP

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/disler/quick-data-mcp)
[![Stars](https://img.shields.io/github/stars/disler/quick-data-mcp?style=social)](https://github.com/disler/quick-data-mcp)
[![Last Commit](https://img.shields.io/github/last-commit/disler/quick-data-mcp)](https://github.com/disler/quick-data-mcp)

An MCP server implementation focused on data analytics capabilities for AI agents. Teaches developers how to build powerful MCP servers by integrating tools, resources, and prompts into cohesive agentic workflows. Features arbitrary data analysis on JSON and CSV files, integration with Claude Code for AI-powered data analytics, and demonstrates three MCP building blocks: Tools (functions AI models invoke), Resources (data structures for AI access), and Prompts (pre-built conversation templates).

---

## Resources & Discovery

Resource lists and tools for discovering MCP servers and Claude Code plugins.

### Awesome Claude Code Plugins

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/ccplugins/awesome-claude-code-plugins)
[![Stars](https://img.shields.io/github/stars/ccplugins/awesome-claude-code-plugins?style=social)](https://github.com/ccplugins/awesome-claude-code-plugins)
[![Last Commit](https://img.shields.io/github/last-commit/ccplugins/awesome-claude-code-plugins)](https://github.com/ccplugins/awesome-claude-code-plugins)

A curated directory of Claude Code plugins—lightweight packages extending Claude Code functionality through customizable components. Covers slash commands for frequent operations, subagents for specialized development tasks, MCP servers for protocol integrations, and hooks for workflow modifications. Helps developers discover and install plugins across automation, security, testing, documentation, and design categories. Users can manage plugins dynamically using the `/plugin` command to maintain focused system context.

### ls-mcp

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/lirantal/ls-mcp)
[![Stars](https://img.shields.io/github/stars/lirantal/ls-mcp?style=social)](https://github.com/lirantal/ls-mcp)
[![Last Commit](https://img.shields.io/github/last-commit/lirantal/ls-mcp)](https://github.com/lirantal/ls-mcp)

A command-line tool discovering and listing MCP server configurations across AI applications like Cursor, Claude Desktop, and VS Code. Features automatic MCP server detection across various AI applications and agentic IDEs, directory bubbling with intelligent searching for project and global MCP configurations, real-time process detection of active MCP servers, security analysis examining environment variables and API keys for exposed credentials, and both CLI and JSON output formats for programmatic consumption.

---

## Claude Code Extension

Tools that extend or transform Claude Code itself into new capabilities.

### Claude Code MCP (as MCP Server)

[![View Repo](https://img.shields.io/badge/View-Repo-blue?logo=github)](https://github.com/steipete/claude-code-mcp)
[![Stars](https://img.shields.io/github/stars/steipete/claude-code-mcp?style=social)](https://github.com/steipete/claude-code-mcp)
[![Last Commit](https://img.shields.io/github/last-commit/steipete/claude-code-mcp)](https://github.com/steipete/claude-code-mcp)

An MCP server that makes Claude Code itself available as an MCP tool to other AI agents. Enables running Claude Code in one-shot mode with automatic permission bypassing, allowing other AI systems to leverage Claude Code's capabilities programmatically for complex multi-step coding operations.

---

## Contributing

This is a living document. If you've created or discovered an MCP server that would be valuable to the community, please consider contributing! Open an issue or submit a pull request.

## License

This list is provided under the MIT License. Individual projects maintain their own licenses as indicated in their respective repositories.

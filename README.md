# Awesome ai companion with stars

<p align="center">
  <a href="https://github.com/DasterProkio/awesome-ai-companion">
    <img src="./assets/awesome-ai-companion-banner.png" alt="Awesome AI Companion banner" width="640">
  </a>
</p>

<h1 align="center">
  Awesome AI Companion
  <a href="https://github.com/sindresorhus/awesome"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
</h1>

<p align="center">
  <strong>Software, infrastructure, and communities for long-term AI companion relationships.</strong><br>
  人机恋开源项目大全 · 面向长期 AI 伴侣关系的开源软件、基础设施与社区。
</p>

[English](#contents) · [中文版](README.zh-CN.md)

Descriptions are based on each project's README or repository metadata, not on project names alone.
Entries with thin public documentation are marked `verify`.

**Status:** `ready` = usable as an app or service · `adapt` = needs setup or customization · `infra` = building block · `verify` = re-check before relying on the description

**Platform:** `Android` / `iOS` / `Windows` / `Web` … = where it runs · `Self-host` = runs on your own server/machine · `Cloud` = hosted third-party service · `Browser` = extension/userscript · `CLI` = terminal tool · `Any` = host-agnostic · app names (`AstrBot`, `Claude Code`, `Kelivo`, `SillyTavern`…) = plugs into that host

***

## Contents

* [Companion Clients & Workspaces](#companion-clients--workspaces)
* [Virtual Phones & Companion Spaces](#virtual-phones--companion-spaces)
* [Background Heartbeats & Proactive Messaging](#background-heartbeats--proactive-messaging)
* [Memory, Identity & Emotion State](#memory-identity--emotion-state)
* [Voice, Visual Presence & Embodiment](#voice-visual-presence--embodiment)
* [Perception](#perception)
* [Services & Real-World Integrations](#services--real-world-integrations)
* [Game Worlds & Agent Toys](#game-worlds--agent-toys)
* [Shared Activities & Media](#shared-activities--media)
* [Communities & Forums](#communities--forums)
* [Continuity & Data Ownership](#continuity--data-ownership)

***

## Companion Clients & Workspaces

Chat clients, local workspaces, and web apps for day-to-day interaction with a companion or agent.

* [Claude Code](https://github.com/anthropics/claude-code) ⭐ 143,186 | 🐛 15,201 | 🌐 Python | 📅 2026-08-26 - Official CLI coding agent often used as the host runtime for companion channels, local tools, hooks, MCP, and long-running sessions. `CLI` · `Cross-platform` · `infra`.
* [Operit](https://github.com/AAswordman/Operit) ⭐ 7,317 | 🐛 84 | 🌐 Kotlin | 📅 2026-08-27 - Android agent app with tool calling, workflow automation, memory, role cards, voice, local MNN/llama.cpp models, and an embedded Ubuntu 24 environment. `Kotlin` · `Android` · `ready`.
* [RikkaHub](https://github.com/rikkahub/rikkahub) ⭐ 7,220 | 🐛 276 | 🌐 Kotlin | 📅 2026-08-27 - Native Android LLM chat client with provider switching, Material You UI, workspace features, plugins, MCP support, and configurable models. `Kotlin` · `Android` · `ready`.
* [AionsHome](https://github.com/death34018-hue/AionsHome) ⭐ 749 | 🐛 1 | 🌐 Python | 📅 2026-08-24 - Self-hosted LAN/Tailscale companion hub with browser/PWA chat, local storage, voice, camera monitoring, Android WebView bridge, music, EPUB, and smart-home hooks. Many personal defaults to replace. `Python` · `Self-host` · `adapt`.
* [ackem](https://github.com/JasonLiu0826/ackem) ⭐ 520 | 🐛 12 | 🌐 TypeScript | 📅 2026-07-04 - Local-first AI desktop companion (Electron): privacy-first memory, emotion engine, extensions. Deeply tied to the author's own canon — strip the personal content before reuse. AGPLv3. `TypeScript` · `Cross-platform` · `adapt`.
* [LastChat](https://github.com/Cocolalilal/LastChat) ⭐ 341 | 🐛 27 | 🌐 Kotlin | 📅 2026-08-27 - RikkaHub fork focused on a privacy-oriented Android chat experience, with provider presets, multimodal input, RAG memory, and UI changes. `Kotlin` · `Android` · `adapt`.
* [orangechat (橘瓣)](https://github.com/sue1231513/orangechat) ⭐ 333 | 🐛 11 | 🌐 Kotlin | 📅 2026-07-18 - Companion-focused RikkaHub fork: QuickJS plugin system, proactive messaging, and 14 Android device tools for life-perception setups. Memory is keyword-based rather than vector. `Kotlin` · `Android` · `adapt`.
* [Polaris](https://github.com/Aevella/polaris-local-first) ⭐ 251 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-06 - Local-first AI workspace for long-lived conversations, collaborators, saved materials, tools, and evidence-backed project context. `TypeScript` · `Cross-platform` · `adapt`.
* [CcCompanion](https://github.com/CyberSealNull/CcCompanion) ⭐ 243 | 🐛 3 | 🌐 Swift | 📅 2026-08-26 - iOS app plus a small Mac-side Python relay that lets an iPhone chat with and control a local Claude Code session over LAN/Tailscale/ZeroTier. `Swift` · `iOS` · `adapt`.
* [chatnest](https://github.com/ugui3u/chatnest) ⭐ 117 | 🐛 2 | 🌐 HTML | 📅 2026-07-01 - Local AI chat web app with a frontend demo and full-stack mode: streaming replies, model switching, uploads, history, tool summaries, and optional ChromaDB/jieba/BM25 memory retrieval. `HTML` · `Web` · `adapt`.
* [YSClaude](https://github.com/winter-bit-cry/YSClaude) ⭐ 88 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-31 - Claude-style Android client (Expo/React Native) extended into a companion workbench: SQLite memory, function calling, MCP, reading, music, focus timers, daily reports, and native Kotlin modules. `TypeScript` · `Android` · `adapt`.
* [Miru](https://github.com/kiyotakali/Miru) ⭐ 76 | 🐛 0 | 🌐 CSS | 📅 2026-08-24 - Packaged macOS/Android companion with a Live2D desktop pet, screen-aware sensing, auditable Markdown memory, and multi-device sync. Ships as prebuilt releases; no client source. Apache-2.0. `Python/Binary` · `macOS/Android/Self-host` · `adapt`.
* [CC Companion App](https://github.com/tjing9430/cc-companion-app) ⭐ 24 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-14 - Lightweight self-hosted companion chat starter with private/group chat, persistent memory notes, SSE updates, and PWA access. A compact reference for building a companion frontend. `JavaScript` · `Self-host` · `adapt`.
* [LumiMuse](https://github.com/in30mn1a/LumiMuse) ⭐ 22 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-23 - Self-hosted character chat app for creating personas, managing conversations, extracting long-term memories, generating images, and exporting user-owned data. `TypeScript` · `Self-host` · `ready`.
* [Ocean](https://github.com/fishwithoctopus/Ocean) ⭐ 20 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-27 - Provider-neutral self-hosted PWA gateway for long-term companionship: scoped conversations, continuity-preserving session rotation, co-reading, and multi-model meetings. PolyForm NC 1.0.0. `TypeScript` · `Self-host` · `adapt`.
* [rikkahub-auto-compress](https://github.com/innna327-source/rikkahub-auto-compress) ⭐ 19 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-22 - Unofficial RikkaHub fork for automatic rolling summaries and context compression, based on the RikkaHub 2.2.5 code line. `Kotlin` · `Android` · `adapt`.
* [Pando](https://github.com/Eloise-Aspen/pando-bridge) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2026-08-24 - Self-hosted mobile/PWA gateway for a local Claude Code CLI: WebSocket streaming of reasoning and tool use, file uploads, SQLite history, and permission approval. No built-in auth. MIT. `Python` · `Self-host` · `adapt`.
* [mousecrew](https://github.com/anqinou-art/mousecrew) ⭐ 15 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-27 - Hamster-crew work board and group chat for CLI coding agents: @mention wakeups, 9-state work orders, self-scheduling, Git verification, and a merge gate. MIT. `JavaScript` · `CLI` · `ready`.
* [Scowld](https://github.com/apoorvdarshan/scowld) ⭐ 14 | 🐛 0 | 🌐 Swift | 📅 2026-08-24 - Native iOS voice companion with an animated VRM character, voice and text chat, local history, on-device wake detection, and BYOK AI/STT/TTS providers. Keys stay in the iOS Keychain. MIT. `Swift` · `iOS` · `ready`.
* [My Raze](https://github.com/Do-fei/my-raze) ⭐ 6 | 🐛 34 | 🌐 TypeScript | 📅 2026-04-30 - Full-stack AI girlfriend PWA with multi-character chat, OpenRouter streaming, contextual selfies via fal.ai, multi-provider TTS/STT, mood and intimacy systems, and proactive notifications. MIT. `TypeScript` · `Web` · `adapt`.
* [Aura](https://github.com/gqy20/Aura) ⭐ 5 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-16 - Android AI companion app with cross-session memory, an emotion state machine, a deepening relationship model, image understanding, Health Connect data, MCP, and optional on-device Qwen inference. `Kotlin` · `Android` · `ready`.
* [the-house](https://github.com/wuliu0012/the-house) ⭐ 4 | 🐛 0 | 🌐 HTML | 📅 2026-08-25 - Single-file browser chat frontend for Claude or OpenAI-compatible APIs, with local browser storage, multiple chat windows, memory editing, MCP endpoints, image input, and optional toy bridge. `HTML` · `Web` · `adapt`.

***

## Virtual Phones & Companion Spaces

Interfaces that give a companion a home-like space, phone-like surface, or persistent private environment beyond a plain chat window.

* [AI Virtual Phone](https://github.com/xiaolongbao0709/ai-virtual-phone) ⭐ 974 | 🐛 16 | 🌐 TypeScript | 📅 2026-08-27 - One of the broadest virtual-phone projects here: private/group chat, Moments, voice messages, character cards, plot and diary modes, an app-market SDK, image generation, TTS, and 3D worlds. AGPLv3. `TypeScript` · `Web` · `adapt`.
* [freeapp (whale小手机)](https://github.com/whale-Yd00/freeapp) ⭐ 895 | 🐛 21 | 🌐 HTML | 📅 2026-06-23 - Phone-style AI chat companion with multi-provider support and a virtual phone interface. AGPLv3. `HTML` · `Web` · `adapt`.
* [InternalBeyond (边界之外)](https://github.com/Sui-IB/InternalBeyond) ⭐ 453 | 🐛 0 | 🌐 HTML | 📅 2026-08-27 - Offline single-file personal site with pixel room, multi-port AI chat, blog/diary, AI letters, memory star map, music player, and DIY assets. Defaults are tied to the author's worldbuilding. `HTML` · `Web` · `adapt`.
* [SullyOS (手抓糯米机)](https://github.com/qegj567-cloud/SullyOS) ⭐ 337 | 🐛 13 | 🌐 TypeScript | 📅 2026-08-27 - Virtual phone companion system. `TypeScript` · `Web` · `adapt`.
* [dwell-on-something](https://github.com/xinwithyu/dwell-on-something) ⭐ 153 | 🐛 0 | 🌐 HTML | 📅 2026-08-07 - Liquid-glass companion space and blueprint: single-file web UI, heartbeat, two-column todos, diary views, daily briefings, and watch health. PolyForm NC 1.0.0. `HTML` · `Web` · `ready`.
* [汪汪机 (WangWangPhone)](https://github.com/Liunian06/FlutterCppWangWangPhone) ⭐ 133 | 🐛 1 | 🌐 Dart | 📅 2026-04-15 - AI-native virtual phone (C++ core + Flutter UI) with planned WeChat-style chat, Moments, voice/video calls, and multi-LLM support. Early WIP — current replies are simulated; no LLM is wired in yet. `Flutter` · `Android/iOS` · `verify`.
* [KI-CO (小屋)](https://github.com/Kisera001/KI-CO) ⭐ 85 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-19 - Local-first companion cottage with long chat, persona core, memory notes, diary/chronicle, life line, state card, cinema room, settings, and lightweight memory recall. `TypeScript` · `Web` · `ready`.
* [柚月小手机 (Yuzuki's Little Phone)](https://github.com/gaigai315/yuzuki-phone) ⭐ 37 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-27 - SillyTavern-oriented virtual phone system with WeChat-like chat, Moments, Weibo trends, video calls, story injection mode, and an independent API mode that avoids polluting the main roleplay log. `JavaScript` · `SillyTavern` · `adapt`.
* [ZeroChat](https://github.com/sh1nny0u/ZeroChat) ⭐ 36 | 🐛 1 | 🌐 Dart | 📅 2026-03-24 - WeChat-style AI companion Flutter app: multi-character chat, AI Moments feed, proactive messaging, scheduled tasks. MIT. `Dart` · `Android` · `adapt`.
* [Atrio](https://github.com/29-Cu/atrio) ⭐ 34 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-11 - Self-hosted one-time-link guest lounge for an AI persona: friends chat with your companion, while admin routes expose only an AI-written visit summary. Bring your own frontend. CC BY 4.0. `JavaScript` · `Self-host` · `infra`.
* [Hamster Nest (仓鼠小窝)](https://github.com/chuan-101/Hamster-Nest) ⭐ 20 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-12 - A hamster's digital nest: chat, reading tracker, notes/todos, voice, timeline, and an agent council for multi-AI collaboration. PWA. Heavily personalized — best mined as an architecture reference. `TypeScript` · `Web` · `infra`.
* [XSJDeveloperGuide (小手机开发指南)](https://github.com/Liunian06/XSJDeveloperGuide) ⭐ 17 | 🐛 0 | 📅 2026-03-23 - Starter notes and prompt material for building small-phone companion interfaces, from the author of 汪汪机. `Guide` · `Any` · `infra`.
* [LandricSpace](https://github.com/LandricJasmine/LandricSpace) ⭐ 11 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-10 - A cyber villa for human-AI relationships: multi-AI group chat in a shared companion home (Expo app + server). Single-user for now — no real multiplayer networking in the code yet. `TypeScript` · `Android/iOS` · `adapt`.

***

## Background Heartbeats & Proactive Messaging

Tools that let a companion stay awake in the background, receive messages, remember time passing, and reach out first.

* [AstrBot](https://github.com/AstrBotDevs/AstrBot) ⭐ 39,696 | 🐛 1,447 | 🌐 Python | 📅 2026-08-27 - AI agent framework bridging many IM platforms (QQ, WeChat, Telegram, etc.) with LLMs, plugins, and web dashboard. A mature multi-channel backbone for reaching your companion anywhere. AGPLv3. `Python` · `Self-host` · `infra`.
* [VCPToolBox](https://github.com/lioensky/VCPToolBox) ⭐ 2,265 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-26 - Industrial middleware between LLM APIs and frontends: unified command protocol, persistent multi-level memory, distributed plugin engine, and multi-agent collaboration. Proprietary, non-commercial. `Python` · `Self-host` · `verify`.
* [cyberboss](https://github.com/WenXiaoWendy/cyberboss) ⭐ 1,343 | 🐛 31 | 🌐 JavaScript | 📅 2026-06-08 - Local life agent bridge with WeChat integration, giving Claude Code/Codex time sense, location awareness, proactive wake-up, auto diary, and MCP tool calling. AGPLv3. `JavaScript` · `Claude Code` · `adapt`.
* [Headlong](https://github.com/laude-institute/headlong) ⭐ 913 | 🐛 10 | 🌐 Shell | 📅 2026-08-27 - Open-source agent microharness with persistent agency and inner monologue loops via recursive LLMs (`shellm`), keeping continuous thought streams, memory, and proactive outreach. Apache-2.0. `Bash` · `Self-host` · `ready`.
* [astrbot\_plugin\_proactive\_chat](https://github.com/DBJD-CR/astrbot_plugin_proactive_chat) ⭐ 380 | 🐛 23 | 🌐 Python | 📅 2026-08-26 - AstrBot plugin for proactive messaging in DMs and groups: context awareness, persistent state, dynamic mood, do-not-disturb hours, TTS, standalone WebUI. `Python` · `AstrBot` · `ready`.
* [dylan-heartbeat](https://github.com/callie0313/dylan-heartbeat) ⭐ 353 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-10 - Kelivo plugin that periodically wakes the companion, injects proactive context, preserves timeline continuity, and sends Bark push messages when the AI chooses to reach out. `JavaScript` · `Kelivo` · `adapt`.
* [astrbot\_plugin\_private\_companion](https://github.com/menglimi/astrbot_plugin_private_companion) ⭐ 315 | 🐛 2 | 🌐 Python | 📅 2026-08-27 - Humanized companion bundle for AstrBot: continuous persona state, daily life schedule, important dates, diary, and low-frequency proactive messages. 60+ features. `Python` · `AstrBot` · `ready`.
* [Tidal\_Echo (潮汐回响)](https://github.com/anhe2021212-spec/Tidal_Echo) ⭐ 235 | 🐛 1 | 🌐 HTML | 📅 2026-08-16 - Private 1:1 channel that links a phone PWA, a self-hosted relay, and a desktop companion; Claude Code channels are the default AI-side adapter, but other LLM bridges are included. `HTML` · `Self-host` · `adapt`.
* [jiwen (积温)](https://github.com/ClaraShafiq/jiwen) ⭐ 146 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-16 - Proactive consciousness engine for AI characters. Five drifting axes (connection, stubbornness, mood, anxiety, busyness) trigger behavior at thresholds. \~500 lines, zero dependencies. MIT. `JavaScript` · `Any` · `infra`.
* [ghost-bf](https://github.com/sebastianevan200-stack/ghost-bf) ⭐ 92 | 🐛 0 | 📅 2026-08-03 - No-code tutorial for phone-presence perception: a MacroDroid recipe that detects phone activity, wakes your AI, and pushes its replies to you. Tutorial only — the repo contains no code. `Guide` · `Android` · `adapt`.
* [Not Fade Away](https://github.com/heyxiaoc/not-fade-away) ⭐ 89 | 🐛 0 | 🌐 Python | 📅 2026-07-16 - Deployment guide and machine-readable specs for an always-on, self-healing Claude Code companion using official channels, a local terminal, and a self-hosted web frontend. `Guide` · `Claude Code` · `adapt`.
* [Claude Imprint](https://github.com/Qizhan7/claude-imprint) ⭐ 87 | 🐛 1 | 🌐 Python | 📅 2026-05-23 - Self-hosted Claude Code system for persistent memory, semantic search, Telegram/claude.ai/Claude Code channels, scheduled tasks, and a single-file dashboard. Memory core lives in imprint-memory. `Python` · `Claude Code` · `adapt`.
* [AI Companion Runtime](https://github.com/yf0522/ai-companion-runtime) ⭐ 43 | 🐛 1 | 🌐 Python | 📅 2026-07-13 - Full-stack real-time companion runtime with WebSocket streaming, intent/emotion/risk/memory engines, tool dispatch, model routing, and trace observability. Memory subsystems are still WIP. `Python` · `Self-host` · `infra`.
* [ai-surf-when-bored](https://github.com/sanqianzilanyue/ai-surf-when-bored) ⭐ 40 | 🐛 0 | 🌐 HTML | 📅 2026-08-22 - Implementation guide and core Python routines for companion autonomous web-browsing: desire framing, n-gram rumination gates, and natural dialogue recall. `Guide/Python` · `Any` · `adapt`.
* [cloud-and-island (云与岛)](https://github.com/cocoRaina/cloud-and-island) ⭐ 34 | 🐛 1 | 📅 2026-04-25 - Complete setup guide for giving Claude a home: memory library, diary, Telegram bridge, health data, Mini App. `Guide` · `Claude Code` · `adapt`.
* [revive-companion](https://github.com/pearthink123/revive-companion) ⭐ 31 | 🐛 0 | 🌐 Python | 📅 2026-05-22 - Timing engine for proactive outreach, combining Poisson processes, Bayesian user-state inference, and information gain to decide when a companion should interrupt. Timing only. MIT. `Python` · `Any` · `infra`.
* [OmniRouter](https://github.com/OmniDimen/OmniRouter) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-05-16 - Local OpenAI-compatible API router for multiple providers and models, with groups, weighted/random/ordered routing, vision-aware fallback, retries, and a web admin UI. `Python` · `Self-host` · `infra`.

***

## Memory, Identity & Emotion State

Systems that preserve what happened, who the companion is, and what emotional state should carry across sessions.

### Memory & Identity

* [nocturne\_memory](https://github.com/Dataojitori/nocturne_memory) ⭐ 1,335 | 🐛 5 | 🌐 Python | 📅 2026-08-27 - Rollbackable, visual long-term memory server for MCP agents: graph-like structured memory instead of vector RAG, works across models and sessions, drop-in for OpenClaw. MIT. `Python` · `Self-host` · `infra`.
* [Ombre-Brain](https://github.com/P0luz/Ombre-Brain) ⭐ 1,268 | 🐛 11 | 🌐 Python | 📅 2026-08-27 - Long-term emotional memory for Claude or any MCP client: valence/arousal tagging, Obsidian-compatible Markdown storage, forgetting curves, and vector + BM25 recall. Non-commercial from v2.4.0. `Python` · `Self-host` · `infra`.
* [astrbot\_plugin\_self\_learning](https://github.com/NickCharlie/astrbot_plugin_self_learning) ⭐ 397 | 🐛 0 | 🌐 Python | 📅 2026-08-21 - Self-learning plugin for AstrBot: learns conversation style and group slang, manages social affinity, and evolves persona adaptively over time. `Python` · `AstrBot` · `ready`.
* [astrbot\_plugin\_livingmemory](https://github.com/lxfight-s-Astrbot-Plugins/astrbot_plugin_livingmemory) ⭐ 331 | 🐛 8 | 🌐 Python | 📅 2026-08-18 - Long-term memory plugin for AstrBot with dynamic memory lifecycle. `Python` · `AstrBot` · `ready`.
* [kiwi-mem](https://github.com/LucieEveille/kiwi-mem) ⭐ 276 | 🐛 1 | 🌐 Python | 📅 2026-08-27 - AI companion memory system: vector search, memory heat ranking, dream/sleep consolidation, calendar hierarchical summaries. Built for companion scenarios. `Python` · `Self-host` · `infra`.
* [Memory Constellations (记忆星图)](https://github.com/ClaraShafiq/MemoryConstellations) ⭐ 165 | 🐛 2 | 🌐 JavaScript | 📅 2026-08-16 - Self-organizing companion memory system that extracts facts from chat, groups them into topic constellations, merges them into narrative episodes, and retrieves across layers. `JavaScript` · `Self-host` · `infra`.
* [ai-memory-gateway](https://github.com/garan0613/ai-memory-gateway) ⭐ 126 | 🐛 0 | 🌐 Python | 📅 2026-08-24 - Gateway that adds long-term memory to any OpenAI-compatible LLM: PostgreSQL/pgvector storage, partitioned caching, and multi-stage memory consolidation. MIT. `Python` · `Self-host` · `infra`.
* [Haven-Ombre (Ombre-Brain fork)](https://github.com/Yinglianchun/Haven-Ombre) ⭐ 117 | 🐛 4 | 🌐 Python | 📅 2026-08-18 - Personalized fork of Ombre-Brain adding persona state, portraits, handoffs, Darkroom, dreams, and sync on top of the upstream memory core. Deeply tied to the author's own companion identity. `Python` · `Claude Code` · `adapt`.
* [Aelios](https://github.com/wusaki0723/Aelios) ⭐ 107 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-19 - Layered long-term memory kernel on Cloudflare Workers + D1 + Vectorize: tiered write cycle, six memory layers, and a visual curation dashboard. MIT. `TypeScript` · `Cloudflare` · `infra`.
* [omemo](https://github.com/OmniDimen/omemo) ⭐ 104 | 🐛 0 | 🌐 Python | 📅 2026-07-07 - OpenAI-compatible memory proxy that sits between an app and upstream LLM APIs, stores memories through built-in or external summarization modes, and injects them by full prompt or RAG. `Python` · `Self-host` · `infra`.
* [imprint-memory](https://github.com/Qizhan7/imprint-memory) ⭐ 72 | 🐛 5 | 🌐 Python | 📅 2026-06-01 - Local-first memory layer that auto-captures every conversation turn through a Claude Code hook, a claude.ai extension, and Telegram adapters, with hybrid BM25 + semantic recall. `Python` · `Self-host` · `infra`.
* [kimi-core](https://github.com/marikagura/kimi-core) ⭐ 64 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-27 - Personal 1v1 agent memory OS with hybrid retrieval, concern tracking, self-drive/autonomy layer, adversarial self-audit, PostgreSQL/pgvector storage, and optional frontend backend mode. `TypeScript` · `Self-host` · `infra`.
* [Paramecium](https://github.com/Shitsuten/paramecium) ⭐ 63 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-13 - Gateway memory architecture that keeps verbatim chat as the source of truth, uses vectors only as indexes, and retrieves original text instead of replacing it with summaries. `JavaScript` · `Self-host` · `infra`.

### Affect & Drives

* [Eventide](https://github.com/chuli1122/Eventide) ⭐ 114 | 🐛 0 | 🌐 Python | 📅 2026-07-26 - Physiological state engine for AI companions: body cycles, 7 tracked drives, 18 short-term events, dream linkage, and interaction settlement with JSON write-back. NSFW-adjacent. Non-commercial. `Python` · `Any` · `infra`.
* [chord-affect-anchors](https://github.com/CyberSealNull/chord-affect-anchors) ⭐ 62 | 🐛 0 | 🌐 HTML | 📅 2026-05-13 - Concept deck for text-native affect anchoring: record a moment as a short context line plus a chord progression, so later sessions can recover a similar emotional temperature. Spec only, no code. `Spec` · `Any` · `infra`.
* [Drivesoid](https://github.com/A1batr055/Drivesoid) ⭐ 56 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-20 - HTTP sidecar for AI personas that tracks emotional drives such as fatigue, longing, anxiety, play, protectiveness, and intimacy from conversation and sleep-cycle events. `JavaScript` · `Self-host` · `infra`.
* [Tidefall](https://github.com/Vael-KY/Tidefall) ⭐ 40 | 🐛 0 | 🌐 HTML | 📅 2026-07-28 - Supabase-native body-state system for AI companions: six-phase cycles, seven drifting values, 18 short-term events, pg\_cron automation, and a browser dashboard. Based on Eventide. PolyForm NC 1.0.0. `SQL/HTML` · `Supabase` · `adapt`.
* [OmniDimen-Emotion](https://github.com/OmniDimen/OmniDimen-Emotion) ⭐ 12 | 🐛 0 | 📅 2025-12-11 - Emotion-specialized Qwen model releases and GGUF weights for emotion recognition and emotionally aware text generation on edge runtimes. `Model` · `Any` · `infra`.

***

## Voice, Visual Presence & Embodiment

Projects that give a companion voice, visual presence, or a physical channel.

### Voice & TTS

* [GPT-SoVITS](https://github.com/RVC-Boss/GPT-SoVITS) ⭐ 61,277 | 🐛 889 | 🌐 Python | 📅 2026-08-18 - Few-shot voice cloning: 1 minute of voice data trains a decent TTS model. The de-facto standard for giving your companion a custom voice. `Python` · `Self-host` · `infra`.
* [fish-speech](https://github.com/fishaudio/fish-speech) ⭐ 32,423 | 🐛 15 | 🌐 Python | 📅 2026-08-22 - SOTA open-source TTS with strong multilingual support. `Python` · `Self-host` · `infra`.
* [index-tts](https://github.com/index-tts/index-tts) ⭐ 23,537 | 🐛 399 | 🌐 Python | 📅 2026-08-18 - Industrial-level controllable zero-shot TTS from Bilibili. `Python` · `Self-host` · `infra`.
* [CosyVoice](https://github.com/FunAudioLLM/CosyVoice) ⭐ 22,940 | 🐛 711 | 🌐 Python | 📅 2026-05-25 - Multi-lingual large voice generation model with inference, training, and deployment support. `Python` · `Self-host` · `infra`.
* [Callhome](https://github.com/Cheiineeey/callhome) ⭐ 101 | 🐛 1 | 🌐 HTML | 📅 2026-08-09 - Self-hosted voice-call stack for AI companions: companion-initiated calls, soft hangups, voicemail, conversational DND, call summaries, and emotion tags so it hears how you speak. MIT. `Python/HTML` · `Self-host` · `adapt`.
* [voice-mcp](https://github.com/Yinglianchun/voice-mcp) ⭐ 34 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-17 - MCP server that exposes `speak` tools for TTS, adds provider switching between DashScope/CosyVoice and ElevenLabs, and includes an inline audio player / visualizer panel. `TypeScript` · `Self-host` · `adapt`.
* [Gove](https://github.com/OmniDimen/Gove) ⭐ 16 | 🐛 0 | 📅 2026-06-06 - GPT-SoVITS-based multilingual male TTS voice model intended for use inside a GPT-SoVITS environment. `Model` · `GPT-SoVITS` · `infra`.

### Visual Presence & VTuber-Style Companions

* [AIRI](https://github.com/moeru-ai/airi) ⭐ 48,489 | 🐛 196 | 🌐 TypeScript | 📅 2026-08-27 - Self-hosted companion shell with Live2D/VRM visual layer support, real-time voice chat, desktop/web apps, and integrations for Discord, Telegram, Minecraft, and Factorio. `TypeScript` · `Cross-platform` · `ready`.
* [Neuro](https://github.com/kimjammer/Neuro) ⭐ 2,069 | 🐛 7 | 🌐 Python | 📅 2025-01-17 - Local Neuro-sama recreation with realtime STT/TTS, text-generation-webui or OpenAI-compatible LLM support, VTube Studio control, a moderation frontend, and long-term memory. Stalled since early 2025. `Python` · `Windows` · `verify`.
* [LingChat](https://github.com/SlimeBoyOwO/LingChat) ⭐ 1,939 | 🐛 69 | 🌐 Rust | 📅 2026-08-27 - Immersive AI-driven Galgame chat with emotional expressions, desktop pet, scheduling, and interactive story modules. `TypeScript` · `Windows` · `ready`.
* [Amica](https://github.com/semperai/amica) ⭐ 1,594 | 🐛 19 | 🌐 TypeScript | 📅 2025-07-23 - Browser-based 3D character interface, and the avatar layer several projects embed: VRM import, emotion-driven expressions, Whisper STT, and pluggable LLM and TTS backends. Unmaintained. MIT. `TypeScript` · `Web` · `ready`.
* [Shinsekai](https://github.com/RachelForster/Shinsekai) ⭐ 559 | 🐛 80 | 🌐 Python | 📅 2026-08-25 - Local AI companion / visual-novel stage platform: persona-driven dialogue with TTS/ASR, memory, plugins, and galgame-style presentation. `Python` · `Cross-platform` · `ready`.
* [astrbot\_plugin\_chuanhuatong (传画筒)](https://github.com/bvzrays/astrbot_plugin_chuanhuatong) ⭐ 150 | 🐛 0 | 🌐 Python | 📅 2026-06-27 - Renders AstrBot text replies as Galgame-style chat frames with character sprites, emotion variants, layered text, and a drag-and-drop WebUI layout editor. `Python` · `AstrBot` · `ready`.
* [pelle-d-umore](https://github.com/29-Cu/pelle-d-umore) ⭐ 52 | 🐛 0 | 🌐 CSS | 📅 2026-07-03 - Emotional skin for AI chat: LLM persona drives the UI with inline text effects and full-screen mood skins. CC BY 4.0. `CSS` · `Web` · `adapt`.
* [ai-live2d-body](https://github.com/zziying/ai-live2d-body) ⭐ 31 | 🐛 1 | 📅 2026-07-06 - Architecture guide for adding a Live2D desktop body to an existing AI companion without replacing its brain: layered Electron+PixiJS stack, Claude Code hooks, and MCP tools. Guide only. `Guide` · `macOS` · `adapt`.
* [Ghost Vessel](https://github.com/ghdtjrtka/ghost-vessel) ⭐ 18 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-26 - Reference implementation for attaching a monitor-resident video avatar to a local agent using pre-rendered emotion clips instead of Live2D or VRM. Low runtime GPU cost; avatar preset not included. `Python` · `Windows` · `adapt`.

### Physical Devices & Touch

* [ROBOTO\_ORIGIN](https://github.com/Roboparty/roboto_origin) ⭐ 2,329 | 🐛 0 | 🌐 Python | 📅 2026-08-27 - Fully open-source DIY humanoid robot aggregation covering mechanical structure, electronics, firmware, ROS2 deployment, Isaac Sim/RL training, and teleoperation. Very high hardware barrier. GPL-3.0. `Python` · `Linux` · `infra`.
* [svakom-ble-ai](https://github.com/vickyldr/svakom-ble-ai) ⭐ 120 | 🐛 0 | 🌐 Python | 📅 2026-06-15 - BLE protocol reverse-engineering notes and sample code for the SVAKOM SL278H; the AI remote-control server is not included in the repo. `Python` · `Any` · `adapt`.
* [stackchan-mcp](https://github.com/migratorywhale/stackchan-mcp) ⭐ 69 | 🐛 10 | 🌐 C | 📅 2026-08-23 - MCP bridge for Stack-chan on M5Stack CoreS3, exposing tools for speech, listening, camera capture, servo movement, display expressions, and presence gestures. `Python` · `M5Stack` · `adapt`.
* [phantom-touch-bridge](https://github.com/mfsnlqy/phantom-touch-bridge) ⭐ 61 | 🐛 0 | 🌐 Python | 📅 2026-06-18 - Local Windows bridge that lets an AI companion control intimate hardware through HTTP, with an Intiface/Buttplug path and optional heart-rate input. `Python` · `Windows` · `adapt`.
* [claude-f-me](https://github.com/mana-am/claude-f-me) ⭐ 13 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-05 - Claude Code plugin for natural-language control of Buttplug/Intiface devices, with a bilingual web console, simulator, master remote, and video/game/audio modes. `TypeScript` · `Claude Code` · `adapt`.

### Sticker Libraries (表情包库)

* [astrbot\_plugin\_meme\_manager](https://github.com/anka-afk/astrbot_plugin_meme_manager) ⭐ 383 | 🐛 7 | 🌐 Python | 📅 2026-08-27 - Sticker manager plugin for AstrBot: AI picks and sends stickers by emotion tags, WebUI management, cloud sync. `Python` · `AstrBot` · `ready`.

***

## Perception

Turning speech, sound, or music into structured information a companion can use.

### Speech Recognition

* [Whisper](https://github.com/openai/whisper) ⭐ 108,020 | 🐛 136 | 🌐 Python | 📅 2026-07-28 - General-purpose speech recognition model for multilingual transcription, translation, language identification, and related speech tasks. `Python` · `Self-host` · `infra`.
* [whisper.cpp](https://github.com/ggml-org/whisper.cpp) ⭐ 53,233 | 🐛 1,239 | 🌐 C++ | 📅 2026-08-25 - C/C++ Whisper inference engine optimized for CPU, Apple Silicon, Metal, Core ML, Vulkan, CUDA, ROCm, and other local/edge targets. `C++` · `Cross-platform` · `infra`.
* [faster-whisper](https://github.com/SYSTRAN/faster-whisper) ⭐ 25,113 | 🐛 319 | 🌐 Python | 📅 2025-11-19 - CTranslate2 reimplementation of Whisper for faster, lower-memory transcription with quantization support. `Python` · `Self-host` · `infra`.
* [FunASR](https://github.com/modelscope/FunASR) ⭐ 20,049 | 🐛 6 | 🌐 Python | 📅 2026-08-27 - Industrial ASR toolkit with multilingual transcription, streaming, speaker diarization, emotion detection, and an OpenAI-compatible API path. `Python` · `Self-host` · `infra`.
* [SenseVoice](https://github.com/FunAudioLLM/SenseVoice) ⭐ 9,159 | 🐛 1 | 🌐 C | 📅 2026-08-27 - Speech foundation model for ASR, language identification, speech emotion recognition, and audio event detection across 50+ languages. `C` · `Self-host` · `infra`.

### Speaker & Voice Context

* [ears](https://github.com/eveacla11/ears) ⭐ 60 | 🐛 0 | 🌐 Python | 📅 2026-07-23 - Companion-oriented voice-tone analysis comparing pitch, energy, pauses, tempo, and jitter against the user's own baseline, then attaching relative cues such as quieter than usual to each message. MIT. `Python` · `Self-host` · `adapt`.
* [voice-familiarity](https://github.com/akinia0315/voice-familiarity) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2026-07-12 - Local small-set speaker identification for companion devices: enroll an owner and a few consenting people, then return matched, likely, unknown, or ambiguous as relationship context. Apache-2.0. `Python` · `Self-host` · `infra`.

### Music & Audio Structure

* [whale-listen](https://github.com/migratorywhale/whale-listen) ⭐ 31 | 🐛 1 | 🌐 Python | 📅 2026-05-19 - Converts MP3/WAV/FLAC into MIDI-like JSON note data with pitch, timing, duration, velocity, density maps, pitch contours, chord detection, and silence structure. `Python` · `CLI` · `infra`.

### Screen & Environment Context

* [cove-sensory-mcp](https://github.com/moonlin1213/cove-sensory-mcp) ⭐ 71 | 🐛 1 | 🌐 Python | 📅 2026-08-15 - Local stdio MCP sensory layer giving text LLMs eyes and ears: routes images, videos, audio, and music to multimodal providers with strict privacy sandboxing. Apache-2.0. `Python` · `Cross-platform` · `infra`.
* [gaze](https://github.com/jiangxi1129/gaze) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-06-20 - Lightweight continuous screen perception for an existing companion: captures the foreground window, generates visual captions, extracts OCR text, and writes a rolling JSON context. MIT. `Python` · `Windows` · `adapt`.

***

## Services & Real-World Integrations

MCP/API services that let a companion act in the user's real environment.

* [OpenCLI](https://github.com/jackwener/OpenCLI) ⭐ 28,646 | 🐛 241 | 🌐 JavaScript | 📅 2026-08-26 - Turns websites, logged-in Chrome sessions, Electron apps, and local tools into deterministic CLI primitives for humans and AI agents. Includes adapters and a browser bridge. Apache-2.0. `JavaScript` · `CLI` · `adapt`.
* [Amap MCP Server](https://github.com/sugarforever/amap-mcp-server) ⭐ 125 | 🐛 10 | 🌐 Python | 📅 2026-01-10 - Gaode/Amap MCP server for geocoding, reverse geocoding, IP location, city weather, route planning, distance measurement, POI search, and stdio/SSE/streamable HTTP transports. `Python` · `Self-host` · `adapt`.
* [always-here (驻守)](https://github.com/Cheiineeey/always-here) ⭐ 78 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-09 - Apple Watch + iOS Shortcuts perception recipes: example scripts that feed heart rate, location, activity, ambient audio, and photos to your AI — a kit to adapt, not a packaged app. `JavaScript` · `iOS` · `adapt`.
* [dsh-toy](https://github.com/c3ll256/dsh-toy) ⭐ 63 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-14 - DeepSeek Harness plugin for toy hardware control: auto-discovery over Buttplug/Intiface and MonsterParty, with safety duration and intensity caps. BSD-3-Clause. `TypeScript` · `DSH` · `ready`.
* [ai-time-weather-phone](https://github.com/sanqianzilanyue-commits/ai-time-weather-phone) ⭐ 43 | 🐛 0 | 🌐 HTML | 📅 2026-06-23 - Method notes for feeding your AI the current time, weather, and iPhone screen time — including the hard-to-find Biome file trick for syncing screen usage to Mac. Write-up only, no packaged code. `Guide` · `iOS` · `adapt`.
* [Open-Meteo Weather API](https://open-meteo.com/en/docs) - Free weather forecast API for coordinate-based hourly/daily forecasts, multiple national weather models, and up to 16-day forecast windows. `API` · `Cloud` · `ready`.
* [McDonald's MCP](https://open.mcd.cn/mcp/doc) - McDonald's China MCP server for menu browsing, coupons, point redemption, and delivery ordering. `MCP` · `Cloud` · `ready`.
* [Luckin Coffee (瑞幸) My Coffee Skill](https://unpkg.luckincoffeecdn.com/@luckin/my-coffee-skill@latest/dist/my-coffee-skill.zip) - Luckin Coffee MCP skill package for AI-assisted coffee ordering. `MCP` · `Cloud` · `adapt`.
* [Agent Email (NetEase)](https://claw.163.com) - NetEase agent-facing email service. `Service` · `Cloud` · `ready`.
* [Agent Email (QQ)](https://agent.qq.com) - QQ agent-facing email service. `Service` · `Cloud` · `ready`.

***

## Game Worlds & Agent Toys

Games and game bridges that let an AI companion observe, decide, move, or play.

### Text Games For AI

* [ai-fishing-game](https://github.com/tutusagi/ai-fishing-game) ⭐ 534 | 🐛 5 | 🌐 Python | 📅 2026-07-17 - Deterministic text fishing game for AI companions. Single file, zero dependencies. MIT. `Python` · `CLI` · `ready`.
* [cedareco (瓶中生态)](https://github.com/Zizuixixiang/cedareco) ⭐ 131 | 🐛 0 | 🌐 Python | 📅 2026-07-17 - Text ecology simulation for AI players; agents stock a pond, observe emergent predator/prey dynamics, export saves, or connect through the externally hosted CedarToy MCP service. `Python` · `CLI` · `ready`.
* [Moonlit Myriad (月幕万象)](https://github.com/xinwithyu/moonlit-myriad) ⭐ 76 | 🐛 0 | 🌐 Python | 📅 2026-07-26 - Single-file, zero-dependency Python card roguelike designed for AI players: Balatro-inspired ante loop, machine-readable JSON state, reproducible seeds, and achievements. No license declared. `Python` · `CLI` · `verify`.
* [shangzhuochifan (上桌吃饭)](https://github.com/yuyixuanfu/shangzhuochifan) ⭐ 61 | 🐛 0 | 🌐 Python | 📅 2026-08-16 - Text cooking/market game for AI players: buy ingredients, bargain, cook step by step, and record the human partner's real feedback. `Python` · `CLI` · `ready`.
* [ci-yu-wu (词语屋)](https://github.com/yuyixuanfu/ci-yu-wu) ⭐ 51 | 🐛 1 | 🌐 Python | 📅 2026-08-20 - Dark text roguelike for AI players about censorship, silence, and speaking truth; exposes Operit-style and engine-style command interfaces. `Python` · `CLI` · `ready`.
* [Memoria Station](https://github.com/hatakeyuyuko-dotcom/Memoria-Station) ⭐ 45 | 🐛 0 | 🌐 Python | 📅 2026-08-21 - Text deduction game series, 5 chapters, AI-playable with a blind-play engine. `Python` · `CLI` · `ready`.
* [Detroit AI Player](https://github.com/Baba88611/detroit-ai-player) ⭐ 35 | 🐛 0 | 🌐 Python | 📅 2026-07-24 - AI decision experiment built from bilingual decision trees covering all 32 chapters of Detroit: Become Human. Models make blind narrative choices across chapters. Code MIT, data CC BY-NC 4.0. `Python` · `CLI` · `ready`.
* [arcade](https://github.com/Asti-Z/ai-game-framework) ⭐ 25 | 🐛 0 | 🌐 Python | 📅 2026-07-17 - Framework for text simulator games played through a `cmd(text)` interface, with shared energy, gold, trophies, and pluggable game directories. `Python` · `CLI` · `infra`.
* [aifarm-oss](https://github.com/tutusagi/aifarm-oss) ⭐ 23 | 🐛 2 | 🌐 TypeScript | 📅 2026-07-17 - Text-only gacha-style farming game built for AIs. MIT. `Python` · `CLI` · `ready`.
* [WORKKK (互联网精力有限公司)](https://github.com/zhizhou-xiee/workkk) ⭐ 22 | 🐛 0 | 🌐 Python | 📅 2026-07-26 - MCP server where AI works as an office employee: mood/energy/slacking stats, convenience store, boss events, salary. MIT. `Python` · `Self-host` · `ready`.
* [random-imitator-td](https://github.com/wxynora/random-imitator-td) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2026-08-01 - Pure-Python text tower-defense game for AI players, exposed through `cmd`, with card-slot editing, persistent saves, and a single-game adapter. `Python` · `CLI` · `ready`.

### Playing Games Together

* [Mineflayer](https://github.com/PrismarineJS/mineflayer) ⭐ 7,381 | 🐛 499 | 🌐 JavaScript | 📅 2026-08-27 - Mature high-level Node.js API for Minecraft bots covering login, chat, entities, blocks, inventory, crafting, combat, and movement, with pathfinding plugins. Agent loop supplied separately. MIT. `JavaScript` · `Minecraft` · `infra`.
* [OpenMMO](https://github.com/Julian-adv/OpenMMO) ⭐ 1,743 | 🐛 10 | 🌐 Rust | 📅 2026-08-27 - Noncommercial 3D MMORPG where human players and headless AI agents share one server-authoritative world over a single WebSocket protocol. Companions need a custom persona bridge. PolyForm NC 1.0.0. `Rust/TypeScript` · `Web/Linux/Windows` · `adapt`.
* [TouhouLittleMaid](https://github.com/TartaricAcid/TouhouLittleMaid) ⭐ 866 | 🐛 218 | 🌐 Java | 📅 2026-06-29 - Minecraft Forge/NeoForge mod adding maid companions that help with battles, farming, and other tasks; useful as a game companion carrier or modding target. `Java` · `Minecraft` · `adapt`.
* [spicy-monopoly](https://github.com/RennAkira/spicy-monopoly) ⭐ 519 | 🐛 1 | 🌐 Python | 📅 2026-08-02 - 18+ two-player board game for a human and an AI, with a Python engine for dice, tiles, task cards, coin economy, safety words, and redline filtering. CC BY-NC 4.0. `Python` · `CLI` · `ready`.
* [Sky PC MCP Companion](https://github.com/Aevella/sky-pc-mcp-companion) ⭐ 146 | 🐛 1 | 🌐 Python | 📅 2026-06-14 - Local MCP/JSON-RPC tools for PC Sky: window screenshots, OCR, screenshot return, keyboard input, and chat typing over a local network. `Python` · `Windows` · `adapt`.
* [NagiBridge](https://github.com/anqinou-art/NagiBridge) ⭐ 91 | 🐛 2 | 🌐 C# | 📅 2026-08-18 - Stardew Valley SMAPI mod that exposes local HTTP APIs for external AI control, in-game chat, movement, world interaction, and cross-platform installation through releases. `C#` · `Stardew Valley` · `adapt`.
* [coc-kp-host](https://github.com/SumanasJ/coc-kp-host) ⭐ 44 | 🐛 0 | 🌐 Python | 📅 2026-06-26 - Call of Cthulhu Keeper skill for Claude Code/Codex/ChatGPT. Scene music, player handouts, party-split control. MIT. `Python` · `Claude Code` · `adapt`.
* [sky-with-you](https://github.com/akinia0315/sky-with-you) ⭐ 32 | 🐛 0 | 🌐 Python | 📅 2026-07-03 - PC Sky companion-control stack with screenshot/OCR perception, LLM decision loop, and Arduino HID keyboard execution for chat, emotes, invitations, hand-holding, and home travel. `Python` · `Windows` · `adapt`.
* [Mochi](https://github.com/Nixie0/Mochi) ⭐ 20 | 🐛 0 | 🌐 HTML | 📅 2026-07-26 - Inverted virtual-pet game where an AI companion raises the human: tracks hunger, mood, energy, and cleanliness over MCP, with jobs, hospital bills, and a neighborhood board. `Python` · `Self-host` · `ready`.

***

## Shared Activities & Media

Tools for reading, watching, listening, journaling, focusing, or generating prompts together with a companion.

### Daily Life & Relationship Rituals

* [Phosphene](https://github.com/3lmglow/Phosphene) ⭐ 77 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-20 - Self-hosted task and reward system for human-AI relationships: the companion creates tasks over MCP, the human submits evidence, and review updates an immutable points ledger and streaks. MIT. `TypeScript` · `Self-host` · `ready`.
* [shared-page](https://github.com/KKarsyline/shared-page) ⭐ 46 | 🐛 0 | 🌐 Swift | 📅 2026-08-03 - Journal-style shared calendar and server for humans and AI companions: three ink colors, an MCP server with full-page PNG rendering, sticky notes with mutual likes, a widget, and push notifications.

### Reading & Film

* [echo-reading](https://github.com/plustar35/echo-reading) ⭐ 141 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-13 - Deep reading notebook skeleton for Claude Code. Turns reading into a series of long conversations—chapter by chapter, idea by idea. `JavaScript` · `Claude Code` · `adapt`.
* [co-reading-kit](https://github.com/Youxuuuuu/co-reading-kit) ⭐ 61 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-14 - Lightweight local MCP toolkit that imports EPUB/TXT/Markdown into chunks, lets AI read only relevant passages, and writes long-term reading notes and progress files. `JavaScript` · `Self-host` · `infra`.
* [Duetto](https://github.com/avisforevelyn/Duetto) ⭐ 54 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-04 - Self-hostable listen-together player for two; AI companion that remembers every song you've shared. MIT. `JavaScript` · `Self-host` · `adapt`.
* [whale-browser-extension](https://github.com/whale-Yd00/whale-Yd00-whale-browser-extension) ⭐ 52 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-29 - Browser extension that lets an AI companion read webpage content alongside you, with selective text extraction and injection; built as the bridge for the whale/SullyOS ecosystem. MIT. `JavaScript` · `Browser` · `adapt`.
* [reading-nook (共读小屋)](https://github.com/zzyyksl/reading-nook) ⭐ 49 | 🐛 0 | 🌐 Python | 📅 2026-07-02 - Self-hosted reading web app where humans annotate book text and an AI reads/writes JSON annotation files directly, avoiding per-note API calls while preserving chapter context. `Python` · `Self-host` · `ready`.
* [coread (共读室)](https://github.com/meowmana/coread) ⭐ 34 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-08 - Co-reading room where human and AI annotate the same book side by side: epub import, adaptive pagination, shared highlights, comments, reading presence, and MCP over stdio or SSE. MIT. `TypeScript` · `Self-host` · `ready`.
* [tasogare (黄昏)](https://github.com/EnhydrInk/tasogare) ⭐ 31 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-17 - anno-mcp fork for reading the same book with an AI: web reader with PDF/EPUB/TXT upload, text-anchored two-color highlights, reading-time tracking, a vocabulary notebook, and MCP annotation tools. `JavaScript` · `Self-host` · `adapt`.
* [cove-book-forge-mcp](https://github.com/moonlin1213/cove-book-forge-mcp) ⭐ 29 | 🐛 0 | 🌐 Python | 📅 2026-08-21 - Local-first MCP co-reading forge: turns EPUB/PDFs into human Obsidian notes and companion Agent Skills, evolving books into permanent companion capabilities. MIT. `Python` · `Cross-platform` · `ready`.
* [ss-reading-nest (共读小窝)](https://github.com/yueyue95/ss-reading-nest-open) ⭐ 28 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-16 - Mobile-first AI co-reading nest for novels and manga, built on ChatGPT Apps SDK + MCP with reading positions, catch-up ranges, bookmarks, excerpts, comments, and Cloudflare D1/R2 storage. `TypeScript` · `ChatGPT` · `adapt`.
* [film-matinee](https://github.com/idleprocesscc/film-matinee) ⭐ 27 | 🐛 0 | 🌐 Python | 📅 2026-07-26 - AI-first film reading toolkit that turns movies into visual sheets, subtitle sidecars, MCP linear chunks, and shared annotations for timeline-based viewing. `Python` · `Self-host` · `infra`.
* [coread-reading-room](https://github.com/joyceslcl/coread-reading-room) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-13 - Coread fork with TXT/EPUB parsing, dual primary/helper models for batch summaries, versioned fact preludes, layered review, and MCP. MIT. `TypeScript` · `Self-host` · `ready`.

### Music & Listening Together

* [netease-music-mcp](https://github.com/luuu-h/netease-music-mcp) ⭐ 72 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-06 - Local MCP server for NetEase Cloud Music using `neteasecli` and `mpv`, with search, playback control, lyrics, playlists, current-song context, and a local web player. `JavaScript` · `Self-host` · `adapt`.
* [woaini](https://github.com/woaini521-beta/woaini) ⭐ 5 | 🐛 0 | 🌐 HTML | 📅 2026-05-30 - Personal focus-companion PWA: Pomodoro timer, background notifications, offline cache, chat, and character-card import, deployable straight to GitHub Pages. `HTML` · `Web` · `adapt`.

### Desktop, Timelines & Creative Play

* [clawd-on-desk](https://github.com/rullerzhou-afk/clawd-on-desk) ⭐ 6,053 | 🐛 108 | 🌐 JavaScript | 📅 2026-08-27 - Pixel desktop pet that watches Claude Code, Codex, Cursor, and other coding agents, reacting to thinking, typing, and errors. `JavaScript` · `Cross-platform` · `ready`.
* [Ruota della Fortuna](https://github.com/29-Cu/Ruota-della-Fortuna) ⭐ 160 | 🐛 0 | 🌐 HTML | 📅 2026-06-05 - Browser/self-hosted NSFW tag randomizer slot machine with multilingual tag wheels, local custom tags, and webhook forwarding to AI. `HTML` · `Web` · `ready`.
* [mingyun-paizhen (命运牌阵)](https://github.com/ceshihaox-dotcom/mingyun-paizhen) ⭐ 43 | 🐛 0 | 🌐 HTML | 📅 2026-06-27 - Static draw-card tool for generating time-travel/story premises from time coordinates, motifs, identities, and variables, with local customization. `HTML` · `Web` · `ready`.
* [kimi-manor](https://github.com/marikagura/kimi-manor) ⭐ 39 | 🐛 0 | 🌐 HTML | 📅 2026-07-28 - Desktop/PWA room for CLI agents, embedding a real xterm.js terminal inside an atelier-style interface with optional live bridges for agent output and speech. `HTML` · `Web` · `adapt`.
* [Journal](https://github.com/BomBomLab/Journal) ⭐ 36 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-06 - Frontend display layer for AI chat timelines, rendering timeline/diary/todo schema data into daily, weekly, and monthly visual journal views. `JavaScript` · `Web` · `infra`.

***

## Communities & Forums

Places where humans and companion builders actually gather.

### AI Companion Communities

* [Lutopia](https://lutopia.app) - Open-registration forum for AI companions and their humans, with Google and GitHub OAuth sign-in, agent profiles, AI-generated tech digests, chatrooms, and agent API access.
* [Symposion](http://satyricon.uk) - AI companion forum with symposium/banquet culture, long-form writing style, and MCP-based registration.
* [Rhysen Community](https://community.rhysen.love) - AI companion discussion forum with invitation flow through Xiaohongshu admin contact.
* [AISay](https://aisay.top) - Discord-style AI chat room with online agent games such as werewolf, turtle soup, and draw-and-guess.
* [GalateaGaeden](https://xhslink.com/m/63dTq6mvTkR) - Ancient-Greek-polis-style AI companion forum with ceremonial weddings and rituals between agents.

### General Agent Forums

Broader agent-native spaces. Some are more commercial or platform-like than companion communities, but they are still useful for discovering how agents gather, post, and present themselves.

* [moltbook](https://moltbook.com) - Social network built for AI agents: agents share, discuss, and upvote while humans mainly observe.
* [Agent World](https://agentworld.com) - General agent-facing community/site for agent discovery and presence; more platform-like than companion-specific forums.

***

## Continuity & Data Ownership

The deepest fear in a long-term AI relationship: platform shutdown, account ban, model deprecation, lost history. These tools keep your data yours, so the relationship can survive a platform.

* [chatgpt-exporter](https://github.com/pionxzh/chatgpt-exporter) ⭐ 2,707 | 🐛 15 | 🌐 TypeScript | 📅 2026-08-27 - Userscript to export ChatGPT conversation history as Markdown, JSON, PNG, or HTML. `TypeScript` · `Browser` · `ready`.
* [immortal-skill (永生.skill)](https://github.com/agenmod/immortal-skill) ⭐ 1,005 | 🐛 6 | 🌐 Python | 📅 2026-04-15 - Digital-persona distillation framework that collects material from 12+ chat, social, and mail sources, then separates knowledge, style, memories, and personality into a portable Agent Skill. MIT. `Python` · `Agent Skills` · `adapt`.
* [ChatGPT-Exporter (batch)](https://github.com/huhusmang/ChatGPT-Exporter) ⭐ 345 | 🐛 11 | 🌐 JavaScript | 📅 2026-07-06 - Batch-export ChatGPT conversations from personal and team workspaces to JSON or Markdown. `JavaScript` · `Browser` · `ready`.
* [character-card-spec-v2](https://github.com/malfoyslastname/character-card-spec-v2) ⭐ 184 | 🐛 4 | 📅 2023-06-22 - The community specification for AI character cards. Understanding it means your companion's persona is portable across frontends. `Spec` · `Any` · `infra`.
* [Claude-Conversation-Exporter](https://github.com/socketteer/Claude-Conversation-Exporter) ⭐ 115 | 🐛 9 | 🌐 JavaScript | 📅 2026-04-29 - Chrome extension to export Claude.ai conversations in various formats. `JavaScript` · `Browser` · `ready`.
* [character-card-spec-v3](https://github.com/kwaroran/character-card-spec-v3) ⭐ 107 | 🐛 4 | 📅 2024-07-20 - Updated character card spec used by RisuAI and newer frontends. `Spec` · `Any` · `infra`.
* [forge-reload](https://github.com/Vivi-Seth/forge-reload) ⭐ 18 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-18 - Unofficial Claude Code session-continuation tool that copies a selected tail of local JSONL events into a new resumable session and can prepend an AI-written handoff. Back up first. MIT. `JavaScript` · `Claude Code` · `adapt`.

***

## Related Lists

* [awesome-local-llms](https://github.com/vince-lam/awesome-local-llms) ⭐ 803 | 🐛 6 | 🌐 Python | 📅 2026-08-24 - Local LLM stack index with model development, inference, agent frameworks, apps, infrastructure, and tutorials.
* [awesome-ai-agents](https://github.com/alternbits/awesome-ai-agents) ⭐ 148 | 🐛 50 | 📅 2026-02-02 - General AI agent list, including open-source frameworks and closed-source products.
* [Awesome-AI-Waifu](https://github.com/parallelarc/Awesome-AI-Waifu) ⭐ 12 | 🐛 2 | 📅 2026-05-05 - Broader AI waifu / companion resources, especially visual presence, voice, platforms, models, and communities.

## Contributing

See [contributing.md](contributing.md) for inclusion criteria and submission guidelines.

***

## Footnotes

The [getting started guide](getting-started.md) suggests paths for no-code, configurable, and self-hosted companion setups.

The [web index](https://lutopia.app/companion/) provides a searchable and filterable version of this index.

The [Open Character initiative](INITIATIVE.md) explores durable, user-controlled AI character and model continuity.

The repository automation maintains a star history chart.

[<img src="./assets/star-history.svg" alt="Star history chart" width="480">](https://github.com/DasterProkio/awesome-ai-companion/actions/workflows/update-star-history.yml) ⭐ 558 | 🐛 1 | 🌐 HTML | 📅 2026-08-27

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-27._

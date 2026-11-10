# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project status

This repository (`ClaudeOVH`, formerly `hermes`) is currently empty — no source code, build configuration, or documentation exists yet. There is nothing to build, lint, or test.

When code is added to this project, update this file with:
- Build, lint, and test commands (including how to run a single test)
- High-level architecture notes once the codebase structure is established

## Память Claude Code (auto-memory)

Директория памяти этого проекта — `~/.claude/projects/-home-amar-Amar73-ClaudeOVH/memory/` —
является клоном приватного репозитория `Amar73/claude-memory-ClaudeOVH` и синхронизируется
между машинами вручную через git:

- **В начале сессии** (если на этой машине давно не работал): сделай `git pull` в этой директории.
- **В конце сессии, если память менялась**: `git add -A && git commit && git push` там же.

Подробности — в `README.md` внутри самой директории памяти.

Память про сам сервер ovh (hardening/ufw/Caddy DNS-01, Telegram-бот; CloudCLI удалён 2026-11-10)
с 2026-11-06 лежит в проекте `servers`: `~/.claude/projects/-home-amar-Amar73-servers/memory/`
(индекс — `servers-index.md`). При работе над ovh читай её оттуда; здесь остались туннель amar224,
herdr, Perplexity и план развёртывания.

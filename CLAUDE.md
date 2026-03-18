# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

Early-stage Python project. Main file: `Oficial.py`.

## Running

```bash
python Oficial.py
```

No build system, test framework, or dependencies are configured yet.

## GitHub

Repositório: https://github.com/lucahs10/PJ-CLAUDE

Auto-save configurado via hook `Stop` no `~/.claude/settings.json`. A cada vez que o Claude Code encerra uma sessão, ele verifica se há alterações e faz commit + push automaticamente para `origin master` com a mensagem `auto: YYYY-MM-DD HH:MM:SS`.

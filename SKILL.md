---
name: caveman-compress
description: "Compress natural language memory files (CLAUDE.md, todos, preferences) into caveman format
to save input tokens. Preserves all technical substance, code, URLs, and structure.
Compressed version overwrites the original file. Human-readable backup saved as FILE.original.md.
Trigger: /caveman-compress FILEPATH or "compress memory file""
version: 1.0.0
author: Community
license: MIT
platforms: [linux, macos, windows]
tags: [general]
---

# Caveman Compress — Skill

Compress natural language memory files (CLAUDE.md, todos, preferences) into caveman format
to save input tokens. Preserves all technical substance, code, URLs, and structure.
Compressed version overwrites the original file. Human-readable backup saved as FILE.original.md.
Trigger: /caveman-compress FILEPATH or "compress memory file"

## Install

```bash
cp -r <skill-name> ~/.hermes/skills/<skill-path>/
```

Or clone this repository:

```bash
git clone https://github.com/iizcm/caveman-compress-skill.git ~/.hermes/skills/<skill-path>/
```

## Usage

Invoke your AI agent with a clear instruction matching this skill's purpose. The agent will route tasks to this skill when the instruction matches its description or trigger keywords.

Refer to `README.md` in this repository for:
- Detailed step-by-step installation guide
- Bilingual documentation (English + Indonesian)
- Troubleshooting table
- Security best practices
- Customization tips

## Safety rules

- Never commit private keys, seed phrases, API tokens, or personal data to version control
- Use placeholders (`<YOUR_...>`) in all examples and code snippets
- Validate all outputs before acting on them
- Keep real credentials in your runtime's secure credential store only

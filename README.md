> [!NOTE]
> **This skill now lives in the main collection: [milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills/tree/main/skills/codebase-time-machine)**. Please ⭐ star it there; that's where updates land first.
> Docs: **https://milad-ahmd.github.io/agent-skills/skills/codebase-time-machine/** · Claude Code: `/plugin install all-skills --marketplace milad-ahmd/agent-skills`

<div align="center">

# ⏳ codebase-time-machine

**The story of your repo from git history, as a documentary: eras, cast, plot twists, cursed files. An Agent Skill for Claude Code, Cline, Cursor, Codex and other AI coding agents.**

[![License: MIT](https://img.shields.io/github/license/milad-ahmd/codebase-time-machine)](LICENSE)
[![Stars](https://img.shields.io/github/stars/milad-ahmd/codebase-time-machine?style=social)](https://github.com/milad-ahmd/codebase-time-machine)
![Category](https://img.shields.io/badge/category-Fun%20&%20Viral-blue)
![Works with](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Cline%20%7C%20Cursor%20%7C%20Codex-8A2BE2)

[Install](#-install) · [Usage](#-usage) · [How it works](skills/codebase-time-machine/SKILL.md) · [All skills](https://github.com/milad-ahmd/agent-skills)

<img src="assets/demo.gif" alt="codebase-time-machine demo (real output)" width="760"/>

</div>

> Part of **[agent-skills](https://github.com/milad-ahmd/agent-skills)**, a growing collection of practical skills for AI coding agents.

## 📦 Install

**One command (installs the whole collection):**

```bash
curl -fsSL https://raw.githubusercontent.com/milad-ahmd/agent-skills/main/install.sh | bash -s -- codebase-time-machine
```

**Manually (Claude Code):**

```bash
git clone https://github.com/milad-ahmd/codebase-time-machine /tmp/codebase-time-machine
mkdir -p ~/.claude/skills && cp -r /tmp/codebase-time-machine/skills/codebase-time-machine ~/.claude/skills/
```

**Per project:** copy `skills/codebase-time-machine` into `<project>/.claude/skills/`.
**Any other agent:** paste [`SKILL.md`](skills/codebase-time-machine/SKILL.md) into your rules or system prompt.

## 💬 Usage

Just ask your agent:

```text
Tell me the story of this codebase
Who built what in this repo, and when?
```

The full workflow, rules and output format are in [`SKILL.md`](skills/codebase-time-machine/SKILL.md).

## 🧩 More skills

See the full collection: **[milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills)**.

## 🤝 Contributing

Issues and PRs are welcome, especially real-world before/after examples.

## 📄 License

[MIT](LICENSE) © Milad Ahmadi

<div align="center">

**If this skill saved you time, a ⭐ helps others find it.**

</div>

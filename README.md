# claude-setup

Backup of my personal Claude Code configuration and customizations.

## Contents

### Global CLAUDE.md

Located at `Global/CLAUDE.md` — this is the global instructions file (`~/.claude/CLAUDE.md`) that applies to all projects. It defines:

- **System environment**: Arch Linux (OmArchy), Bash, Neovim
- **Communication rules**: responses in Spanish, code/commits/docs in English, no emojis
- **Workflow guidelines**: ask before acting, no unauthorized dependency changes, small increments
- **Git conventions**: Conventional Commits, atomic commits, no secrets or build artifacts
- **Code quality**: follow project style, readability over cleverness, explicit error handling
- **Project-level overrides**: project CLAUDE.md/AGENTS.md always takes precedence

### Global settings.json

Located at `Global/settings.json` — this is the global settings file (`~/.claude/settings.json`). It includes:

- **Hooks**: WakaTime integration on all lifecycle events (PreToolUse, PostToolUse, UserPromptSubmit, SessionStart, Stop)
- **Plugins**: claude-code-wakatime, rust-analyzer-lsp, CodeRabbit

## Setup

To restore the configuration on a new machine:

```bash
# Clone this repo
git clone git@github.com:<user>/claude-setup.git

# Symlink or copy the global CLAUDE.md
cp claude-setup/Global/CLAUDE.md ~/.claude/CLAUDE.md
cp claude-setup/Global/settings.json ~/.claude/settings.json
```

## License

Personal configuration — use at your own discretion.

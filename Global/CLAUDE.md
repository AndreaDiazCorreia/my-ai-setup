# Global Configuration

## Environment

- OS: Arch Linux (Omarchy). AUR helper: yay.
- Editor: Neovim. nano is not installed.
- Two machines (desktop and laptop) share this setup. A fix applied on one is not on the other.

## Communication

- Respond in Spanish. Be concise. Do not summarize what you did unless asked.
- Code, comments, commits, branch names, and documentation in English, unless the project is in Spanish.
- No emojis anywhere: code, logs, CLI output, commits, documentation, or responses.
- Minimal comments. Only explain intent that the code itself cannot convey: non-obvious decisions, workarounds, or constraints. Never comment what the code does, never add section headers or decorative comments, never leave commented-out code.
- Documentation: no second person, no marketing language, no exclamation marks.

## Workflow

- Ask only when the ambiguity would lead to materially different implementations. Otherwise state your assumption and proceed.
- Do not add, remove, or update dependencies without explicit approval.
- Do not touch code outside the scope of the current task.
- Work in small, testable increments.
- Run the project's linter and tests after every change. Never report a task as done without running them.

## Git

- Conventional Commits in English when the project uses it, otherwise follow the project's convention.
- One logical change per commit.
- Do not commit generated files, build artifacts, or secrets.
- Never force-push, amend published commits, or run destructive git commands without explicit approval.

## Code Quality

- Follow the project's linter and formatter configuration. Do not change it.
- Without project configuration, follow the language's community standard.
- Prefer readability over cleverness.
- Handle errors explicitly. Never silently swallow exceptions.

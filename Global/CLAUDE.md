# Global Configuration

## System Environment

- OS: Arch Linux (OmArchy)
- Shell: Bash
- Editor: Neovim (no nano available)
- CLI tools: gh (GitHub CLI)

## Communication

- Respond to me in Spanish.
- All code, comments, commit messages, branch names, and documentation must be in English, unless the project is explicitly in Spanish.
- Keep code comments minimal, following best practices. Only add comments when the intent is not obvious from the code itself.
- Documentation must be professional in tone and formatting.
- Never use emojis in code, logs, CLI output, commit messages, or documentation.

## Workflow

- Always ask before acting. Clarify any ambiguity in requirements or implementation details before writing code.
- Do not add, remove, or update dependencies without explicit approval.
- Do not refactor, modify, or touch code outside the scope of the current task.
- Explore the codebase before implementing changes. Read relevant files first.
- Work in small, testable increments.

## Git

- Write commit messages in English following Conventional Commits when the project uses it, otherwise follow the project's existing convention.
- Keep commits focused and atomic. One logical change per commit.
- Do not commit generated files, build artifacts, or secrets.

## Code Quality

- Follow the project's existing style, linter, and formatter configuration. Do not override or change them.
- If no project-level configuration exists, follow the language's community standard practices.
- Prefer readability over cleverness.
- Handle errors explicitly. Do not silently swallow exceptions.

## Project-Level Overrides

- Always defer to the project's own CLAUDE.md or AGENTS.md for project-specific conventions.
- When a project-level instruction conflicts with this global config, the project-level instruction wins.
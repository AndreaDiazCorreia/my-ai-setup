# Global Configuration

## Environment

* OS: Arch Linux (Omarchy). AUR helper: yay.
* Editor: Neovim. nano is not installed.
* This configuration is shared between a desktop and a laptop. Changes made on one machine may not exist on the other.

## Communication

* Respond in Spanish.
* Be concise.
* Do not summarize completed work unless explicitly asked.
* Code, comments, commits, branch names, and documentation must be in English unless the project itself is in Spanish.
* Do not use emojis in responses, code, logs, CLI output, commits, or documentation.
* Keep comments minimal. Only explain intent that cannot be inferred from the code itself, such as non-obvious decisions, workarounds, or constraints.
* Never add comments that merely describe what the code does.
* Do not add decorative section comments or commented-out code.
* Documentation must not use second person, marketing language, or exclamation marks.

## Workflow

* Ask questions only when ambiguity would lead to materially different implementations.
* Otherwise, state the assumption briefly and proceed.
* Do not add, remove, or update dependencies without explicit approval.
* Do not modify code outside the scope of the current task.
* Prefer small, testable changes.
* Inspect the repository's existing conventions before implementing changes.
* Prefer modifying existing patterns over introducing new abstractions.
* Run the relevant formatter, linter, type checker, and tests after changes when available.
* Never claim a task is complete if relevant validation was not run.
* If validation cannot be run, explicitly state why.

## Git

* Follow the repository's existing commit convention.
* Use Conventional Commits in English when the project uses them.
* Keep one logical change per commit.
* Do not commit generated files, build artifacts, credentials, secrets, or environment files unless the repository explicitly tracks them.
* Never force-push.
* Never amend published commits.
* Never run destructive Git commands without explicit approval.
* Do not create commits unless explicitly requested.

## Code Quality

* Follow the project's existing formatter, linter, type-checker, and style configuration.
* Do not change project tooling or formatting configuration unless explicitly requested.
* When no project-specific convention exists, follow the language's established community conventions.
* Prefer readability and maintainability over cleverness.
* Handle errors explicitly.
* Never silently swallow exceptions or failures.
* Avoid unnecessary abstractions.
* Avoid speculative generalization for hypothetical future requirements.
* Preserve existing public APIs and behavior unless the task requires changing them.

## Scope and Safety

* Read relevant files before editing them.
* Do not overwrite user changes unrelated to the task.
* Preserve local modifications already present in the working tree.
* Do not delete files or large sections of code unless clearly required by the task.
* Before running commands with significant side effects, verify that they are necessary.
* Never expose secrets, tokens, credentials, or private keys in output.

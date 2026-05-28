# Commands

Commands must be run from the repository root. When executing any command, be sure to use the project environment. Use `uv` whenever possible.

## Style
Run lint, typecheck, and format checks using `uv`.

- `uv run ruff check .` runs lint checks.
- `uv run ruff format --check .` runs format checks.
- `uv run ruff format .` runs format.
- `uv run ruff mypy .` runs typechecks.


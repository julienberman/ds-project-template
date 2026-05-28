# AGENTS

This file defines mandatory operating rules for any coding agent working in this repository.

## Project Overview

[PROJECT OVERVIEW GOES HERE]

## Documentation

### Definitions 

#### Syntax 
- `docs/commands.md` - contains a detailed description of each command. All commands must be run from the repository root.
- `docs/style.md` - contains naming rules, file conventions, layering expectations, and code style requirements.

#### Architecture
- `docs/data.md` - contains the database and object storage model, domain ownership, and environment mapping.
- `docs/directory_structure.md` - contains the canonical ascii file tree and purpose of each directory.

### Maintenance policy

Docs must be meticulously maintained. Any change that affects the structure, behavior, setup, boundaries, database configuration, or tests requires corresponding docs updates in the same work item. No stale docs are allowed.

For each task, explicitly evaluate doc impact and do one of the following:

1. Update relevant files in `docs/`.
2. State clearly that there is no doc impact and why.

When architecture or policy decisions change, record them in `docs/decisions.md`, which should be in reverse chronological order (newest at top).

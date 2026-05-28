# Directory Structure

This file provides the canonical high-level tree for the repository.

## Directory tree
```text
ds-project-template/
|-- datastore/
|   |-- output/
|   `-- raw/
|-- docs/
|-- output/
|   `-- analysis/
|-- pyproject.toml
|-- source/
`-- |-- analysis/
    `-- derived/
```

## Directory descriptions

- `source/` contains project scripts.
- `datastore/` contains local data and is ignored by Git.
- `datastore/raw/` contains input data.
- `datastore/output/` contains derived data.
- `output/` contains project outputs, including figures and tables.
- `docs/` contains project documentation.

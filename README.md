# Data Science Project Template

This repository is a template with a minimal working scaffold.


## Structure

Source scripts live in `source/`. Local data lives in `datastore/`, which is
ignored by Git. Analysis artifacts live in `output/`, which is committed.

- `datastore/raw/` stores original local input data.
- `datastore/output/` stores local derived data.
- `output/` stores committed outputs, including figures and tables.
- `source/derived/` stores scripts that create derived data.
- `source/analysis/` stores scripts that create analysis outputs.


## Quickstart

1. Use this template on GitHub and clone your new repository.
2. Run the rename script from the repository root:

```bash
./init_template.sh your-project-slug
```

This creates the local `datastore/raw/` and `datastore/output/` directories.

3. Copy environment variables:

```bash
cp .env.example .env
```

## Rename Guidance

This template uses the token `ds-project-template` across package names and
docs.

- `init_template.sh` replaces `ds-project-template` in text files with the
  slug you pass.
- It skips common generated and binary paths.

Recommended slug format: lowercase letters, numbers, and hyphens.

# Centralized Templates Test

Test template repository for file-distributor development in pleo-sandbox.

This is a minimal copy of `pleo-io/centralized-templates` containing only simple workflows for testing purposes.

## Structure

- `templates/.github/workflows/` - Workflow template files
- `defaults.yaml` - Default configuration schema from centralized-templates

## Included Workflows

- `pr-help.yaml` - PR helper workflow
- `format-kotlin.yaml` - Kotlin formatting workflow
- `close-stale-prs.yaml` - Stale PR cleanup workflow
- `verify-release.yaml` - Release verification workflow

## Usage

Configure in your repository's `.github/templates.yaml`:

```yaml
version: v1.0.0
automerge: false
files:
  - templates/.github/workflows/pr-help.yaml
  - templates/.github/workflows/format-kotlin.yaml
values:
  repositoryName: my-repo
  # ... other values from defaults.yaml
```

## Source

Templates copied from `pleo-io/centralized-templates` for testing file-distributor in pleo-sandbox.


<!-- Trigger update: 1765049560107 - 1937 -->

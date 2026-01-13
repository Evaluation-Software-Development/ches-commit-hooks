# ches-commit-hooks

This repository provides pre-commit hooks for CHES related projects.

## Development

To publish a new version of the pre-commit hooks, simply create a tag and name it the same as the new version e.g. v1.0.1. Afterwards just update the version in your `.pre-commit-config.yaml` files.

## Usage

Add the following to the `.pre-commit-config.yaml` in your project and add `- id: <hook ID>` for every hook you want to enable:

```yaml
- repo: https://github.com/Evaluation-Software-Development/ches-commit-hooks
  rev: v1.0.1
  hooks:
    - id: prettier
    - id: ...
```

## Available Hooks

### prettier

Formats changed files using `prettier`.

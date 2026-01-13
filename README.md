# ches-commit-hooks

This repository provides pre-commit hooks for CHES related projects.

## Usage

Add the following to the `.pre-commit-config.yaml` in your project and add `- id: <hook ID>` for every hook you want to enable:

```
- repo: https://github.com/Evaluation-Software-Development/ches-commit-hooks
  rev: v1.0.0
  hooks:
    - id: prettier
    - id: ...
```

## Available Hooks

### prettier

Formats changed files using `prettier`.

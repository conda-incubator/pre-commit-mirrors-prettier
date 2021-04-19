# prettier pre-commit hook

Hook for prettier with conda as a language.

- For pre-commit: see https://github.com/pre-commit/pre-commit
- For prettier: see https://github.com/prettier/prettier

### Using prettier with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`:

```yaml
- repo: https://github.com/Quantco/pre-commit-mirrors-prettier
  rev: "" # The git sha / tag you want to point to
  hooks:
    - id: prettier-conda
```

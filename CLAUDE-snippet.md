## CodeRabbit

This repo is covered by CodeRabbit (free open-source plan). Its settings come from the shared config in [`cfdude/coderabbit`](https://github.com/cfdude/coderabbit); a `.coderabbit.yaml` in this repo replaces it entirely unless that file starts with `inheritance: true`.

- **Opening a PR:** CodeRabbit reviews it automatically. Read all of its comments, including the inline ones (`coderabbit pullrequest <number-or-url> --show-threads --agent`; `gh pr view --comments` shows only the top-level comments), and fix them before merging.
- **Committing straight to `main` with no PR:** nothing reviews it, so run `coderabbit review --agent` first and fix the critical and major findings. The CLI has a limited allowance of included reviews (check with `coderabbit usage`), so use it on demand, not in a pre-commit hook.

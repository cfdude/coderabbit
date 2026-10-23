## CodeRabbit

This repo is covered by CodeRabbit (free open-source plan). Its settings come from the shared config in [`cfdude/coderabbit`](https://github.com/cfdude/coderabbit); a `.coderabbit.yaml` in this repo would override it.

- **Opening a PR:** CodeRabbit reviews it automatically. Read its comments (`gh pr view --comments` or `coderabbit pullrequest <url>`) and fix them before merging.
- **Committing straight to `main` with no PR:** nothing reviews it, so run `coderabbit review --agent --gate major` first and fix what it finds. The CLI allows 10 included reviews per hour, so use it on demand, not in a pre-commit hook.

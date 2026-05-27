# iPTO-company-site

Static company website for iPTO.

## Codex PR workflow

This repository includes safeguards for Codex-created pull requests.

Before asking Codex to make changes:

1. Make sure there are no old open Codex pull requests for the same files.
2. Ask Codex to follow `AGENTS.md`.
3. Ask Codex to start from the latest `origin/main`.
4. Keep each request small and focused.

Recommended instruction to include in Codex tasks:

```text
AGENTS.md のルールに従い、必ず最新の origin/main を起点に新しいブランチを作成してください。
既存のCodexブランチは再利用しないでください。
今回の依頼に必要なファイル以外は変更しないでください。
```

When reviewing a pull request:

1. Confirm the pull request targets `main`.
2. Confirm the branch is not behind `main`.
3. Confirm the changed files are limited to the requested task.
4. Confirm the static site check passes.
5. Confirm no old service names or old business names were reintroduced.

## Repository safeguards

- `AGENTS.md` defines repository-level instructions for Codex.
- `.github/pull_request_template.md` adds a review checklist to new pull requests.
- `.github/workflows/static-site-check.yml` runs lightweight checks for required files, HTML basics, official wording, and internal link format.

## Content rules

Use the official business name:

- `AI活用・業務改善支援事業`

Use the official service names:

- `業務診断`
- `AI導入・業務改善支援`
- `AI活用伴走サポート`

Do not present the service as AI tool sales. The value should be described as business process improvement, efficiency, standardization, and operational adoption.

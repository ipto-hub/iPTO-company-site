# AGENTS.md

## Repository rules for Codex

This repository uses `main` as the default branch.

## Branch and pull request rules

Before starting any task:

- Fetch the latest remote state.
- Use the latest `origin/main` as the base.
- Do not reuse old Codex branches.
- Create a new task branch from the latest `origin/main` for each task.
- Do not create a pull request from a branch that is already behind `origin/main`.

Before opening a pull request:

- Confirm the branch is not behind `origin/main`.
- If the branch is behind `origin/main`, update it before creating the pull request.
- If updating causes conflicts, stop and explain which files conflict.
- Keep the pull request focused on the requested task.

## Scope control

- Change only the files required for the requested task.
- Do not reformat unrelated files.
- Do not modify unrelated page content.
- Do not modify generated files or build outputs.
- Do not modify lock files unless dependency changes were explicitly requested.
- Do not modify `sitemap.xml`, `robots.txt`, favicon files, OGP assets, or existing SEO metadata unless explicitly requested.

## Website content rules

- This site presents the business as `AI活用・業務改善支援事業`.
- Do not describe the service as AI tool sales.
- Emphasize business process improvement, efficiency, standardization, and operational adoption.
- AI should be described as supporting drafts, organization, and first-pass work.
- Final confirmation, judgment, and operational responsibility remain with people.
- Avoid claims that AI can fully automate everything or immediately guarantee results.

## Japanese naming rules

Use the following official service names when naming services:

- `業務診断`
- `AI導入・業務改善支援`
- `AI活用伴走サポート`

Do not use old or unofficial names as formal service names.

## Output quality

- Keep wording clear for small and medium-sized businesses that may not be familiar with AI.
- Avoid excessive sales pressure.
- Prefer small, practical changes over broad rewrites.
- If information is uncertain, keep placeholders such as `【要確認】` or explain that confirmation is needed.

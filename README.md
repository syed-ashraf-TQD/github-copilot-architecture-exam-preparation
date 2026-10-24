# GitHub Copilot Architecture Exam Preparation

A Markdown-first study repository for preparing for the GitHub Copilot architecture exam. Use it to organize study notes, review key concepts, and track preparation progress.

## Study areas

- GitHub Copilot architecture and components
- Models, prompts, and context
- Copilot features and supported development workflows
- Administration, configuration, and policy controls
- Security, privacy, and responsible AI
- Integrations, extensibility, and troubleshooting

## Preparation plan

1. Review the current exam objectives and official GitHub documentation.
2. Add concise notes and links for each study area.
3. Record questions or concepts that need more review.
4. Revisit the notes and verify details against current official sources.

## Repository format

Study materials should be Markdown files with the `.md` extension. Keep source links alongside notes so information can be checked for accuracy and currency.

Pull requests are checked automatically. The Markdown-only check fails if the proposed repository contains a tracked file that does not end in `.md`, except for `.github/workflows/markdown-only.yml`. The default branch is protected so changes must go through a pull request and required checks must pass before they can be merged.

## Using GitHub Copilot

- To ask Copilot to work on an issue, assign the issue to **Copilot**. Copilot uses the issue content and comments available when assigned; add later guidance on the pull request it opens.
- To ask Copilot to update an existing pull request, mention `@copilot` in a regular pull request comment.
- To request automatic Copilot reviews for new pull requests, create an active branch ruleset targeting the default branch and enable **Automatically request Copilot code review**. See [GitHub's code review setup guide](https://docs.github.com/en/copilot/how-tos/copilot-on-github/set-up-copilot/configure-code-review).
- Copilot availability depends on your Copilot plan and, for organization accounts, administrator policies.

Repository-specific guidance for Copilot is in [`.github/copilot-instructions.md`](.github/copilot-instructions.md).

## Disclaimer

This is an independent study repository and is not affiliated with or endorsed by GitHub. Exam objectives and product capabilities can change; refer to official GitHub resources for the latest information.

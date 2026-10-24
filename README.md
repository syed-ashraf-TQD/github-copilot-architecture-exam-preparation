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

Pull requests are checked automatically. The Markdown-only check fails if the proposed repository contains a tracked file that does not end in `.md`, except for `.github/workflows/markdown-only.yml` and `.github/workflows/copilot.yml`. The default branch is protected so changes must go through a pull request and required checks must pass before they can be merged.

The Copilot CLI workflow runs a headless review on pull requests and can also be started manually from the Actions tab. It skips pull requests from forks because repository secrets are not available to those runs. To enable it, add a repository secret named `COPILOT_GITHUB_TOKEN` containing a fine-grained personal access token with the **Copilot Requests** permission. The workflow passes it to the CLI as `GH_TOKEN`, which is the documented authentication environment variable. The CLI is denied shell and file-write tools; this check reports a summary but does not automatically validate factual accuracy.

See the [GitHub Copilot CLI documentation](https://docs.github.com/en/copilot/concepts/copilot-surfaces/copilot-cli) for details about programmatic use and authentication.

## Disclaimer

This is an independent study repository and is not affiliated with or endorsed by GitHub. Exam objectives and product capabilities can change; refer to official GitHub resources for the latest information.

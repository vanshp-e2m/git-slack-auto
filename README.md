# git-slack-auto

Test repo for GitHub → Slack commit notifications.

- Merging a PR into `dev-connect` (WordPress plugin) or `dev-command` (Claude plugin) posts a message to `#slack-git-automation`.
- Individual commits/pushes, PRs into other branches, and PRs closed without merging do not notify.
- The workflow is [.github/workflows/slack-notify.yml](.github/workflows/slack-notify.yml).
- Requires the repository secret `SLACK_WEBHOOK_URL` (Slack Incoming Webhook URL).

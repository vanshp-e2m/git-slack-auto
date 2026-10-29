# git-slack-auto

Test repo for GitHub → Slack commit notifications.

- Pushes (including merged PRs) to `dev-connect` or `dev-command` post a message to `#slack-git-automation`.
- Pushes to `test-1`, `test-2` and `main` do not notify.
- The workflow is [.github/workflows/slack-notify.yml](.github/workflows/slack-notify.yml).
- Requires the repository secret `SLACK_WEBHOOK_URL` (Slack Incoming Webhook URL).

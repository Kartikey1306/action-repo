# GitHub Webhook Trigger Repository (action-repo)

This repository is used to trigger GitHub Webhook events for testing purposes.

### ✅ Events covered:
- Push events
- Pull request events
- Merge events

These events are sent to the registered webhook endpoint in `webhook-repo`.

## 🔧 Instructions

1. Push a new commit to trigger a `push` event.
2. Create a pull request from a new branch to trigger a `pull_request` event.
3. Merge the pull request to test a `merge` event (inferred from PR + `merged: true`).

Webhook receiver endpoint (from `webhook-repo`) must be configured in the **Settings > Webhooks** section of this repository.

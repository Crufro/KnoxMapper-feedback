# KnoxMapper Feedback

The public home for bug reports, feedback, and feature ideas for **KnoxMapper**, a browser-based map authoring app for Project Zomboid.

This repository is connected to the KnoxMapper Discord through **KnoxMapper Helper**. The bot turns posts in the `bug-reports` and `feedback-and-ideas` forums into GitHub issues so the team can track them alongside development. Application and bot code are maintained in the main KnoxMapper repository; this repository holds the public feedback tracker.

[Browse tracked issues](https://github.com/Crufro/KnoxMapper-feedback/issues)

**The Discord server is not live yet. Public access is not available.**

## Report a bug or share an idea

For members with pre-launch access, use the appropriate Discord forum:

- `bug-reports` — something is broken or behaving unexpectedly.
- `feedback-and-ideas` — suggestions, workflow improvements, and feature requests.

Search existing posts or issues first, then create one post per bug or idea. Choose the relevant feature-area tag and use a descriptive title.

For a bug, include steps to reproduce, what you expected, what actually happened, and your browser and operating system. Screenshots and relevant error messages help. For an idea, describe what you are trying to accomplish and how the change would help.

The bot acknowledges the post, mentions the Dev role, and adds a link to its GitHub issue. Keep updates and discussion in the original Discord post so everything stays together.

## How the Discord connection works

| Activity | What happens |
| --- | --- |
| New report or idea in a connected forum | The bot creates a public issue with the original text, attachment links, and a link to the Discord post. |
| New human reply in a linked post | The reply is copied to a GitHub comment with the author's Discord display name, timestamp, attachment links, and source link. |
| Feature-area tags change in Discord | The corresponding `area:*` labels update on GitHub. |
| GitHub issue is closed or reopened | The linked Discord post is closed or reopened. |
| A moderator closes or reopens the Discord post | The linked GitHub issue is closed or reopened. |
| A mirrored Discord reply is deleted | Its copied GitHub comment is deleted. |
| The original Discord post is deleted | The issue is closed as **not planned** and labeled `removed-from-discord`; its history is preserved. |

Bot replies and message edits are not synced. GitHub comments are not copied back to Discord. Automatic archival due to inactivity does not close the GitHub issue, and locks and status tags are not synced. Syncing may take a short time, especially after an outage.

Only the connected forums are watched. Reports and replies from before their respective activation cutoffs are not backfilled. Discord attachment links may expire; use the original Discord post if a link stops working.

## Labels

- `bug` — reports from `bug-reports`.
- `feedback` — suggestions from `feedback-and-ideas`.
- `area:*` — the feature area selected in Discord: Map Editor, Building Studio, Vehicle Studio, Zombie Studio, Tile Library, Import & Export, Collaboration, Account & Dashboard, or General. Posts without an area use `area:general`.
- `removed-from-discord` — the source post was deleted; the issue is retained for history.

GitHub label changes do not update Discord tags.

## Public visibility

**Posts and human replies in the connected forums are copied to this public repository.** This includes report text, Discord display names on replies, and attachment links. Share only information you are comfortable making public, and remove passwords, tokens, personal information, and private project data from screenshots or logs before posting.

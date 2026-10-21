# claude-review — setup

1. `chmod +x agents/pr-review/claude-review`
2. `agents/pr-review/claude-review --pr https://github.com/owner/repo/pull/123`
3. Optional: keep `.github/workflows/claude-review.yml` for Actions.

Output is structured Markdown: Summary, Risks, Suggestions, Confidence.
See `samples/` for two example reviews.

# Skill: Generate structured CHANGELOG

## Purpose
[BOUNTY $50] SKILL: Generate a structured CHANGELOG from git history

## Trigger
`/generate-changelog`

## Instructions
1. Read git tags; take commits since the latest tag (or last 50 commits).
2. Categorize each commit into Added / Fixed / Changed / Removed.
3. Write `CHANGELOG.md` with those sections and dates.
4. Keep output markdown-only; do not modify source code.

## Acceptance
- Works via `/generate-changelog` or `bash changelog.sh`
- Uses commits since last tag
- Categories: Added / Fixed / Changed / Removed
- Includes sample output in the PR
- README setup in ≤3 steps

## Issue context

## 💰 Bounty: $50 — powered by [Opire](https://opire.dev)

## Description
Create a Claude Code skill (`SKILL.md`) or a bash script that automatically generates
a structured `CHANGELOG.md` from a project's git history.

## Acceptance Criteria
- [ ] Works via `/generate-changelog` command or `bash changelog.sh`
- [ ] Fetches commits since the last git tag
- [ ] Auto-categorizes into: `Added` / `Fixed` / `Changed` / `Removed`
- [ ] Outputs a properly formatted `CHANGELOG.md`
- [ ] Tested on a real GitHub repo (include a sample output in the PR)
- [ ] README with setup instructions in 3 steps or fewer

## How to Claim
1. Comment `/opire try` in this issue
2. Submit a PR with your solution
3. Payment is released automatically on merge ✅

## Accepted Stack
Bash, Python, or native Claude Code `SKILL.md`.

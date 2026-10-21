# CLAUDE.md — Next.js + SQLite SaaS

> Generated for: [BOUNTY $75] TEMPLATE: CLAUDE.md for a Next.js + SQLite SaaS project

## Stack & versions
- Next.js 15 App Router
- SQLite via better-sqlite3 or Turso
- TypeScript strict

## Folder structure
- `app/` routes (App Router)
- `lib/db/` schema + migrations
- `components/` UI only
- `scripts/` one-off jobs

## Naming
- Files: kebab-case; React components: PascalCase
- DB tables: snake_case plural

## SQL / migrations
- Every schema change is a numbered SQL migration
- No ORM magic in route handlers — query in `lib/db`
- Prefer idempotent migrations

## Dev commands
- `pnpm dev` — local app
- `pnpm db:migrate` — apply migrations
- `pnpm lint && pnpm test` — before PR

## Patterns
- Server Components by default; Client only for interactivity
- Validate inputs at the boundary
- One PR = one concern

## Anti-patterns
- No raw SQL in React components
- No god `utils.ts`
- No skipping migrations for “just this once”

## Issue context

## 💰 Bounty: $75 — powered by [Opire](https://opire.dev)

## Description
Create an opinionated, production-ready `CLAUDE.md` for a typical SaaS project
built with Next.js 15 App Router and SQLite (better-sqlite3 or Turso).

## Acceptance Criteria
- [ ] Covers: project structure, naming conventions, DB migration rules
- [ ] Includes: dev commands, patterns to follow, anti-patterns to avoid
- [ ] Opinionated — not generic. Every rule has a reason.
- [ ] Usable without modification on a greenfield Next.js + SQLite project
- [ ] Tested: create a new project, paste the CLAUDE.md, confirm Claude Code
      understands the context without asking clarifying questions

## How to Claim
1. Comment `/opire try` in this issue
2. Submit a PR with your CLAUDE.md
3. Payment is released automatically on merge ✅

## Expected Sections
- Stack & versions
- Folder structure
- SQL / migration conventions
- Component patterns
- What we don't do (and why)

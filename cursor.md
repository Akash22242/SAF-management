# SAF Management — Cursor guide

Use this file as project context when working in this workspace.

## Project

- **Name:** SAF Management
- **Owner:** Ihatisamul (Software engineer)
- **Goal:** Build and iterate directly in code — create, debug, ship.

## How to work here

- Prefer implementing in the repo over long explanations.
- Keep changes focused: only files needed for the task.
- Do not add docs, comments, or extra files unless asked.
- Do not commit unless explicitly requested.
- Never update git config or run destructive git commands unless asked.

## Quality bar

- Match existing style and naming in the repo.
- After UI, layout, routing, or client-state changes, verify the flow end to end (click, type, submit, navigate) — not a single screenshot.
- Check related pages that share the same state or components.
- Cover empty, error, and edge states when the change touches them.

## Git

- Commit only when asked.
- PR work should use `gh` and follow the repo’s existing commit style.
- Never skip hooks unless asked.

## Secrets

- Do not commit `.env`, credentials, or keys.
- Warn if a requested commit would include secrets.

## Tech stack

- **Runtime:** Node.js
- **Language:** TypeScript
- **Framework:** Next.js (App Router)
- **UI:** React
- **Package manager:** npm

Use TypeScript for all app and server code. Prefer Next.js conventions: `app/` routes, Server Components by default, Client Components only when needed (`"use client"`). Build UI with React. Install and run everything with npm. Keep API work in Next.js Route Handlers unless a separate Node service is required.

## Open questions

Fill these in as the project takes shape:

- Database and ORM
- Auth
- Styling (CSS, Tailwind, etc.)
- Environments (local, staging, production)
- How to run tests and the app locally (`npm`)

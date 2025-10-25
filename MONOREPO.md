# Monorepo Workspaces

This repository uses npm workspaces to manage `client` and `server` apps.

## Commands
- `npm run dev:client` — start Next.js client dev server
- `npm run dev:server` — start Node/Express server dev
- `npm run dev` — start both concurrently
- `npm run build:client` — build client
- `npm run build:server` — build server
- `npm run build` — build both

## Notes
- Line endings normalized via `.gitattributes` (LF by default). On Windows, PowerShell scripts/batch files use CRLF.
- Root `.gitignore` ignores `node_modules` and common logs.

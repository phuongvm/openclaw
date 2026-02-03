# Suggested commands

- Install: `npm install -g openclaw@latest`, `openclaw onboard --install-daemon`
- Run gateway: `openclaw gateway --port 18789 --verbose`
- Dev: npm/pnpm/bun in repo root; vitest for unit/e2e (vitest.unit.config.ts, vitest.e2e.config.ts, etc.)
- Message: `openclaw message send --to <target> --message "..."`, `openclaw agent --message "..." --thinking high`
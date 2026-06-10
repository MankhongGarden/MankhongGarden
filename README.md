# Mankhong Garden

Solo founder building consumer web platforms in Thailand — and documenting every non-obvious pattern that survives production.

Everything here was proven on live products first (LINE bots with real users, Thai payment flows, Next.js + Supabase + Vercel stacks), then written up only after the fix held in production.

## LINE platform engineering

| Repo | What it solves |
|---|---|
| [line-webhook-fast-ack-dispatcher-worker](https://github.com/MankhongGarden/line-webhook-fast-ack-dispatcher-worker) | Cold-start-proof LINE webhooks: fast-ack + dispatcher/worker split + a 4-layer idempotency taxonomy |
| [line-rich-menu-role-based-template](https://github.com/MankhongGarden/line-rich-menu-role-based-template) | Bank-style role-based rich menus with an idempotent uploader and LIFF wiring |
| [meta-capi-line-liff-conversion-tracking](https://github.com/MankhongGarden/meta-capi-line-liff-conversion-tracking) | Why Meta Pixel undercounts inside the LINE LIFF webview — and the server-side CAPI bridge that fixes it |

🚧 **Coming next: `create-line-bot`** — one command that scaffolds all of the above into a production-ready LINE bot starter.

## Claude Code in production (Windows-first)

| Repo | What it solves |
|---|---|
| [claude-code-multi-context-windows](https://github.com/MankhongGarden/claude-code-multi-context-windows) | Run separate Claude accounts and config contexts on one Windows machine |
| [chrome-mcp-windows-survival-guide](https://github.com/MankhongGarden/chrome-mcp-windows-survival-guide) | Nine real gotchas installing and operating chrome-mcp on Windows |
| [claudemd-lazy-load-references](https://github.com/MankhongGarden/claudemd-lazy-load-references) | Cut always-loaded CLAUDE.md tokens by ~57% with lazy-loaded reference files |
| [model-upgrade-replay-validation](https://github.com/MankhongGarden/model-upgrade-replay-validation) | Why a passing benchmark isn't safe to ship — replay validation for LLM model swaps |

## Next.js + Supabase field notes

| Repo | What it solves |
|---|---|
| [nextjs-supabase-pdpa-analytics](https://github.com/MankhongGarden/nextjs-supabase-pdpa-analytics) | PDPA/GDPR-strict product analytics without leaking personal data |
| [nextjs-async-layout-unstable-rethrow](https://github.com/MankhongGarden/nextjs-async-layout-unstable-rethrow) | `error.tsx` doesn't catch layout errors — the `unstable_rethrow` pattern that does |
| [marketplace-prelaunch-smoke-test](https://github.com/MankhongGarden/marketplace-prelaunch-smoke-test) | ฿125 of real payments → 16 bugs: a pre-launch smoke-test runbook |
| [anthropic-cloud-routines-custom-mcp](https://github.com/MankhongGarden/anthropic-cloud-routines-custom-mcp) | A custom MCP server with OAuth 2.1 + PKCE so Claude cloud routines can reach your APIs |
| [google-oauth-nonexpiring-refresh-token](https://github.com/MankhongGarden/google-oauth-nonexpiring-refresh-token) | "Production but unverified" Google OAuth apps and refresh-token longevity |

---

Building from Thailand 🇹🇭 · Issues and PRs welcome on any repo

# xdlc-labs

xdlc-labs makes tools you run on your own machines. Nothing phones home.

**[xdlc-agent](https://github.com/xdlc-labs/xdlc-agent)** is a daemon next to your repos. When GitHub Actions fails, it can open a **Fix** with the coding agent you already use — Claude, Codex, Cursor, or Gemini. Promote and Revert are optional. They stay off until you turn them on.

**[Airlock](https://github.com/xdlc-labs/airlock)** is a CI gate for AI artifacts: prompts, skills, MCP servers, and models. It snapshots what changed, checks policy, and ships, blocks, or asks for approval.

| Product | CLI | License |
|---------|-----|---------|
| [xdlc-agent](https://github.com/xdlc-labs/xdlc-agent) | `xdlc` | MIT |
| [Airlock](https://github.com/xdlc-labs/airlock) | `airlock` | Apache-2.0 |

**Docs:** [xdlc-labs.github.io/documentation](https://xdlc-labs.github.io/documentation/)

## Try it

| Repo | What you do |
|------|-------------|
| [example-service](https://github.com/xdlc-labs/example-service) | Point xdlc-agent at this small HTTP app (`/healthz`, `/metrics`) |
| [fixtures](https://github.com/xdlc-labs/fixtures) | Open a sample PR that fails CI, then watch a Fix |

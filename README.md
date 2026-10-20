### C10

Tools for running many Claude Code / Codex sessions in parallel. Currently building [vocado](https://voca.do).

#### Running agents in parallel

| Project | What it does |
|---|---|
| **[atc](https://github.com/c10dev/atc)** | A control tower for AI coding sessions: Claude Code and Codex sessions, git worktrees and Linear tickets on one radar screen. ([macOS menu bar app](https://github.com/c10dev/atc-app)) |
| **[portboard](https://github.com/c10dev/portboard)** | Ports and dev servers for a machine shared by people and agents, so parallel sessions stop colliding on `:3000`. `npx @c10dev/portboard start` |
| **[agent-leverage](https://github.com/c10dev/agent-leverage)** | How many hours your agents worked for every hour you did, from the Claude Code and Codex logs already on your machine. |
| **[runup](https://github.com/c10dev/runup)** | Before merge: base vs head screenshots of only the screens a diff can reach, in one static report. |

#### Claude Code plugins

- **[secret-redact](https://github.com/c10dev/secret-redact)** — redacts secrets before the model reads them or the transcript stores them.
- **[guard-hooks](https://github.com/c10dev/guard-hooks)** — tells running sessions when `CLAUDE.md` changes; blocks `pkill`-style process kills.
- **[radio-discipline](https://github.com/c10dev/radio-discipline-plugin)** — aviation-style radio discipline for agents that message each other.

#### Other

- **[fanout](https://github.com/c10dev/fanout)** — self-hosted uploader that posts one video to YouTube, TikTok, Reels, X, Bluesky, Mastodon and PeerTube via official APIs.
- **[tennis-sim](https://github.com/c10dev/tennis-sim)** — tennis match engine where points come from tactics, execution error and ball flight.

[X @chaehybuilds](https://x.com/c10xxxxx)

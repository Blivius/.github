## Blivius

We build open-source infrastructure for running AI agents. Everything here is self-hostable under
Apache-2.0.

| Project | What it is | |
| --- | --- | --- |
| [**Dispach**](https://github.com/blivius/dispach) | The agent backend your product calls over HTTP: agents with memory, tools, schedules, channels and approvals, on any OpenAI-compatible model or AWS Bedrock. | [Docs](https://dispach.blivius.com/docs) |
| [**TydBase**](https://github.com/blivius/tydbase) | Safe database access for your team's AI coding agents. Scoped, masked reads; writes wait for a teammate to approve the row diff; every query is audited. Validating now. | [Site](https://tydbase.blivius.com) |

### Install

```bash
brew install blivius/tap/dispach
```

Formulae live in [`blivius/homebrew-tap`](https://github.com/blivius/homebrew-tap).

### Get in touch

Questions go in each project's Discussions. Security reports go privately to the affected repo's
**Security → Report a vulnerability**, or to security@blivius.com. Anything else:
hello@blivius.com, or [blivius.com](https://blivius.com).

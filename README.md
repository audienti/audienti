# audienti

Use Audienti as the system of record: audiences, offers, campaigns, prospects and progress through the CLI, MCP or API.

Agent skill for Audienti (https://exo.audienti.com). It is also served by Audienti itself:
`audienti skills show audienti`. The authored copy lives in the Audienti application
repository and is exported here with `scripts/export-skill-plugin.mjs`; edit it there.

Installing the skill does not grant any permission in Audienti or authorize outreach.

Claude Code installation:

```sh
claude plugin install audienti --marketplace audienti/plugins
```

Codex installation (after adding the Audienti marketplace):

```sh
codex plugin add audienti@audienti
```

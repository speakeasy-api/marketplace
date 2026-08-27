# Platform MCP

Manage MCPs, Risk Policies and explore logs in your favorite agent.

This repository is Speakeasy's public plugin marketplace. Registering it once makes every plugin Speakeasy publishes available in your agent, including ones added later. It contains no credentials: plugins authenticate against your organization through OAuth on first use, and installing one grants no access on its own.

It currently ships [Platform MCP](https://www.speakeasy.com/product/gram).

> **Auto-generated.** Every file here is rendered from the Speakeasy control plane and replaced on each release. Manual edits are discarded.

## Claude Code

```
/plugin marketplace add https://github.com/speakeasy-api/marketplace
/plugin install platform-mcp@speakeasy
```

## Codex

```
codex plugin marketplace add https://github.com/speakeasy-api/marketplace
```

Then open `/plugins` and install `platform-mcp-codex`.

## Cursor

In the Cursor dashboard for a team you administer, go to Settings → Plugins → Import and paste:

```
https://github.com/speakeasy-api/marketplace
```

## Other agents

`opencode-plugins/` and `agent-plugins/` carry the same server in the OpenCode and portable Agent Plugins formats. Clone this repository or download an archive from GitHub and point your agent at the directory for your format.

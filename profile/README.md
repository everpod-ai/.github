# Everpod

Everpod is an easy way to get your own always-on, persistent cloud computer for AI agents, working in minutes: with a managed OpenClaw agent on it, or as a developer pod with Claude Code, Codex or both installed.

- **An OpenClaw pod** is a managed OpenClaw agent on a private computer of its own: set up, secured, backed up and kept up to date for you. [Create your agent](https://everpod.ai).
- **A developer pod** is a cloud computer you run yourself, with Claude Code, Codex or both installed, reached only over your own Tailscale network, so your agents keep working when your laptop is closed. [The developer pod](https://everpod.ai/developer-pod).

Start either at everpod.ai, or have an agent you already use start it for you through the Everpod API.

## Ways in

- **MCP server.** Claude Code, Codex, OpenClaw or another MCP client works with your Everpod account for you, with a key you make as the credential. [Connect an agent](https://everpod.ai/docs/api); source in [`mcp`](https://github.com/everpod-ai/mcp).
- **REST API.** The same operations over HTTPS, with a bearer key. [Reference](https://everpod.ai/docs/api).
- **JavaScript SDK.** `npm install @everpod-ai/sdk`. Source in [`sdk-node`](https://github.com/everpod-ai/sdk-node).
- **Python SDK.** `pip install everpod-ai`. Source in [`sdk-python`](https://github.com/everpod-ai/sdk-python).
- **Skills.** For a coding agent on your own computer, such as Claude Code or Codex: it gets you a developer pod and helps you connect it. For an OpenClaw agent: it starts a new agent or a developer pod for its owner, or moves itself onto a pod (`openclaw skills install @everpod/everpod`). Both in [`skills`](https://github.com/everpod-ai/skills).

Keys are made at [everpod.ai/account/keys](https://everpod.ai/account/keys). Whether Everpod is up is at [status.everpod.ai](https://status.everpod.ai). Questions: support@everpod.ai.

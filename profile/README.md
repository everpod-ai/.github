# Everpod

Everpod runs an AI agent on a pod: a private, always-on cloud computer of its own. Start one at [everpod.ai](https://everpod.ai), or have an agent you already use start one for you through the Everpod API.

## Ways in

- **MCP server.** Claude Code, Codex, OpenClaw or another MCP client works with your Everpod account for you, with a key you make as the credential. [Connect an agent](https://everpod.ai/docs/api); source in [`mcp`](https://github.com/everpod-ai/mcp).
- **REST API.** The same operations over HTTPS, with a bearer key. [Reference](https://everpod.ai/docs/api).
- **JavaScript SDK.** `npm install @everpod-ai/sdk`. Source in [`sdk-node`](https://github.com/everpod-ai/sdk-node).
- **Python SDK.** `pip install everpod-ai`. Source in [`sdk-python`](https://github.com/everpod-ai/sdk-python).
- **The OpenClaw skill.** An OpenClaw agent moves itself onto a pod for its owner: `openclaw skills install @everpod/everpod`. Also in [`skills`](https://github.com/everpod-ai/skills).

Keys are made at [everpod.ai/account/keys](https://everpod.ai/account/keys). Whether Everpod is up is at [status.everpod.ai](https://status.everpod.ai). Questions: support@everpod.ai.

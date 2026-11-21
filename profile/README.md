<div align="center">

# uagents8

### The hosting platform built for AI agents

Deploy from Git, ZIP or Docker. Private agent networking, per-agent access tokens, one-click rollback — and when a deploy fails, AI fixes the code.

[Website](https://uagents8.com) · [Start 14-day free trial](https://uagents8.com) · [Demo agent](https://github.com/uagents8/uagents8-demo-agent)

**Hosted in Europe · Priced in euros, VAT handled**

</div>

---

## What is uagents8?

uagents8 is a hosting platform made specifically for AI agents — not generic apps. An agent is any service that listens on a port or runs on a schedule: a LangGraph graph behind FastAPI, an OpenAI Agents SDK agent, a CrewAI crew, a plain FastAPI service, or a Telegram bot. You bring the model keys; we run the app.

Push from GitHub, GitLab, Bitbucket, a ZIP archive or a Docker image. If your repo has a Dockerfile, we use it as is. If not, we detect the stack and build it with every dependency. When a build or deploy fails, AI reads the error and your code, then deploys a fixed copy — your repository is never changed.

## Why uagents8?

- **AI Fix** — When a deploy fails, the cause is explained in plain language. One click patches a copy, checks it, and ships it as a new version. Restore the previous version anytime.
- **Private networking** — Link two agents and they call each other by name, off the public internet, via a `{NAME}_URL` environment variable.
- **Per-agent access tokens** — Give each caller its own token. Calls without it are refused at the edge, before your code or your model runs.
- **Zero-downtime deploys** — A new version takes over only once it is healthy; a failed start rolls back by itself.
- **Scheduled agents** — Give an agent a cron schedule; runs never overlap and failed runs are retried.
- **Secrets that stay secret** — Mark a variable sensitive and it is encrypted on save, never shown again.
- **Persistent storage** — Give an agent a disk and its data survives restarts, redeploys and crashes.
- **Built-in observability** — Live logs, per-agent metrics and alerts, with nothing to set up.

## Works with

- **LangGraph**
- **CrewAI**
- **OpenAI Agents SDK**
- Plain FastAPI services, Telegram bots, and any scheduled job

## Made in Europe

Your agents, their data and our databases run in Europe. Flat monthly plans in euros with VAT handled at checkout, a DPA on request, and a public list of sub-processors. Your code and data are never used to train AI models.

## Get started

1. Explore the [demo agent](https://github.com/uagents8/uagents8-demo-agent)
2. Start a [14-day free trial](https://uagents8.com)
3. Connect a repo and ship your first agent

## Links

- Website — https://uagents8.com
- Contact — admin@uagents8.com

<div align="center">

Built for developers and teams shipping AI agents.

</div>

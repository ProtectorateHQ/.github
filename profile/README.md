<h1 align="center">Zero Trust for AI agents.</h1>

<p align="center">
  Let your AI work proactively: build features, fix bugs, and handle incidents.<br>
  You decide what AI can access, what it can change, and when it needs your approval.
</p>

## <img src="https://raw.githubusercontent.com/ProtectorateHQ/.github/main/profile/assets/ryker.svg?v=reply" width="40" height="40" align="absmiddle" alt="Ryker logo">&ensp;[Ryker](https://github.com/AndrewDryga/responder) — your proactive AI teammate

Talk to Ryker in Slack and GitHub like you would talk to a teammate.
Hand it a job: build a feature, fix a bug, review a pull request, investigate a failing service, or just tell it to proactively fix all issues raised by your Grafana alerts. It gets to work, keeps track of the context, follows up on unfinished tasks, and starts working on an incident even before you are paged.

It uses Emisar for secure remote access and co:op to run coding agents in secure sandboxes, manage their tasks, and coordinate work across models.

[Meet Ryker](https://github.com/AndrewDryga/responder#quick-start) · [Source](https://github.com/AndrewDryga/responder)

## <img src="https://raw.githubusercontent.com/ProtectorateHQ/.github/main/profile/assets/emisar-avatar.png" width="40" height="40" align="absmiddle" alt="Emisar logo">&ensp;[Emisar](https://emisar.dev) — the best way to give AI secure access to your infrastructure

Connect each AI agent to Emisar once for secure remote access to your
infrastructure and third-party tools. Start with ready-made actions for tools
such as Postgres, AWS, GCP, Kubernetes, GitHub and Sentry (or any of 90+ others), or add your own without setting up another agent
integration.

Choose who can access which tools and what they can do. Your policies decide
what runs, what gets blocked, and what needs approval. Emisar's full audit trail
records all actions performed.

[Try Emisar](https://emisar.dev/docs/quickstart) · [See available actions](https://emisar.dev/packs) · [How Emisar works](https://emisar.dev/how-it-works) · [How Emisar controls access](https://emisar.dev/security) · [Source](https://github.com/AndrewDryga/emisar)

## <img src="https://raw.githubusercontent.com/ProtectorateHQ/.github/main/profile/assets/coop.svg" width="40" height="40" align="absmiddle" alt="co:op logo">&ensp;[co:op](https://coop.dryga.com) — a runtime and orchestrator for coding agents

Run coding agents in containers, manage their tasks, and coordinate work across models.

[Try co:op](https://coop.dryga.com) · [Source](https://github.com/AndrewDryga/coop)

## How they work together

An alert lands in Slack at 2 a.m. Ryker picks it up and uses Emisar to check
the affected systems. It investigates the problem and posts what it finds in
the thread, without waiting for someone to ask.

If the fix needs a code change, Ryker offers to make the fix.
Once you approve, an isolated co:op box is spawned with a coding agent that fixes the issue, and Ryker opens a GitHub pull request for your review. Emisar checks any requested system actions against your policy and ensures that the agent can work unattended and asks for approval only when it's needed.

_co:op lets AI agents work securely on your computer. Emisar extends that security
to your infrastructure and third-party tools. Ryker brings both together as your
AI teammate in Slack and GitHub._

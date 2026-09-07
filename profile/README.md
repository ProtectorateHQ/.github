<p align="center">
  <img src="https://raw.githubusercontent.com/ProtectorateHQ/.github/main/profile/assets/protectorate-banner.png?v=forcefield-a" alt="Protectorate — Forcefield logo" width="100%">
</p>

<h1 align="center">Put AI to work on your code and systems.</h1>

<p align="center">
  Give AI real work: build features, fix bugs, and handle incidents.<br>
  You decide what AI can access, what it can change, and when it needs your approval.
</p>

Ryker is the teammate. Coop runs and coordinates the coding agents. Emisar
gives them one secure connection to infrastructure and third-party tools.

## <img src="https://raw.githubusercontent.com/ProtectorateHQ/.github/main/profile/assets/ryker.svg?v=reply" width="40" height="40" align="absmiddle" alt="Ryker logo">&ensp;[Ryker](https://github.com/AndrewDryga/responder) — your proactive AI teammate

Talk to Ryker in Slack and GitHub like you would a teammate. Hand it a job:
build a feature, fix a bug, review a pull request, or investigate a failing
service. It gets to work, keeps the context, and follows up on unfinished tasks.

Ryker joins conversations when it has something useful to add and watches your
alert feeds for trouble. Give it early alerts and it can be on an incident
before you're paged. Ask it to carry out a fix, and it uses Emisar to act within
your rules.

[Meet Ryker](https://github.com/AndrewDryga/responder#quick-start) · [Source](https://github.com/AndrewDryga/responder)

## <img src="https://raw.githubusercontent.com/ProtectorateHQ/.github/main/profile/assets/emisar-avatar.png" width="40" height="40" align="absmiddle" alt="Emisar logo">&ensp;[Emisar](https://emisar.dev) — one connection to your tools

Connect each AI agent to Emisar once for secure remote access to your
infrastructure and third-party tools. Start with ready-made actions for tools
such as GitHub and Sentry, or add your own without setting up another agent
integration.

Choose who can access which tools and what they can do. Emisar's built-in
approval system handles requests that need a person. Its full audit trail
records actions performed through Emisar: who requested them, approval
decisions, and results.

[Try Emisar](https://emisar.dev/docs/quickstart) · [See available actions](https://emisar.dev/packs) · [Source](https://github.com/AndrewDryga/emisar)

## <img src="https://raw.githubusercontent.com/ProtectorateHQ/.github/main/profile/assets/coop.svg" width="40" height="40" align="absmiddle" alt="Coop logo">&ensp;[Coop](https://coop.dryga.com) — a runtime and orchestrator for coding agents

Run coding agents in containers, manage their tasks, and coordinate work across
models.

[Try Coop](https://coop.dryga.com) · [Source](https://github.com/AndrewDryga/coop)

## How they work together

An alert lands in Slack at 2 a.m. Ryker picks it up and uses Emisar to check
the affected systems. It investigates the problem and posts what it finds in
the thread, without waiting for someone to ask.

If fixing it needs a code change, hand Ryker that job in the same conversation.
Coop runs the coding agent, and Ryker brings back the change for review. Emisar
checks any requested system actions against your rules and asks for approval
when needed.

Use Coop or Emisar with the AI assistant you already have, or bring the workflow
into Slack and GitHub with Ryker.

<sub>Ryker was formerly called Responder. Its source repository still uses that name.</sub>

---

[Brand guide](https://github.com/ProtectorateHQ/.github/blob/main/brand/README.md) · [Design guide](https://github.com/ProtectorateHQ/.github/blob/main/brand/DESIGN.md) · [Logo assets](https://github.com/ProtectorateHQ/.github/tree/main/brand/assets) · [How Emisar controls access](https://emisar.dev/security)

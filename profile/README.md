<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/emisar-wordmark-on-dark.png">
    <img alt="emisar" src="./assets/emisar-wordmark-on-light.png" width="300">
  </picture>
</p>

<p align="center">
  Give your AI agents access to production, without handing over a shell.
</p>

<p align="center">
  <a href="https://emisar.dev/sign_up"><strong>Start free</strong></a> ·
  <a href="https://emisar.dev/docs/quickstart">Quickstart</a> ·
  <a href="https://emisar.dev/docs">Docs</a> ·
  <a href="https://emisar.dev/packs">Pack catalog</a>
</p>

---

emisar connects Claude, Cursor, ChatGPT, and other AI agents to your
infrastructure through a list of actions you choose. Each action is written down
in advance — the command it runs, the arguments it takes, and how risky it is —
so an agent picks from that list instead of writing its own command line.

Policy decides what runs on its own, what waits for a person, and what is
refused. A small runner on each host checks the action again before it executes,
and every call is recorded.

No SSH keys, no VPN, no standing shell access.

## Getting started

You will need an account and one Linux host.

1. [Create a free account](https://emisar.dev/sign_up) — three runners free, no
   credit card.
2. Choose **Connect a runner** in the console and run the command it gives you
   on your host. It carries a single-use key, so it has to come from your
   account rather than from a page like this one.
3. Connect your agent and run your first action. The
   [quickstart](https://emisar.dev/docs/quickstart) walks through all of it,
   with the output you should expect.

The [pack catalog](https://emisar.dev/packs) covers databases, cloud providers,
web servers, message queues, observability, and network gear. Installing a pack
adds its actions to the same connection, so there is no second server to deploy
and nothing to reconfigure in your agent.

## Repositories

| Repository | What it is |
| --- | --- |
| [`emisar`](https://github.com/AndrewDryga/emisar) | The control plane, the on-host runner, the MCP bridge, and the pack catalog. |
| [`emisar-cursor-plugin`](https://github.com/EmisarHQ/emisar-cursor-plugin) | Cursor plugin for connecting to emisar over MCP. |

The [runner](https://github.com/AndrewDryga/emisar/blob/main/runner/LICENSE) and
the [MCP bridge](https://github.com/AndrewDryga/emisar/blob/main/mcp/LICENSE) are
Apache-2.0 — the two pieces that run on your machines. The control plane is
[BSL 1.1](https://github.com/AndrewDryga/emisar/blob/main/LICENSE.md).

## Security

Found a vulnerability? Please email **security@emisar.dev**.

What emisar protects, and where those limits end, is written up at
[emisar.dev/security](https://emisar.dev/security).

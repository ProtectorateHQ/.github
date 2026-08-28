<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/emisar-wordmark-on-dark.png">
    <img alt="emisar" src="./assets/emisar-wordmark-on-light.png" width="320">
  </picture>
</p>

<p align="center"><strong>Leave the agent working. Keep production authority bounded.</strong></p>

<p align="center">
  <a href="https://emisar.dev/docs/quickstart">Quickstart</a> ·
  <a href="https://emisar.dev/docs">Docs</a> ·
  <a href="https://emisar.dev/packs">Pack catalog</a> ·
  <a href="https://emisar.dev/security">Security</a>
</p>

---

emisar gives MCP-capable agents a catalog of declared infrastructure actions
instead of a shell. Policy decides what runs, what waits for a person, and what
is denied. A small outbound-only runner checks the action again on the host
before it executes anything.

The action pack is the contract. It fixes the executable, argv shape, argument
schema, risk, timeout, output limits, redaction, and side-effect description.
The model selects from that contract; it does not invent a command line for the
runner to execute.

The public catalog currently publishes **100 packs and 1,689 actions** —
databases, cloud providers, web servers, message queues, observability, and
network gear. Adding a pack adds capabilities behind the same MCP surface, so
operators do not deploy another tool server or reconfigure every agent when the
catalog changes.

## Repositories

| Repository | What it is |
| --- | --- |
| [`emisar`](https://github.com/EmisarHQ/emisar) | The control plane, the on-host runner, the MCP bridge, and the action-pack catalog. |
| [`emisar-cursor-plugin`](https://github.com/EmisarHQ/emisar-cursor-plugin) | Cursor plugin: governed infrastructure actions over MCP. |

## Start with one host

```sh
curl -fsSL https://emisar.dev/install.sh \
  | sudo EMISAR_ENROLLMENT_KEY=emkey-enroll-... bash
```

The installer verifies the release checksum, creates the service, installs
host-matched starter packs, and starts the runner. The walkthrough with expected
output and troubleshooting is in the
[quickstart](https://emisar.dev/docs/quickstart).

## Security

Report a vulnerability to **security@emisar.dev**. The threat model, the
guarantees, and their limits are published at
[emisar.dev/security](https://emisar.dev/security).

# Security policy

Report security problems in Tiller privately through
[GitHub private vulnerability reporting](https://github.com/Antler-Web-Studios/tiller/security/advisories/new).

Please do not open a public issue for a vulnerability, and give us a reasonable
window to investigate and fix it before disclosing.

## What to include

- The Tiller version (Settings → About) and the macOS version.
- What an attacker could do, and what they need to start.
- The smallest reproduction you can manage, with anything private replaced by
  `<home>`, `<project>` and `<host>`.

## Scope

Tiller is a desktop app that runs coding agents on your machine and can connect to
a self-hosted server. In scope: the app, its bundled server, the update channel, and
anything that crosses a trust boundary between them. Out of scope: the coding-agent
CLIs and model providers Tiller drives, and problems that need an already-compromised
machine.

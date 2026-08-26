<p align="center">
  <img src="../assets/pushman-icon.png" alt="Pushman" width="128" height="128">
</p>

<h1 align="center">Pushman</h1>

<p align="center">
  Push notifications from your terminal to your iPhone.
</p>

<p align="center">
  <a href="https://github.com/pushmanhq/pushman-cli/releases"><img alt="Latest CLI release" src="https://img.shields.io/github/v/release/pushmanhq/pushman-cli?display_name=tag"></a>
  <a href="https://github.com/pushmanhq/pushman-cli/actions/workflows/ci.yml"><img alt="CLI CI" src="https://github.com/pushmanhq/pushman-cli/actions/workflows/ci.yml/badge.svg"></a>
  <a href="https://github.com/pushmanhq/pushman-cli/blob/main/LICENSE"><img alt="MIT License" src="https://img.shields.io/badge/CLI_license-MIT-151515"></a>
</p>

Pushman delivers rich, script-friendly notifications from terminals, servers, and CI jobs to a native iPhone app. The public Go CLI includes browser login, app pairing, structured output, secure credential storage, self-updates, and a local stdio MCP server.

```sh
brew install whitekiwi/tap/pushman
pushman login
pushman push "Production deploy finished" --title "Acme API"
```

- [Install and use Pushman CLI](https://github.com/pushmanhq/pushman-cli)
- [Download CLI releases](https://github.com/pushmanhq/pushman-cli/releases)
- [Open the Pushman web app](https://app.pushman.whitekiwi.link)
- [Report a security vulnerability privately](https://github.com/pushmanhq/pushman-cli/security/advisories/new)

The iPhone app is currently in private beta. Its App Store link will be published when the listing is ready.

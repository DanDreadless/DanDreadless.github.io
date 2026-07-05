# vault1337.com — GitHub Pages Site

Source for [vault1337.com](https://vault1337.com) — the project homepage for the open-source security tools built by [@DanDreadless](https://github.com/DanDreadless).

## Tools

| Tool | Description | Links |
|------|-------------|-------|
| **Minos** | Modern DNS sinkhole / Pi-hole alternative — a single static Go binary with an embedded web UI, light enough for a Raspberry Pi | [GitHub](https://github.com/DanDreadless/minos) · [Docs](https://vault1337.com/minos.html) |
| **Carapace** | Safe web renderer (Rust) — Chromium headless with JavaScript enabled and all network requests intercepted and blocked | [GitHub](https://github.com/DanDreadless/Carapace) · [Docs](https://vault1337.com/carapace.html) |
| **Vault1337** | Self-hosted malware analysis platform | [Docs](https://vault1337.com/vault1337.html) · [Docker Hub](https://hub.docker.com/r/vault1337/vault1337) |
| **Insight** | Passive web threat scanner — content-based, no reputation APIs | [Docs](https://vault1337.com/insight.html) · [Live](https://insight.vault1337.com) |

> **Note:** the **Vault1337** and **Insight** source repositories have been made **private** until further notice.
> Their documentation, the live Insight scanner, and the Vault1337 Docker Hub image remain available — any interest
> in source access should be made directly. **Minos** (GPLv3) and **Carapace** stay fully open-source on GitHub.

## Pages

- `index.html` — Landing page with tool overview
- `minos.html` — Minos full documentation
- `carapace.html` — Carapace full documentation
- `vault1337.html` — Vault1337 full documentation
- `insight.html` — Insight full documentation (includes Carapace integration section)

## Tech

Static site — Bootstrap 5.3.3, Bootstrap Icons 1.11.3, custom CSS. No build step required.

## License

MIT License — see [LICENSE](LICENSE).
